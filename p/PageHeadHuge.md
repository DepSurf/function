# Function: <code>PageHeadHuge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811dc5c0)
Location: mm/hugetlb.c:1311
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
Direct callers:
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pmd
  - mm/swap.c:__get_page_tail
  - mm/swap.c:__get_page_tail
  - mm/swap.c:__get_page_tail
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_mapped_in_vma
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:rmap_walk
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff811dc5c0-ffffffff811dc5ec: PageHeadHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811fa820)
Location: mm/hugetlb.c:1338
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_mapped_in_vma
  - mm/rmap.c:page_address_in_vma
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff811fa820-ffffffff811fa84f: PageHeadHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120b250)
Location: mm/hugetlb.c:1338
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_mapped_in_vma
  - mm/rmap.c:page_address_in_vma
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff8120b250-ffffffff8120b27f: PageHeadHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812167b0)
Location: mm/hugetlb.c:1356
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
**Symbols:**

```
ffffffff812167b0-ffffffff812167dc: PageHeadHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81231460)
Location: mm/hugetlb.c:1362
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
**Symbols:**

```
ffffffff81231460-ffffffff8123148c: PageHeadHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81254360)
Location: mm/hugetlb.c:1350
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff81254360-ffffffff8125438d: PageHeadHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81268740)
Location: mm/hugetlb.c:1351
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff81268740-ffffffff8126876e: PageHeadHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81283820)
Location: mm/hugetlb.c:1382
Inline: False
Direct callers:
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
**Symbols:**

```
ffffffff81283820-ffffffff8128384e: PageHeadHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812933c0)
Location: mm/hugetlb.c:1430
Inline: False
Direct callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
**Symbols:**

```
ffffffff812933c0-ffffffff812933ee: PageHeadHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c4082)
Location: mm/hugetlb.c:1575
Inline: True
Direct callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
**Symbols:**

```
ffffffff812c67e0-ffffffff812c6801: PageHeadHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d6f3e)
Location: mm/hugetlb.c:1603
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:isolate_huge_page
Direct callers:
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
**Symbols:**

```
ffffffff812d23e0-ffffffff812d2401: PageHeadHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812de551)
Location: mm/hugetlb.c:1561
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_huge_page
  - mm/hugetlb.c:isolate_huge_page
```
**Symbols:**

```
ffffffff812d8e90-ffffffff812d8eb1: PageHeadHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81325841)
Location: mm/hugetlb.c:1752
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_huge_page
  - mm/hugetlb.c:isolate_huge_page
```
**Symbols:**

```
ffffffff8131f890-ffffffff8131f8b1: PageHeadHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81387360)
Location: mm/hugetlb.c:1863
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
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
  - mm/folio-compat.c:pagecache_get_page
  - mm/util.c:folio_mapcount
  - mm/util.c:folio_mapcount
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
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
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:folio_referenced_one
  - mm/hugetlb.c:get_hwpoison_huge_page
  - mm/hugetlb.c:isolate_hugetlb
  - mm/mempolicy.c:new_page
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/verity/enable.c:read_file_data_page
  - fs/iomap/buffered-io.c:iomap_write_iter
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
**Symbols:**

```
ffffffff81387360-ffffffff813873bb: PageHeadHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81405420)
Location: mm/hugetlb.c:2059
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:filemap_map_pages
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
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:unuse_pte
  - mm/hugetlb.c:get_hwpoison_huge_page
  - mm/hugetlb.c:isolate_hugetlb
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/mempolicy.c:new_page
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/userfaultfd.c:mcopy_continue
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/iomap/buffered-io.c:iomap_write_iter
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
**Symbols:**

```
ffffffff81405420-ffffffff8140547a: PageHeadHuge (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff8000103313b8)
Location: mm/hugetlb.c:1430
Inline: False
Direct callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
**Symbols:**

```
ffff8000103313b8-ffff80001033140c: PageHeadHuge (STB_GLOBAL)
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
In mm/debug.c (0)
Location: include/linux/page-flags.h:578
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/page-flags.h:578
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/page-flags.h:578
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c00000000040a110)
Location: mm/hugetlb.c:1430
Inline: False
Direct callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
c00000000040a110-c00000000040a15c: PageHeadHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022e4ca)
Location: mm/hugetlb.c:1430
Inline: False
Direct callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
**Symbols:**

```
ffffffe00022e4ca-ffffffe00022e516: PageHeadHuge (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128b9a0)
Location: mm/hugetlb.c:1430
Inline: False
Direct callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
**Symbols:**

```
ffffffff8128b9a0-ffffffff8128b9ce: PageHeadHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127d7d0)
Location: mm/hugetlb.c:1430
Inline: False
Direct callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff8127d7d0-ffffffff8127d7fe: PageHeadHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812897b0)
Location: mm/hugetlb.c:1430
Inline: False
Direct callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
**Symbols:**

```
ffffffff812897b0-ffffffff812897de: PageHeadHuge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int PageHeadHuge(struct page *page_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81299590)
Location: mm/hugetlb.c:1430
Inline: False
Direct callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
**Symbols:**

```
ffffffff81299590-ffffffff812995be: PageHeadHuge (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
