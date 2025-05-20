# Function: <code>xa_to_value</code>

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
In mm/shmem.c (ffffffff81222be7)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_free_swap
```
```
In mm/workingset.c (ffffffff81238e65)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/mincore.c (ffffffff81245588)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff812593cb)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
```
```
In mm/memcontrol.c (ffffffff81294655)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/dax.c (ffffffff8130e9e3)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_lock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In lib/idr.c (ffffffff81a08836)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - lib/idr.c:ida_free
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
In mm/shmem.c (ffffffff812330bb)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_free_swap
```
```
In mm/workingset.c (ffffffff8124a065)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/mincore.c (ffffffff81257625)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff81274c00)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
```
```
In mm/memcontrol.c (ffffffff812b088b)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/dax.c (ffffffff81335148)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_lock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In lib/idr.c (ffffffff81a781e5)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - lib/idr.c:ida_free
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
In mm/shmem.c (ffffffff812412db)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_free_swap
```
```
In mm/workingset.c (ffffffff812584b5)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/mincore.c (ffffffff81265b75)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff8128428e)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/memcontrol.c (ffffffff812c22eb)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/dax.c (ffffffff81348d28)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In lib/idr.c (ffffffff81aaf4a5)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - lib/idr.c:ida_free
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
In mm/shmem.c (ffffffff8126db29)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/workingset.c (ffffffff81286b75)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/mincore.c (ffffffff81295eb6)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff812b61c5)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
```
```
In mm/memcontrol.c (ffffffff812f9241)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/dax.c (ffffffff8138ef9e)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In lib/idr.c (ffffffff815e9345)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In net/core/devlink.c (ffffffff81a5134b)
Location: include/linux/xarray.h:65
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
In mm/shmem.c (ffffffff81279869)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/workingset.c (ffffffff81290e2e)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/madvise.c (ffffffff812c1013)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff812c4eef)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
```
```
In fs/dax.c (ffffffff813a065a)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In lib/idr.c (ffffffff8160e3f5)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In net/core/devlink.c (ffffffff81a5745b)
Location: include/linux/xarray.h:65
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
In mm/shmem.c (ffffffff8127e9c9)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/workingset.c (ffffffff8129648e)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/madvise.c (ffffffff812c7e26)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff812cbb96)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
```
```
In fs/dax.c (ffffffff813a6d9a)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In lib/idr.c (ffffffff815f1b45)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In net/core/devlink.c (ffffffff81a4221f)
Location: include/linux/xarray.h:65
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
In mm/shmem.c (ffffffff812bc548)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/workingset.c (ffffffff812d6c26)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/madvise.c (ffffffff8130cbec)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff81310cc1)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
```
```
In fs/dax.c (ffffffff813f6c5b)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In lib/idr.c (ffffffff8165eca7)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In net/core/devlink.c (ffffffff81afa8df)
Location: include/linux/xarray.h:65
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
In mm/shmem.c (ffffffff81318594)
Location: include/linux/xarray.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/workingset.c (ffffffff81336385)
Location: include/linux/xarray.h:66
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/madvise.c (ffffffff81376125)
Location: include/linux/xarray.h:66
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff8137baf8)
Location: include/linux/xarray.h:66
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
```
```
In fs/dax.c (ffffffff8146983e)
Location: include/linux/xarray.h:66
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In lib/idr.c (ffffffff8177856d)
Location: include/linux/xarray.h:66
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In net/core/devlink.c (ffffffff81c7f40f)
Location: include/linux/xarray.h:66
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
In mm/shmem.c (ffffffff8138c493)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/workingset.c (ffffffff813ad5e4)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:lru_gen_refault
```
```
In mm/madvise.c (ffffffff813f3a72)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff813f947c)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - mm/swap_state.c:filemap_get_incore_folio
```
```
In fs/dax.c (ffffffff814fa60b)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In drivers/pci/p2pdma.c (ffffffff8191d468)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
```
```
In net/core/devlink.c (ffffffff81e382d7)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_region_snapshot_create
  - net/core/devlink.c:__devlink_snapshot_id_decrement
```
```
In lib/idr.c (ffffffff8202130d)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - lib/idr.c:ida_free
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
In mm/filemap.c (ffffffff8138ccbe)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
```
```
In mm/shmem.c (ffffffff813bea8c)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/workingset.c (ffffffff813e19d1)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:lru_gen_refault
```
```
In mm/madvise.c (ffffffff81427535)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
```
```
In mm/swap_state.c (ffffffff8142c1eb)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - mm/swap_state.c:filemap_get_incore_folio
```
```
In fs/dax.c (ffffffff81531a75)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In drivers/pci/p2pdma.c (ffffffff81960a28)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
```
```
In net/devlink/leftover.c (ffffffff820391f7)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - net/devlink/leftover.c:__devlink_region_snapshot_create
  - net/devlink/leftover.c:__devlink_snapshot_id_decrement
```
```
In lib/idr.c (ffffffff820a133d)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - lib/idr.c:ida_free
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
In mm/filemap.c (ffffffff813b67ba)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
```
```
In mm/shmem.c (ffffffff813e9ab0)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/workingset.c (ffffffff8140c109)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:lru_gen_refault
```
```
In mm/madvise.c (ffffffff81460c19)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
```
```
In mm/swap_state.c (ffffffff8146594b)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - mm/swap_state.c:filemap_get_incore_folio
```
```
In fs/dax.c (ffffffff81566959)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_folio
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In drivers/pci/p2pdma.c (ffffffff819aa149)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
```
```
In net/devlink/region.c (ffffffff8210ff96)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - net/devlink/region.c:__devlink_region_snapshot_create
  - net/devlink/region.c:__devlink_snapshot_id_decrement
```
```
In lib/idr.c (ffffffff8217936c)
Location: include/linux/xarray.h:67
Inline: True
Inline callers:
  - lib/idr.c:ida_free
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
In mm/shmem.c (ffff8000102d36c8)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_free_swap
```
```
In mm/workingset.c (ffff8000102f02c4)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/mincore.c (ffff8000102fcd70)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffff80001031e6bc)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/madvise.c:__arm64_sys_madvise
```
```
In mm/memcontrol.c (ffff800010363dcc)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/dax.c (ffff8000104091d8)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In lib/idr.c (ffff800010d89304)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - lib/idr.c:ida_free
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
In mm/shmem.c (c04fb950)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_free_swap
```
```
In mm/workingset.c (c05139bc)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/mincore.c (c051c470)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (c0538630)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
```
```
In mm/memcontrol.c (c05560f0)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In lib/idr.c (c0e83c4c)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - lib/idr.c:ida_free
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
In mm/shmem.c (c00000000039274c)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_free_swap
```
```
In mm/workingset.c (c0000000003b4c9c)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/mincore.c (c0000000003c7d30)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (c0000000003f2920)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
```
```
In mm/memcontrol.c (c000000000451010)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/dax.c (c0000000005155a8)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_lock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In lib/idr.c (c000000000ec989c)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - lib/idr.c:ida_free
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
In mm/shmem.c (ffffffe0001ef78a)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_free_swap
```
```
In mm/workingset.c (ffffffe000203cdc)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/mincore.c (ffffffe00020b988)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffe000221598)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
```
```
In mm/memcontrol.c (ffffffe000241c9c)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/dax.c (ffffffe0002b34ee)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In lib/idr.c (ffffffe0008b2b62)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - lib/idr.c:ida_free
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
In mm/shmem.c (ffffffff8123992b)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_free_swap
```
```
In mm/workingset.c (ffffffff81250b05)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/mincore.c (ffffffff8125e1c5)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff8127c8de)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/memcontrol.c (ffffffff812ba8cb)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/dax.c (ffffffff81341308)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In lib/idr.c (ffffffff81a4e2f5)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - lib/idr.c:ida_free
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
In mm/shmem.c (ffffffff8122c95b)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_free_swap
```
```
In mm/workingset.c (ffffffff81243a85)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/mincore.c (ffffffff81250655)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff8126e78e)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/memcontrol.c (ffffffff812aba89)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/dax.c (ffffffff81331cd8)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In lib/idr.c (ffffffff81a0b3e5)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - lib/idr.c:ida_free
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
In mm/shmem.c (ffffffff812376cb)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_free_swap
```
```
In mm/workingset.c (ffffffff8124e8a5)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/mincore.c (ffffffff8125bf65)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff8127a67e)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/memcontrol.c (ffffffff812b86db)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/dax.c (ffffffff8133edd8)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In lib/idr.c (ffffffff81aba6e5)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - lib/idr.c:ida_free
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
In mm/shmem.c (ffffffff81246c0a)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_free_swap
```
```
In mm/workingset.c (ffffffff8125e215)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/mincore.c (ffffffff8126b955)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff8128a25e)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/memcontrol.c (ffffffff812c8d1b)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/dax.c (ffffffff813511b6)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In lib/idr.c (ffffffff81ac6b35)
Location: include/linux/xarray.h:65
Inline: True
Inline callers:
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
</details>
</li>
</ul>

## Differences
