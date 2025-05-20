# Function: <code>xas_store</code>

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
void *xas_store(struct xa_state *xas, void *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a18540)
Location: lib/xarray.c:751
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_replace_entry
  - mm/workingset.c:shadow_lru_isolate
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_entry
  - fs/dax.c:dax_unlock_entry
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_reserve
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
```
**Symbols:**

```
ffffffff81a18540-ffffffff81a18a7c: xas_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *xas_store(struct xa_state *xas, void *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a88160)
Location: lib/xarray.c:768
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_replace_entry
  - mm/workingset.c:shadow_lru_isolate
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_entry
  - fs/dax.c:dax_unlock_entry
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
```
**Symbols:**

```
ffffffff81a88160-ffffffff81a8878f: xas_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *xas_store(struct xa_state *xas, void *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abf400)
Location: lib/xarray.c:769
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_replace_entry
  - mm/workingset.c:shadow_lru_isolate
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
```
**Symbols:**

```
ffffffff81abf400-ffffffff81abfa2f: xas_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *xas_store(struct xa_state *xas, void *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fb8e0)
Location: lib/xarray.c:769
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:page_cache_delete
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_delete_from_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/workingset.c:shadow_lru_isolate
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:xa_erase
```
**Symbols:**

```
ffffffff815fb8e0-ffffffff815fbd1b: xas_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *xas_store(struct xa_state *xas, void *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81620470)
Location: lib/xarray.c:772
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:page_cache_delete
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_delete_from_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_delete_node
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:xa_erase
```
**Symbols:**

```
ffffffff81620470-ffffffff816208bf: xas_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *xas_store(struct xa_state *xas, void *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81603a90)
Location: lib/xarray.c:772
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_delete_node
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:xa_erase
```
**Symbols:**

```
ffffffff81603a90-ffffffff81604098: xas_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *xas_store(struct xa_state *xas, void *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff816721f0)
Location: lib/xarray.c:772
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_delete_node
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:xa_erase
```
**Symbols:**

```
ffffffff816721f0-ffffffff81672910: xas_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *xas_store(struct xa_state *xas, void *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178c950)
Location: lib/xarray.c:777
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
  - mm/truncate.c:clear_shadow_entry
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_destroy_list_lru
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_delete_node
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
```
**Symbols:**

```
ffffffff8178c950-ffffffff8178d0d2: xas_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *xas_store(struct xa_state *xas, void *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8204a020)
Location: lib/xarray.c:777
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
  - mm/truncate.c:clear_shadow_entry
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_destroy_list_lru
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_delete_node
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
```
**Symbols:**

```
ffffffff8204a020-ffffffff8204a6ed: xas_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *xas_store(struct xa_state *xas, void *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c88c0)
Location: lib/xarray.c:775
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
  - mm/truncate.c:clear_shadow_entry
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_destroy_list_lru
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_delete_node
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
```
**Symbols:**

```
ffffffff820c88c0-ffffffff820c8fef: xas_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *xas_store(struct xa_state *xas, void *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a3240)
Location: lib/xarray.c:775
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
  - mm/truncate.c:clear_shadow_entry
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_destroy_list_lru
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_folio
  - fs/dax.c:dax_unlock_entry
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_delete_node
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
```
**Symbols:**

```
ffffffff821a3240-ffffffff821a396f: xas_store (STB_GLOBAL)
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
void *xas_store(struct xa_state *xas, void *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d9a660)
Location: lib/xarray.c:769
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_replace_entry
  - mm/workingset.c:shadow_lru_isolate
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
```
**Symbols:**

```
ffff800010d9a660-ffff800010d9ab88: xas_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *xas_store(struct xa_state *xas, void *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e97394)
Location: lib/xarray.c:769
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:clear_shadow_entry
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_replace_entry
  - mm/workingset.c:shadow_lru_isolate
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
```
**Symbols:**

```
c0e97394-c0e97978: xas_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *xas_store(struct xa_state *xas, void *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000ee0cd0)
Location: lib/xarray.c:769
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_replace_entry
  - mm/workingset.c:shadow_lru_isolate
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_entry
  - fs/dax.c:dax_unlock_entry
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
```
**Symbols:**

```
c000000000ee0cd0-c000000000ee144c: xas_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *xas_store(struct xa_state *xas, void *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c2c64)
Location: lib/xarray.c:769
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_replace_entry
  - mm/workingset.c:shadow_lru_isolate
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_lock_page
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
```
**Symbols:**

```
ffffffe0008c2c64-ffffffe0008c30e6: xas_store (STB_GLOBAL)
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
void *xas_store(struct xa_state *xas, void *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5e250)
Location: lib/xarray.c:769
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_replace_entry
  - mm/workingset.c:shadow_lru_isolate
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
```
**Symbols:**

```
ffffffff81a5e250-ffffffff81a5e87f: xas_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *xas_store(struct xa_state *xas, void *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1b320)
Location: lib/xarray.c:769
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_replace_entry
  - mm/workingset.c:shadow_lru_isolate
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
```
**Symbols:**

```
ffffffff81a1b320-ffffffff81a1b94f: xas_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *xas_store(struct xa_state *xas, void *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81aca640)
Location: lib/xarray.c:769
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_replace_entry
  - mm/workingset.c:shadow_lru_isolate
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
```
**Symbols:**

```
ffffffff81aca640-ffffffff81acac6f: xas_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *xas_store(struct xa_state *xas, void *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad6c10)
Location: lib/xarray.c:769
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_replace_entry
  - mm/workingset.c:shadow_lru_isolate
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
```
**Symbols:**

```
ffffffff81ad6c10-ffffffff81ad723f: xas_store (STB_GLOBAL)
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
