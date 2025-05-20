# Function: <code>alloc_huge_page_noerr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *alloc_huge_page_noerr(struct vm_area_struct *vma, long unsigned int addr, int avoid_reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811dcd60)
Location: mm/hugetlb.c:1944
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
```
**Symbols:**

```
ffffffff811dcd60-ffffffff811dcd7f: alloc_huge_page_noerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *alloc_huge_page_noerr(struct vm_area_struct *vma, long unsigned int addr, int avoid_reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811faff0)
Location: mm/hugetlb.c:1991
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
```
**Symbols:**

```
ffffffff811faff0-ffffffff811fb00f: alloc_huge_page_noerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *alloc_huge_page_noerr(struct vm_area_struct *vma, long unsigned int addr, int avoid_reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120baf0)
Location: mm/hugetlb.c:2097
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
```
**Symbols:**

```
ffffffff8120baf0-ffffffff8120bb0f: alloc_huge_page_noerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *alloc_huge_page_noerr(struct vm_area_struct *vma, long unsigned int addr, int avoid_reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81217160)
Location: mm/hugetlb.c:2077
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
```
**Symbols:**

```
ffffffff81217160-ffffffff8121717f: alloc_huge_page_noerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *alloc_huge_page_noerr(struct vm_area_struct *vma, long unsigned int addr, int avoid_reserve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81231e10)
Location: mm/hugetlb.c:2083
Inline: False
Direct callers:
  - mm/mempolicy.c:new_page
```
**Symbols:**

```
ffffffff81231e10-ffffffff81231e2f: alloc_huge_page_noerr (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
