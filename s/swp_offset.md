# Function: <code>swp_offset</code>

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
In kernel/power/swap.c (ffffffff810d4008)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/memory.c (ffffffff811c14c6)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:48
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/swapops.h:48
Inline: True
```
```
In mm/page_io.c (ffffffff811d1f52)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/swap_state.c (ffffffff811d2c7d)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff811d2f95)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:swap_info_get
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:swap_entry_free
```
```
In mm/frontswap.c (ffffffff811d767a)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff811d86f5)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:48
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/swapops.h:48
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/swapops.h:48
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81278703)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In kernel/power/swap.c (ffffffff810d8e08)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/memory.c (ffffffff811d908a)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:48
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/swapops.h:48
Inline: True
```
```
In mm/page_io.c (ffffffff811efa5f)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff811f0a90)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff811f5385)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__page_file_index
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swap_entry_free
  - mm/swapfile.c:swap_info_get
```
```
In mm/frontswap.c (ffffffff811f5b98)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff811f6f55)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:48
Inline: True
```
```
In mm/migrate.c (ffffffff81211832)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (0)
Location: include/linux/swapops.h:48
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/swapops.h:48
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812a5026)
Location: include/linux/swapops.h:48
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
In kernel/power/swap.c (ffffffff810df8f8)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/memory.c (ffffffff811e8523)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811ee2fb)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:48
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff811f6c77)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (0)
Location: include/linux/swapops.h:48
Inline: True
```
```
In mm/page_io.c (ffffffff81200408)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff81201490)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81205eb5)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__page_file_index
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swap_entry_free
  - mm/swapfile.c:swap_info_get
  - mm/swapfile.c:scan_swap_map
```
```
In mm/frontswap.c (ffffffff812066c8)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81207905)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:48
Inline: True
```
```
In mm/migrate.c (ffffffff812239f2)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (0)
Location: include/linux/swapops.h:48
Inline: True
```
```
In mm/memcontrol.c (ffffffff81230e72)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/swapops.h:48
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812ba98b)
Location: include/linux/swapops.h:48
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
In kernel/power/swap.c (ffffffff810dea58)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:48
Inline: True
```
```
In mm/memory.c (ffffffff811f76b5)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811f92b9)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:48
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81201b57)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (0)
Location: include/linux/swapops.h:48
Inline: True
```
```
In mm/page_io.c (ffffffff8120b038)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff8120c33e)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8121162f)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__page_file_index
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:__swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/frontswap.c (ffffffff81211e58)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff812128c5)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:48
Inline: True
```
```
In mm/migrate.c (ffffffff8122f352)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (0)
Location: include/linux/swapops.h:48
Inline: True
```
```
In mm/memcontrol.c (ffffffff8123c6ce)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff8124346a)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_record
```
```
In fs/proc/task_mmu.c (ffffffff812c86d7)
Location: include/linux/swapops.h:48
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
In kernel/power/swap.c (ffffffff810e6cd8)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/memremap.c (ffffffff811c89e5)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - kernel/memremap.c:device_private_entry_fault
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:49
Inline: True
```
```
In mm/memory.c (ffffffff8120a85e)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff8121160e)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:49
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff8121ad12)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (0)
Location: include/linux/swapops.h:49
Inline: True
```
```
In mm/page_io.c (ffffffff81224458)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff81225a31)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8122bf83)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__page_file_index
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:__swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/frontswap.c (ffffffff8122c828)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff8122d305)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:49
Inline: True
```
```
In mm/migrate.c (ffffffff8124b860)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8125304e)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8125c355)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff812632ba)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_record
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:49
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812ec4e3)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In kernel/power/swap.c (ffffffff810ee6c8)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/memremap.c (ffffffff811e91e5)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - kernel/memremap.c:device_private_entry_fault
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:49
Inline: True
```
```
In mm/memory.c (ffffffff8122b675)
Location: include/linux/swapops.h:49
Inline: True
```
```
In mm/mincore.c (ffffffff81232463)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffffffff8123940f)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff8123cb43)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8123f29b)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_io.c (ffffffff81246964)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff81247fb5)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8124e46c)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__page_file_index
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:__swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/frontswap.c (ffffffff8124f4da)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81250364)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81256f29)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff8126e440)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812798e9)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8127fc3b)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff81287585)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_record
```
```
In mm/hmm.c (ffffffff81293827)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8131a18c)
Location: include/linux/swapops.h:49
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In kernel/power/swap.c (ffffffff810f9d38)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/memremap.c (ffffffff811f9ef5)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - kernel/memremap.c:device_private_entry_fault
```
```
In mm/shmem.c (ffffffff81221dd1)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:48
Inline: True
```
```
In mm/memory.c (ffffffff8123ea4a)
Location: include/linux/swapops.h:48
Inline: True
```
```
In mm/mincore.c (ffffffff81245c2e)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffffffff8124db1b)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff81251019)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812539a1)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_io.c (ffffffff8125ad84)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff8125c595)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8126282c)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__page_file_index
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:__swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/frontswap.c (ffffffff8126342a)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81264834)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8126b59f)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812832ce)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8128df08)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812945ab)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff8129c4d5)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_record
```
```
In mm/hmm.c (ffffffff812a7d80)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8133124f)
Location: include/linux/swapops.h:48
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In kernel/power/swap.c (ffffffff81102408)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/shmem.c (ffffffff812332de)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/memory.c (ffffffff812530c5)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff81257d7d)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffffffff8125fa0d)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81263305)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff81265bd5)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_io.c (ffffffff81275e85)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff81277783)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8127d71b)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__page_file_index
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/frontswap.c (ffffffff8127e365)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff8127fda4)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8128685b)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff8129f6c0)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a8889)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812b0896)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff812b7675)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_record
```
```
In mm/hmm.c (ffffffff812c450c)
Location: include/linux/swapops.h:50
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81359047)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In kernel/power/swap.c (ffffffff8110e828)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/shmem.c (ffffffff812414e0)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/memory.c (ffffffff81261625)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8126628d)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffffffff8126e21d)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81271ab5)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812744f4)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_io.c (ffffffff8128594f)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff81287273)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8128d1bb)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__page_file_index
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/frontswap.c (ffffffff8128ddc5)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff8128f231)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8129644a)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812aea2d)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b9e09)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812c22f6)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff812c9555)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_record
```
```
In mm/hmm.c (ffffffff812d5e5e)
Location: include/linux/swapops.h:50
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81371297)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In kernel/power/swap.c (ffffffff81119b7f)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/shmem.c (ffffffff8126d2ec)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/memory.c (ffffffff8129198f)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_one_pte
  - mm/memory.c:copy_one_pte
```
```
In mm/mincore.c (ffffffff812965e6)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffffffff8129e961)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812a20e8)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812a5799)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_io.c (ffffffff812b7ce4)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff812b9a8e)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff812bfc5b)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__page_file_index
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/frontswap.c (ffffffff812c0b05)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff812c1ee1)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812c99ed)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812e4164)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ee9bd)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812f9257)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff812fecd5)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/hmm.c (ffffffff8130b06d)
Location: include/linux/swapops.h:50
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813b8ac9)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In kernel/power/swap.c (ffffffff8111558f)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/shmem.c (ffffffff81277adc)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/memory.c (ffffffff8129c293)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff812a1559)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812a9d17)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812ada2d)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812b0b5c)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_io.c (ffffffff812c33a1)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff812c54fe)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff812cb80b)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:map_swap_page
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:swap_page_sector
```
```
In mm/frontswap.c (ffffffff812cc525)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff812cdac1)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812d5665)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812f0199)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812fa031)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8130185f)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff8130b015)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/hmm.c (ffffffff81316f3d)
Location: include/linux/swapops.h:50
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813ca4fd)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In kernel/power/swap.c (ffffffff81115a5b)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/shmem.c (ffffffff8127c83c)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:60
Inline: True
```
```
In mm/memory.c (ffffffff812a1558)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff812a6d6e)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812af1a2)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812b2eae)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812b624c)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_io.c (ffffffff812ca1a1)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff812cc1b3)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff812d23af)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:swap_page_sector
```
```
In mm/frontswap.c (ffffffff812d2f55)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff812d4d92)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812dc3c0)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812f5876)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81300ddd)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8130804f)
Location: include/linux/swapops.h:60
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff81311675)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/hmm.c (ffffffff8131d173)
Location: include/linux/swapops.h:60
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813d0d1d)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In kernel/power/swap.c (ffffffff81135c9b)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/shmem.c (ffffffff812ba99c)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:60
Inline: True
```
```
In mm/memory.c (ffffffff812e06fb)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mincore.c (ffffffff812e8246)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812f096a)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812f4a56)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812f7e93)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_io.c (ffffffff8130f1c2)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff813113b5)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff81317c7f)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_page_sector
```
```
In mm/frontswap.c (ffffffff81318959)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff8131a382)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8132355f)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff8133ff54)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81344cb8)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff813521df)
Location: include/linux/swapops.h:60
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff8135c9d5)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/memory-failure.c (ffffffff8135ebdc)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/hmm.c (ffffffff8136a50f)
Location: include/linux/swapops.h:60
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff814224f6)
Location: include/linux/swapops.h:60
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
In kernel/power/swap.c (ffffffff811580cb)
Location: include/linux/swapops.h:62
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/filemap.c (ffffffff812f59c3)
Location: include/linux/swapops.h:62
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
```
```
In mm/shmem.c (ffffffff81318070)
Location: include/linux/swapops.h:62
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:62
Inline: True
```
```
In mm/memory.c (ffffffff81340ddb)
Location: include/linux/swapops.h:62
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mincore.c (ffffffff813495b1)
Location: include/linux/swapops.h:62
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff813540e5)
Location: include/linux/swapops.h:62
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff813588c1)
Location: include/linux/swapops.h:62
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8135f17c)
Location: include/linux/swapops.h:62
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swap_state.c (ffffffff8137c44f)
Location: include/linux/swapops.h:62
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff8138332c)
Location: include/linux/swapops.h:62
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:try_to_free_swap
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_page_sector
```
```
In mm/frontswap.c (ffffffff81384055)
Location: include/linux/swapops.h:62
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff8138582a)
Location: include/linux/swapops.h:62
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81390ffa)
Location: include/linux/swapops.h:62
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff813b1c91)
Location: include/linux/swapops.h:62
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff813b73d7)
Location: include/linux/swapops.h:62
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c19f1)
Location: include/linux/swapops.h:62
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff813ce6ec)
Location: include/linux/swapops.h:62
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff813d6685)
Location: include/linux/swapops.h:62
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/memory-failure.c (ffffffff813d9099)
Location: include/linux/swapops.h:62
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/hmm.c (ffffffff813e86a6)
Location: include/linux/swapops.h:62
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8149b7cd)
Location: include/linux/swapops.h:62
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
In kernel/power/swap.c (ffffffff81189c5b)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/filemap.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/shmem.c (ffffffff8138ab06)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/memory.c (ffffffff813b6531)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mincore.c (ffffffff813c19aa)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff813ce6a4)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/rmap.c (ffffffff813da034)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/swap_state.c (ffffffff813f9c0f)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff81400d2c)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:arch_max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:folio_free_swap
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_page_sector
```
```
In mm/frontswap.c (ffffffff81401b6a)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff8140358f)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8141281d)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/migrate.c (ffffffff8143273c)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff81438f3b)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81443adf)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8145014c)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff8145c135)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/memory-failure.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/hmm.c (ffffffff814705e6)
Location: include/linux/swapops.h:107
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81530121)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
In kernel/power/swap.c (ffffffff8119b14b)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/filemap.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/shmem.c (ffffffff813bd046)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/memory.c (ffffffff813ebeb3)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:pfn_swap_entry_to_page
```
```
In mm/mincore.c (ffffffff813f6839)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81402ed7)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/rmap.c (ffffffff8140e763)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/swap_state.c (ffffffff8142cb6f)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff81433c0c)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:generic_max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:swap_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_page_sector
```
```
In mm/frontswap.c (ffffffff81434a5e)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff8143657f)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:shrink_worker
```
```
In mm/hugetlb.c (ffffffff81445e2b)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/migrate.c (ffffffff81467eea)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146f77b)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8147901a)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/memcontrol.c (ffffffff81485bac)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff81491dd5)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/memory-failure.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/hmm.c (ffffffff814a4dc1)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/proc/task_mmu.c (ffffffff81568003)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
In kernel/power/swap.c (ffffffff811aa1ab)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/filemap.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/shmem.c (ffffffff813e7eb6)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/memory.c (ffffffff81416da3)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:pfn_swap_entry_to_page
```
```
In mm/mincore.c (ffffffff814224ee)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8142f4a1)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/rmap.c (ffffffff8143af6a)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/swap_state.c (ffffffff81466870)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff8146d04c)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__page_file_index
  - mm/swapfile.c:swapcache_clear
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:generic_max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:swap_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_folio_sector
```
```
In mm/zswap.c (ffffffff81471550)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/zswap.c:zswap_invalidate
  - mm/zswap.c:zswap_load
  - mm/zswap.c:zswap_load
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:shrink_memcg_cb
  - mm/zswap.c:shrink_memcg_cb
```
```
In mm/hugetlb.c (ffffffff8147f863)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/migrate.c (ffffffff81497bdd)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149d620)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a8631)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/memcontrol.c (ffffffff814b455c)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff814c17e5)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/memory-failure.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/hmm.c (ffffffff814d5e10)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/proc/task_mmu.c (ffffffff8159d67f)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
In mm/shmem.c (ffff8000102d3854)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/memory.c (ffff8000102f7058)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffff8000102fd0ac)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/page_vma_mapped.c (ffff800010307078)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/page_io.c (ffff800010320024)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffff800010321dc0)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffff800010328964)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__page_file_index
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:map_swap_page
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/frontswap.c (ffff80001032aa0c)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffff80001032c504)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/migrate.c (ffff800010350d6c)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffff800010354c7c)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/memcontrol.c (ffff800010363dd4)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffff80001036cbd8)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_record
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In fs/proc/task_mmu.c (ffff800010439768)
Location: include/linux/swapops.h:50
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
In kernel/power/swap.c (c03c1ea4)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/shmem.c (c04fbbb0)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/memory.c (c0519158)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (c051c6e4)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/page_vma_mapped.c (c0524df0)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/page_io.c (c0538888)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (c053a484)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (c053fdd4)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__page_file_index
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/frontswap.c (c05409b0)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (c0542818)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (c0552448)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/memcontrol.c (c0556108)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (c055db8c)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_record
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In fs/proc/task_mmu.c (c06013b4)
Location: include/linux/swapops.h:50
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
In mm/shmem.c (c000000000392aa4)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/memory.c (c0000000003c1eb0)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (c0000000003c8730)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/page_vma_mapped.c (c0000000003d60d0)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/page_io.c (c0000000003f4e90)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (c0000000003f7698)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (c0000000003ffca0)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__page_file_index
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:map_swap_page
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/frontswap.c (c0000000004012d8)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (c000000000403f28)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/migrate.c (c0000000004344f8)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (c00000000043be10)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/memcontrol.c (c000000000450eb0)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (c00000000045cb04)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_record
```
```
In mm/hmm.c (c000000000470308)
Location: include/linux/swapops.h:50
Inline: True
```
```
In fs/proc/task_mmu.c (c00000000054d358)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/shmem.c (ffffffe0001ef938)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/memory.c (ffffffe000207610)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffe00020bb7e)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffe00021264c)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/page_io.c (ffffffe000221742)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffe000222e70)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffe00022872a)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__page_file_index
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:map_swap_page
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/frontswap.c (ffffffe0002295ee)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffe00022b0ca)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/migrate.c (ffffffe00023f73e)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/memcontrol.c (ffffffe000241cac)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffe000249a94)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_record
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffe0002d353e)
Location: include/linux/swapops.h:50
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
In kernel/power/swap.c (ffffffff81106df8)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/shmem.c (ffffffff81239b30)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/memory.c (ffffffff81259c75)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8125e8dd)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffffffff8126686d)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff8126a105)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8126cb44)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_io.c (ffffffff8127df9f)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff8127f8c5)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8128579b)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__page_file_index
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/frontswap.c (ffffffff812863a5)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81287811)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8128ea2a)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812a700d)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b23e9)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812ba8d6)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff812c1b35)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_record
```
```
In mm/hmm.c (ffffffff812ce43e)
Location: include/linux/swapops.h:50
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81369877)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In kernel/power/swap.c (ffffffff810f7ce8)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/shmem.c (ffffffff8122cb4c)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/memory.c (ffffffff8124c0a3)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff81250d16)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffffffff81258e86)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff8125c2f7)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8125eb94)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_io.c (ffffffff8126fdcf)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff812716e3)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8127760b)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__page_file_index
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/frontswap.c (ffffffff81278205)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81279671)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812807dd)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff81298a4a)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a377c)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812aba94)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff812b2b85)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_record
```
```
In mm/hmm.c (ffffffff812bf365)
Location: include/linux/swapops.h:50
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813596f9)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In kernel/power/swap.c (ffffffff81104cf8)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/shmem.c (ffffffff812378d0)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/memory.c (ffffffff81257a15)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8125c67d)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffffffff8126460d)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81267ea5)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8126a8e4)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_io.c (ffffffff8127bd3f)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff8127d663)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff812835ab)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__page_file_index
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/frontswap.c (ffffffff812841b5)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81285621)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8128c83a)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812a4e1d)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b01f9)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812b86e6)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff812bf945)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_record
```
```
In mm/hmm.c (ffffffff812cc24e)
Location: include/linux/swapops.h:50
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81367347)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In kernel/power/swap.c (ffffffff811100d8)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/shmem.c (ffffffff81246e43)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (0)
Location: include/linux/swapops.h:50
Inline: True
```
```
In mm/memory.c (ffffffff812673fe)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8126c064)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffffffff81273fcb)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81277827)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8127a25e)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_io.c (ffffffff8128b91f)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff8128d213)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8129328b)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__page_file_index
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/frontswap.c (ffffffff81293e95)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81294c11)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8129c618)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812b5979)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812c0539)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812c8d26)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff812d03a5)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_record
```
```
In mm/hmm.c (ffffffff812dcfa2)
Location: include/linux/swapops.h:50
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8137a98f)
Location: include/linux/swapops.h:50
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
</details>
</li>
</ul>

## Differences
