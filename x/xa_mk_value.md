# Function: <code>xa_mk_value</code>

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
In mm/shmem.c (ffffffff81223529)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
```
```
In mm/workingset.c (ffffffff81238e13)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/dax.c (ffffffff8130d1a0)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_entry
```
```
In lib/idr.c (ffffffff81a08852)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
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
In mm/shmem.c (ffffffff8123323c)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/workingset.c (ffffffff8124a01a)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/dax.c (ffffffff81334526)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_entry
```
```
In lib/idr.c (ffffffff81a78200)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
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
In mm/shmem.c (ffffffff81241754)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_confirm_swap
```
```
In mm/workingset.c (ffffffff81258462)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/dax.c (ffffffff81348d3b)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (ffffffff81aaf4c0)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
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
In mm/shmem.c (ffffffff8126dd10)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/workingset.c (ffffffff81286b21)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/dax.c (ffffffff8138efb1)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (ffffffff815e93da)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In net/core/devlink.c (ffffffff81a51357)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_snapshot_id_decrement
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
In mm/shmem.c (ffffffff81279a0e)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/workingset.c (ffffffff81290d88)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/dax.c (ffffffff813a066d)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (ffffffff8160e48a)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In net/core/devlink.c (ffffffff81a57467)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_snapshot_id_decrement
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
In mm/shmem.c (ffffffff8127eb68)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/workingset.c (ffffffff812963e6)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/dax.c (ffffffff813a6dad)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (ffffffff815f1bda)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In net/core/devlink.c (ffffffff81a42222)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_region_snapshot_create
  - net/core/devlink.c:__devlink_snapshot_id_decrement
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
In mm/shmem.c (ffffffff812bc6ea)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/workingset.c (ffffffff812d6b83)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/dax.c (ffffffff813f6c6e)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (ffffffff8165ed5a)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In net/core/devlink.c (ffffffff81afa8e2)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_region_snapshot_create
  - net/core/devlink.c:__devlink_snapshot_id_decrement
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
In mm/shmem.c (ffffffff813186bd)
Location: include/linux/xarray.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_writepage
```
```
In mm/workingset.c (ffffffff813362a2)
Location: include/linux/xarray.h:53
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/dax.c (ffffffff81469851)
Location: include/linux/xarray.h:53
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (ffffffff817785a1)
Location: include/linux/xarray.h:53
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In net/core/devlink.c (ffffffff81c7f412)
Location: include/linux/xarray.h:53
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_region_snapshot_create
  - net/core/devlink.c:__devlink_snapshot_id_decrement
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
In mm/shmem.c (ffffffff8138c5c6)
Location: include/linux/xarray.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_writepage
```
```
In mm/workingset.c (ffffffff813ad534)
Location: include/linux/xarray.h:54
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:lru_gen_eviction
```
```
In fs/dax.c (ffffffff814fa61e)
Location: include/linux/xarray.h:54
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In drivers/pci/p2pdma.c (ffffffff8191ca52)
Location: include/linux/xarray.h:54
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
```
```
In drivers/pci/doe.c (ffffffff8191f9c8)
Location: include/linux/xarray.h:54
Inline: True
Inline callers:
  - drivers/pci/doe.c:pci_doe_supports_prot
  - drivers/pci/doe.c:pcim_doe_create_mb
```
```
In net/core/devlink.c (ffffffff81e382da)
Location: include/linux/xarray.h:54
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_region_snapshot_create
  - net/core/devlink.c:__devlink_snapshot_id_decrement
```
```
In lib/idr.c (ffffffff82021345)
Location: include/linux/xarray.h:54
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
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
In mm/shmem.c (ffffffff813bebf9)
Location: include/linux/xarray.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_writepage
```
```
In mm/workingset.c (ffffffff813e1941)
Location: include/linux/xarray.h:54
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:lru_gen_eviction
```
```
In fs/dax.c (ffffffff81531a88)
Location: include/linux/xarray.h:54
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In drivers/pci/p2pdma.c (ffffffff81960010)
Location: include/linux/xarray.h:54
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
```
```
In drivers/pci/doe.c (ffffffff819630a8)
Location: include/linux/xarray.h:54
Inline: True
Inline callers:
  - drivers/pci/doe.c:pci_doe_supports_prot
  - drivers/pci/doe.c:pci_doe_create_mb
```
```
In net/devlink/leftover.c (ffffffff820391fa)
Location: include/linux/xarray.h:54
Inline: True
Inline callers:
  - net/devlink/leftover.c:__devlink_region_snapshot_create
  - net/devlink/leftover.c:__devlink_snapshot_id_decrement
```
```
In lib/idr.c (ffffffff820a1375)
Location: include/linux/xarray.h:54
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
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
In mm/shmem.c (ffffffff813e9c34)
Location: include/linux/xarray.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_writepage
```
```
In mm/workingset.c (ffffffff8140c07e)
Location: include/linux/xarray.h:54
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:lru_gen_eviction
```
```
In fs/dax.c (ffffffff8156696c)
Location: include/linux/xarray.h:54
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_folio
```
```
In drivers/pci/p2pdma.c (ffffffff819a96f5)
Location: include/linux/xarray.h:54
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
```
```
In drivers/pci/doe.c (ffffffff819ac728)
Location: include/linux/xarray.h:54
Inline: True
Inline callers:
  - drivers/pci/doe.c:pci_doe_supports_prot
  - drivers/pci/doe.c:pci_doe_create_mb
```
```
In net/devlink/dev.c (0)
Location: include/linux/xarray.h:54
Inline: True
```
```
In net/devlink/region.c (ffffffff8210ff99)
Location: include/linux/xarray.h:54
Inline: True
Inline callers:
  - net/devlink/region.c:__devlink_region_snapshot_create
  - net/devlink/region.c:__devlink_snapshot_id_decrement
```
```
In lib/idr.c (ffffffff821793e8)
Location: include/linux/xarray.h:54
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
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
In mm/shmem.c (ffff8000102d3c00)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_confirm_swap
```
```
In mm/workingset.c (ffff8000102f024c)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/dax.c (ffff8000104091e8)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (ffff800010d89328)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
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
In mm/shmem.c (c04fbb00)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/workingset.c (c051396c)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In lib/idr.c (c0e83c70)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
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
In mm/shmem.c (c000000000392974)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/workingset.c (c0000000003b4bfc)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/dax.c (c000000000515a68)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_entry
```
```
In lib/idr.c (c000000000ec99c0)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
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
In mm/shmem.c (ffffffe0001efbae)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_confirm_swap
```
```
In mm/workingset.c (ffffffe000203c4a)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/dax.c (ffffffe0002b3504)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (ffffffe0008b2b88)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
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
In mm/shmem.c (ffffffff81239da4)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_confirm_swap
```
```
In mm/workingset.c (ffffffff81250ab2)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/dax.c (ffffffff8134131b)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (ffffffff81a4e310)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
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
In mm/shmem.c (ffffffff8122cdba)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_confirm_swap
```
```
In mm/workingset.c (ffffffff81243a32)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/dax.c (ffffffff81331ceb)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (ffffffff81a0b400)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
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
In mm/shmem.c (ffffffff81237b44)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_confirm_swap
```
```
In mm/workingset.c (ffffffff8124e852)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/dax.c (ffffffff8133edeb)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (ffffffff81aba700)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
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
In mm/shmem.c (ffffffff81247159)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_confirm_swap
```
```
In mm/workingset.c (ffffffff8125e1c2)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In fs/dax.c (ffffffff813511c9)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (ffffffff81ac6b50)
Location: include/linux/xarray.h:52
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
</details>
</li>
</ul>

## Differences
