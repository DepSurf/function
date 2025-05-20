# Function: <code>PageTransHuge</code>

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
In mm/swap.c (ffffffff8119c9c8)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff811a2203)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/compaction.c (ffffffff811b60ea)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811c2d0e)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (ffffffff811cab15)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced_one
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff811d28b3)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap
```
```
In mm/migrate.c (ffffffff811f1005)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/memcontrol.c (ffffffff811fa78a)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:lock_page_lru
  - mm/memcontrol.c:unlock_page_lru
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff812016f1)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:put_hwpoison_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/page_idle.c (ffffffff81208230)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
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
In mm/filemap.c (ffffffff811a21ea)
Location: include/linux/page-flags.h:519
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/swap.c (ffffffff811b1fb4)
Location: include/linux/page-flags.h:519
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff811b5542)
Location: include/linux/page-flags.h:519
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_page
```
```
In mm/vmscan.c (ffffffff811bcb20)
Location: include/linux/page-flags.h:519
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811c08aa)
Location: include/linux/page-flags.h:519
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff811c4a1a)
Location: include/linux/page-flags.h:519
Inline: True
```
```
In mm/compaction.c (ffffffff811cff6d)
Location: include/linux/page-flags.h:519
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811df129)
Location: include/linux/page-flags.h:519
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/rmap.c (ffffffff811e7e3a)
Location: include/linux/page-flags.h:519
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_check_address_transhuge
```
```
In mm/swap_state.c (ffffffff811f0599)
Location: include/linux/page-flags.h:519
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap
```
```
In mm/migrate.c (ffffffff8121356d)
Location: include/linux/page-flags.h:519
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/memcontrol.c (ffffffff81224150)
Location: include/linux/page-flags.h:519
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81227be7)
Location: include/linux/page-flags.h:519
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
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
In mm/filemap.c (ffffffff811b203a)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/swap.c (ffffffff811c2615)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff811c5b42)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_page
```
```
In mm/vmscan.c (ffffffff811cd1f6)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811d0e8c)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff811d4b2a)
Location: include/linux/page-flags.h:535
Inline: True
```
```
In mm/compaction.c (ffffffff811dff9c)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811eef40)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff811f6d3a)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff811f91ba)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_check_address_transhuge
```
```
In mm/swap_state.c (ffffffff81200f69)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap
```
```
In mm/migrate.c (ffffffff812258d2)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8122612c)
Location: include/linux/page-flags.h:535
Inline: True
```
```
In mm/memcontrol.c (ffffffff81236650)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8123a174)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
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
In mm/filemap.c (ffffffff811b8d1a)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/swap.c (ffffffff811caa98)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff811cde42)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_page
```
```
In mm/vmscan.c (ffffffff811d5ee0)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811d992b)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff811dd947)
Location: include/linux/page-flags.h:538
Inline: True
```
```
In mm/compaction.c (ffffffff811e9d45)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/swap_slots.c (ffffffff811ec987)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/mlock.c (ffffffff811f9e33)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff81202205)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff81203498)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/swap_state.c (ffffffff8120be87)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8120e0a9)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/migrate.c (ffffffff81230ca2)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8123192c)
Location: include/linux/page-flags.h:538
Inline: True
```
```
In mm/memcontrol.c (ffffffff812425e3)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81245d46)
Location: include/linux/page-flags.h:538
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
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
In mm/filemap.c (ffffffff811cd6f1)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff811df808)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff811e3219)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff811eb400)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff811ef5e4)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff811f33c7)
Location: include/linux/page-flags.h:539
Inline: True
```
```
In mm/compaction.c (ffffffff8120009a)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/swap_slots.c (ffffffff81202ce7)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/mlock.c (ffffffff81212283)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff8121ae05)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8121bfd8)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffffffff81224a14)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff81225488)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81229419)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/zswap.c (ffffffff8122d633)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff81238bdd)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff81989ee7)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff8124e9fc)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff8124f5dc)
Location: include/linux/page-flags.h:539
Inline: True
```
```
In mm/memcontrol.c (ffffffff81262423)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81265d6a)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_isolation.c (ffffffff81267415)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/filemap.c (ffffffff811ef1cc)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81201eb6)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff81204874)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff8120cbd7)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81210e84)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff812145f7)
Location: include/linux/page-flags.h:546
Inline: True
```
```
In mm/compaction.c (ffffffff81221456)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81232fbb)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff8123cc5f)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8123e05d)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffffffff81246e9d)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff81247a28)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8124a6e5)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff8124ec5c)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff812506a1)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff8125c0ad)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff819e6654)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff8127282c)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff81273395)
Location: include/linux/page-flags.h:546
Inline: True
```
```
In mm/memcontrol.c (ffffffff812864e3)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8128a0e8)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff8128bcd7)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/filemap.c (ffffffff8120095c)
Location: include/linux/page-flags.h:563
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81214836)
Location: include/linux/page-flags.h:563
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff81217234)
Location: include/linux/page-flags.h:563
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff8121fa9d)
Location: include/linux/page-flags.h:563
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81222eea)
Location: include/linux/page-flags.h:563
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff812344a9)
Location: include/linux/page-flags.h:563
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8124678e)
Location: include/linux/page-flags.h:563
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff8125112f)
Location: include/linux/page-flags.h:563
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812525f0)
Location: include/linux/page-flags.h:563
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffffffff8125b2cc)
Location: include/linux/page-flags.h:563
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff8125bfea)
Location: include/linux/page-flags.h:563
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
```
```
In mm/swapfile.c (ffffffff8125ecc5)
Location: include/linux/page-flags.h:563
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff8126313c)
Location: include/linux/page-flags.h:563
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff81264b71)
Location: include/linux/page-flags.h:563
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff8127096d)
Location: include/linux/page-flags.h:563
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff81a21ae0)
Location: include/linux/page-flags.h:563
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff81286de4)
Location: include/linux/page-flags.h:563
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff81287915)
Location: include/linux/page-flags.h:563
Inline: True
```
```
In mm/memcontrol.c (ffffffff8129b443)
Location: include/linux/page-flags.h:563
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8129f060)
Location: include/linux/page-flags.h:563
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff812a0c37)
Location: include/linux/page-flags.h:563
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/filemap.c (ffffffff81218652)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81224513)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff81226b49)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff8122f20a)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81233864)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff812442a0)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8124d887)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/mlock.c (ffffffff81258a45)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff8126340f)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8126477d)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffffffff81276418)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff812771ba)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
```
```
In mm/swapfile.c (ffffffff81279955)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff8127e0ac)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff8127f791)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff8128bb86)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff8129c49a)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812a177a)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812a1f85)
Location: include/linux/page-flags.h:596
Inline: True
```
```
In mm/memcontrol.c (ffffffff812b6684)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812b8927)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff812bbf08)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/filemap.c (ffffffff81221730)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff812322a3)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff812349bd)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff8123d39a)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81241a64)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff81252760)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8125bdbd)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/mlock.c (ffffffff81266f15)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff81271bbf)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff81272fed)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffffffff81285f08)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff81286c9a)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
```
```
In mm/swapfile.c (ffffffff81289435)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff8128dafc)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff8128f581)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff8129b766)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff812abef9)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812b2b88)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812b3335)
Location: include/linux/page-flags.h:596
Inline: True
```
```
In mm/memcontrol.c (ffffffff812c8554)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812ca807)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff812cdde8)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/filemap.c (ffffffff8124ff87)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/readahead.c (ffffffff8125cc18)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff8125f428)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff81262019)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff81265960)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8126eb61)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff81282bc0)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81286e95)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/mlock.c (ffffffff8129718b)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff812a21ef)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812a401d)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffffffff812b8228)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff812b921a)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff812bc045)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff812c05bc)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff812c2221)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff812cf2e6)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff812e1101)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812e8106)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812e8785)
Location: include/linux/page-flags.h:612
Inline: True
```
```
In mm/memcontrol.c (ffffffff812fdde5)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81300447)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff813040f8)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/memfd.c (ffffffff8130c002)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/mpage.c (ffffffff81365559)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/iomap/buffered-io.c (ffffffff813ab560)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead_actor
```
```
In fs/ext4/readpage.c (ffffffff8141875b)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/fuse/file.c (ffffffff81475e18)
Location: include/linux/page-flags.h:612
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
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
In mm/filemap.c (ffffffff8125e6ae)
Location: include/linux/page-flags.h:616
Inline: True
Inline callers:
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/truncate.c (ffffffff8126c320)
Location: include/linux/page-flags.h:616
Inline: True
Inline callers:
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:__invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff81270bbb)
Location: include/linux/page-flags.h:616
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81279cec)
Location: include/linux/page-flags.h:616
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mlock.c (ffffffff812a213b)
Location: include/linux/page-flags.h:616
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/page_vma_mapped.c (ffffffff812ad380)
Location: include/linux/page-flags.h:616
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812af40a)
Location: include/linux/page-flags.h:616
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_io.c (ffffffff812c38f2)
Location: include/linux/page-flags.h:616
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_slots.c (ffffffff812cbfec)
Location: include/linux/page-flags.h:616
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff812cdf1a)
Location: include/linux/page-flags.h:616
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff812dad66)
Location: include/linux/page-flags.h:616
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/memory_hotplug.c (ffffffff812ec06a)
Location: include/linux/page-flags.h:616
Inline: True
```
```
In mm/migrate.c (ffffffff812ed40e)
Location: include/linux/page-flags.h:616
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812f3b55)
Location: include/linux/page-flags.h:616
Inline: True
```
```
In mm/memcontrol.c (ffffffff81306594)
Location: include/linux/page-flags.h:616
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8130ed8a)
Location: include/linux/page-flags.h:616
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:__get_hwpoison_page
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
In mm/filemap.c (ffffffff8125fa2e)
Location: include/linux/page-flags.h:610
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff812756a4)
Location: include/linux/page-flags.h:610
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8127ee23)
Location: include/linux/page-flags.h:610
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mlock.c (ffffffff812a79cb)
Location: include/linux/page-flags.h:610
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (ffffffff812b48d8)
Location: include/linux/page-flags.h:610
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/memory_hotplug.c (ffffffff812c699f)
Location: include/linux/page-flags.h:610
Inline: True
```
```
In mm/page_io.c (ffffffff812ca6ad)
Location: include/linux/page-flags.h:610
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_slots.c (ffffffff812d2b9c)
Location: include/linux/page-flags.h:610
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff812d45ba)
Location: include/linux/page-flags.h:610
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff812e25c6)
Location: include/linux/page-flags.h:610
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/migrate.c (ffffffff812f37af)
Location: include/linux/page-flags.h:610
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812f9d85)
Location: include/linux/page-flags.h:610
Inline: True
```
```
In mm/memcontrol.c (ffffffff8130ca7d)
Location: include/linux/page-flags.h:610
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff813150e0)
Location: include/linux/page-flags.h:610
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_any_page
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
In mm/filemap.c (ffffffff8129c39e)
Location: include/linux/page-flags.h:630
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff812b3694)
Location: include/linux/page-flags.h:630
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812bd2ca)
Location: include/linux/page-flags.h:630
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mlock.c (ffffffff812e8feb)
Location: include/linux/page-flags.h:630
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (ffffffff812f64b8)
Location: include/linux/page-flags.h:630
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/memory_hotplug.c (ffffffff8130b442)
Location: include/linux/page-flags.h:630
Inline: True
```
```
In mm/page_io.c (ffffffff8130f6aa)
Location: include/linux/page-flags.h:630
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_slots.c (ffffffff81318570)
Location: include/linux/page-flags.h:630
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff8131a8d1)
Location: include/linux/page-flags.h:630
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff813297f7)
Location: include/linux/page-flags.h:630
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/migrate.c (ffffffff8134354a)
Location: include/linux/page-flags.h:630
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81343beb)
Location: include/linux/page-flags.h:630
Inline: True
```
```
In mm/memcontrol.c (ffffffff81357c7d)
Location: include/linux/page-flags.h:630
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81361184)
Location: include/linux/page-flags.h:630
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/memfd.c (ffffffff8136b5d2)
Location: include/linux/page-flags.h:630
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
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
In mm/filemap.c (ffffffff812f3533)
Location: include/linux/page-flags.h:848
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/rmap.c (ffffffff8135c387)
Location: include/linux/page-flags.h:848
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/memory_hotplug.c (ffffffff81373f23)
Location: include/linux/page-flags.h:848
Inline: True
```
```
In mm/page_io.c (ffffffff81378f40)
Location: include/linux/page-flags.h:848
Inline: True
Inline callers:
  - mm/page_io.c:count_swpout_vm_event
```
```
In mm/zswap.c (ffffffff81385ea9)
Location: include/linux/page-flags.h:848
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/migrate.c (ffffffff813b2c76)
Location: include/linux/page-flags.h:848
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:migrate_pages
```
```
In mm/memory-failure.c (ffffffff813dd452)
Location: include/linux/page-flags.h:848
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/memfd.c (ffffffff813e9645)
Location: include/linux/page-flags.h:848
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
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
In mm/filemap.c (ffffffff8135d883)
Location: include/linux/page-flags.h:845
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/rmap.c (ffffffff813d8158)
Location: include/linux/page-flags.h:845
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_anon_rmap
```
```
In mm/memory_hotplug.c (ffffffff813f19d3)
Location: include/linux/page-flags.h:845
Inline: True
```
```
In mm/page_io.c (ffffffff813f68d0)
Location: include/linux/page-flags.h:845
Inline: True
Inline callers:
  - mm/page_io.c:count_swpout_vm_event
```
```
In mm/zswap.c (ffffffff81403ce9)
Location: include/linux/page-flags.h:845
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/migrate.c (ffffffff81433066)
Location: include/linux/page-flags.h:845
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
```
```
In mm/memory-failure.c (ffffffff814619c6)
Location: include/linux/page-flags.h:845
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/memfd.c (ffffffff81471622)
Location: include/linux/page-flags.h:845
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
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
In mm/memory_hotplug.c (ffffffff81425781)
Location: include/linux/page-flags.h:829
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/page_io.c (ffffffff8142aa84)
Location: include/linux/page-flags.h:829
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:sio_write_complete
```
```
In mm/zswap.c (ffffffff81436b4f)
Location: include/linux/page-flags.h:829
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/migrate.c (ffffffff814689d8)
Location: include/linux/page-flags.h:829
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
```
```
In mm/memory-failure.c (ffffffff8149726b)
Location: include/linux/page-flags.h:829
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/memfd.c (ffffffff814a5b5d)
Location: include/linux/page-flags.h:829
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
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
In mm/memory_hotplug.c (ffffffff8145276d)
Location: include/linux/page-flags.h:864
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/memory-failure.c (ffffffff814c8701)
Location: include/linux/page-flags.h:864
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memfd.c (ffffffff814d6b0d)
Location: include/linux/page-flags.h:864
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
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
In mm/filemap.c (ffff8000102aed34)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffff8000102c10fc)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffff8000102c50a8)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffff8000102ce7cc)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffff8000102d3efc)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffff8000102eb320)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffff8000102f31ac)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/mlock.c (ffff8000102fe174)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffff8000103076b4)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffff800010308d34)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffff8000103204b0)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffff800010321590)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
```
```
In mm/swap_slots.c (ffff800010329ddc)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffff80001032bf30)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffff80001033a630)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/migrate.c (ffff800010353004)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffff80001035416c)
Location: include/linux/page-flags.h:596
Inline: True
```
```
In mm/memcontrol.c (ffff80001036b474)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffff8000103701d8)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_isolation.c (ffff800010372254)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/filemap.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/swap_slots.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/page-flags.h:701
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
In mm/filemap.c (c0000000003621c8)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (c00000000037c1a0)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (c00000000037f8ec)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (c00000000038c5e8)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (c000000000393198)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (c0000000003ac8b8)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (c0000000003b9c30)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/mlock.c (c0000000003c9894)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (c0000000003d61ec)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (c0000000003d7f98)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (c0000000003f5604)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (c0000000003f6be0)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
```
```
In mm/swap_slots.c (c000000000400ab8)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (c000000000402acc)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (c000000000414e3c)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (c00000000042e194)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (c000000000439bac)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (c00000000043b11c)
Location: include/linux/page-flags.h:596
Inline: True
```
```
In mm/memcontrol.c (c00000000045ae30)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (c00000000045ee3c)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (c000000000463b78)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/filemap.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/swap_slots.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/page-flags.h:701
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/page-flags.h:701
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
In mm/filemap.c (ffffffff81219d80)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff8122a8f3)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff8122d00d)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff812359ea)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8123a0b4)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff8124adb0)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8125440d)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/mlock.c (ffffffff8125f565)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff8126a20f)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8126b63d)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffffffff8127e558)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff8127f2ea)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
```
```
In mm/swapfile.c (ffffffff81281a15)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff812860dc)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff81287b61)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff81293d46)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff812a44d9)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812ab168)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812ab915)
Location: include/linux/page-flags.h:596
Inline: True
```
```
In mm/memcontrol.c (ffffffff812c0b34)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812c2de7)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff812c63c8)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/filemap.c (ffffffff8120cf90)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff8121da13)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff812200dd)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff81228a54)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8122d0c4)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff8123dd50)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8124705d)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/mlock.c (ffffffff81251985)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff8125c3ff)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8125d8dd)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffffffff81270388)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff81271104)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
```
```
In mm/swapfile.c (ffffffff81273535)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff81277f3c)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff812799c1)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff81285956)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff81295fa9)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff8129c9e8)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff8129d215)
Location: include/linux/page-flags.h:596
Inline: True
```
```
In mm/memcontrol.c (ffffffff812b1bc4)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812b3e37)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff812b7408)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
```
```
In drivers/nvdimm/pmem.c (ffffffff816ebcd8)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:pmem_rw_page
```
```
In drivers/nvdimm/btt.c (ffffffff816ed3a3)
Location: include/linux/page-flags.h:596
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
In mm/filemap.c (ffffffff81217b20)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81228693)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff8122adad)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff8123378a)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81237e54)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff81248b50)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff812521ad)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/mlock.c (ffffffff8125d305)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff81267faf)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812693dd)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffffffff8127c2f8)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff8127d08a)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
```
```
In mm/swapfile.c (ffffffff8127f825)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff81283eec)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff81285971)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff81291b56)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff812a22e9)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812a8f78)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812a9725)
Location: include/linux/page-flags.h:596
Inline: True
```
```
In mm/memcontrol.c (ffffffff812be944)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812c0bf7)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff812c41d8)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
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
In mm/filemap.c (ffffffff81226be0)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81237a03)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff8123a1ad)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff81242cc1)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81247494)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff81258381)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81261b5d)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/mlock.c (ffffffff8126ccf0)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff8127792f)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff81278f08)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffffffff8128bec8)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff8128cc41)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
```
```
In mm/swapfile.c (ffffffff8128f505)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff81293bcc)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff81295691)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff812a1966)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff812b2649)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812b9292)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812b9cc5)
Location: include/linux/page-flags.h:596
Inline: True
```
```
In mm/memcontrol.c (ffffffff812cf3b4)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812d16b7)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff812d4c98)
Location: include/linux/page-flags.h:596
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
```
</details>
</li>
</ul>

## Differences
