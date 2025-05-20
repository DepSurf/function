# Function: <code>try_to_merge_one_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff811e532b)
Location: mm/ksm.c:1016
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81203e9f)
Location: mm/ksm.c:977
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81215e60)
Location: mm/ksm.c:1006
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff81215e60-ffffffff812165e9: try_to_merge_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81221570)
Location: mm/ksm.c:1164
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff81221570-ffffffff81221d1b: try_to_merge_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8123c880)
Location: mm/ksm.c:1175
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff8123c880-ffffffff8123cfdd: try_to_merge_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81260180)
Location: mm/ksm.c:1205
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff81260180-ffffffff81260981: try_to_merge_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812748b0)
Location: mm/ksm.c:1203
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff812748b0-ffffffff812750e8: try_to_merge_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8128f9d0)
Location: mm/ksm.c:1219
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff8128f9d0-ffffffff8128fbad: try_to_merge_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8129f760)
Location: mm/ksm.c:1201
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff8129f760-ffffffff8129f93d: try_to_merge_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812d3dd0)
Location: mm/ksm.c:1201
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff812d3dd0-ffffffff812d3fad: try_to_merge_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812df7c0)
Location: mm/ksm.c:1202
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff812df7c0-ffffffff812df99d: try_to_merge_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e80e0)
Location: mm/ksm.c:1200
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff812e80e0-ffffffff812e82b9: try_to_merge_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81330010)
Location: mm/ksm.c:1196
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff81330010-ffffffff813301e9: try_to_merge_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff813a09f0)
Location: mm/ksm.c:1216
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff813a09f0-ffffffff813a0c3e: try_to_merge_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81420260)
Location: mm/ksm.c:1232
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff81420260-ffffffff814204ae: try_to_merge_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81454e70)
Location: mm/ksm.c:1276
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff81454e70-ffffffff814550c0: try_to_merge_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81490130)
Location: mm/ksm.c:1475
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff81490130-ffffffff8149036a: try_to_merge_one_page (STB_LOCAL)
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
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffff80001033ea60)
Location: mm/ksm.c:1201
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffff80001033ea60-ffff80001033efbc: try_to_merge_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c05451e8)
Location: mm/ksm.c:1201
Inline: False
Direct callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
c05451e8-c0545404: try_to_merge_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c00000000041b080)
Location: mm/ksm.c:1201
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
c00000000041b080-c00000000041b3b0: try_to_merge_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffe00023480a)
Location: mm/ksm.c:1201
Inline: False
Direct callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffe00023480a-ffffffe000234c0a: try_to_merge_one_page (STB_LOCAL)
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
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81297d40)
Location: mm/ksm.c:1201
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff81297d40-ffffffff81297f1d: try_to_merge_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81289900)
Location: mm/ksm.c:1201
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff81289900-ffffffff81289ad8: try_to_merge_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81295b50)
Location: mm/ksm.c:1201
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff81295b50-ffffffff81295d2d: try_to_merge_one_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct *vma, struct page *page, struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812a5960)
Location: mm/ksm.c:1201
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff812a5960-ffffffff812a5b38: try_to_merge_one_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
