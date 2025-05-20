# Function: <code>alloc_huge_page_vma</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *alloc_huge_page_vma(struct hstate *h, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81254880)
Location: mm/hugetlb.c:1672
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
```
**Symbols:**

```
ffffffff81254880-ffffffff81254913: alloc_huge_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *alloc_huge_page_vma(struct hstate *h, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81268c60)
Location: mm/hugetlb.c:1672
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
```
**Symbols:**

```
ffffffff81268c60-ffffffff81268cf3: alloc_huge_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *alloc_huge_page_vma(struct hstate *h, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81283d40)
Location: mm/hugetlb.c:1715
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
```
**Symbols:**

```
ffffffff81283d40-ffffffff81283dea: alloc_huge_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *alloc_huge_page_vma(struct hstate *h, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812938e0)
Location: mm/hugetlb.c:1795
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
```
**Symbols:**

```
ffffffff812938e0-ffffffff8129398a: alloc_huge_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *alloc_huge_page_vma(struct hstate *h, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c6d20)
Location: mm/hugetlb.c:2040
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
```
**Symbols:**

```
ffffffff812c6d20-ffffffff812c6dc7: alloc_huge_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *alloc_huge_page_vma(struct hstate *h, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d2880)
Location: mm/hugetlb.c:1987
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
```
**Symbols:**

```
ffffffff812d2880-ffffffff812d2938: alloc_huge_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *alloc_huge_page_vma(struct hstate *h, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d92d0)
Location: mm/hugetlb.c:1934
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
```
**Symbols:**

```
ffffffff812d92d0-ffffffff812d9388: alloc_huge_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *alloc_huge_page_vma(struct hstate *h, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8131fdb0)
Location: mm/hugetlb.c:2198
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/mempolicy.c:new_page
```
**Symbols:**

```
ffffffff8131fdb0-ffffffff8131fe6b: alloc_huge_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *alloc_huge_page_vma(struct hstate *h, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8138cb00)
Location: mm/hugetlb.c:2310
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/mempolicy.c:new_page
```
**Symbols:**

```
ffffffff8138cb00-ffffffff8138cbcf: alloc_huge_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *alloc_huge_page_vma(struct hstate *h, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8140b520)
Location: mm/hugetlb.c:2496
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/mempolicy.c:new_page
```
**Symbols:**

```
ffffffff8140b520-ffffffff8140b5ef: alloc_huge_page_vma (STB_GLOBAL)
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
struct page *alloc_huge_page_vma(struct hstate *h, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010331b68)
Location: mm/hugetlb.c:1795
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
```
**Symbols:**

```
ffff800010331b68-ffff800010331c44: alloc_huge_page_vma (STB_GLOBAL)
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
struct page *alloc_huge_page_vma(struct hstate *h, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c00000000040abb0)
Location: mm/hugetlb.c:1795
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
```
**Symbols:**

```
c00000000040abb0-c00000000040ad00: alloc_huge_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *alloc_huge_page_vma(struct hstate *h, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022ea78)
Location: mm/hugetlb.c:1795
Inline: False
```
**Symbols:**

```
ffffffe00022ea78-ffffffe00022eaa6: alloc_huge_page_vma (STB_GLOBAL)
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
struct page *alloc_huge_page_vma(struct hstate *h, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128bec0)
Location: mm/hugetlb.c:1795
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
```
**Symbols:**

```
ffffffff8128bec0-ffffffff8128bf6a: alloc_huge_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *alloc_huge_page_vma(struct hstate *h, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127dcf0)
Location: mm/hugetlb.c:1795
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
```
**Symbols:**

```
ffffffff8127dcf0-ffffffff8127dd9a: alloc_huge_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *alloc_huge_page_vma(struct hstate *h, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81289cd0)
Location: mm/hugetlb.c:1795
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
```
**Symbols:**

```
ffffffff81289cd0-ffffffff81289d7a: alloc_huge_page_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *alloc_huge_page_vma(struct hstate *h, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81299ae0)
Location: mm/hugetlb.c:1795
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
```
**Symbols:**

```
ffffffff81299ae0-ffffffff81299b8a: alloc_huge_page_vma (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
