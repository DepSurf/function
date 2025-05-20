# Function: <code>pmd_none_or_trans_huge_or_clear_bad</code>

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
Location: include/asm-generic/pgtable.h:680
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:handle_mm_fault
```
```
In mm/mincore.c (ffffffff811c274d)
Location: include/asm-generic/pgtable.h:680
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/pagewalk.c (ffffffff811cffa4)
Location: include/asm-generic/pgtable.h:680
Inline: True
```
```
In mm/madvise.c (ffffffff811d14cd)
Location: include/asm-generic/pgtable.h:680
Inline: True
Inline callers:
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff811d4328)
Location: include/asm-generic/pgtable.h:680
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff811e0052)
Location: include/asm-generic/pgtable.h:680
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memcontrol.c (ffffffff811fafb2)
Location: include/asm-generic/pgtable.h:680
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff812782d8)
Location: include/asm-generic/pgtable.h:680
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
Location: include/asm-generic/pgtable.h:689
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811dac55)
Location: include/asm-generic/pgtable.h:689
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
```
```
In mm/mincore.c (ffffffff811de31e)
Location: include/asm-generic/pgtable.h:689
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811e495b)
Location: include/asm-generic/pgtable.h:689
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e5c25)
Location: include/asm-generic/pgtable.h:689
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff811ed133)
Location: include/asm-generic/pgtable.h:689
Inline: True
```
```
In mm/madvise.c (ffffffff811eeac5)
Location: include/asm-generic/pgtable.h:689
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff811f210e)
Location: include/asm-generic/pgtable.h:689
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff811fed54)
Location: include/asm-generic/pgtable.h:689
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memcontrol.c (ffffffff81221098)
Location: include/asm-generic/pgtable.h:689
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff812a55df)
Location: include/asm-generic/pgtable.h:689
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
Location: include/asm-generic/pgtable.h:703
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811ea818)
Location: include/asm-generic/pgtable.h:703
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
```
```
In mm/mincore.c (ffffffff811ee12e)
Location: include/asm-generic/pgtable.h:703
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811f494d)
Location: include/asm-generic/pgtable.h:703
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f5ea5)
Location: include/asm-generic/pgtable.h:703
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff811f7523)
Location: include/asm-generic/pgtable.h:703
Inline: True
```
```
In mm/madvise.c (ffffffff811ff405)
Location: include/asm-generic/pgtable.h:703
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81202b0d)
Location: include/asm-generic/pgtable.h:703
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff81210590)
Location: include/asm-generic/pgtable.h:703
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memcontrol.c (ffffffff812337df)
Location: include/asm-generic/pgtable.h:703
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff812baf2f)
Location: include/asm-generic/pgtable.h:703
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
Location: include/asm-generic/pgtable.h:817
Inline: True
```
```
In mm/memory.c (ffffffff811f5d89)
Location: include/asm-generic/pgtable.h:817
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mincore.c (ffffffff811f913b)
Location: include/asm-generic/pgtable.h:817
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811ff898)
Location: include/asm-generic/pgtable.h:817
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81200c9d)
Location: include/asm-generic/pgtable.h:817
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81202366)
Location: include/asm-generic/pgtable.h:817
Inline: True
```
```
In mm/madvise.c (ffffffff8120a0bb)
Location: include/asm-generic/pgtable.h:817
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8120dba0)
Location: include/asm-generic/pgtable.h:817
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff8121bf88)
Location: include/asm-generic/pgtable.h:817
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memcontrol.c (ffffffff8123f085)
Location: include/asm-generic/pgtable.h:817
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff812c80af)
Location: include/asm-generic/pgtable.h:817
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
Location: include/asm-generic/pgtable.h:870
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff8120d7e9)
Location: include/asm-generic/pgtable.h:870
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mincore.c (ffffffff812114be)
Location: include/asm-generic/pgtable.h:870
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81217ee1)
Location: include/asm-generic/pgtable.h:870
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81219198)
Location: include/asm-generic/pgtable.h:870
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8121b425)
Location: include/asm-generic/pgtable.h:870
Inline: True
```
```
In mm/madvise.c (ffffffff812232d7)
Location: include/asm-generic/pgtable.h:870
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81228df5)
Location: include/asm-generic/pgtable.h:870
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff8123738b)
Location: include/asm-generic/pgtable.h:870
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8124b5fa)
Location: include/asm-generic/pgtable.h:870
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff8125ec0d)
Location: include/asm-generic/pgtable.h:870
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff812eb9c5)
Location: include/asm-generic/pgtable.h:870
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
In mm/gup.c (ffffffff81227a3c)
Location: include/asm-generic/pgtable.h:913
Inline: True
```
```
In mm/memory.c (ffffffff8122e400)
Location: include/asm-generic/pgtable.h:913
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mincore.c (ffffffff8123225e)
Location: include/asm-generic/pgtable.h:913
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81239040)
Location: include/asm-generic/pgtable.h:913
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8123ab3b)
Location: include/asm-generic/pgtable.h:913
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8123d18a)
Location: include/asm-generic/pgtable.h:913
Inline: True
```
```
In mm/madvise.c (ffffffff81246149)
Location: include/asm-generic/pgtable.h:913
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8124a0ed)
Location: include/asm-generic/pgtable.h:913
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff8125a8ce)
Location: include/asm-generic/pgtable.h:913
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8126e2e5)
Location: include/asm-generic/pgtable.h:913
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff81282f79)
Location: include/asm-generic/pgtable.h:913
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff81318e85)
Location: include/asm-generic/pgtable.h:913
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
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8123b213)
Location: include/asm-generic/pgtable.h:951
Inline: True
```
```
In mm/memory.c (ffffffff81242257)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mincore.c (ffffffff81245a2e)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8124d5e2)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124ed47)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81251662)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/madvise.c (ffffffff8125a569)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8125e72d)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff8126e794)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81283173)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff81298fc9)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff8132ff35)
Location: include/asm-generic/pgtable.h:951
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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124c449)
Location: include/asm-generic/pgtable.h:951
Inline: True
```
```
In mm/memory.c (ffffffff8124fb7b)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/mincore.c (ffffffff81257b83)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8125f5b5)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8126109d)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81263929)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/madvise.c (ffffffff81275646)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8127b98a)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff81289de9)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memcontrol.c (ffffffff812b43b3)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff81357d67)
Location: include/asm-generic/pgtable.h:951
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
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125a9f6)
Location: include/asm-generic/pgtable.h:951
Inline: True
```
```
In mm/memory.c (ffffffff8125e11b)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/mincore.c (ffffffff81266093)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8126ddc5)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8126f836)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81271e0e)
Location: include/asm-generic/pgtable.h:951
Inline: True
```
```
In mm/madvise.c (ffffffff81284616)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8128b46a)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff81299959)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812aed2c)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff812c5cd3)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff8136ff97)
Location: include/asm-generic/pgtable.h:951
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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81288e0f)
Location: include/linux/pgtable.h:1165
Inline: True
```
```
In mm/memory.c (ffffffff81292238)
Location: include/linux/pgtable.h:1165
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:unmap_page_range
```
```
In mm/mincore.c (ffffffff812963e3)
Location: include/linux/pgtable.h:1165
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8129e465)
Location: include/linux/pgtable.h:1165
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812a03c4)
Location: include/linux/pgtable.h:1165
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812a275b)
Location: include/linux/pgtable.h:1165
Inline: True
```
```
In mm/madvise.c (ffffffff812b67b3)
Location: include/linux/pgtable.h:1165
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812bde94)
Location: include/linux/pgtable.h:1165
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/mempolicy.c (ffffffff812ced1e)
Location: include/linux/pgtable.h:1165
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812e4339)
Location: include/linux/pgtable.h:1165
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff812fb9c3)
Location: include/linux/pgtable.h:1165
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c843)
Location: include/linux/pgtable.h:1165
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/proc/task_mmu.c (ffffffff813b7fc2)
Location: include/linux/pgtable.h:1165
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
Location: include/linux/pgtable.h:1255
Inline: True
```
```
In mm/memory.c (ffffffff8129cae8)
Location: include/linux/pgtable.h:1255
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:unmap_page_range
```
```
In mm/mincore.c (ffffffff812a1356)
Location: include/linux/pgtable.h:1255
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812a9844)
Location: include/linux/pgtable.h:1255
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812ab8df)
Location: include/linux/pgtable.h:1255
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812ae09b)
Location: include/linux/pgtable.h:1255
Inline: True
```
```
In mm/madvise.c (ffffffff812c2a03)
Location: include/linux/pgtable.h:1255
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812c99b8)
Location: include/linux/pgtable.h:1255
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/mempolicy.c (ffffffff812da65e)
Location: include/linux/pgtable.h:1255
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812effb3)
Location: include/linux/pgtable.h:1255
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff81307613)
Location: include/linux/pgtable.h:1255
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff81318783)
Location: include/linux/pgtable.h:1255
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/proc/task_mmu.c (ffffffff813c9e82)
Location: include/linux/pgtable.h:1255
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
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_none_or_trans_huge_or_clear_bad(pmd_t *pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125facd)
Location: include/linux/pgtable.h:1267
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff812984e7)
Location: include/linux/pgtable.h:1267
Inline: True
```
```
In mm/memory.c (ffffffff812a21fb)
Location: include/linux/pgtable.h:1267
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
```
```
In mm/mincore.c (ffffffff812a6b4f)
Location: include/linux/pgtable.h:1267
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812aecd4)
Location: include/linux/pgtable.h:1267
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812b0ccf)
Location: include/linux/pgtable.h:1267
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812b348a)
Location: include/linux/pgtable.h:1267
Inline: True
```
```
In mm/madvise.c (ffffffff812c9883)
Location: include/linux/pgtable.h:1267
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812d0624)
Location: include/linux/pgtable.h:1267
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff812e1ece)
Location: include/linux/pgtable.h:1267
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812f5a48)
Location: include/linux/pgtable.h:1267
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff8130dd91)
Location: include/linux/pgtable.h:1267
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e973)
Location: include/linux/pgtable.h:1267
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/proc/task_mmu.c (ffffffff813d14e2)
Location: include/linux/pgtable.h:1267
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_range
Direct callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff813cfe50-ffffffff813cfee3: pmd_none_or_trans_huge_or_clear_bad (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_none_or_trans_huge_or_clear_bad(pmd_t *pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129c43d)
Location: include/linux/pgtable.h:1286
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff812d8f25)
Location: include/linux/pgtable.h:1286
Inline: True
```
```
In mm/memory.c (ffffffff812e356b)
Location: include/linux/pgtable.h:1286
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_anonymous_page
Direct callers:
  - mm/memory.c:finish_fault
```
```
In mm/mincore.c (ffffffff812e802f)
Location: include/linux/pgtable.h:1286
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812f04c4)
Location: include/linux/pgtable.h:1286
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812f270e)
Location: include/linux/pgtable.h:1286
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812f5017)
Location: include/linux/pgtable.h:1286
Inline: True
```
```
In mm/madvise.c (ffffffff8130e8a3)
Location: include/linux/pgtable.h:1286
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81315b6e)
Location: include/linux/pgtable.h:1286
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff81328fae)
Location: include/linux/pgtable.h:1286
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8134000c)
Location: include/linux/pgtable.h:1286
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff81358bf1)
Location: include/linux/pgtable.h:1286
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8135f3ea)
Location: include/linux/pgtable.h:1286
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bd53)
Location: include/linux/pgtable.h:1286
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/proc/task_mmu.c (ffffffff814229e2)
Location: include/linux/pgtable.h:1286
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_range
Direct callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff812dd620-ffffffff812dd6b3: pmd_none_or_trans_huge_or_clear_bad (STB_LOCAL)
ffffffff81421470-ffffffff81421503: pmd_none_or_trans_huge_or_clear_bad (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_none_or_trans_huge_or_clear_bad(pmd_t *pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f357e)
Location: include/linux/pgtable.h:1348
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff81338ec4)
Location: include/linux/pgtable.h:1348
Inline: True
```
```
In mm/memory.c (ffffffff8134490a)
Location: include/linux/pgtable.h:1348
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
```
```
In mm/mincore.c (ffffffff81349346)
Location: include/linux/pgtable.h:1348
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff813539cd)
Location: include/linux/pgtable.h:1348
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8135673d)
Location: include/linux/pgtable.h:1348
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81358f6e)
Location: include/linux/pgtable.h:1348
Inline: True
```
```
In mm/madvise.c (ffffffff81376725)
Location: include/linux/pgtable.h:1348
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81381168)
Location: include/linux/pgtable.h:1348
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff81398219)
Location: include/linux/pgtable.h:1348
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate_device.c (ffffffff813b754e)
Location: include/linux/pgtable.h:1348
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff813d2e23)
Location: include/linux/pgtable.h:1348
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff813d9a81)
Location: include/linux/pgtable.h:1348
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9f63)
Location: include/linux/pgtable.h:1348
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/proc/task_mmu.c (ffffffff81499afd)
Location: include/linux/pgtable.h:1348
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_range
Direct callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff814990f0-ffffffff81499194: pmd_none_or_trans_huge_or_clear_bad (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_none_or_trans_huge_or_clear_bad(pmd_t *pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135d8d1)
Location: include/linux/pgtable.h:1371
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff813b0817)
Location: include/linux/pgtable.h:1371
Inline: True
```
```
In mm/memory.c (ffffffff813bcb0a)
Location: include/linux/pgtable.h:1371
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
```
```
In mm/mincore.c (ffffffff813c170c)
Location: include/linux/pgtable.h:1371
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff813cde74)
Location: include/linux/pgtable.h:1371
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813d0d38)
Location: include/linux/pgtable.h:1371
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff813d38c1)
Location: include/linux/pgtable.h:1371
Inline: True
```
```
In mm/madvise.c (ffffffff813f4073)
Location: include/linux/pgtable.h:1371
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff813ff8fb)
Location: include/linux/pgtable.h:1371
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff81417fa0)
Location: include/linux/pgtable.h:1371
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate_device.c (ffffffff814390b9)
Location: include/linux/pgtable.h:1371
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff81458627)
Location: include/linux/pgtable.h:1371
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8145fe2d)
Location: include/linux/pgtable.h:1371
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff81472005)
Location: include/linux/pgtable.h:1371
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/proc/task_mmu.c (ffffffff8152dd33)
Location: include/linux/pgtable.h:1371
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_range
Direct callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8152d490-ffffffff8152d544: pmd_none_or_trans_huge_or_clear_bad (STB_LOCAL)
```
</details>
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
In mm/gup.c (ffff8000102f22a0)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffff8000102f9d28)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:unmap_page_range
```
```
In mm/mincore.c (ffff8000102fcfb8)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffff800010305064)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffff800010305fb8)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffff800010307a44)
Location: include/asm-generic/pgtable.h:951
Inline: True
```
```
In mm/madvise.c (ffff80001031ea14)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffff800010326794)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffff8000103385e4)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memcontrol.c (ffff800010368a0c)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffff800010439b8c)
Location: include/asm-generic/pgtable.h:951
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
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0518d60)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/madvise.c (c0537214)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (c053d578)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/gup.c (c0000000003b83f4)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (c0000000003c3df4)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:unmap_page_range
```
```
In mm/mincore.c (c0000000003c83a0)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (c0000000003d20c8)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d3df4)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (c0000000003d6848)
Location: include/asm-generic/pgtable.h:951
Inline: True
```
```
In mm/madvise.c (c0000000003f2e9c)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (c0000000003fcfd8)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (c000000000413094)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (c000000000434ad0)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (c000000000456a68)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (c00000000054d410)
Location: include/asm-generic/pgtable.h:951
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
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020756a)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/madvise.c (ffffffe000220950)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffe000226926)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/gup.c (ffffffff81253046)
Location: include/asm-generic/pgtable.h:951
Inline: True
```
```
In mm/memory.c (ffffffff8125676b)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/mincore.c (ffffffff8125e6e3)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81266415)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81267e86)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8126a45e)
Location: include/asm-generic/pgtable.h:951
Inline: True
```
```
In mm/madvise.c (ffffffff8127cc66)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81283a4a)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff81291f39)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a730c)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff812be2b3)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff81368577)
Location: include/asm-generic/pgtable.h:951
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
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81245d2d)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff8124d6e4)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
```
```
In mm/mincore.c (ffffffff81250b60)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81258b4d)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8125a17d)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8125c91d)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/madvise.c (ffffffff8126eafe)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812758f6)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff81283b75)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81298d76)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff812af3c1)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff813598a6)
Location: include/asm-generic/pgtable.h:951
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
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81250de6)
Location: include/asm-generic/pgtable.h:951
Inline: True
```
```
In mm/memory.c (ffffffff8125450b)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/mincore.c (ffffffff8125c483)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812641b5)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81265c26)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812681fe)
Location: include/asm-generic/pgtable.h:951
Inline: True
```
```
In mm/madvise.c (ffffffff8127aa06)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8128185a)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff8128fd49)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a511c)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff812bc0c3)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff81366047)
Location: include/asm-generic/pgtable.h:951
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
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81260767)
Location: include/asm-generic/pgtable.h:951
Inline: True
```
```
In mm/memory.c (ffffffff81263f9b)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
```
```
In mm/mincore.c (ffffffff8126be6c)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81273b75)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812755c8)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81277b7e)
Location: include/asm-generic/pgtable.h:951
Inline: True
```
```
In mm/madvise.c (ffffffff8128a5e6)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81291588)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff8129f1e5)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812b5c74)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff812cc891)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff81379c30)
Location: include/asm-generic/pgtable.h:951
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
