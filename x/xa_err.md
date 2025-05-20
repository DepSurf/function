# Function: <code>xa_err</code>

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
In kernel/memremap.c (ffffffff811fa4cd)
Location: include/linux/xarray.h:195
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/filemap.c (ffffffff811fe8e9)
Location: include/linux/xarray.h:195
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff812215c1)
Location: include/linux/xarray.h:195
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8125bbff)
Location: include/linux/xarray.h:195
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff8128f90e)
Location: include/linux/xarray.h:195
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/dax.c (ffffffff8130cd77)
Location: include/linux/xarray.h:195
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81a089ec)
Location: include/linux/xarray.h:195
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81a1906d)
Location: include/linux/xarray.h:195
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
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff81230df8)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81276dbe)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812aa9b5)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memremap.c (ffffffff812c2b25)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In fs/dax.c (ffffffff8133541b)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81a783c6)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81a88c94)
Location: include/linux/xarray.h:217
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
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff8123f01b)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8128689a)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812bbf56)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff812d49e2)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/dax.c (ffffffff81349017)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81aaf686)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81abff34)
Location: include/linux/xarray.h:217
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
In mm/filemap.c (ffffffff81250b7b)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff8126c8dd)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff812b8e37)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812f147c)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff8130a50e)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/dax.c (ffffffff8138e397)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff815e9526)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff815fc534)
Location: include/linux/xarray.h:217
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
```
In drivers/base/memory.c (ffffffff817d9167)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - drivers/base/memory.c:init_memory_block
```
```
In net/core/devlink.c (ffffffff81a587c7)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:__devlink_snapshot_id_increment
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
In mm/filemap.c (ffffffff8125af17)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff81277324)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff812c45ad)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812fd9d1)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff81315ed3)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/io_uring.c (ffffffff8138a97c)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_add_task_file
```
```
In fs/dax.c (ffffffff8139fae7)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff8160e5d6)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81621154)
Location: include/linux/xarray.h:217
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
```
In drivers/base/memory.c (ffffffff817ed710)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - drivers/base/memory.c:init_memory_block
```
```
In net/core/devlink.c (ffffffff81a607ac)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:__devlink_snapshot_id_increment
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
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81069933)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In mm/filemap.c (ffffffff8125ebdf)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff8127c38c)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff812cb22e)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff81304753)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff8131c0d6)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/io_uring.c (ffffffff8139265a)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_add_task_file
```
```
In fs/dax.c (ffffffff813a7122)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In block/bio.c (ffffffff815635ab)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
```
In lib/idr.c (ffffffff815f1d20)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81604b37)
Location: include/linux/xarray.h:217
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
```
In drivers/base/memory.c (ffffffff817d1faa)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - drivers/base/memory.c:init_memory_block
```
```
In net/core/devlink.c (ffffffff81a427fe)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:__devlink_region_snapshot_create
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
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81074013)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In mm/filemap.c (ffffffff8129bfff)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff812ba599)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81310229)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff8134e488)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff813693c2)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/io_uring.c (ffffffff813e06a1)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_add_tctx_node
```
```
In fs/dax.c (ffffffff813f6fe5)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In block/bio.c (ffffffff815c7f1e)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
```
In lib/idr.c (ffffffff8165ee87)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81673427)
Location: include/linux/xarray.h:217
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
```
In drivers/base/memory.c (ffffffff8185d0bf)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - drivers/base/memory.c:init_memory_block
```
```
In drivers/vfio/vfio.c (ffffffff81922b8f)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_assign_device_set
```
```
In net/core/devlink.c (ffffffff81afae9e)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:__devlink_region_snapshot_create
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
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81082564)
Location: include/linux/xarray.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In mm/filemap.c (ffffffff812f2476)
Location: include/linux/xarray.h:218
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff81317aef)
Location: include/linux/xarray.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/list_lru.c (ffffffff813359fa)
Location: include/linux/xarray.h:218
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
```
```
In mm/swap_state.c (ffffffff8137acd9)
Location: include/linux/xarray.h:218
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/huge_memory.c (ffffffff813bf6c7)
Location: include/linux/xarray.h:218
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff813c4b98)
Location: include/linux/xarray.h:218
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff813e7542)
Location: include/linux/xarray.h:218
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/dax.c (ffffffff814693bc)
Location: include/linux/xarray.h:218
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In block/bio.c (ffffffff81672c47)
Location: include/linux/xarray.h:218
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
```
In io_uring/io_uring.c (ffffffff816ce2aa)
Location: include/linux/xarray.h:218
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_register_pbuf_ring
  - io_uring/io_uring.c:io_register_pbuf_ring
  - io_uring/io_uring.c:__io_uring_add_tctx_node
  - io_uring/io_uring.c:__io_uring_add_tctx_node
  - io_uring/io_uring.c:io_provide_buffers
  - io_uring/io_uring.c:io_provide_buffers
```
```
In lib/idr.c (ffffffff81778769)
Location: include/linux/xarray.h:218
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff8178da60)
Location: include/linux/xarray.h:218
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
```
In drivers/xen/grant-dma-ops.c (0)
Location: include/linux/xarray.h:218
Inline: True
```
```
In drivers/base/memory.c (ffffffff819a4354)
Location: include/linux/xarray.h:218
Inline: True
Inline callers:
  - drivers/base/memory.c:add_memory_block
```
```
In drivers/vfio/vfio.c (ffffffff81a774a3)
Location: include/linux/xarray.h:218
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_assign_device_set
```
```
In net/core/devlink.c (ffffffff81c7fa0c)
Location: include/linux/xarray.h:218
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:__devlink_region_snapshot_create
  - net/core/devlink.c:__devlink_region_snapshot_create
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
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81094fe1)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In mm/filemap.c (ffffffff8135aa7c)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff8138afd4)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/list_lru.c (ffffffff813ac7ba)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
```
```
In mm/swap_state.c (ffffffff813f8800)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/huge_memory.c (ffffffff81441c23)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff814493eb)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff8146f1c2)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/dax.c (ffffffff814f9e4c)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In block/bio.c (ffffffff8172e707)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
```
In io_uring/tctx.c (ffffffff8179bd36)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - io_uring/tctx.c:__io_uring_add_tctx_node
```
```
In io_uring/kbuf.c (ffffffff8179fd3d)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/kbuf.c:io_provide_buffers
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81a35591)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac1f63)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
```
```
In drivers/iommu/iommu.c (ffffffff81acf380)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
```
```
In drivers/base/memory.c (ffffffff81b16374)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - drivers/base/memory.c:add_memory_block
```
```
In net/core/devlink.c (ffffffff81e38a9d)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:devlink_nl_cmd_region_new
  - net/core/devlink.c:__devlink_region_snapshot_create
  - net/core/devlink.c:__devlink_region_snapshot_create
```
```
In lib/idr.c (ffffffff82021518)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/maple_tree.c (ffffffff82038eb0)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mas_expected_entries
  - lib/maple_tree.c:mas_expected_entries
  - lib/maple_tree.c:mas_preallocate
  - lib/maple_tree.c:mas_preallocate
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
```
```
In lib/xarray.c (ffffffff8204b100)
Location: include/linux/xarray.h:219
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
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81097f64)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In mm/filemap.c (ffffffff8138c4a8)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff813bd607)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/list_lru.c (ffffffff813e0b5a)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
```
```
In mm/swap_state.c (ffffffff8142b5bf)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/huge_memory.c (ffffffff814775ca)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8147fdcd)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff814a39a7)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/dax.c (ffffffff815312c9)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In block/bio.c (ffffffff8176a9d7)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
```
In io_uring/tctx.c (ffffffff817dce66)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - io_uring/tctx.c:__io_uring_add_tctx_node
```
```
In io_uring/kbuf.c (ffffffff817e0e96)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/kbuf.c:io_provide_buffers
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81a7efb3)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0ebfc)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
```
```
In drivers/iommu/iommu.c (ffffffff81b1e010)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
```
```
In drivers/base/memory.c (ffffffff81b650e4)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - drivers/base/memory.c:add_memory_block
```
```
In net/devlink/leftover.c (ffffffff82039bed)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_region_new
  - net/devlink/leftover.c:devlink_nl_cmd_region_new
  - net/devlink/leftover.c:__devlink_region_snapshot_create
  - net/devlink/leftover.c:__devlink_region_snapshot_create
```
```
In lib/idr.c (ffffffff820a1548)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/maple_tree.c (ffffffff820b7229)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mas_expected_entries
  - lib/maple_tree.c:mas_expected_entries
  - lib/maple_tree.c:mas_preallocate
  - lib/maple_tree.c:mas_preallocate
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
```
```
In lib/xarray.c (ffffffff820c9a00)
Location: include/linux/xarray.h:219
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
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f504)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In mm/filemap.c (ffffffff813b6102)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff813e86f0)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/list_lru.c (ffffffff8140b42a)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
```
```
In mm/swap_state.c (ffffffff81464d93)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/huge_memory.c (ffffffff814a6d3f)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff814aded6)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff814d4842)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/dax.c (ffffffff815661a9)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In block/bio.c (ffffffff817ace66)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
```
In io_uring/tctx.c (ffffffff818211b5)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - io_uring/tctx.c:__io_uring_add_tctx_node
```
```
In io_uring/kbuf.c (ffffffff818254d2)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/kbuf.c:io_provide_buffers
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81ad1523)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b665aa)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
```
```
In drivers/iommu/iommu.c (ffffffff81b73fbd)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
```
```
In drivers/base/memory.c (ffffffff81bb8e73)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - drivers/base/memory.c:add_memory_block
```
```
In net/netlink/genetlink.c (ffffffff81f8fe1a)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_sk_priv_get
```
```
In net/devlink/region.c (ffffffff82110cd9)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_new_doit
  - net/devlink/region.c:devlink_nl_region_new_doit
  - net/devlink/region.c:__devlink_region_snapshot_create
  - net/devlink/region.c:__devlink_region_snapshot_create
```
```
In lib/idr.c (ffffffff82179539)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/maple_tree.c (ffffffff82188934)
Location: include/linux/xarray.h:219
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_dup
  - lib/maple_tree.c:mtree_dup
  - lib/maple_tree.c:__mt_dup
  - lib/maple_tree.c:__mt_dup
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mas_expected_entries
  - lib/maple_tree.c:mas_expected_entries
  - lib/maple_tree.c:mas_preallocate
  - lib/maple_tree.c:mas_preallocate
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
```
```
In lib/xarray.c (ffffffff821a4380)
Location: include/linux/xarray.h:219
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
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffff8000102d16c0)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffff800010321080)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffff80001035d268)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/dax.c (ffff800010409c18)
Location: include/linux/xarray.h:217
Inline: True
```
```
In lib/idr.c (ffff800010d88f44)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffff800010d9b8cc)
Location: include/linux/xarray.h:217
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
In mm/filemap.c (c04dd7bc)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (c04f8a9c)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (c05399b4)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In lib/idr.c (c0e83e2c)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (c0e97ffc)
Location: include/linux/xarray.h:217
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
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (c00000000038f118)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (c0000000003f653c)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (c0000000004485e4)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (c00000000046e30c)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/dax.c (c000000000515a78)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (c000000000ec9b4c)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (c000000000ee1cd8)
Location: include/linux/xarray.h:217
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
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffe0001edb2a)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffe0002224ce)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In fs/dax.c (ffffffe0002b37a8)
Location: include/linux/xarray.h:217
Inline: True
```
```
In lib/idr.c (ffffffe0008b2cda)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffe0008c3aec)
Location: include/linux/xarray.h:217
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
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff8123766b)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8127eeea)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812b4536)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff812ccfc2)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/dax.c (ffffffff813415f7)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81a4e4d6)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81a5ed84)
Location: include/linux/xarray.h:217
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
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff8122a4fb)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff81270d1a)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812a55b6)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff812bde32)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/dax.c (ffffffff81331fb1)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81a0b5c6)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81a1be54)
Location: include/linux/xarray.h:217
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
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff8123540b)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8127cc8a)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812b2346)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff812cadd2)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/dax.c (ffffffff8133f0c7)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81aba8c6)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81acb174)
Location: include/linux/xarray.h:217
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
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff8124551b)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8128c85a)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff812c274d)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memremap.c (ffffffff812dbb10)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/dax.c (ffffffff81350b5d)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In lib/idr.c (ffffffff81ac6d16)
Location: include/linux/xarray.h:217
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81ad77d4)
Location: include/linux/xarray.h:217
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
