# Function: <code>xas_load</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *xas_load(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a17170)
Location: lib/xarray.c:225
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_replace_entry
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_lock_page
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_clear_mark
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:__xa_reserve
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81a17170-ffffffff81a171e7: xas_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *xas_load(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a86e00)
Location: lib/xarray.c:230
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_replace_entry
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_lock_page
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_clear_mark
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81a86e00-ffffffff81a86e78: xas_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *xas_load(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abe070)
Location: lib/xarray.c:231
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_replace_entry
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_lock_page
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_clear_mark
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81abe070-ffffffff81abe0e8: xas_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *xas_load(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fa8b0)
Location: lib/xarray.c:231
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_delete_from_page_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_lock_page
  - lib/idr.c:ida_free
  - lib/xarray.c:xa_clear_mark
  - lib/xarray.c:xa_set_mark
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff815fa8b0-ffffffff815fa924: xas_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *xas_load(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8161f0b0)
Location: lib/xarray.c:231
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_entry
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_delete_from_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_lock_page
  - lib/idr.c:ida_free
  - lib/xarray.c:xa_clear_mark
  - lib/xarray.c:xa_set_mark
  - lib/xarray.c:xa_get_order
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff8161f0b0-ffffffff8161f124: xas_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *xas_load(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81602700)
Location: lib/xarray.c:231
Inline: False
Direct callers:
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:pagecache_get_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_lock_page
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/idr.c:ida_free
  - lib/xarray.c:xa_clear_mark
  - lib/xarray.c:xa_set_mark
  - lib/xarray.c:xa_get_order
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81602700-ffffffff81602774: xas_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *xas_load(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:231
Inline: False
Direct callers:
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:pagecache_get_page
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_lock_page
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/idr.c:ida_free
  - lib/xarray.c:xa_clear_mark
  - lib/xarray.c:xa_set_mark
  - lib/xarray.c:xa_get_order
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81cdfe9b-ffffffff81cdfeb9: xas_load.cold (STB_LOCAL)
ffffffff81670a40-ffffffff81670afe: xas_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *xas_load(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178c8af)
Location: lib/xarray.c:233
Inline: True
Inline callers:
  - lib/xarray.c:xa_load
Direct callers:
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:__filemap_get_folio
  - mm/page-writeback.c:__folio_start_writeback
  - mm/truncate.c:clear_shadow_entry
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/swap_state.c:add_to_swap_cache
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_lock_page
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_clear_mark
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:xa_get_order
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff8178a7d0-ffffffff8178a825: xas_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *xas_load(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff82049f6f)
Location: lib/xarray.c:233
Inline: True
Inline callers:
  - lib/xarray.c:xa_load
Direct callers:
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:__filemap_get_folio
  - mm/page-writeback.c:__folio_start_writeback
  - mm/truncate.c:clear_shadow_entry
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_writepage
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/swap_state.c:add_to_swap_cache
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_page
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_clear_mark
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:xa_get_order
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff82047d00-ffffffff82047d55: xas_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *xas_load(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c880f)
Location: lib/xarray.c:235
Inline: True
Inline callers:
  - lib/xarray.c:xa_load
Direct callers:
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_entry
  - mm/page-writeback.c:__folio_start_writeback
  - mm/truncate.c:clear_shadow_entry
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_writepage
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/swap_state.c:add_to_swap_cache
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_page
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_clear_mark
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:xa_get_order
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff820c64a0-ffffffff820c64f5: xas_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *xas_load(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a318f)
Location: lib/xarray.c:235
Inline: True
Inline callers:
  - lib/xarray.c:xa_load
Direct callers:
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_entry
  - mm/page-writeback.c:__folio_start_writeback
  - mm/truncate.c:clear_shadow_entry
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_writepage
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/swap_state.c:add_to_swap_cache
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_folio
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_clear_mark
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:xa_get_order
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff821a0e20-ffffffff821a0e75: xas_load (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *xas_load(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d992d0)
Location: lib/xarray.c:231
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_replace_entry
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/dax.c:dax_lock_page
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_clear_mark
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffff800010d992d0-ffff800010d9935c: xas_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *xas_load(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e95d68)
Location: lib/xarray.c:231
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/truncate.c:clear_shadow_entry
  - mm/shmem.c:shmem_replace_entry
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_clear_mark
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
```
**Symbols:**

```
c0e95d68-c0e95ddc: xas_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *xas_load(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000edeff0)
Location: lib/xarray.c:231
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_replace_entry
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/dax.c:dax_lock_page
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_clear_mark
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
```
**Symbols:**

```
c000000000edeff0-c000000000edf0c0: xas_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *xas_load(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c231e)
Location: lib/xarray.c:231
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_replace_entry
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - fs/dax.c:dax_lock_page
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_clear_mark
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffe0008c231e-ffffffe0008c2388: xas_load (STB_GLOBAL)
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
void *xas_load(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5cec0)
Location: lib/xarray.c:231
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_replace_entry
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_lock_page
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_clear_mark
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81a5cec0-ffffffff81a5cf38: xas_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *xas_load(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a19f90)
Location: lib/xarray.c:231
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_replace_entry
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_lock_page
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_clear_mark
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81a19f90-ffffffff81a1a008: xas_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *xas_load(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac92b0)
Location: lib/xarray.c:231
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_replace_entry
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_lock_page
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_clear_mark
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81ac92b0-ffffffff81ac9328: xas_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *xas_load(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad5780)
Location: lib/xarray.c:231
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_replace_entry
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_lock_page
  - lib/idr.c:ida_free
  - lib/xarray.c:__xa_clear_mark
  - lib/xarray.c:__xa_set_mark
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81ad5780-ffffffff81ad57f8: xas_load (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
