# Function: <code>follow_page_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, unsigned int *page_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811ba750)
Location: mm/gup.c:177
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:break_ksm
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:SyS_move_pages
```
**Symbols:**

```
ffffffff811ba750-ffffffff811baac8: follow_page_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, unsigned int *page_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811d4e20)
Location: mm/gup.c:214
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
  - mm/migrate.c:SyS_move_pages
  - mm/migrate.c:do_pages_stat
```
**Symbols:**

```
ffffffff811d4e20-ffffffff811d5337: follow_page_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, unsigned int *page_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811e4e40)
Location: mm/gup.c:224
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:do_pages_stat
```
**Symbols:**

```
ffffffff811e4e40-ffffffff811e5352: follow_page_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, unsigned int *page_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811ef440)
Location: mm/gup.c:363
Inline: True
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:do_pages_stat
```
**Symbols:**

```
ffffffff811ef440-ffffffff811efa14: follow_page_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, unsigned int *page_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81206bc0)
Location: mm/gup.c:381
Inline: True
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:do_pages_stat
```
**Symbols:**

```
ffffffff81206bc0-ffffffff81206dca: follow_page_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, unsigned int *page_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812273d0)
Location: mm/gup.c:397
Inline: True
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:do_pages_stat
```
**Symbols:**

```
ffffffff812273d0-ffffffff81227b3c: follow_page_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct follow_page_context *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8123ab70)
Location: mm/gup.c:402
Inline: True
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
**Symbols:**

```
ffffffff8123ab70-ffffffff8123b314: follow_page_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct follow_page_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124c5c0)
Location: mm/gup.c:519
Inline: True
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
**Symbols:**

```
ffffffff8124c5c0-ffffffff8124c7f8: follow_page_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct follow_page_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125aaf0)
Location: mm/gup.c:518
Inline: True
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
**Symbols:**

```
ffffffff8125aaf0-ffffffff8125ad28: follow_page_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct follow_page_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81289070)
Location: mm/gup.c:752
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
**Symbols:**

```
ffffffff81289070-ffffffff812891e2: follow_page_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct follow_page_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81292d50)
Location: mm/gup.c:716
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
**Symbols:**

```
ffffffff81292d50-ffffffff81292ec2: follow_page_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct follow_page_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81298780)
Location: mm/gup.c:801
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
**Symbols:**

```
ffffffff81298780-ffffffff812988be: follow_page_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct follow_page_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/gup.c (0)
Location: mm/gup.c:824
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
**Symbols:**

```
ffffffff812d91d0-ffffffff812d931f: follow_page_mask (STB_LOCAL)
ffffffff81cbc0ed-ffffffff81cbc109: follow_page_mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct follow_page_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/gup.c (0)
Location: mm/gup.c:845
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
**Symbols:**

```
ffffffff813391a0-ffffffff813392f8: follow_page_mask (STB_LOCAL)
ffffffff81e6dc65-ffffffff81e6dc81: follow_page_mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct follow_page_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/gup.c (0)
Location: mm/gup.c:779
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
**Symbols:**

```
ffffffff813b0ac0-ffffffff813b0bfd: follow_page_mask (STB_LOCAL)
ffffffff82063d09-ffffffff82063d32: follow_page_mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct follow_page_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/gup.c (0)
Location: mm/gup.c:809
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
**Symbols:**

```
ffffffff813e4ef0-ffffffff813e5030: follow_page_mask (STB_LOCAL)
ffffffff820e340d-ffffffff820e3436: follow_page_mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct follow_page_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/gup.c (0)
Location: mm/gup.c:811
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
**Symbols:**

```
ffffffff8140f720-ffffffff8140f8b1: follow_page_mask (STB_LOCAL)
ffffffff821bfe69-ffffffff821bfe8a: follow_page_mask.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct follow_page_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f2368)
Location: mm/gup.c:518
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
**Symbols:**

```
ffff8000102f2368-ffff8000102f24b8: follow_page_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (c05147b4)
Location: mm/gup.c:518
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct follow_page_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b86c0)
Location: mm/gup.c:518
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
**Symbols:**

```
c0000000003b86c0-c0000000003b89e8: follow_page_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/gup.c (ffffffe000204962)
Location: mm/gup.c:518
Inline: True
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
**Symbols:**

```
ffffffe000204962-ffffffe000204ab4: follow_page_mask.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct follow_page_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81253140)
Location: mm/gup.c:518
Inline: True
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
**Symbols:**

```
ffffffff81253140-ffffffff81253378: follow_page_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct follow_page_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81245e60)
Location: mm/gup.c:518
Inline: True
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
**Symbols:**

```
ffffffff81245e60-ffffffff81246051: follow_page_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct follow_page_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81250ee0)
Location: mm/gup.c:518
Inline: True
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
**Symbols:**

```
ffffffff81250ee0-ffffffff81251118: follow_page_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct page *follow_page_mask(struct vm_area_struct *vma, long unsigned int address, unsigned int flags, struct follow_page_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81260860)
Location: mm/gup.c:518
Inline: True
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
**Symbols:**

```
ffffffff81260860-ffffffff81260a91: follow_page_mask (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct follow_page_context *ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int *page_mask</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
