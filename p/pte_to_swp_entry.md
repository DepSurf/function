# Function: <code>pte_to_swp_entry</code>

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
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811bd93a)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811c28e5)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811c8966)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff811d1625)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff811d649c)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In mm/hugetlb.c (ffffffff811db0d7)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff811f0c9a)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/memcontrol.c (ffffffff811fa953)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812780f0)
Location: include/linux/swapops.h:65
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
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811d9a56)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811de49a)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811e465d)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff811eebdd)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff811f456e)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In mm/hugetlb.c (ffffffff811fc5fa)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff812117dd)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff8121e87f)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812a4fc6)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811e95bf)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811ee2b1)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811f4c4d)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff811f6ba6)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff811ff50e)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81205097)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In mm/hugetlb.c (ffffffff8120d0e6)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff8122399d)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff81230ea0)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812ba92b)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f472f)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811f9277)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811ff622)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff81201b0f)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff8120a1c5)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81210908)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In mm/hugetlb.c (ffffffff81218f47)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff8122f30e)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff8123c707)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812c8521)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8120c51e)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff81211671)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8121823f)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff8121a578)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff81223411)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81226093)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/swap_state.c:do_swap_page_readahead
  - mm/swap_state.c:swap_readahead_detect
```
```
In mm/swapfile.c (ffffffff81227e06)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapon
```
```
In mm/hugetlb.c (ffffffff81233edd)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff8124b818)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff8125c392)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:66
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812ec6de)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8122d1cf)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff81232408)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81239369)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff8123c33f)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff8124628f)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81248461)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8124d105)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
```
```
In mm/hugetlb.c (ffffffff81256ee6)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff8126e1b3)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff8127fbf4)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff8129367f)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8131a177)
Location: include/linux/swapops.h:66
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124075f)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff81245bdb)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8124dad2)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff81250f5a)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff8125a6af)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8125ca31)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81261505)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
```
```
In mm/hugetlb.c (ffffffff8126b55c)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff81283024)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff81294564)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812a7c25)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8133123a)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81252a0f)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff81257d3e)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8125f909)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812631f9)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff81275792)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81277c26)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8127c475)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128681b)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff8129f3d0)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812b0917)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812c436b)
Location: include/linux/swapops.h:65
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81359032)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81260f6f)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8126624e)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8126e119)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812719a9)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff81284762)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81287716)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8128bf55)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8129640a)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff812ae8f3)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812c2377)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812d5ca1)
Location: include/linux/swapops.h:65
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81371282)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (ffffffff812886cf)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812913d7)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_one_pte
```
```
In mm/mincore.c (ffffffff81296599)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8129e74c)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812a1907)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/madvise.c (ffffffff812b68f9)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812b986f)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_ra_info
```
```
In mm/swapfile.c (ffffffff812bee55)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812c998c)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff812e3ff5)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812f5d15)
Location: include/linux/swapops.h:65
Inline: True
```
```
In mm/hmm.c (ffffffff8130afbf)
Location: include/linux/swapops.h:65
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813b7dfc)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
In mm/gup.c (ffffffff812923b5)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129bd47)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff812a150c)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812a9b0c)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812ad1c4)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/madvise.c (ffffffff812c2b49)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812c52d8)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff812caa75)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812d5389)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff812efeab)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff813017e5)
Location: include/linux/swapops.h:65
Inline: True
```
```
In mm/hmm.c (ffffffff81316e8f)
Location: include/linux/swapops.h:65
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813c988c)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
In mm/gup.c (ffffffff81297d13)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812a0fe7)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff812a6d00)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812aef97)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812b2c6f)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff812c99c5)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812cbf86)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff812d1555)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812dc35b)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff812f593c)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff81307fd5)
Location: include/linux/swapops.h:75
Inline: True
```
```
In mm/hmm.c (ffffffff8131d0c2)
Location: include/linux/swapops.h:75
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813d0979)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
swp_entry_t pte_to_swp_entry(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d8753)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812e06a1)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mincore.c (ffffffff812e81e0)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812f0787)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812f4830)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff8130e9e5)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81311156)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff81316c55)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff813234fa)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff8133ff01)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff81352165)
Location: include/linux/swapops.h:75
Inline: True
```
```
In mm/memory-failure.c (ffffffff8135eb96)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/hmm.c (ffffffff8136a3b8)
Location: include/linux/swapops.h:75
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81421a8b)
Location: include/linux/swapops.h:75
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
**Symbols:**

```
ffffffff812de120-ffffffff812de179: pte_to_swp_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
swp_entry_t pte_to_swp_entry(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813386c5)
Location: include/linux/swapops.h:77
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81343a8c)
Location: include/linux/swapops.h:77
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
Direct callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mincore.c (ffffffff81349541)
Location: include/linux/swapops.h:77
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81353e2f)
Location: include/linux/swapops.h:77
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff8135867f)
Location: include/linux/swapops.h:77
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8135e7cb)
Location: include/linux/swapops.h:77
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81376b92)
Location: include/linux/swapops.h:77
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8137c187)
Location: include/linux/swapops.h:77
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff81382275)
Location: include/linux/swapops.h:77
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81390f9b)
Location: include/linux/swapops.h:77
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
In mm/migrate.c (ffffffff813b4b6d)
Location: include/linux/swapops.h:77
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait_huge
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff813b71e8)
Location: include/linux/swapops.h:77
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff813ce83c)
Location: include/linux/swapops.h:77
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff813d902c)
Location: include/linux/swapops.h:77
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff813e4475)
Location: include/linux/swapops.h:77
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff813e8460)
Location: include/linux/swapops.h:77
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8145da4d)
Location: include/linux/swapops.h:77
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff814995db)
Location: include/linux/swapops.h:77
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
**Symbols:**

```
ffffffff8133e260-ffffffff8133e2cf: pte_to_swp_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
swp_entry_t pte_to_swp_entry(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bb17f)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mincore.c (ffffffff813c192a)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff813ce2d9)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff813d2df7)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff813d962b)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff813f435c)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff813f9927)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff81400aa5)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/swapfile.c:arch_max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff814127ac)
Location: include/linux/swapops.h:133
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
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
```
```
In mm/ksm.c (ffffffff81421a87)
Location: include/linux/swapops.h:133
Inline: True
```
```
In mm/migrate.c (ffffffff81433cfd)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait_huge
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff81438c04)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff81453426)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8145f020)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff8146bf4c)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff81470391)
Location: include/linux/swapops.h:133
Inline: True
```
```
In fs/userfaultfd.c (ffffffff814ed47c)
Location: include/linux/swapops.h:133
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152e883)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
**Symbols:**

```
ffffffff813b5150-ffffffff813b51c1: pte_to_swp_entry (STB_LOCAL)
ffffffff81407000-ffffffff81407071: pte_to_swp_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
swp_entry_t pte_to_swp_entry(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f0558)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
Direct callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mincore.c (ffffffff813f67c3)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (ffffffff81402bb6)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff8140739f)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff8140dec3)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81427a49)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8142c7be)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff81433914)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/swapfile.c:generic_max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81445dbb)
Location: include/linux/swapops.h:133
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
In mm/ksm.c (ffffffff8145682f)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate.c (ffffffff814696cf)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146f49a)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8147eff8)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memcontrol.c (ffffffff8148915c)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81494fd0)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff814a0ca7)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814a4bc7)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff81524183)
Location: include/linux/swapops.h:133
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81566b39)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
**Symbols:**

```
ffffffff813e9ef0-ffffffff813e9f61: pte_to_swp_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
swp_entry_t pte_to_swp_entry(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141fff8)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
Direct callers:
  - mm/memory.c:set_pte_range
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mincore.c (ffffffff81422473)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (ffffffff8142f1c9)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81433a0f)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff8143a698)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8146125d)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81465f06)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff8146cd04)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/swapfile.c:generic_max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8147f7f2)
Location: include/linux/swapops.h:133
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
In mm/mempolicy.c (ffffffff8148514c)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/ksm.c (ffffffff81491326)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate.c (ffffffff814985ff)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149dfa3)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff814afcd0)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memcontrol.c (ffffffff814b9015)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814c48d0)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff814d2eb1)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814d5bf4)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff815586ce)
Location: include/linux/swapops.h:133
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159d312)
Location: include/linux/swapops.h:133
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
**Symbols:**

```
ffffffff81415ca0-ffffffff81415d11: pte_to_swp_entry (STB_LOCAL)
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
In mm/gup.c (ffff8000102f1d10)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102f8340)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffff8000102fd04c)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffff800010305418)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffff800010307068)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffff80001031eac8)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffff800010322244)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffff800010325de0)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffff800010335ddc)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffff800010350d50)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffff800010363e4c)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffff80001037b778)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffff8000104396e8)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/gup.c (c0514228)
Location: include/linux/swapops.h:65
Inline: True
```
```
In mm/memory.c (c051ab1c)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (c051c634)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (c0523410)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (c0524dd8)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/madvise.c (c0537710)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (c053a900)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (c053d660)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/migrate.c (c0552408)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (c0556188)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (c05664d0)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (c0601380)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/gup.c (c0000000003b6490)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003c1694)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (c0000000003c86fc)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (c0000000003d2670)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (c0000000003d6004)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (c0000000003f3118)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (c0000000003f7c84)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (c0000000003fc258)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (c00000000040fe60)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (c0000000004344dc)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (c000000000450e88)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (c00000000046fecc)
Location: include/linux/swapops.h:65
Inline: True
```
```
In fs/proc/task_mmu.c (c00000000054d1dc)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/gup.c (ffffffe00020462e)
Location: include/linux/swapops.h:65
Inline: True
```
```
In mm/memory.c (ffffffe0002088c2)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffe00020bb7c)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffe000211256)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffe0002125fc)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffe000220562)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffe00022325a)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffe0002261c4)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffe000231eba)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffe00023f720)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffe000241cfc)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffe000251f6e)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffe0002d353c)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812595bf)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8125e89e)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81266769)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81269ff9)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff8127cdb2)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127fcdf)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81284535)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128e9ea)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff812a6ed3)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812ba957)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812ce281)
Location: include/linux/swapops.h:65
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81369862)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (ffffffff81245681)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124ba3f)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff81250c54)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81258e25)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff8125c1bb)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff8126ec18)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81271b37)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81274c9e)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812807a4)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff81298918)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812abb0e)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812bf102)
Location: include/linux/swapops.h:65
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813596cf)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125735f)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8125c63e)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81264509)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81267d99)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff8127ab52)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127db06)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81282345)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128c7fa)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff812a4ce3)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812b8767)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812cc091)
Location: include/linux/swapops.h:65
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81367332)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81266d4f)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8126c025)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81273ec7)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff8127775c)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/madvise.c (ffffffff8128a733)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8128d6b6)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81292035)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8129c5d8)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff812b583f)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812c8da7)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812dcdd1)
Location: include/linux/swapops.h:65
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8137a97a)
Location: include/linux/swapops.h:65
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
