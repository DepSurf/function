# Function: <code>mprotect_fixup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mprotect_fixup(struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff811c8ca0)
Location: mm/mprotect.c:258
Inline: False
Direct callers:
  - mm/mprotect.c:SyS_mprotect
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff811c8ca0-ffffffff811c8ed6: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mprotect_fixup(struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff811e4f60)
Location: mm/mprotect.c:262
Inline: False
Direct callers:
  - mm/mprotect.c:SyS_mprotect
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff811e4f60-ffffffff811e51cb: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mprotect_fixup(struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff811f4fb0)
Location: mm/mprotect.c:276
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff811f4fb0-ffffffff811f521f: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mprotect_fixup(struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff811ffde0)
Location: mm/mprotect.c:279
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff811ffde0-ffffffff81200042: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mprotect_fixup(struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81218580)
Location: mm/mprotect.c:296
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff81218580-ffffffff812187e2: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mprotect_fixup(struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81239f20)
Location: mm/mprotect.c:346
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff81239f20-ffffffff8123a266: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mprotect_fixup(struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8124e090)
Location: mm/mprotect.c:347
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff8124e090-ffffffff8124e3d6: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mprotect_fixup(struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812603e0)
Location: mm/mprotect.c:348
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff812603e0-ffffffff81260716: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mprotect_fixup(struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8126ec00)
Location: mm/mprotect.c:373
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff8126ec00-ffffffff8126eeae: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mprotect_fixup(struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8129f1c0)
Location: mm/mprotect.c:399
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff8129f1c0-ffffffff8129f49d: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mprotect_fixup(struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812aa580)
Location: mm/mprotect.c:399
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff812aa580-ffffffff812aa85d: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mprotect_fixup(struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812af9c0)
Location: mm/mprotect.c:399
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff812af9c0-ffffffff812afc9f: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mprotect_fixup(struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812f1210)
Location: mm/mprotect.c:409
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff812f1210-ffffffff812f14ef: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mprotect_fixup(struct mmu_gather *tlb, struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81354e70)
Location: mm/mprotect.c:501
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff81354e70-ffffffff8135517c: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mprotect_fixup(struct mmu_gather *tlb, struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff813cf390)
Location: mm/mprotect.c:557
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff813cf390-ffffffff813cf6ab: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mprotect_fixup(struct vma_iterator *vmi, struct mmu_gather *tlb, struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81403d30)
Location: mm/mprotect.c:575
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff81403d30-ffffffff81404048: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mprotect_fixup(struct vma_iterator *vmi, struct mmu_gather *tlb, struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81430280)
Location: mm/mprotect.c:577
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff81430280-ffffffff81430615: mprotect_fixup (STB_GLOBAL)
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
int mprotect_fixup(struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffff800010305788)
Location: mm/mprotect.c:373
Inline: False
Direct callers:
  - mm/mprotect.c:__arm64_sys_mprotect
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffff800010305788-ffff8000103059e0: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mprotect_fixup(struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (c05236c8)
Location: mm/mprotect.c:373
Inline: False
Direct callers:
  - mm/mprotect.c:__se_sys_mprotect
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
c05236c8-c052392c: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mprotect_fixup(struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (c0000000003d2c40)
Location: mm/mprotect.c:373
Inline: False
Direct callers:
  - mm/mprotect.c:__se_sys_mprotect
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
c0000000003d2c40-c0000000003d2f90: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mprotect_fixup(struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffe00021156e)
Location: mm/mprotect.c:373
Inline: False
Direct callers:
  - mm/mprotect.c:__se_sys_mprotect
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffe00021156e-ffffffe000211748: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int mprotect_fixup(struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81267250)
Location: mm/mprotect.c:373
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff81267250-ffffffff812674fe: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mprotect_fixup(struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812595a0)
Location: mm/mprotect.c:373
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff812595a0-ffffffff8125984e: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mprotect_fixup(struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81264ff0)
Location: mm/mprotect.c:373
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff81264ff0-ffffffff8126529e: mprotect_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mprotect_fixup(struct vm_area_struct *vma, struct vm_area_struct **pprev, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812749a0)
Location: mm/mprotect.c:373
Inline: False
Direct callers:
  - mm/mprotect.c:do_mprotect_pkey
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
ffffffff812749a0-ffffffff81274c4e: mprotect_fixup (STB_GLOBAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mmu_gather *tlb</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, pprev, start, end, newflags</code> ➡️ <code>tlb, vma, pprev, start, end, newflags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vma_iterator *vmi</code>
</li>
<li>
<b>Param reordered. </b>
<code>tlb, vma, pprev, start, end, newflags</code> ➡️ <code>vmi, tlb, vma, pprev, start, end, newflags</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
