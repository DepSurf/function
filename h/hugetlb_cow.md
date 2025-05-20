# Function: <code>hugetlb_cow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hugetlb_cow(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t pte, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811ddbc0)
Location: mm/hugetlb.c:3350
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff811ddbc0-ffffffff811ddfb8: hugetlb_cow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hugetlb_cow(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t pte, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811fbe90)
Location: mm/hugetlb.c:3365
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff811fbe90-ffffffff811fc39b: hugetlb_cow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hugetlb_cow(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120c940)
Location: mm/hugetlb.c:3476
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff8120c940-ffffffff8120ce81: hugetlb_cow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hugetlb_cow(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812182b0)
Location: mm/hugetlb.c:3460
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff812182b0-ffffffff81218758: hugetlb_cow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hugetlb_cow(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81233130)
Location: mm/hugetlb.c:3481
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff81233130-ffffffff8123368b: hugetlb_cow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hugetlb_cow(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81256140)
Location: mm/hugetlb.c:3511
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff81256140-ffffffff8125668f: hugetlb_cow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t hugetlb_cow(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8126a610)
Location: mm/hugetlb.c:3540
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff8126a610-ffffffff8126abc3: hugetlb_cow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t hugetlb_cow(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81285740)
Location: mm/hugetlb.c:3610
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff81285740-ffffffff81285d52: hugetlb_cow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t hugetlb_cow(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81295300)
Location: mm/hugetlb.c:3727
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff81295300-ffffffff81295937: hugetlb_cow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t hugetlb_cow(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c8a10)
Location: mm/hugetlb.c:4149
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff812c8a10-ffffffff812c8f5d: hugetlb_cow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t hugetlb_cow(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d4590)
Location: mm/hugetlb.c:4119
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff812d4590-ffffffff812d4b82: hugetlb_cow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t hugetlb_cow(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812db340)
Location: mm/hugetlb.c:4333
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff812db340-ffffffff812dba04: hugetlb_cow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
vm_fault_t hugetlb_cow(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:4638
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff81322550-ffffffff81322bf0: hugetlb_cow (STB_LOCAL)
ffffffff81cbfc9a-ffffffff81cbfdd0: hugetlb_cow.cold (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
vm_fault_t hugetlb_cow(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010333fe8)
Location: mm/hugetlb.c:3727
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffff800010333fe8-ffff800010334618: hugetlb_cow (STB_LOCAL)
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
vm_fault_t hugetlb_cow(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c00000000040cc60)
Location: mm/hugetlb.c:3727
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
c00000000040cc60-c00000000040d6dc: hugetlb_cow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t hugetlb_cow(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe0002300e8)
Location: mm/hugetlb.c:3727
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffe0002300e8-ffffffe0002305e0: hugetlb_cow (STB_LOCAL)
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
vm_fault_t hugetlb_cow(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128d8e0)
Location: mm/hugetlb.c:3727
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff8128d8e0-ffffffff8128df17: hugetlb_cow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t hugetlb_cow(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127f670)
Location: mm/hugetlb.c:3727
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff8127f670-ffffffff8127fc93: hugetlb_cow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t hugetlb_cow(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128b6f0)
Location: mm/hugetlb.c:3727
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff8128b6f0-ffffffff8128bd27: hugetlb_cow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t hugetlb_cow(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, struct page *pagecache_page, spinlock_t *ptl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8129b500)
Location: mm/hugetlb.c:3727
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff8129b500-ffffffff8129bb15: hugetlb_cow (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>pte_t pte</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, vma, address, ptep, pte, pagecache_page, ptl</code> ➡️ <code>mm, vma, address, ptep, pagecache_page, ptl</code>
</li>
</ul>
</details>
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
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
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
