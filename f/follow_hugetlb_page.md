# Function: <code>follow_hugetlb_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811df3b0)
Location: mm/hugetlb.c:3822
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff811df3b0-ffffffff811df762: follow_hugetlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811fd9f0)
Location: mm/hugetlb.c:3837
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff811fd9f0-ffffffff811fdde3: follow_hugetlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120e4d0)
Location: mm/hugetlb.c:3951
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff8120e4d0-ffffffff8120e8de: follow_hugetlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags, int *nonblocking);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81219e80)
Location: mm/hugetlb.c:4072
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff81219e80-ffffffff8121a284: follow_hugetlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags, int *nonblocking);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81234f40)
Location: mm/hugetlb.c:4121
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff81234f40-ffffffff812353aa: follow_hugetlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags, int *nonblocking);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81257e90)
Location: mm/hugetlb.c:4150
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff81257e90-ffffffff812582f0: follow_hugetlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags, int *nonblocking);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8126c550)
Location: mm/hugetlb.c:4190
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff8126c550-ffffffff8126c9b1: follow_hugetlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags, int *nonblocking);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81287900)
Location: mm/hugetlb.c:4270
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff81287900-ffffffff81287dd3: follow_hugetlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags, int *nonblocking);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81297510)
Location: mm/hugetlb.c:4387
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff81297510-ffffffff812979d7: follow_hugetlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812cab00)
Location: mm/hugetlb.c:4825
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff812cab00-ffffffff812cb063: follow_hugetlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d6720)
Location: mm/hugetlb.c:4815
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff812d6720-ffffffff812d6c80: follow_hugetlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812dd8d0)
Location: mm/hugetlb.c:5099
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff812dd8d0-ffffffff812ddea9: follow_hugetlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:5434
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff81cc0171-ffffffff81cc03f1: follow_hugetlb_page.cold (STB_LOCAL)
ffffffff81324a90-ffffffff813250be: follow_hugetlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:6120
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff81e7259b-ffffffff81e727f0: follow_hugetlb_page.cold (STB_LOCAL)
ffffffff81393260-ffffffff813939f1: follow_hugetlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:6444
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff82066e71-ffffffff82066f61: follow_hugetlb_page.cold (STB_LOCAL)
ffffffff814119f0-ffffffff81412110: follow_hugetlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:6531
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff820e66ad-ffffffff820e681d: follow_hugetlb_page.cold (STB_LOCAL)
ffffffff81444e80-ffffffff814456cc: follow_hugetlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags, int *nonblocking);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010335338)
Location: mm/hugetlb.c:4387
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffff800010335338-ffff8000103357b8: follow_hugetlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags, int *nonblocking);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c00000000040f280)
Location: mm/hugetlb.c:4387
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
c00000000040f280-c00000000040fa88: follow_hugetlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags, int *nonblocking);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe0002319ec)
Location: mm/hugetlb.c:4387
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffe0002319ec-ffffffe000231e54: follow_hugetlb_page (STB_GLOBAL)
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
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags, int *nonblocking);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128faf0)
Location: mm/hugetlb.c:4387
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff8128faf0-ffffffff8128ffb7: follow_hugetlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags, int *nonblocking);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812817b0)
Location: mm/hugetlb.c:4387
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff812817b0-ffffffff81281c6d: follow_hugetlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags, int *nonblocking);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128d900)
Location: mm/hugetlb.c:4387
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff8128d900-ffffffff8128ddc7: follow_hugetlb_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int follow_hugetlb_page(struct mm_struct *mm, struct vm_area_struct *vma, struct page **pages, struct vm_area_struct **vmas, long unsigned int *position, long unsigned int *nr_pages, long int i, unsigned int flags, int *nonblocking);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8129d6b0)
Location: mm/hugetlb.c:4387
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff8129d6b0-ffffffff8129db78: follow_hugetlb_page (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int *nonblocking</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int *locked</code>
</li>
<li>
<b>Param removed. </b>
<code>int *nonblocking</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct **vmas</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, vma, pages, vmas, position, nr_pages, i, flags, locked</code> ➡️ <code>mm, vma, pages, position, nr_pages, i, flags, locked</code>
</li>
</ul>
</details>
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
