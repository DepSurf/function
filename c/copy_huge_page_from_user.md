# Function: <code>copy_huge_page_from_user</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int copy_huge_page_from_user(struct page *dst_page, const void *usr_src, unsigned int pages_per_huge_page, bool allow_pagefault);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f8d00)
Location: mm/memory.c:4449
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff811f8d00-ffffffff811f8df0: copy_huge_page_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int copy_huge_page_from_user(struct page *dst_page, const void *usr_src, unsigned int pages_per_huge_page, bool allow_pagefault);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81211090)
Location: mm/memory.c:4659
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81211090-ffffffff81211180: copy_huge_page_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int copy_huge_page_from_user(struct page *dst_page, const void *usr_src, unsigned int pages_per_huge_page, bool allow_pagefault);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81231a90)
Location: mm/memory.c:4745
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81231a90-ffffffff81231b80: copy_huge_page_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int copy_huge_page_from_user(struct page *dst_page, const void *usr_src, unsigned int pages_per_huge_page, bool allow_pagefault);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81245260)
Location: mm/memory.c:4535
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81245260-ffffffff81245350: copy_huge_page_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int copy_huge_page_from_user(struct page *dst_page, const void *usr_src, unsigned int pages_per_huge_page, bool allow_pagefault);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812572a0)
Location: mm/memory.c:4590
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812572a0-ffffffff81257390: copy_huge_page_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int copy_huge_page_from_user(struct page *dst_page, const void *usr_src, unsigned int pages_per_huge_page, bool allow_pagefault);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81265830)
Location: mm/memory.c:4615
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81265830-ffffffff81265920: copy_huge_page_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int copy_huge_page_from_user(struct page *dst_page, const void *usr_src, unsigned int pages_per_huge_page, bool allow_pagefault);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81295b30)
Location: mm/memory.c:4980
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81295b30-ffffffff81295c20: copy_huge_page_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int copy_huge_page_from_user(struct page *dst_page, const void *usr_src, unsigned int pages_per_huge_page, bool allow_pagefault);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a0ad0)
Location: mm/memory.c:5207
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812a0ad0-ffffffff812a0c6e: copy_huge_page_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int copy_huge_page_from_user(struct page *dst_page, const void *usr_src, unsigned int pages_per_huge_page, bool allow_pagefault);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a6410)
Location: mm/memory.c:5274
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812a6410-ffffffff812a654e: copy_huge_page_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int copy_huge_page_from_user(struct page *dst_page, const void *usr_src, unsigned int pages_per_huge_page, bool allow_pagefault);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e78d0)
Location: mm/memory.c:5420
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812e78d0-ffffffff812e7a16: copy_huge_page_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int copy_huge_page_from_user(struct page *dst_page, const void *usr_src, unsigned int pages_per_huge_page, bool allow_pagefault);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81348a80)
Location: mm/memory.c:5719
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81348a80-ffffffff81348c79: copy_huge_page_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int copy_huge_page_from_user(struct page *dst_page, const void *usr_src, unsigned int pages_per_huge_page, bool allow_pagefault);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813c0f00)
Location: mm/memory.c:5798
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff813c0f00-ffffffff813c1016: copy_huge_page_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
long int copy_huge_page_from_user(struct page *dst_page, const void *usr_src, unsigned int pages_per_huge_page, bool allow_pagefault);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fc170)
Location: mm/memory.c:4615
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffff8000102fc170-ffff8000102fc3b4: copy_huge_page_from_user (STB_GLOBAL)
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
long int copy_huge_page_from_user(struct page *dst_page, const void *usr_src, unsigned int pages_per_huge_page, bool allow_pagefault);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c79d0)
Location: mm/memory.c:4615
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
c0000000003c79d0-c0000000003c7b20: copy_huge_page_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int copy_huge_page_from_user(struct page *dst_page, const void *usr_src, unsigned int pages_per_huge_page, bool allow_pagefault);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020b796)
Location: mm/memory.c:4615
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffe00020b796-ffffffe00020b880: copy_huge_page_from_user (STB_GLOBAL)
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
long int copy_huge_page_from_user(struct page *dst_page, const void *usr_src, unsigned int pages_per_huge_page, bool allow_pagefault);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125de80)
Location: mm/memory.c:4615
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8125de80-ffffffff8125df70: copy_huge_page_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int copy_huge_page_from_user(struct page *dst_page, const void *usr_src, unsigned int pages_per_huge_page, bool allow_pagefault);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812502d0)
Location: mm/memory.c:4615
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812502d0-ffffffff812503c0: copy_huge_page_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int copy_huge_page_from_user(struct page *dst_page, const void *usr_src, unsigned int pages_per_huge_page, bool allow_pagefault);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125bc20)
Location: mm/memory.c:4615
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8125bc20-ffffffff8125bd10: copy_huge_page_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int copy_huge_page_from_user(struct page *dst_page, const void *usr_src, unsigned int pages_per_huge_page, bool allow_pagefault);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8126b600)
Location: mm/memory.c:4615
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8126b600-ffffffff8126b6f9: copy_huge_page_from_user (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
