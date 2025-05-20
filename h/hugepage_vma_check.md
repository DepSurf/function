# Function: <code>hugepage_vma_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff811f3fd0)
Location: mm/huge_memory.c:2491
Inline: True
Direct callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
```
**Symbols:**

```
ffffffff811f3fd0-ffffffff811f4019: hugepage_vma_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81219550)
Location: mm/khugepaged.c:816
Inline: True
Direct callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:hugepage_vma_revalidate
```
**Symbols:**

```
ffffffff81219550-ffffffff812195e7: hugepage_vma_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8122bad0)
Location: mm/khugepaged.c:818
Inline: True
Direct callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:hugepage_vma_revalidate
```
**Symbols:**

```
ffffffff8122bad0-ffffffff8122bb67: hugepage_vma_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81237590)
Location: mm/khugepaged.c:816
Inline: True
Direct callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:hugepage_vma_revalidate
```
**Symbols:**

```
ffffffff81237590-ffffffff81237638: hugepage_vma_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81256920)
Location: mm/khugepaged.c:822
Inline: True
Direct callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:hugepage_vma_revalidate
```
**Symbols:**

```
ffffffff81256920-ffffffff812569c8: hugepage_vma_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8127a8f0)
Location: mm/khugepaged.c:822
Inline: True
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:hugepage_vma_revalidate
```
**Symbols:**

```
ffffffff8127a8f0-ffffffff8127a9a1: hugepage_vma_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma, long unsigned int vm_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8128eef0)
Location: mm/khugepaged.c:400
Inline: True
Direct callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:hugepage_vma_revalidate
```
**Symbols:**

```
ffffffff8128eef0-ffffffff8128efa3: hugepage_vma_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma, long unsigned int vm_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812a97c0)
Location: mm/khugepaged.c:400
Inline: True
Direct callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:hugepage_vma_revalidate
```
**Symbols:**

```
ffffffff812a97c0-ffffffff812a9876: hugepage_vma_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma, long unsigned int vm_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812bad30)
Location: mm/khugepaged.c:407
Inline: True
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
```
**Symbols:**

```
ffffffff812bad30-ffffffff812bade6: hugepage_vma_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma, long unsigned int vm_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812efbb0)
Location: mm/khugepaged.c:437
Inline: True
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
```
**Symbols:**

```
ffffffff812efbb0-ffffffff812efc7d: hugepage_vma_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma, long unsigned int vm_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812fb2b0)
Location: mm/khugepaged.c:442
Inline: True
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
```
**Symbols:**

```
ffffffff812fb2b0-ffffffff812fb37e: hugepage_vma_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma, long unsigned int vm_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81302080)
Location: mm/khugepaged.c:442
Inline: True
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
```
**Symbols:**

```
ffffffff81302080-ffffffff8130214e: hugepage_vma_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma, long unsigned int vm_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8134bee0)
Location: mm/khugepaged.c:442
Inline: True
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
```
**Symbols:**

```
ffffffff8134bee0-ffffffff8134bfb0: hugepage_vma_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma, long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813c60e0)
Location: mm/khugepaged.c:440
Inline: True
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
  - mm/khugepaged.c:hugepage_madvise
```
**Symbols:**

```
ffffffff813c60e0-ffffffff813c6204: hugepage_vma_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma, long unsigned int vm_flags, bool smaps, bool in_pf, bool enforce_sysfs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8143e050)
Location: mm/huge_memory.c:74
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff8143e050-ffffffff8143e2a7: hugepage_vma_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma, long unsigned int vm_flags, bool smaps, bool in_pf, bool enforce_sysfs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814738d0)
Location: mm/huge_memory.c:74
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff814738d0-ffffffff81473aac: hugepage_vma_check (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma, long unsigned int vm_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffff80001035bda8)
Location: mm/khugepaged.c:407
Inline: True
Direct callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
```
**Symbols:**

```
ffff80001035bda8-ffff80001035be70: hugepage_vma_check (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma, long unsigned int vm_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (c000000000445910)
Location: mm/khugepaged.c:407
Inline: True
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
```
**Symbols:**

```
c000000000445910-c000000000445a70: hugepage_vma_check (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma, long unsigned int vm_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b3310)
Location: mm/khugepaged.c:407
Inline: True
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
```
**Symbols:**

```
ffffffff812b3310-ffffffff812b33c6: hugepage_vma_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma, long unsigned int vm_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812a4690)
Location: mm/khugepaged.c:407
Inline: True
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
```
**Symbols:**

```
ffffffff812a4690-ffffffff812a4746: hugepage_vma_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma, long unsigned int vm_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b1120)
Location: mm/khugepaged.c:407
Inline: True
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
```
**Symbols:**

```
ffffffff812b1120-ffffffff812b11d6: hugepage_vma_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool hugepage_vma_check(struct vm_area_struct *vma, long unsigned int vm_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812c1460)
Location: mm/khugepaged.c:407
Inline: True
Direct callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hugepage_vma_revalidate
```
**Symbols:**

```
ffffffff812c1460-ffffffff812c1516: hugepage_vma_check (STB_LOCAL)
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
<code>long unsigned int vm_flags</code>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool smaps</code>
</li>
<li>
<b>Param added. </b>
<code>bool in_pf</code>
</li>
<li>
<b>Param added. </b>
<code>bool enforce_sysfs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
