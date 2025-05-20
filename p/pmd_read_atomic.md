# Function: <code>pmd_read_atomic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bd7b3)
Location: include/asm-generic/pgtable.h:636
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mincore.c (ffffffff811c274d)
Location: include/asm-generic/pgtable.h:636
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/pagewalk.c (ffffffff811cffa4)
Location: include/asm-generic/pgtable.h:636
Inline: True
```
```
In mm/madvise.c (ffffffff811d14cd)
Location: include/asm-generic/pgtable.h:636
Inline: True
Inline callers:
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff811d4328)
Location: include/asm-generic/pgtable.h:636
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff811e0052)
Location: include/asm-generic/pgtable.h:636
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memcontrol.c (ffffffff811fafb2)
Location: include/asm-generic/pgtable.h:636
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In mm/userfaultfd.c (ffffffff81207936)
Location: include/asm-generic/pgtable.h:636
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_zeropage
```
```
In fs/proc/task_mmu.c (ffffffff812782d8)
Location: include/asm-generic/pgtable.h:636
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811d5285)
Location: include/asm-generic/pgtable.h:645
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811db8ad)
Location: include/asm-generic/pgtable.h:645
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:unmap_page_range
```
```
In mm/mincore.c (ffffffff811de31e)
Location: include/asm-generic/pgtable.h:645
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811e495b)
Location: include/asm-generic/pgtable.h:645
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e5c25)
Location: include/asm-generic/pgtable.h:645
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff811ed133)
Location: include/asm-generic/pgtable.h:645
Inline: True
```
```
In mm/madvise.c (ffffffff811eeac5)
Location: include/asm-generic/pgtable.h:645
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff811f210e)
Location: include/asm-generic/pgtable.h:645
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff811fed54)
Location: include/asm-generic/pgtable.h:645
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memcontrol.c (ffffffff81221098)
Location: include/asm-generic/pgtable.h:645
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8122d7b1)
Location: include/asm-generic/pgtable.h:645
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/proc/task_mmu.c (ffffffff812a55df)
Location: include/asm-generic/pgtable.h:645
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811e52a0)
Location: include/asm-generic/pgtable.h:668
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811eb372)
Location: include/asm-generic/pgtable.h:668
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:unmap_page_range
```
```
In mm/mincore.c (ffffffff811ee12e)
Location: include/asm-generic/pgtable.h:668
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811f494d)
Location: include/asm-generic/pgtable.h:668
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f5ea5)
Location: include/asm-generic/pgtable.h:668
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff811f7523)
Location: include/asm-generic/pgtable.h:668
Inline: True
```
```
In mm/madvise.c (ffffffff811ff405)
Location: include/asm-generic/pgtable.h:668
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81202b0d)
Location: include/asm-generic/pgtable.h:668
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff81210590)
Location: include/asm-generic/pgtable.h:668
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memcontrol.c (ffffffff812337df)
Location: include/asm-generic/pgtable.h:668
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8123fcef)
Location: include/asm-generic/pgtable.h:668
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/proc/task_mmu.c (ffffffff812baf2f)
Location: include/asm-generic/pgtable.h:668
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811ef947)
Location: include/asm-generic/pgtable.h:782
Inline: True
```
```
In mm/memory.c (ffffffff811f1664)
Location: include/asm-generic/pgtable.h:782
Inline: True
```
```
In mm/mincore.c (ffffffff811f913b)
Location: include/asm-generic/pgtable.h:782
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811ff898)
Location: include/asm-generic/pgtable.h:782
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81200c9d)
Location: include/asm-generic/pgtable.h:782
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8120276a)
Location: include/asm-generic/pgtable.h:782
Inline: True
```
```
In mm/madvise.c (ffffffff8120a0bb)
Location: include/asm-generic/pgtable.h:782
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8120dbc1)
Location: include/asm-generic/pgtable.h:782
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff8121bf88)
Location: include/asm-generic/pgtable.h:782
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memcontrol.c (ffffffff8123f085)
Location: include/asm-generic/pgtable.h:782
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8124bb37)
Location: include/asm-generic/pgtable.h:782
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/proc/task_mmu.c (ffffffff812c80af)
Location: include/asm-generic/pgtable.h:782
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81206aae)
Location: include/asm-generic/pgtable.h:835
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff81208354)
Location: include/asm-generic/pgtable.h:835
Inline: True
```
```
In mm/mincore.c (ffffffff812114be)
Location: include/asm-generic/pgtable.h:835
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81217ee1)
Location: include/asm-generic/pgtable.h:835
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81219198)
Location: include/asm-generic/pgtable.h:835
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8121b425)
Location: include/asm-generic/pgtable.h:835
Inline: True
```
```
In mm/madvise.c (ffffffff812232d7)
Location: include/asm-generic/pgtable.h:835
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81228df5)
Location: include/asm-generic/pgtable.h:835
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff8123738b)
Location: include/asm-generic/pgtable.h:835
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8124b5fa)
Location: include/asm-generic/pgtable.h:835
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff8125ec0d)
Location: include/asm-generic/pgtable.h:835
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8126be7b)
Location: include/asm-generic/pgtable.h:835
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8126e5bf)
Location: include/asm-generic/pgtable.h:835
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff812eb9c5)
Location: include/asm-generic/pgtable.h:835
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/asm-generic/pgtable.h:878
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:878
Inline: True
```
```
In mm/mincore.c (0)
Location: include/asm-generic/pgtable.h:878
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:878
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:878
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:878
Inline: True
```
```
In mm/madvise.c (0)
Location: include/asm-generic/pgtable.h:878
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:878
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/pgtable.h:878
Inline: True
```
```
In mm/migrate.c (0)
Location: include/asm-generic/pgtable.h:878
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/asm-generic/pgtable.h:878
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/pgtable.h:878
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/pgtable.h:878
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/pgtable.h:878
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mincore.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/madvise.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/migrate.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mincore.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/madvise.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
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
In mm/gup.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mincore.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/madvise.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/migrate.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
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
In mm/gup.c (ffffffff81288e0f)
Location: include/linux/pgtable.h:1130
Inline: True
```
```
In mm/memory.c (ffffffff81292238)
Location: include/linux/pgtable.h:1130
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:unmap_page_range
```
```
In mm/mincore.c (ffffffff812963e3)
Location: include/linux/pgtable.h:1130
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8129e465)
Location: include/linux/pgtable.h:1130
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812a03c4)
Location: include/linux/pgtable.h:1130
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812a275b)
Location: include/linux/pgtable.h:1130
Inline: True
```
```
In mm/madvise.c (ffffffff812b67b3)
Location: include/linux/pgtable.h:1130
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812bde94)
Location: include/linux/pgtable.h:1130
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/mempolicy.c (ffffffff812ced1e)
Location: include/linux/pgtable.h:1130
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812e4339)
Location: include/linux/pgtable.h:1130
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff812fb9c3)
Location: include/linux/pgtable.h:1130
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff81308d7f)
Location: include/linux/pgtable.h:1130
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8130b324)
Location: include/linux/pgtable.h:1130
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c83f)
Location: include/linux/pgtable.h:1130
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/proc/task_mmu.c (ffffffff813b7fc2)
Location: include/linux/pgtable.h:1130
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/gup.c (ffffffff81292aef)
Location: include/linux/pgtable.h:1220
Inline: True
```
```
In mm/memory.c (ffffffff8129cae8)
Location: include/linux/pgtable.h:1220
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:unmap_page_range
```
```
In mm/mincore.c (ffffffff812a1356)
Location: include/linux/pgtable.h:1220
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812a9844)
Location: include/linux/pgtable.h:1220
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812ab8df)
Location: include/linux/pgtable.h:1220
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812ae09b)
Location: include/linux/pgtable.h:1220
Inline: True
```
```
In mm/madvise.c (ffffffff812c2a03)
Location: include/linux/pgtable.h:1220
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812c99b8)
Location: include/linux/pgtable.h:1220
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/mempolicy.c (ffffffff812da65e)
Location: include/linux/pgtable.h:1220
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812effb3)
Location: include/linux/pgtable.h:1220
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff81307613)
Location: include/linux/pgtable.h:1220
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff81314b8a)
Location: include/linux/pgtable.h:1220
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff813171e4)
Location: include/linux/pgtable.h:1220
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131877f)
Location: include/linux/pgtable.h:1220
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/proc/task_mmu.c (ffffffff813c9e82)
Location: include/linux/pgtable.h:1220
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/filemap.c (ffffffff8125facd)
Location: include/linux/pgtable.h:1232
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff812984e7)
Location: include/linux/pgtable.h:1232
Inline: True
```
```
In mm/memory.c (ffffffff812a21fb)
Location: include/linux/pgtable.h:1232
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
```
```
In mm/mincore.c (ffffffff812a6b4f)
Location: include/linux/pgtable.h:1232
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812aecd4)
Location: include/linux/pgtable.h:1232
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812b0ccf)
Location: include/linux/pgtable.h:1232
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812b348a)
Location: include/linux/pgtable.h:1232
Inline: True
```
```
In mm/madvise.c (ffffffff812c9883)
Location: include/linux/pgtable.h:1232
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812d0624)
Location: include/linux/pgtable.h:1232
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff812e1ece)
Location: include/linux/pgtable.h:1232
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812f5a48)
Location: include/linux/pgtable.h:1232
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff8130dd91)
Location: include/linux/pgtable.h:1232
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8131ad37)
Location: include/linux/pgtable.h:1232
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8131d4dd)
Location: include/linux/pgtable.h:1232
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e96f)
Location: include/linux/pgtable.h:1232
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/proc/task_mmu.c (ffffffff813d14e2)
Location: include/linux/pgtable.h:1232
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/filemap.c (ffffffff8129c43d)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff812d8f25)
Location: include/linux/pgtable.h:1251
Inline: True
```
```
In mm/memory.c (ffffffff812e356b)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_anonymous_page
```
```
In mm/mincore.c (ffffffff812e802f)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812f04c4)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812f270e)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812f5017)
Location: include/linux/pgtable.h:1251
Inline: True
```
```
In mm/madvise.c (ffffffff8130e8a3)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81315b6e)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff81328fae)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8134000c)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff81358bf1)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8135f3ea)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff81368127)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8136a87d)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bd4f)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/proc/task_mmu.c (ffffffff814229e2)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/filemap.c (ffffffff812f357e)
Location: include/linux/pgtable.h:1313
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff81338ec4)
Location: include/linux/pgtable.h:1313
Inline: True
```
```
In mm/memory.c (ffffffff8134490a)
Location: include/linux/pgtable.h:1313
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
```
```
In mm/mincore.c (ffffffff81349346)
Location: include/linux/pgtable.h:1313
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff813539cd)
Location: include/linux/pgtable.h:1313
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8135673d)
Location: include/linux/pgtable.h:1313
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81358f6e)
Location: include/linux/pgtable.h:1313
Inline: True
```
```
In mm/madvise.c (ffffffff81376725)
Location: include/linux/pgtable.h:1313
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81381168)
Location: include/linux/pgtable.h:1313
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff81398219)
Location: include/linux/pgtable.h:1313
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate_device.c (ffffffff813b754e)
Location: include/linux/pgtable.h:1313
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff813d2e23)
Location: include/linux/pgtable.h:1313
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff813d9a81)
Location: include/linux/pgtable.h:1313
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff813e595a)
Location: include/linux/pgtable.h:1313
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff813e8a83)
Location: include/linux/pgtable.h:1313
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9f5f)
Location: include/linux/pgtable.h:1313
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/proc/task_mmu.c (ffffffff81499afd)
Location: include/linux/pgtable.h:1313
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_range
```
</details>
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
In mm/gup.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mincore.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/madvise.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/madvise.c (c0537214)
Location: include/asm-generic/pgtable.h:916
Inline: True
Inline callers:
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (c053d578)
Location: include/asm-generic/pgtable.h:916
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/userfaultfd.c (c0563fdc)
Location: include/asm-generic/pgtable.h:916
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
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
In mm/gup.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mincore.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/madvise.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/migrate.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/madvise.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
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
In mm/gup.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mincore.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/madvise.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/migrate.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
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
In mm/gup.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mincore.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/madvise.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/migrate.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
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
In mm/gup.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mincore.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/madvise.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/migrate.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
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
In mm/gup.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mincore.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/madvise.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/migrate.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/pgtable.h:916
Inline: True
```
</details>
</li>
</ul>

## Differences
