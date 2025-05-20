# Function: <code>folio_address</code>

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
In mm/slub.c (ffffffff813a5377)
Location: include/linux/mm.h:1764
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:free_partial
  - mm/slub.c:deactivate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:slab_pad_check
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:print_trailer
  - mm/slub.c:__fill_map
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff813d34e0)
Location: include/linux/mm.h:1764
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In mm/usercopy.c (ffffffff813e6ca4)
Location: include/linux/mm.h:1764
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In drivers/scsi/scsicam.c (ffffffff819fa8e4)
Location: include/linux/mm.h:1764
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
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
In mm/shmem.c (ffffffff8138d9f5)
Location: include/linux/mm.h:1897
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
```
```
In mm/slab_common.c (ffffffff813a24b1)
Location: include/linux/mm.h:1897
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
```
```
In mm/slub.c (ffffffff814264b5)
Location: include/linux/mm.h:1897
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:free_partial
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_slab
  - mm/slub.c:free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:shuffle_freelist
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:slab_pad_check
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:print_trailer
  - mm/slub.c:__fill_map
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff81458ec3)
Location: include/linux/mm.h:1897
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In mm/usercopy.c (ffffffff8146e87b)
Location: include/linux/mm.h:1897
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In block/partitions/core.c (ffffffff81755229)
Location: include/linux/mm.h:1897
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In drivers/scsi/scsicam.c (ffffffff81b788e4)
Location: include/linux/mm.h:1897
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
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
In mm/shmem.c (ffffffff813c1b85)
Location: include/linux/mm.h:2168
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
```
```
In mm/slab_common.c (ffffffff813d5999)
Location: include/linux/mm.h:2168
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
```
```
In mm/slub.c (ffffffff8145b525)
Location: include/linux/mm.h:2168
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:free_partial
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_slab
  - mm/slub.c:free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:shuffle_freelist
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:slab_pad_check
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:print_trailer
  - mm/slub.c:__fill_map
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8148eb53)
Location: include/linux/mm.h:2168
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In mm/usercopy.c (ffffffff814a3013)
Location: include/linux/mm.h:2168
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In fs/buffer.c (ffffffff81509da9)
Location: include/linux/mm.h:2168
Inline: True
Inline callers:
  - fs/buffer.c:folio_alloc_buffers
```
```
In block/partitions/core.c (ffffffff81791507)
Location: include/linux/mm.h:2168
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In drivers/scsi/scsicam.c (ffffffff81bcc571)
Location: include/linux/mm.h:2168
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
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
In mm/shmem.c (ffffffff813ec902)
Location: include/linux/mm.h:2223
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
```
```
In mm/slab_common.c (ffffffff813ff64c)
Location: include/linux/mm.h:2223
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
```
```
In mm/memory.c (ffffffff8141c98a)
Location: include/linux/mm.h:2223
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/slub.c (ffffffff81456705)
Location: include/linux/mm.h:2223
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:free_partial
  - mm/slub.c:__kmalloc_large_node
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_slab
  - mm/slub.c:free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:shuffle_freelist
  - mm/slub.c:__memcg_slab_free_hook
  - mm/slub.c:__memcg_slab_post_alloc_hook
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:slab_pad_check
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:print_trailer
  - mm/slub.c:__fill_map
```
```
In mm/hugetlb_vmemmap.c (ffffffff81480aa4)
Location: include/linux/mm.h:2223
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
```
```
In mm/memcontrol.c (ffffffff814be503)
Location: include/linux/mm.h:2223
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In mm/usercopy.c (ffffffff814d3ea4)
Location: include/linux/mm.h:2223
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In fs/buffer.c (ffffffff8153ec07)
Location: include/linux/mm.h:2223
Inline: True
Inline callers:
  - fs/buffer.c:folio_alloc_buffers
```
```
In block/partitions/core.c (ffffffff817d4e09)
Location: include/linux/mm.h:2223
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In drivers/scsi/scsicam.c (ffffffff81c211a1)
Location: include/linux/mm.h:2223
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
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
