# Function: <code>copy_user_huge_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811c2210)
Location: mm/memory.c:3864
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff811c2210-ffffffff811c250a: copy_user_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ddd40)
Location: mm/memory.c:4059
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff811ddd40-ffffffff811de016: copy_user_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811edb60)
Location: mm/memory.c:4140
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff811edb60-ffffffff811ede2e: copy_user_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f8ad0)
Location: mm/memory.c:4430
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff811f8ad0-ffffffff811f8cf4: copy_user_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81210e20)
Location: mm/memory.c:4640
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff81210e20-ffffffff8121108b: copy_user_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr_hint, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81231760)
Location: mm/memory.c:4724
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff81231760-ffffffff81231a88: copy_user_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr_hint, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81244f40)
Location: mm/memory.c:4514
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff81244f40-ffffffff8124525e: copy_user_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr_hint, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256f10)
Location: mm/memory.c:4569
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff81256f10-ffffffff81257299: copy_user_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr_hint, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812654a0)
Location: mm/memory.c:4594
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff812654a0-ffffffff81265829: copy_user_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr_hint, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81295890)
Location: mm/memory.c:4959
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff81295890-ffffffff81295b2e: copy_user_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr_hint, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a0720)
Location: mm/memory.c:5186
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff812a0720-ffffffff812a0ace: copy_user_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr_hint, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a6060)
Location: mm/memory.c:5253
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff812a6060-ffffffff812a640c: copy_user_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr_hint, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e74f0)
Location: mm/memory.c:5399
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff812e74f0-ffffffff812e78c9: copy_user_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr_hint, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813487a0)
Location: mm/memory.c:5698
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff813487a0-ffffffff81348a72: copy_user_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr_hint, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813c0c90)
Location: mm/memory.c:5777
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff813c0c90-ffffffff813c0ef0: copy_user_huge_page (STB_GLOBAL)
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
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr_hint, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fbec8)
Location: mm/memory.c:4594
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffff8000102fbec8-ffff8000102fc16c: copy_user_huge_page (STB_GLOBAL)
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
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr_hint, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c7570)
Location: mm/memory.c:4594
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
c0000000003c7570-c0000000003c79cc: copy_user_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr_hint, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020b4c2)
Location: mm/memory.c:4594
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffe00020b4c2-ffffffe00020b796: copy_user_huge_page (STB_GLOBAL)
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
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr_hint, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125daf0)
Location: mm/memory.c:4594
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff8125daf0-ffffffff8125de79: copy_user_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr_hint, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124ff40)
Location: mm/memory.c:4594
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff8124ff40-ffffffff812502c9: copy_user_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr_hint, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125b890)
Location: mm/memory.c:4594
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff8125b890-ffffffff8125bc19: copy_user_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void copy_user_huge_page(struct page *dst, struct page *src, long unsigned int addr_hint, struct vm_area_struct *vma, unsigned int pages_per_huge_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8126b260)
Location: mm/memory.c:4594
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff8126b260-ffffffff8126b5fe: copy_user_huge_page (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int addr_hint</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int addr</code>
</li>
</ul>
</details>
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
