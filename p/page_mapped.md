# Function: <code>page_mapped</code>

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
In kernel/events/uprobes.c (ffffffff811878ba)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8118e50b)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/swap.c (ffffffff8119c597)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/truncate.c (ffffffff8119e9f4)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_page
  - mm/truncate.c:invalidate_inode_page
```
```
In mm/vmscan.c (ffffffff811a26a9)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811a858d)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/rmap.c (ffffffff811ca425)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/rmap.c:page_not_mapped
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_referenced
  - mm/rmap.c:try_to_unmap
```
```
In mm/swap_state.c (ffffffff811d2995)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:free_pages_and_swap_cache
```
```
In mm/swapfile.c (ffffffff811d5210)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/ksm.c (ffffffff811e4bd1)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff811f26c0)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/memcontrol.c (ffffffff811faa25)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81201bd3)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_idle.c (ffffffff81208315)
Location: include/linux/mm.h:982
Inline: True
```
```
In fs/proc/page.c (ffffffff812880a3)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/hugetlbfs/inode.c (ffffffff812f39a8)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fuse/dev.c (ffffffff8130ea24)
Location: include/linux/mm.h:982
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool page_mapped(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811c49b0)
Location: mm/util.c:354
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_inode_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/rmap.c:page_not_mapped
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:remove_stable_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/khugepaged.c:collapse_shmem
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - fs/proc/page.c:stable_page_flags
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff811c49b0-ffffffff811c4a3c: page_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool page_mapped(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811d4ac0)
Location: mm/util.c:357
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_inode_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/rmap.c:page_not_mapped
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/khugepaged.c:collapse_shmem
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - fs/proc/page.c:stable_page_flags
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff811d4ac0-ffffffff811d4b4c: page_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool page_mapped(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811dd8e0)
Location: mm/util.c:441
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_inode_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/rmap.c:page_not_mapped
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/khugepaged.c:collapse_shmem
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - fs/proc/page.c:stable_page_flags
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff811dd8e0-ffffffff811dd96a: page_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool page_mapped(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811f3360)
Location: mm/util.c:441
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/rmap.c:page_not_mapped
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/khugepaged.c:collapse_shmem
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - fs/proc/page.c:stable_page_flags
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff811f3360-ffffffff811f33ea: page_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool page_mapped(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81214590)
Location: mm/util.c:467
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/rmap.c:page_not_mapped
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/khugepaged.c:collapse_shmem
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - fs/proc/page.c:stable_page_flags
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff81214590-ffffffff8121461a: page_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool page_mapped(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81227460)
Location: mm/util.c:470
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/rmap.c:page_not_mapped
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/khugepaged.c:collapse_shmem
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - fs/proc/page.c:stable_page_flags
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff81227460-ffffffff812274f1: page_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool page_mapped(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812371e0)
Location: mm/util.c:513
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/rmap.c:page_not_mapped
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/khugepaged.c:collapse_shmem
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - fs/proc/page.c:stable_page_flags
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff812371e0-ffffffff8123727c: page_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool page_mapped(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81245450)
Location: mm/util.c:618
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/rmap.c:page_not_mapped
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - fs/proc/page.c:stable_page_flags
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81245450-ffffffff812454ee: page_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool page_mapped(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81272fa0)
Location: mm/util.c:646
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/rmap.c:page_not_mapped
  - mm/rmap.c:page_mkclean
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/hugetlb.c:hugetlb_page_mapping_lock_write
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mc_handle_present_pte
  - mm/memory-failure.c:unpoison_memory
  - fs/proc/page.c:stable_page_flags
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81272fa0-ffffffff81273041: page_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool page_mapped(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127d640)
Location: mm/util.c:659
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
  - mm/vmscan.c:__isolate_lru_page_prepare
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/rmap.c:page_not_mapped
  - mm/rmap.c:page_mkclean
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - fs/proc/page.c:stable_page_flags
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff8127d640-ffffffff8127d6d1: page_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool page_mapped(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812827c0)
Location: mm/util.c:659
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/rmap.c:page_not_mapped
  - mm/rmap.c:page_mkclean
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - fs/proc/page.c:stable_page_flags
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff812827c0-ffffffff81282851: page_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool page_mapped(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c0930)
Location: mm/util.c:680
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/rmap.c:page_not_mapped
  - mm/rmap.c:page_mkclean
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - fs/proc/page.c:stable_page_flags
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff812c0930-ffffffff812c09c1: page_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool page_mapped(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff81300d10)
Location: mm/folio-compat.c:42
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/swap.c:lru_deactivate_file_fn
  - mm/vmscan.c:isolate_lru_pages
  - mm/shmem.c:shmem_writepage
  - mm/memory.c:__do_fault
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - fs/proc/page.c:stable_page_flags
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81300d10-ffffffff81300d67: page_mapped (STB_GLOBAL)
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
In mm/memory.c (ffffffff813ba6b8)
Location: include/linux/mm.h:948
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
```
```
In mm/ksm.c (ffffffff8141f386)
Location: include/linux/mm.h:948
Inline: True
Inline callers:
  - mm/ksm.c:remove_stable_node
```
```
In mm/migrate_device.c (ffffffff814380df)
Location: include/linux/mm.h:948
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
```
```
In mm/memcontrol.c (ffffffff81453233)
Location: include/linux/mm.h:948
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8146207f)
Location: include/linux/mm.h:948
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/page.c (ffffffff81548067)
Location: include/linux/mm.h:948
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/memory.c (ffffffff813ef078)
Location: include/linux/mm.h:1193
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
```
```
In mm/ksm.c (ffffffff81453f26)
Location: include/linux/mm.h:1193
Inline: True
Inline callers:
  - mm/ksm.c:remove_stable_node
```
```
In mm/migrate_device.c (ffffffff8146ddaf)
Location: include/linux/mm.h:1193
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
```
```
In mm/memcontrol.c (ffffffff81488e8f)
Location: include/linux/mm.h:1193
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814984d2)
Location: include/linux/mm.h:1193
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/page.c (ffffffff8157fc3b)
Location: include/linux/mm.h:1193
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/memory.c (ffffffff8141af80)
Location: include/linux/mm.h:1276
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
```
```
In mm/ksm.c (ffffffff8148e7e6)
Location: include/linux/mm.h:1276
Inline: True
Inline callers:
  - mm/ksm.c:remove_stable_node
```
```
In mm/migrate_device.c (ffffffff8149e77c)
Location: include/linux/mm.h:1276
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
```
```
In mm/memcontrol.c (ffffffff814b9196)
Location: include/linux/mm.h:1276
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814c7ab9)
Location: include/linux/mm.h:1276
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/page.c (ffffffff815b863c)
Location: include/linux/mm.h:1276
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool page_mapped(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffff8000102d83b0)
Location: mm/util.c:618
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/rmap.c:page_not_mapped
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - fs/proc/page.c:stable_page_flags
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffff8000102d83b0-ffff8000102d846c: page_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool page_mapped(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (c04ff694)
Location: mm/util.c:618
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/rmap.c:page_not_mapped
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/page.c:stable_page_flags
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
c04ff694-c04ff738: page_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool page_mapped(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (c000000000398180)
Location: mm/util.c:618
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/rmap.c:page_not_mapped
  - mm/rmap.c:page_mkclean
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - fs/proc/page.c:stable_page_flags
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
c000000000398180-c0000000003982b0: page_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool page_mapped(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f2c7e)
Location: mm/util.c:618
Inline: True
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/rmap.c:page_not_mapped
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/page.c:stable_page_flags
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffe0001f2c7e-ffffffe0001f2d1a: page_mapped (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool page_mapped(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123daa0)
Location: mm/util.c:618
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/rmap.c:page_not_mapped
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - fs/proc/page.c:stable_page_flags
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff8123daa0-ffffffff8123db3e: page_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool page_mapped(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81230aa0)
Location: mm/util.c:618
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/rmap.c:page_not_mapped
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - fs/proc/page.c:stable_page_flags
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81230aa0-ffffffff81230b3e: page_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool page_mapped(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123b840)
Location: mm/util.c:618
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/rmap.c:page_not_mapped
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - fs/proc/page.c:stable_page_flags
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff8123b840-ffffffff8123b8de: page_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool page_mapped(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8124af50)
Location: mm/util.c:618
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/rmap.c:page_not_mapped
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_get_anon_vma
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memory-failure.c:unpoison_memory
  - fs/proc/page.c:stable_page_flags
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff8124af50-ffffffff8124afee: page_mapped (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
