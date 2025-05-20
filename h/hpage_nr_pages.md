# Function: <code>hpage_nr_pages</code>

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
Location: include/linux/huge_mm.h:143
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
Location: include/linux/huge_mm.h:143
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
Location: include/linux/huge_mm.h:143
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811c2d0e)
Location: include/linux/huge_mm.h:143
Inline: True
Inline callers:
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:munlock_vma_page
```
```
In mm/rmap.c (ffffffff811cae5b)
Location: include/linux/huge_mm.h:143
Inline: True
Inline callers:
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/migrate.c (ffffffff811f1031)
Location: include/linux/huge_mm.h:143
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/memcontrol.c (ffffffff811fed21)
Location: include/linux/huge_mm.h:143
Inline: True
Inline callers:
  - mm/memcontrol.c:lock_page_lru
  - mm/memcontrol.c:unlock_page_lru
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
In mm/filemap.c (ffffffff811a1dbc)
Location: include/linux/huge_mm.h:134
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/swap.c (ffffffff811b1fb4)
Location: include/linux/huge_mm.h:134
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
In mm/vmscan.c (ffffffff811bcaef)
Location: include/linux/huge_mm.h:134
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
```
```
In mm/shmem.c (ffffffff811c0542)
Location: include/linux/huge_mm.h:134
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff811c4a1a)
Location: include/linux/huge_mm.h:134
Inline: True
```
```
In mm/compaction.c (ffffffff811cff6d)
Location: include/linux/huge_mm.h:134
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811def40)
Location: include/linux/huge_mm.h:134
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/rmap.c (ffffffff811e7d84)
Location: include/linux/huge_mm.h:134
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_check_address_transhuge
```
```
In mm/migrate.c (ffffffff8121356d)
Location: include/linux/huge_mm.h:134
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_copy
```
```
In mm/memcontrol.c (ffffffff81224168)
Location: include/linux/huge_mm.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
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
In mm/filemap.c (ffffffff811b1c30)
Location: include/linux/huge_mm.h:138
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/swap.c (ffffffff811c2615)
Location: include/linux/huge_mm.h:138
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
In mm/vmscan.c (ffffffff811cd0b0)
Location: include/linux/huge_mm.h:138
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
```
```
In mm/shmem.c (ffffffff811d0b22)
Location: include/linux/huge_mm.h:138
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff811d4b2a)
Location: include/linux/huge_mm.h:138
Inline: True
```
```
In mm/compaction.c (ffffffff811dff9c)
Location: include/linux/huge_mm.h:138
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811eed7b)
Location: include/linux/huge_mm.h:138
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff811f6d97)
Location: include/linux/huge_mm.h:138
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff811f9104)
Location: include/linux/huge_mm.h:138
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_check_address_transhuge
```
```
In mm/migrate.c (ffffffff812258d2)
Location: include/linux/huge_mm.h:138
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_copy
```
```
In mm/memcontrol.c (ffffffff81236668)
Location: include/linux/huge_mm.h:138
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
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
In mm/filemap.c (ffffffff811b893f)
Location: include/linux/huge_mm.h:200
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/swap.c (ffffffff811caa98)
Location: include/linux/huge_mm.h:200
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
In mm/vmscan.c (ffffffff811d5eb5)
Location: include/linux/huge_mm.h:200
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
```
```
In mm/shmem.c (ffffffff811d90b2)
Location: include/linux/huge_mm.h:200
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff811dd947)
Location: include/linux/huge_mm.h:200
Inline: True
```
```
In mm/compaction.c (ffffffff811e996e)
Location: include/linux/huge_mm.h:200
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811f9d2b)
Location: include/linux/huge_mm.h:200
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff81202205)
Location: include/linux/huge_mm.h:200
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff81203498)
Location: include/linux/huge_mm.h:200
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/swap_state.c (ffffffff8120be87)
Location: include/linux/huge_mm.h:200
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/migrate.c (ffffffff81230ca2)
Location: include/linux/huge_mm.h:200
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_copy
```
```
In mm/memcontrol.c (ffffffff812425e3)
Location: include/linux/huge_mm.h:200
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
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
In mm/filemap.c (ffffffff811cd19f)
Location: include/linux/huge_mm.h:207
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff811df808)
Location: include/linux/huge_mm.h:207
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
In mm/vmscan.c (ffffffff811eb3d5)
Location: include/linux/huge_mm.h:207
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
```
```
In mm/shmem.c (ffffffff811ee392)
Location: include/linux/huge_mm.h:207
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff811f33c7)
Location: include/linux/huge_mm.h:207
Inline: True
```
```
In mm/compaction.c (ffffffff811ffcb4)
Location: include/linux/huge_mm.h:207
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8121217b)
Location: include/linux/huge_mm.h:207
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff8121ae05)
Location: include/linux/huge_mm.h:207
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8121bfd8)
Location: include/linux/huge_mm.h:207
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffffffff81224a20)
Location: include/linux/huge_mm.h:207
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff81225488)
Location: include/linux/huge_mm.h:207
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/mempolicy.c (ffffffff812369cf)
Location: include/linux/huge_mm.h:207
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff81989ef5)
Location: include/linux/huge_mm.h:207
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff8124e9fc)
Location: include/linux/huge_mm.h:207
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memcontrol.c (ffffffff81262423)
Location: include/linux/huge_mm.h:207
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
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
In mm/filemap.c (ffffffff811eed00)
Location: include/linux/huge_mm.h:208
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81201eb6)
Location: include/linux/huge_mm.h:208
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8120cbd7)
Location: include/linux/huge_mm.h:208
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
```
```
In mm/shmem.c (ffffffff8120ecd2)
Location: include/linux/huge_mm.h:208
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff812145f7)
Location: include/linux/huge_mm.h:208
Inline: True
```
```
In mm/compaction.c (ffffffff81221456)
Location: include/linux/huge_mm.h:208
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81232ebc)
Location: include/linux/huge_mm.h:208
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff8123cc5f)
Location: include/linux/huge_mm.h:208
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8123e05d)
Location: include/linux/huge_mm.h:208
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffffffff81246ea9)
Location: include/linux/huge_mm.h:208
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff81247a28)
Location: include/linux/huge_mm.h:208
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/mempolicy.c (ffffffff8125999f)
Location: include/linux/huge_mm.h:208
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff819e667a)
Location: include/linux/huge_mm.h:208
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff8127282c)
Location: include/linux/huge_mm.h:208
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memcontrol.c (ffffffff812864e3)
Location: include/linux/huge_mm.h:208
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812889b5)
Location: include/linux/huge_mm.h:208
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
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
In mm/filemap.c (ffffffff811fbe20)
Location: include/linux/huge_mm.h:214
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81214836)
Location: include/linux/huge_mm.h:214
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8121fa9d)
Location: include/linux/huge_mm.h:214
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
```
```
In mm/compaction.c (ffffffff812344a9)
Location: include/linux/huge_mm.h:214
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8124668c)
Location: include/linux/huge_mm.h:214
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff8125112f)
Location: include/linux/huge_mm.h:214
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812525f0)
Location: include/linux/huge_mm.h:214
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffffffff8125b2da)
Location: include/linux/huge_mm.h:214
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff8125bfea)
Location: include/linux/huge_mm.h:214
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
```
```
In mm/swapfile.c (ffffffff8125ecc5)
Location: include/linux/huge_mm.h:214
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/mempolicy.c (ffffffff8126d5b1)
Location: include/linux/huge_mm.h:214
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff81a21b06)
Location: include/linux/huge_mm.h:214
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff81286de4)
Location: include/linux/huge_mm.h:214
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memcontrol.c (ffffffff8129b443)
Location: include/linux/huge_mm.h:214
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8129d6b5)
Location: include/linux/huge_mm.h:214
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
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
In mm/filemap.c (ffffffff81213f20)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81224513)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8122f20a)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff812442a0)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8124d887)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff812588f5)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff8126340f)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8126477d)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffffffff81276427)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff812771ba)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
```
```
In mm/swapfile.c (ffffffff81279955)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/mempolicy.c (ffffffff81288af4)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff8129c4c0)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a177a)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memcontrol.c (ffffffff812b6684)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812b89f3)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff812322a3)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8123d39a)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81252760)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8125bdbd)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff81266dc5)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff81271bbf)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff81272fed)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffffffff81285f17)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff81286c9a)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
```
```
In mm/swapfile.c (ffffffff81289435)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/mempolicy.c (ffffffff81298664)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff812abf1f)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b2b88)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memcontrol.c (ffffffff812c8554)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812ca8d3)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
Location: include/linux/huge_mm.h:268
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/readahead.c (ffffffff8125cc18)
Location: include/linux/huge_mm.h:268
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff8125f428)
Location: include/linux/huge_mm.h:268
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
In mm/vmscan.c (ffffffff81265960)
Location: include/linux/huge_mm.h:268
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
```
```
In mm/compaction.c (ffffffff81282bc0)
Location: include/linux/huge_mm.h:268
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81286e95)
Location: include/linux/huge_mm.h:268
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/mlock.c (ffffffff81297004)
Location: include/linux/huge_mm.h:268
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff812a21ef)
Location: include/linux/huge_mm.h:268
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812a401d)
Location: include/linux/huge_mm.h:268
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffffffff812b8237)
Location: include/linux/huge_mm.h:268
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff812b921a)
Location: include/linux/huge_mm.h:268
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff812bc045)
Location: include/linux/huge_mm.h:268
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/mempolicy.c (ffffffff812cc1d4)
Location: include/linux/huge_mm.h:268
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff812e137d)
Location: include/linux/huge_mm.h:268
Inline: True
```
```
In mm/migrate.c (ffffffff812e8106)
Location: include/linux/huge_mm.h:268
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memcontrol.c (ffffffff812fdde5)
Location: include/linux/huge_mm.h:268
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff813006c3)
Location: include/linux/huge_mm.h:268
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/memfd.c (ffffffff8130c002)
Location: include/linux/huge_mm.h:268
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/mpage.c (ffffffff81365559)
Location: include/linux/huge_mm.h:268
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/iomap/buffered-io.c (ffffffff813ab560)
Location: include/linux/huge_mm.h:268
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead_actor
```
```
In fs/ext4/readpage.c (ffffffff8141875b)
Location: include/linux/huge_mm.h:268
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/fuse/file.c (ffffffff81475e18)
Location: include/linux/huge_mm.h:268
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
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
In mm/filemap.c (ffff8000102aed34)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffff8000102c10fc)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffff8000102ce7cc)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffff8000102eb320)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffff8000102f31ac)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffff8000102fdfdc)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffff8000103076b4)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffff800010308d34)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffff8000103204b8)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffff800010321590)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
```
```
In mm/mempolicy.c (ffff8000103372d4)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/migrate.c (ffff800010353004)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memcontrol.c (ffff80001036b474)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (0)
Location: include/linux/huge_mm.h:234
Inline: True
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (c00000000037c1a0)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (c00000000038c5e8)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (c0000000003ac8b8)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (c0000000003b9c30)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (c0000000003c9638)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (c0000000003d61ec)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (c0000000003d7f98)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (c0000000003f5610)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (c0000000003f6be0)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
```
```
In mm/mempolicy.c (c000000000411ce0)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (c00000000042e1c4)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (c000000000439bac)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memcontrol.c (c00000000045ae30)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (c00000000045e96c)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff8122a8f3)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812359ea)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff8124adb0)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8125440d)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff8125f415)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff8126a20f)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8126b63d)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffffffff8127e567)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff8127f2ea)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
```
```
In mm/swapfile.c (ffffffff81281a15)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/mempolicy.c (ffffffff81290c44)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff812a44ff)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812ab168)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memcontrol.c (ffffffff812c0b34)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812c2eb3)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff8121da13)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81228a54)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff8123dd50)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8124705d)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff8125182f)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff8125c3ff)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8125d8dd)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffffffff81270397)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff81271104)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
```
```
In mm/swapfile.c (ffffffff81273535)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/mempolicy.c (ffffffff812828c4)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff81295fcf)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff8129c9e8)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memcontrol.c (ffffffff812b1bc4)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812b3fa8)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In drivers/nvdimm/pmem.c (ffffffff816ebcd8)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:pmem_rw_page
```
```
In drivers/nvdimm/btt.c (ffffffff816ed3a3)
Location: include/linux/huge_mm.h:234
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
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81228693)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8123378a)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81248b50)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff812521ad)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff8125d1b5)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff81267faf)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812693dd)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffffffff8127c307)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff8127d08a)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
```
```
In mm/swapfile.c (ffffffff8127f825)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/mempolicy.c (ffffffff8128ea54)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff812a230f)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a8f78)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memcontrol.c (ffffffff812be944)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812c0cc3)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81237a03)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81242cc1)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81258381)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81261b5d)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff8126cbab)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff8127792f)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff81278f08)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffffffff8128bed7)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff8128cc41)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
```
```
In mm/swapfile.c (ffffffff8128f505)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/mempolicy.c (ffffffff8129e954)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff812b266f)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b9292)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memcontrol.c (ffffffff812cf3b4)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812d1783)
Location: include/linux/huge_mm.h:234
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
</details>
</li>
</ul>

## Differences
