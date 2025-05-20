# Function: <code>mmget_still_valid</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125cd58)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
```
```
In mm/khugepaged.c (ffffffff812ab698)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/userfaultfd.c (ffffffff81325888)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/proc/task_mmu.c (ffffffff813573cc)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126b528)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
```
```
In mm/khugepaged.c (ffffffff812bce98)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/userfaultfd.c (ffffffff81338728)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/proc/task_mmu.c (ffffffff8136ef09)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129ac58)
Location: include/linux/sched/mm.h:74
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
```
```
In mm/madvise.c (ffffffff812b62f7)
Location: include/linux/sched/mm.h:74
Inline: True
```
```
In mm/khugepaged.c (ffffffff812f3b2c)
Location: include/linux/sched/mm.h:74
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:hugepage_vma_revalidate
```
```
In fs/userfaultfd.c (ffffffff81372607)
Location: include/linux/sched/mm.h:74
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/proc/task_mmu.c (ffffffff813b724e)
Location: include/linux/sched/mm.h:74
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a2892)
Location: include/linux/sched/mm.h:74
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010302ce0)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
```
```
In mm/khugepaged.c (ffff80001035e254)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/userfaultfd.c (ffff8000103f8300)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c052133c)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
```
```
In fs/userfaultfd.c (c05cbf88)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cf45c)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
```
```
In mm/khugepaged.c (c0000000004475e0)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/userfaultfd.c (c0000000004ff6d0)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020fa44)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
```
```
In fs/userfaultfd.c (ffffffe0002a7448)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81263b78)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
```
```
In mm/khugepaged.c (ffffffff812b5478)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/userfaultfd.c (ffffffff81330d08)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/proc/task_mmu.c (ffffffff813674e9)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81255f98)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
```
```
In mm/khugepaged.c (ffffffff812a64b1)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/userfaultfd.c (ffffffff81321d58)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/proc/task_mmu.c (ffffffff81358189)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81261918)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
```
```
In mm/khugepaged.c (ffffffff812b3288)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/userfaultfd.c (ffffffff8132e7d8)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/proc/task_mmu.c (ffffffff81364fb9)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812712d8)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - mm/mmap.c:find_extend_vma
```
```
In mm/khugepaged.c (ffffffff812c36d8)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/userfaultfd.c (ffffffff81341fbd)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/proc/task_mmu.c (ffffffff81377ff6)
Location: include/linux/sched/mm.h:72
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
</details>
</li>
</ul>

## Differences
