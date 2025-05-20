# Function: <code>ptep_get</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81287fdd)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/mincore.c (ffffffff81295d94)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff812cb100)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812ce948)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/userfaultfd.c (ffffffff813089a2)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8130b68a)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff8137458b)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff813b6f65)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
In kernel/events/core.c (ffffffff8123cbd2)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff81291cbd)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/mincore.c (ffffffff812a0c84)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff812d6d10)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812da288)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/userfaultfd.c (ffffffff8131477f)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8131754e)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff813824e3)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff813c8605)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
In kernel/events/core.c (ffffffff81243ee7)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff812977dd)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/memory.c (ffffffff8129fbff)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mincore.c (ffffffff812a6564)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff812ddf40)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812e1ae8)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/userfaultfd.c (ffffffff8131a92c)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8131d24e)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/ptdump.c (ffffffff8131ed05)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pte_entry
```
```
In fs/userfaultfd.c (ffffffff81389569)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff813cf645)
Location: include/linux/pgtable.h:255
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
In kernel/events/core.c (ffffffff8127e857)
Location: include/linux/pgtable.h:274
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff812d819d)
Location: include/linux/pgtable.h:274
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/memory.c (ffffffff812e31f5)
Location: include/linux/pgtable.h:274
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mincore.c (ffffffff812e7a34)
Location: include/linux/pgtable.h:274
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff81325150)
Location: include/linux/pgtable.h:274
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81328bc3)
Location: include/linux/pgtable.h:274
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/memory-failure.c (ffffffff8135ec30)
Location: include/linux/pgtable.h:274
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
```
```
In mm/userfaultfd.c (ffffffff81367828)
Location: include/linux/pgtable.h:274
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8136a5e9)
Location: include/linux/pgtable.h:274
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/ptdump.c (ffffffff8136c0e5)
Location: include/linux/pgtable.h:274
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pte_entry
```
```
In fs/userfaultfd.c (ffffffff813d6863)
Location: include/linux/pgtable.h:274
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81420a25)
Location: include/linux/pgtable.h:274
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d34c4)
Location: include/linux/pgtable.h:282
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff81338096)
Location: include/linux/pgtable.h:282
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/memory.c (ffffffff8134457c)
Location: include/linux/pgtable.h:282
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mincore.c (ffffffff81348c94)
Location: include/linux/pgtable.h:282
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff81393a9c)
Location: include/linux/pgtable.h:282
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81397e03)
Location: include/linux/pgtable.h:282
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff813b4b5a)
Location: include/linux/pgtable.h:282
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait_huge
```
```
In mm/memory-failure.c (ffffffff813d90c0)
Location: include/linux/pgtable.h:282
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
```
```
In mm/userfaultfd.c (ffffffff813e4efc)
Location: include/linux/pgtable.h:282
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff813e81ac)
Location: include/linux/pgtable.h:282
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/ptdump.c (ffffffff813ea365)
Location: include/linux/pgtable.h:282
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pte_entry
```
```
In fs/userfaultfd.c (ffffffff8145d9ed)
Location: include/linux/pgtable.h:282
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81499905)
Location: include/linux/pgtable.h:282
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
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
In kernel/events/core.c (ffffffff8133b742)
Location: include/linux/pgtable.h:313
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff813af833)
Location: include/linux/pgtable.h:313
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/memory.c (ffffffff813bc6b4)
Location: include/linux/pgtable.h:313
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mincore.c (ffffffff813c1044)
Location: include/linux/pgtable.h:313
Inline: True
Inline callers:
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/hugetlb.c (ffffffff8141245e)
Location: include/linux/pgtable.h:313
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81417a8a)
Location: include/linux/pgtable.h:313
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff81433cea)
Location: include/linux/pgtable.h:313
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait_huge
```
```
In mm/memory-failure.c (ffffffff8145f0e0)
Location: include/linux/pgtable.h:313
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
```
```
In mm/userfaultfd.c (ffffffff8146c9df)
Location: include/linux/pgtable.h:313
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff814700ba)
Location: include/linux/pgtable.h:313
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/ptdump.c (ffffffff81472455)
Location: include/linux/pgtable.h:313
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pte_entry
```
```
In fs/userfaultfd.c (ffffffff814ed41d)
Location: include/linux/pgtable.h:313
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152db15)
Location: include/linux/pgtable.h:313
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6606)
Location: include/linux/pgtable.h:313
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
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
In kernel/events/core.c (ffffffff8136d101)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In kernel/events/uprobes.c (ffffffff81380de3)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8138fb48)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/vmscan.c (ffffffff813b78af)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
```
```
In mm/gup.c (ffffffff813e3fb8)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813eb488)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:follow_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mincore.c (ffffffff813f672e)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mlock.c (ffffffff813f9672)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff8140261a)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81404bbf)
Location: include/linux/pgtable.h:216
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff814075ef)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff8140e7db)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/vmalloc.c (ffffffff814129d7)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff81427864)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8142c78a)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff814321ef)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81441aab)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff814477f1)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/mempolicy.c (ffffffff8144b00d)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff8214fdb9)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff81453bcf)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate.c (ffffffff814696b4)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146f462)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff814816c9)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/memcontrol.c (ffffffff8148e40f)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff81495090)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff814a15f2)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_pte_zeropage
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814a4890)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a6735)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In mm/ptdump.c (ffffffff814a6bb5)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pte_entry
```
```
In fs/userfaultfd.c (ffffffff8152412b)
Location: include/linux/pgtable.h:216
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81565f45)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/hugetlbfs/inode.c (ffffffff8162e6cc)
Location: include/linux/pgtable.h:216
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
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
In kernel/events/core.c (ffffffff81396341)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In kernel/events/uprobes.c (ffffffff813aa1ab)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff813b94df)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
```
```
In mm/vmscan.c (ffffffff813e06e1)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
```
```
In mm/gup.c (ffffffff8140e818)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8141540a)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:follow_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:alloc_anon_folio
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mincore.c (ffffffff814223de)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mlock.c (ffffffff81425215)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff8142ecba)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff814311a3)
Location: include/linux/pgtable.h:289
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81433c63)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff8143afe7)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/vmalloc.c (ffffffff8143f447)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff81461041)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81465eda)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff8146b5df)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8147bd1b)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff814811d1)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
  - mm/hugetlb_vmemmap.c:vmemmap_pte_entry
  - mm/hugetlb_vmemmap.c:vmemmap_pmd_entry
```
```
In mm/mempolicy.c (ffffffff81484a0d)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff82232be9)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff8148e416)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate.c (ffffffff814985e4)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149d2f7)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff814b066b)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/memcontrol.c (ffffffff814bdc7c)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff814c4990)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff814d2c11)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814d58c0)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d7795)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In mm/ptdump.c (ffffffff814d7bb5)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pte_entry
```
```
In fs/userfaultfd.c (ffffffff8155876c)
Location: include/linux/pgtable.h:289
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159df15)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_scan_hugetlb_entry
  - fs/proc/task_mmu.c:pagemap_scan_hugetlb_entry
  - fs/proc/task_mmu.c:pagemap_scan_pmd_entry
  - fs/proc/task_mmu.c:pagemap_scan_pmd_entry
  - fs/proc/task_mmu.c:pagemap_scan_pmd_entry
  - fs/proc/task_mmu.c:make_uffd_wp_pte
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/hugetlbfs/inode.c (ffffffff81667b9c)
Location: include/linux/pgtable.h:289
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
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
