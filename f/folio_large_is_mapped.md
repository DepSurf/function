# Function: <code>folio_large_is_mapped</code>

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
In <code>5.8</code>: Absent ⚠️
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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8134fe60)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff813599b3)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/swap.c (ffffffff81370428)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/truncate.c (ffffffff8137189d)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff81381238)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:isolate_folio
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff8138f94f)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff813ba6d3)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
```
```
In mm/rmap.c (ffffffff813d5ce3)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/rmap.c:folio_not_mapped
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/memory_hotplug.c (ffffffff813f1e7e)
Location: include/linux/mm.h:920
Inline: True
```
```
In mm/swap_state.c (ffffffff813f90a3)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff813fe7b4)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/ksm.c (ffffffff8141f2ce)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
```
```
In mm/migrate.c (ffffffff814349df)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/migrate_device.c (ffffffff81438356)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
```
```
In mm/khugepaged.c (ffffffff81449b32)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff81453351)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff814620aa)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In mm/page_idle.c (ffffffff8146e003)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In fs/proc/page.c (ffffffff81548089)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/ext4/inode.c (ffffffff81579e2a)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6ba2)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fuse/dev.c (ffffffff8161b145)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
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
In kernel/events/uprobes.c (ffffffff81381019)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8138b300)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/swap.c (ffffffff813a25a8)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/truncate.c (ffffffff813a39aa)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff813b25ec)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff813bf723)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff813ef093)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
```
```
In mm/rmap.c (ffffffff8140ae13)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/rmap.c:folio_not_mapped
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/memory_hotplug.c (ffffffff81425a7d)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/swap_state.c (ffffffff8142be73)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff81431705)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/ksm.c (ffffffff81453e1b)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
```
```
In mm/migrate.c (ffffffff8146a265)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
```
```
In mm/migrate_device.c (ffffffff8146dfcf)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
```
```
In mm/khugepaged.c (ffffffff8147ff6a)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff81488f3b)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81496df5)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In mm/page_idle.c (ffffffff814a287b)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In fs/proc/page.c (ffffffff8157fc5d)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/ext4/inode.c (ffffffff815b19bd)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff8162ec5c)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fuse/dev.c (ffffffff816532b5)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
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
In kernel/events/uprobes.c (ffffffff813aa3f2)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff813b4e2d)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/swap.c (ffffffff813cc21d)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/truncate.c (ffffffff813cd4c7)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff813dbb81)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff813ea75c)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff8141af98)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
```
```
In mm/rmap.c (ffffffff81437570)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - mm/rmap.c:folio_not_mapped
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/memory_hotplug.c (ffffffff81452bea)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/swap_state.c (ffffffff814655cd)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff8146aaf2)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/ksm.c (ffffffff8148e6e3)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
```
```
In mm/migrate.c (ffffffff8149922c)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
```
```
In mm/migrate_device.c (ffffffff8149e98d)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
```
```
In mm/khugepaged.c (ffffffff814adf26)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff814b91cd)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff814c6bf7)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In mm/page_idle.c (ffffffff814d3718)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In fs/proc/page.c (ffffffff815b865b)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/ext4/inode.c (ffffffff815eaa24)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff81668124)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fuse/dev.c (ffffffff8168c8b8)
Location: include/linux/mm.h:1248
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
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
