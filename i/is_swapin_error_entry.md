# Function: <code>is_swapin_error_entry</code>

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
In mm/shmem.c (ffffffff813185ad)
Location: include/linux/swapops.h:116
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:116
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/swapops.h:116
Inline: True
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
In mm/shmem.c (ffffffff8138c4a8)
Location: include/linux/swapops.h:438
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/memory.c (ffffffff813b933c)
Location: include/linux/swapops.h:438
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mprotect.c (ffffffff813ce4d8)
Location: include/linux/swapops.h:438
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/madvise.c (ffffffff813f43bd)
Location: include/linux/swapops.h:438
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff8140f228)
Location: include/linux/swapops.h:438
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
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
In mm/shmem.c (ffffffff813bea9e)
Location: include/linux/swapops.h:429
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/memory.c (ffffffff813ede6a)
Location: include/linux/swapops.h:429
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mprotect.c (ffffffff81402d84)
Location: include/linux/swapops.h:429
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/madvise.c (ffffffff81427aaa)
Location: include/linux/swapops.h:429
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff8144259a)
Location: include/linux/swapops.h:429
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
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
