# Function: <code>pte_marker_get</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81341273)
Location: include/linux/swapops.h:308
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff81354052)
Location: include/linux/swapops.h:308
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8135da02)
Location: include/linux/swapops.h:308
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81390eb7)
Location: include/linux/swapops.h:308
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In fs/proc/task_mmu.c (ffffffff8149960d)
Location: include/linux/swapops.h:308
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (0)
Location: include/linux/swapops.h:418
Inline: True
```
```
In mm/memory.c (ffffffff813bbb74)
Location: include/linux/swapops.h:418
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_marker
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:418
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/swapops.h:418
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/swapops.h:418
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:418
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/swapops.h:418
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (0)
Location: include/linux/swapops.h:409
Inline: True
```
```
In mm/memory.c (ffffffff813f05b0)
Location: include/linux/swapops.h:409
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_marker
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:409
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/swapops.h:409
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/swapops.h:409
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:409
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/swapops.h:409
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/swapops.h:409
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (0)
Location: include/linux/swapops.h:414
Inline: True
```
```
In mm/memory.c (ffffffff8141fef0)
Location: include/linux/swapops.h:414
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_marker
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:414
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/swapops.h:414
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/swapops.h:414
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:414
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/swapops.h:414
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/swapops.h:414
Inline: True
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
