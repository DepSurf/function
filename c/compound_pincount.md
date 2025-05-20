# Function: <code>compound_pincount</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff81287149)
Location: include/linux/mm.h:904
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81270f38)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (ffffffff81299d84)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/huge_memory.c (ffffffff812f7f13)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813c8014)
Location: include/linux/mm.h:942
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81275a6d)
Location: include/linux/mm.h:965
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (ffffffff8129ef27)
Location: include/linux/mm.h:965
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/hugetlb.c (ffffffff812dcd25)
Location: include/linux/mm.h:965
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff812fe458)
Location: include/linux/mm.h:965
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813cf044)
Location: include/linux/mm.h:965
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b377f)
Location: include/linux/mm.h:969
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (ffffffff812e0122)
Location: include/linux/mm.h:969
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/hugetlb.c (ffffffff81323f2d)
Location: include/linux/mm.h:969
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff81348000)
Location: include/linux/mm.h:969
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8142052b)
Location: include/linux/mm.h:969
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
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
