# Function: <code>hugetlb_wp</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_wp(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, unsigned int flags, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:5219
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff8138fa60-ffffffff81390354: hugetlb_wp (STB_LOCAL)
ffffffff81e72013-ffffffff81e72153: hugetlb_wp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_wp(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, unsigned int flags, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:5474
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff81410410-ffffffff81410b45: hugetlb_wp (STB_LOCAL)
ffffffff82066c3a-ffffffff82066ce6: hugetlb_wp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_wp(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, unsigned int flags, struct folio *pagecache_folio, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:5560
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff814437d0-ffffffff81443f84: hugetlb_wp (STB_LOCAL)
ffffffff820e6446-ffffffff820e6555: hugetlb_wp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_wp(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, unsigned int flags, struct folio *pagecache_folio, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:5827
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff8147d850-ffffffff8147e042: hugetlb_wp (STB_LOCAL)
ffffffff821c35ee-ffffffff821c3712: hugetlb_wp.cold (STB_LOCAL)
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *pagecache_folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *pagecache_page</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
