# Function: <code>xas_error</code>

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
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fe8e9)
Location: include/linux/xarray.h:1221
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff812215c1)
Location: include/linux/xarray.h:1221
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8125bbff)
Location: include/linux/xarray.h:1221
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff8128f90e)
Location: include/linux/xarray.h:1221
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/dax.c (ffffffff8130cd77)
Location: include/linux/xarray.h:1221
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81a089ec)
Location: include/linux/xarray.h:1221
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81a1906d)
Location: include/linux/xarray.h:1221
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_reserve
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff81215be9)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff81230df8)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81276dbe)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812aa9b5)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/dax.c (ffffffff8133541b)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81a783c6)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81a88c94)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff812234e9)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff8123f01b)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8128689a)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812bbf56)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/dax.c (ffffffff81349017)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81aaf686)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81abff34)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff81250b77)
Location: include/linux/xarray.h:1385
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff8126c8d9)
Location: include/linux/xarray.h:1385
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff812b8e33)
Location: include/linux/xarray.h:1385
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812f1478)
Location: include/linux/xarray.h:1385
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/dax.c (ffffffff8138e393)
Location: include/linux/xarray.h:1385
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff815e9522)
Location: include/linux/xarray.h:1385
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff815fc530)
Location: include/linux/xarray.h:1385
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_start
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
In mm/filemap.c (ffffffff8125af13)
Location: include/linux/xarray.h:1387
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff81277320)
Location: include/linux/xarray.h:1387
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff812c45a9)
Location: include/linux/xarray.h:1387
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812fd9cd)
Location: include/linux/xarray.h:1387
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/dax.c (ffffffff8139fae3)
Location: include/linux/xarray.h:1387
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff8160e5d2)
Location: include/linux/xarray.h:1387
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81621150)
Location: include/linux/xarray.h:1387
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_start
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
In mm/filemap.c (ffffffff8125ebdb)
Location: include/linux/xarray.h:1389
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff8127c388)
Location: include/linux/xarray.h:1389
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff812cb22a)
Location: include/linux/xarray.h:1389
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff8130474f)
Location: include/linux/xarray.h:1389
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/dax.c (ffffffff813a711e)
Location: include/linux/xarray.h:1389
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff815f1d1c)
Location: include/linux/xarray.h:1389
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81604b33)
Location: include/linux/xarray.h:1389
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_start
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
In mm/filemap.c (ffffffff8129bffb)
Location: include/linux/xarray.h:1389
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff812ba595)
Location: include/linux/xarray.h:1389
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81310225)
Location: include/linux/xarray.h:1389
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff8134e484)
Location: include/linux/xarray.h:1389
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/dax.c (ffffffff813f6fe1)
Location: include/linux/xarray.h:1389
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff8165ee83)
Location: include/linux/xarray.h:1389
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81673423)
Location: include/linux/xarray.h:1389
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_start
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
In mm/filemap.c (ffffffff812f2472)
Location: include/linux/xarray.h:1392
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff81317aeb)
Location: include/linux/xarray.h:1392
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/list_lru.c (ffffffff813359fa)
Location: include/linux/xarray.h:1392
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
```
```
In mm/swap_state.c (ffffffff8137acd5)
Location: include/linux/xarray.h:1392
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/huge_memory.c (ffffffff813bf6c3)
Location: include/linux/xarray.h:1392
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff813c4b94)
Location: include/linux/xarray.h:1392
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/dax.c (ffffffff814693b8)
Location: include/linux/xarray.h:1392
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81778765)
Location: include/linux/xarray.h:1392
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff8178da5c)
Location: include/linux/xarray.h:1392
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_start
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
In mm/filemap.c (ffffffff8135aa78)
Location: include/linux/xarray.h:1407
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff8138afd0)
Location: include/linux/xarray.h:1407
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/list_lru.c (ffffffff813ac7ba)
Location: include/linux/xarray.h:1407
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
```
```
In mm/swap_state.c (ffffffff813f87fc)
Location: include/linux/xarray.h:1407
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/huge_memory.c (ffffffff81441c1f)
Location: include/linux/xarray.h:1407
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff814493e7)
Location: include/linux/xarray.h:1407
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/dax.c (ffffffff814f9e48)
Location: include/linux/xarray.h:1407
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff82021514)
Location: include/linux/xarray.h:1407
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff8204b0fc)
Location: include/linux/xarray.h:1407
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_start
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
In mm/filemap.c (ffffffff8138c4a4)
Location: include/linux/xarray.h:1407
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff813bd603)
Location: include/linux/xarray.h:1407
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/list_lru.c (ffffffff813e0b5a)
Location: include/linux/xarray.h:1407
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
```
```
In mm/swap_state.c (ffffffff8142b5bb)
Location: include/linux/xarray.h:1407
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/huge_memory.c (ffffffff814775c6)
Location: include/linux/xarray.h:1407
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8147fdc9)
Location: include/linux/xarray.h:1407
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/dax.c (ffffffff815312c5)
Location: include/linux/xarray.h:1407
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff820a1544)
Location: include/linux/xarray.h:1407
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff820c99fc)
Location: include/linux/xarray.h:1407
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_start
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
In mm/filemap.c (ffffffff813b60fe)
Location: include/linux/xarray.h:1425
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff813e86ec)
Location: include/linux/xarray.h:1425
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/list_lru.c (ffffffff8140b42a)
Location: include/linux/xarray.h:1425
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
```
```
In mm/swap_state.c (ffffffff81464d8f)
Location: include/linux/xarray.h:1425
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/huge_memory.c (ffffffff814a6d3b)
Location: include/linux/xarray.h:1425
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff814aded2)
Location: include/linux/xarray.h:1425
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/dax.c (ffffffff815661a5)
Location: include/linux/xarray.h:1425
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff82179535)
Location: include/linux/xarray.h:1425
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff821a437c)
Location: include/linux/xarray.h:1425
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_start
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
In mm/filemap.c (ffff8000102b0e68)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffff8000102d16c0)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffff800010321080)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffff80001035d268)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/dax.c (ffff800010409c18)
Location: include/linux/xarray.h:1350
Inline: True
```
```
In lib/idr.c (ffff800010d88f44)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffff800010d9b8cc)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
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
In mm/filemap.c (c04dd7b8)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (c04f8a98)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (c05399b0)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In lib/idr.c (c0e83e28)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (c0e97ff8)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
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
In mm/filemap.c (c000000000366318)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (c00000000038f118)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (c0000000003f653c)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (c0000000004485e4)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/dax.c (c000000000515a78)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (c000000000ec9b4c)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (c000000000ee1cd8)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffe0001d66ea)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffe0001edb2a)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffe0002224ce)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In fs/dax.c (ffffffe0002b37a8)
Location: include/linux/xarray.h:1350
Inline: True
```
```
In lib/idr.c (ffffffe0008b2cda)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffe0008c3aec)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff8121bb39)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff8123766b)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8127eeea)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812b4536)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/dax.c (ffffffff813415f7)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81a4e4d6)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81a5ed84)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff8120ed29)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff8122a4fb)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81270d1a)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812a55b6)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/dax.c (ffffffff81331fb1)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81a0b5c6)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81a1be54)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff812198d9)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff8123540b)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8127cc8a)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812b2346)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/dax.c (ffffffff8133f0c7)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81aba8c6)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81acb174)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff812289c9)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff8124551b)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8128c85a)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812c274d)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/dax.c (ffffffff81350b5d)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81ac6d16)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81ad77d4)
Location: include/linux/xarray.h:1350
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_erase
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
```
</details>
</li>
</ul>

## Differences
