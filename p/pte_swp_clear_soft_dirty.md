# Function: <code>pte_swp_clear_soft_dirty</code>

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
In mm/gup.c (ffffffff811ba4c0)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811bd93a)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811c28e5)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811c8966)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff811d1625)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
```
```
In mm/hugetlb.c (ffffffff811db0d7)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/migrate.c (ffffffff811f0c9a)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/memcontrol.c (ffffffff811fa953)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812780f0)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/gup.c (ffffffff811d4b97)
Location: arch/x86/include/asm/pgtable.h:947
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811d9a56)
Location: arch/x86/include/asm/pgtable.h:947
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811de49a)
Location: arch/x86/include/asm/pgtable.h:947
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811e4c25)
Location: arch/x86/include/asm/pgtable.h:947
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff811eebdd)
Location: arch/x86/include/asm/pgtable.h:947
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff811f21e3)
Location: arch/x86/include/asm/pgtable.h:947
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811fc5fa)
Location: arch/x86/include/asm/pgtable.h:947
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff812117dd)
Location: arch/x86/include/asm/pgtable.h:947
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff8121e87f)
Location: arch/x86/include/asm/pgtable.h:947
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812a4fc6)
Location: arch/x86/include/asm/pgtable.h:947
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/gup.c (ffffffff811e4bc6)
Location: arch/x86/include/asm/pgtable.h:947
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811e95bf)
Location: arch/x86/include/asm/pgtable.h:947
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811ee2b1)
Location: arch/x86/include/asm/pgtable.h:947
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811f4c4d)
Location: arch/x86/include/asm/pgtable.h:947
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff811f6ba6)
Location: arch/x86/include/asm/pgtable.h:947
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff811ff50e)
Location: arch/x86/include/asm/pgtable.h:947
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81202bdb)
Location: arch/x86/include/asm/pgtable.h:947
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8120d0e6)
Location: arch/x86/include/asm/pgtable.h:947
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff8122399d)
Location: arch/x86/include/asm/pgtable.h:947
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff81230ea0)
Location: arch/x86/include/asm/pgtable.h:947
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812ba92b)
Location: arch/x86/include/asm/pgtable.h:947
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/gup.c (ffffffff811ef2b0)
Location: arch/x86/include/asm/pgtable.h:1157
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f472f)
Location: arch/x86/include/asm/pgtable.h:1157
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811f9277)
Location: arch/x86/include/asm/pgtable.h:1157
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811ffb9b)
Location: arch/x86/include/asm/pgtable.h:1157
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff81201b0f)
Location: arch/x86/include/asm/pgtable.h:1157
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff8120a1c5)
Location: arch/x86/include/asm/pgtable.h:1157
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8120dc87)
Location: arch/x86/include/asm/pgtable.h:1157
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81218f47)
Location: arch/x86/include/asm/pgtable.h:1157
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff8122f30e)
Location: arch/x86/include/asm/pgtable.h:1157
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff8123c707)
Location: arch/x86/include/asm/pgtable.h:1157
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812c8767)
Location: arch/x86/include/asm/pgtable.h:1157
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/gup.c (ffffffff81206407)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8120c51e)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff81211671)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8121823f)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff8121a578)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff81223411)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81226093)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/swap_state.c:do_swap_page_readahead
  - mm/swap_state.c:swap_readahead_detect
```
```
In mm/swapfile.c (ffffffff812290e6)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81233ef5)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff8124b818)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff8125c392)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812ec934)
Location: arch/x86/include/asm/pgtable.h:1176
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/gup.c (ffffffff812266e9)
Location: arch/x86/include/asm/pgtable.h:1242
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8122d1cf)
Location: arch/x86/include/asm/pgtable.h:1242
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff81232408)
Location: arch/x86/include/asm/pgtable.h:1242
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81239369)
Location: arch/x86/include/asm/pgtable.h:1242
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff8123c33f)
Location: arch/x86/include/asm/pgtable.h:1242
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff8124628f)
Location: arch/x86/include/asm/pgtable.h:1242
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81248464)
Location: arch/x86/include/asm/pgtable.h:1242
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8124a3fd)
Location: arch/x86/include/asm/pgtable.h:1242
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81256ee6)
Location: arch/x86/include/asm/pgtable.h:1242
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff8126e1b3)
Location: arch/x86/include/asm/pgtable.h:1242
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff8127fbf4)
Location: arch/x86/include/asm/pgtable.h:1242
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff8129367f)
Location: arch/x86/include/asm/pgtable.h:1242
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8131a177)
Location: arch/x86/include/asm/pgtable.h:1242
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/gup.c (ffffffff8123aa29)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124075f)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff81245bdb)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8124dad2)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff81250f5a)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff8125a6af)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8125ca34)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8125ea3d)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8126b55c)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff81283024)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff81294564)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812a7c25)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8133123a)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/gup.c (ffffffff8124bcdc)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81252a0f)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff81257d3e)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8125f909)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812631f9)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff8127497b)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81277c29)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8127b0f1)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128681b)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff8129f3d0)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812b0917)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812c436b)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81359032)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/gup.c (ffffffff8125a1cc)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81260f6f)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8126624e)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8126e119)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812719a9)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff8128392b)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81287719)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8128abd1)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8129640a)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff812ae8f3)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812c2377)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812d5ca1)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81371282)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/gup.c (ffffffff8128871f)
Location: arch/x86/include/asm/pgtable.h:1312
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812913ed)
Location: arch/x86/include/asm/pgtable.h:1312
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_one_pte
```
```
In mm/mincore.c (ffffffff8129659e)
Location: arch/x86/include/asm/pgtable.h:1312
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8129e755)
Location: arch/x86/include/asm/pgtable.h:1312
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812a1a34)
Location: arch/x86/include/asm/pgtable.h:1312
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/madvise.c (ffffffff812b68fe)
Location: arch/x86/include/asm/pgtable.h:1312
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812b9874)
Location: arch/x86/include/asm/pgtable.h:1312
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_ra_info
```
```
In mm/swapfile.c (ffffffff812bd90b)
Location: arch/x86/include/asm/pgtable.h:1312
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812c99a9)
Location: arch/x86/include/asm/pgtable.h:1312
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff812e3ffd)
Location: arch/x86/include/asm/pgtable.h:1312
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812f5d3c)
Location: arch/x86/include/asm/pgtable.h:1312
Inline: True
```
```
In mm/hmm.c (ffffffff8130afc4)
Location: arch/x86/include/asm/pgtable.h:1312
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813b7dfc)
Location: arch/x86/include/asm/pgtable.h:1312
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/gup.c (ffffffff81292405)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129bd5d)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff812a1511)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812a9b15)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812ad2f1)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/madvise.c (ffffffff812c2b4e)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812c52dd)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff812c942b)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812d53a6)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff812efeb3)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff8130180c)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
```
```
In mm/hmm.c (ffffffff81316e94)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813c988c)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/gup.c (ffffffff81297d61)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812a0ffd)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff812a6d04)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812aefa0)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812b2c74)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff812c99ca)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812cbf8b)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff812cffad)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812dc378)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff812f5944)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff81307ffc)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
```
```
In mm/hmm.c (ffffffff8131d0c8)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813d0979)
Location: arch/x86/include/asm/pgtable.h:1308
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/gup.c (ffffffff812d87a1)
Location: arch/x86/include/asm/pgtable.h:1279
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812e06a3)
Location: arch/x86/include/asm/pgtable.h:1279
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mincore.c (ffffffff812e81e4)
Location: arch/x86/include/asm/pgtable.h:1279
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812f0790)
Location: arch/x86/include/asm/pgtable.h:1279
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812f4835)
Location: arch/x86/include/asm/pgtable.h:1279
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff8130e9ea)
Location: arch/x86/include/asm/pgtable.h:1279
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8131115b)
Location: arch/x86/include/asm/pgtable.h:1279
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff813154be)
Location: arch/x86/include/asm/pgtable.h:1279
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81323517)
Location: arch/x86/include/asm/pgtable.h:1279
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff8133ff09)
Location: arch/x86/include/asm/pgtable.h:1279
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff8135218c)
Location: arch/x86/include/asm/pgtable.h:1279
Inline: True
```
```
In mm/memory-failure.c (ffffffff8135eb9c)
Location: arch/x86/include/asm/pgtable.h:1279
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/hmm.c (ffffffff8136a3be)
Location: arch/x86/include/asm/pgtable.h:1279
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8142202c)
Location: arch/x86/include/asm/pgtable.h:1279
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/gup.c (ffffffff8133870e)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81343aaf)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mincore.c (ffffffff81349554)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81353e44)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81358694)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8135e7fa)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81376ba6)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8137c199)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff81380a42)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81390fc5)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff813b4be4)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait_huge
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff813b71fd)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff813ce854)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff813d903e)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff813e448a)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff813e8477)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8145da64)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff814995f1)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/memory.c (ffffffff813bb191)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mincore.c (ffffffff813c193d)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff813ce2ee)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff813d2e0c)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff813d9658)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff813f4370)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff813f9939)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff813ff349)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff814127d9)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/ksm.c (ffffffff81421a9a)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
```
```
In mm/migrate.c (ffffffff81433d74)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait_huge
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff81438c17)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff81453438)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8145f033)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff8146bf5e)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814703a5)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
```
```
In fs/userfaultfd.c (ffffffff814ed491)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152e899)
Location: arch/x86/include/asm/pgtable.h:1331
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/memory.c (ffffffff813f057b)
Location: arch/x86/include/asm/pgtable.h:1329
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mincore.c (ffffffff813f67d6)
Location: arch/x86/include/asm/pgtable.h:1329
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (ffffffff81402bcb)
Location: arch/x86/include/asm/pgtable.h:1329
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff814073b1)
Location: arch/x86/include/asm/pgtable.h:1329
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff8140e359)
Location: arch/x86/include/asm/pgtable.h:1329
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81427a5d)
Location: arch/x86/include/asm/pgtable.h:1329
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8142c7d0)
Location: arch/x86/include/asm/pgtable.h:1329
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff8143393e)
Location: arch/x86/include/asm/pgtable.h:1329
Inline: True
Inline callers:
  - mm/swapfile.c:generic_max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81445de8)
Location: arch/x86/include/asm/pgtable.h:1329
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/ksm.c (ffffffff81456842)
Location: arch/x86/include/asm/pgtable.h:1329
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate.c (ffffffff81469748)
Location: arch/x86/include/asm/pgtable.h:1329
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146f4ac)
Location: arch/x86/include/asm/pgtable.h:1329
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8147f0b0)
Location: arch/x86/include/asm/pgtable.h:1329
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memcontrol.c (ffffffff81489171)
Location: arch/x86/include/asm/pgtable.h:1329
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81494fe3)
Location: arch/x86/include/asm/pgtable.h:1329
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff814a0cb9)
Location: arch/x86/include/asm/pgtable.h:1329
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814a4bd8)
Location: arch/x86/include/asm/pgtable.h:1329
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff81524198)
Location: arch/x86/include/asm/pgtable.h:1329
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81566b47)
Location: arch/x86/include/asm/pgtable.h:1329
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/memory.c (ffffffff8142001b)
Location: arch/x86/include/asm/pgtable.h:1557
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mincore.c (ffffffff81422486)
Location: arch/x86/include/asm/pgtable.h:1557
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (ffffffff8142f1de)
Location: arch/x86/include/asm/pgtable.h:1557
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81433a21)
Location: arch/x86/include/asm/pgtable.h:1557
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff8143a6c5)
Location: arch/x86/include/asm/pgtable.h:1557
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81461270)
Location: arch/x86/include/asm/pgtable.h:1557
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81465f18)
Location: arch/x86/include/asm/pgtable.h:1557
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff8146cd2e)
Location: arch/x86/include/asm/pgtable.h:1557
Inline: True
Inline callers:
  - mm/swapfile.c:generic_max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8147f81f)
Location: arch/x86/include/asm/pgtable.h:1557
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8148515f)
Location: arch/x86/include/asm/pgtable.h:1557
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/ksm.c (ffffffff8149133b)
Location: arch/x86/include/asm/pgtable.h:1557
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate.c (ffffffff81498678)
Location: arch/x86/include/asm/pgtable.h:1557
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149dfb5)
Location: arch/x86/include/asm/pgtable.h:1557
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff814afd97)
Location: arch/x86/include/asm/pgtable.h:1557
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memcontrol.c (ffffffff814b902a)
Location: arch/x86/include/asm/pgtable.h:1557
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814c48e3)
Location: arch/x86/include/asm/pgtable.h:1557
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff814d2ed3)
Location: arch/x86/include/asm/pgtable.h:1557
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814d5c05)
Location: arch/x86/include/asm/pgtable.h:1557
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff815586e5)
Location: arch/x86/include/asm/pgtable.h:1557
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159d31c)
Location: arch/x86/include/asm/pgtable.h:1557
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
</details>
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
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/mincore.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/madvise.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/migrate.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/pgtable.h:773
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
In mm/gup.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/mincore.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/madvise.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/migrate.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/pgtable.h:773
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
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:764
Inline: True
```
```
In mm/memory.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:764
Inline: True
```
```
In mm/mincore.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:764
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:764
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:764
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:764
Inline: True
```
```
In mm/swap_state.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:764
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:764
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:764
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:764
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:764
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:764
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:764
Inline: True
```
```
In mm/hmm.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:764
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:764
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
In mm/gup.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/mincore.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/madvise.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/migrate.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/pgtable.h:773
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/pgtable.h:773
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
In mm/gup.c (ffffffff8125281c)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812595bf)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8125e89e)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81266769)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81269ff9)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff8127bf7b)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127fce2)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff812831b1)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128e9ea)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff812a6ed3)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812ba957)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812ce281)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81369862)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
```
```
In mm/memory.c (ffffffff8124ba3f)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff81250c54)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81258e2f)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff8125bb40)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff8126ec18)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81271cbf)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81274c9e)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812807a4)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/migrate.c (ffffffff81298918)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812abb0e)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812bf102)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813596cf)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/gup.c (ffffffff812505bc)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125735f)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8125c63e)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81264509)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81267d99)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff81279d1b)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127db09)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81280fc1)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128c7fa)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff812a4ce3)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812b8767)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812cc091)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81367332)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/gup.c (ffffffff8125ff3c)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81266d4f)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8126c025)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81273ec7)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff8127775c)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff812898f7)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8128d6b9)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81290cd1)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8129c5d8)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff812b583f)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812c8da7)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812dcdd1)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8137a97a)
Location: arch/x86/include/asm/pgtable.h:1351
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
</details>
</li>
</ul>

## Differences
