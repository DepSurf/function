# Function: <code>pte_swp_uffd_wp_any</code>

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
In mm/memory.c (ffffffff81340c13)
Location: include/linux/userfaultfd_k.h:310
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/rmap.c (ffffffff8135d84d)
Location: include/linux/userfaultfd_k.h:310
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8138f50f)
Location: include/linux/userfaultfd_k.h:310
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In fs/proc/task_mmu.c (ffffffff814994a5)
Location: include/linux/userfaultfd_k.h:310
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
In mm/memory.c (ffffffff813b8bb2)
Location: include/linux/userfaultfd_k.h:309
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/rmap.c (ffffffff813d86ad)
Location: include/linux/userfaultfd_k.h:309
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8140fca0)
Location: include/linux/userfaultfd_k.h:309
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In fs/proc/task_mmu.c (ffffffff8152e73c)
Location: include/linux/userfaultfd_k.h:309
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
In mm/memory.c (ffffffff813ed7f0)
Location: include/linux/userfaultfd_k.h:345
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/rmap.c (ffffffff8140ce9a)
Location: include/linux/userfaultfd_k.h:345
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81443068)
Location: include/linux/userfaultfd_k.h:345
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/khugepaged.c (ffffffff8147efa4)
Location: include/linux/userfaultfd_k.h:345
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81566a4c)
Location: include/linux/userfaultfd_k.h:345
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
In mm/memory.c (ffffffff81418dd3)
Location: include/linux/userfaultfd_k.h:386
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/rmap.c (ffffffff8143958d)
Location: include/linux/userfaultfd_k.h:386
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8147d27e)
Location: include/linux/userfaultfd_k.h:386
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/khugepaged.c (ffffffff814afc82)
Location: include/linux/userfaultfd_k.h:386
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8159d2b0)
Location: include/linux/userfaultfd_k.h:386
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
