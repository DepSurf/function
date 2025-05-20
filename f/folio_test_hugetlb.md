# Function: <code>folio_test_hugetlb</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e5e1d)
Location: include/linux/page-flags.h:830
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812f44ab)
Location: include/linux/page-flags.h:830
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_free_folio
  - mm/filemap.c:__filemap_remove_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/folio-compat.c (ffffffff81300a49)
Location: include/linux/page-flags.h:830
Inline: True
Inline callers:
  - mm/folio-compat.c:pagecache_get_page
```
```
In mm/util.c (ffffffff8131df4f)
Location: include/linux/page-flags.h:830
Inline: True
Inline callers:
  - mm/util.c:folio_mapcount
```
```
In mm/gup.c (ffffffff81337b20)
Location: include/linux/page-flags.h:830
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
```
```
In mm/rmap.c (ffffffff8135bad1)
Location: include/linux/page-flags.h:830
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/mempolicy.c (ffffffff81398adc)
Location: include/linux/page-flags.h:830
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/migrate.c (ffffffff813b1684)
Location: include/linux/page-flags.h:830
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/page_idle.c (ffffffff813e635c)
Location: include/linux/page-flags.h:830
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/verity/enable.c (ffffffff81472092)
Location: include/linux/page-flags.h:830
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/iomap/buffered-io.c (ffffffff8148b5a6)
Location: include/linux/page-flags.h:830
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_iter
```
```
In lib/iov_iter.c (ffffffff816e6bc4)
Location: include/linux/page-flags.h:830
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
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
In kernel/events/uprobes.c (ffffffff8134fa7f)
Location: include/linux/page-flags.h:827
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8135e5a6)
Location: include/linux/page-flags.h:827
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:filemap_free_folio
  - mm/filemap.c:__filemap_remove_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/folio-compat.c (ffffffff8136b314)
Location: include/linux/page-flags.h:827
Inline: True
Inline callers:
  - mm/folio-compat.c:pagecache_get_page
```
```
In mm/swap.c (ffffffff8136f675)
Location: include/linux/page-flags.h:827
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/swap.c:__folio_put
```
```
In mm/vmscan.c (ffffffff8138697d)
Location: include/linux/page-flags.h:827
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff8138d8f4)
Location: include/linux/page-flags.h:827
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
```
```
In mm/gup.c (ffffffff813ae920)
Location: include/linux/page-flags.h:827
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
```
```
In mm/memory.c (ffffffff813bbcde)
Location: include/linux/page-flags.h:827
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff813d6791)
Location: include/linux/page-flags.h:827
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/swap_state.c (ffffffff813f96e8)
Location: include/linux/page-flags.h:827
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffff813fd14d)
Location: include/linux/page-flags.h:827
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81412c85)
Location: include/linux/page-flags.h:827
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/mempolicy.c (ffffffff81418982)
Location: include/linux/page-flags.h:827
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/migrate.c (ffffffff814329f4)
Location: include/linux/page-flags.h:827
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff81449af1)
Location: include/linux/page-flags.h:827
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff814533be)
Location: include/linux/page-flags.h:827
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff8146d4f9)
Location: include/linux/page-flags.h:827
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
```
```
In mm/page_idle.c (ffffffff8146de47)
Location: include/linux/page-flags.h:827
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/verity/enable.c (ffffffff815040d8)
Location: include/linux/page-flags.h:827
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/iomap/buffered-io.c (ffffffff8151f5fb)
Location: include/linux/page-flags.h:827
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_iter
```
```
In lib/iov_iter.c (ffffffff817d6526)
Location: include/linux/page-flags.h:827
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool folio_test_hugetlb(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81446496)
Location: mm/hugetlb.c:2086
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_hugetlb_folio
  - mm/hugetlb.c:isolate_hugetlb
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:filemap_free_folio
  - mm/filemap.c:__filemap_remove_folio
  - mm/filemap.c:__filemap_remove_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/folio-compat.c:pagecache_get_page
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/swap.c:__folio_put
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/gup.c:folio_fast_pin_allowed
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/memory.c:do_swap_page
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:unuse_pte
  - mm/mempolicy.c:new_folio
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_hugetlbs
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/huge_memory.c:split_huge_pages_all
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff81438840-ffffffff81438864: folio_test_hugetlb (STB_GLOBAL)
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
In mm/filemap.c (ffffffff813b5f11)
Location: include/linux/page-flags.h:846
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/swap.c (ffffffff813cb412)
Location: include/linux/page-flags.h:846
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/swap.c:__folio_put
```
```
In mm/vmscan.c (ffffffff813dfcd0)
Location: include/linux/page-flags.h:846
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/gup.c (ffffffff8140dab2)
Location: include/linux/page-flags.h:846
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
```
```
In mm/rmap.c (ffffffff8143a33a)
Location: include/linux/page-flags.h:846
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff8144bb55)
Location: include/linux/page-flags.h:846
Inline: True
Inline callers:
  - mm/page_alloc.c:destroy_large_folio
```
```
In mm/hugetlb.c (ffffffff8147ff36)
Location: include/linux/page-flags.h:846
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_hugetlb_folio
  - mm/hugetlb.c:isolate_hugetlb
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:PageHuge
```
```
In mm/mempolicy.c (ffffffff81485bad)
Location: include/linux/page-flags.h:846
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_migration_target_by_mpol
```
```
In mm/migrate.c (ffffffff81497451)
Location: include/linux/page-flags.h:846
Inline: True
Inline callers:
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_hugetlbs
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff814a7a42)
Location: include/linux/page-flags.h:846
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff814c63a6)
Location: include/linux/page-flags.h:846
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:is_raw_hwpoison_page_in_hugepage
```
```
In lib/scatterlist.c (ffffffff81853985)
Location: include/linux/page-flags.h:846
Inline: True
```
```
In lib/iov_iter.c (ffffffff818587ee)
Location: include/linux/page-flags.h:846
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In net/core/skbuff.c (ffffffff81ece6d7)
Location: include/linux/page-flags.h:846
Inline: True
Inline callers:
  - net/core/skbuff.c:csum_and_copy_from_iter_full
```
```
In net/core/datagram.c (ffffffff81edda6e)
Location: include/linux/page-flags.h:846
Inline: True
Inline callers:
  - net/core/datagram.c:csum_and_copy_to_iter
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
<b>Regular</b>
<ul>
</ul>
