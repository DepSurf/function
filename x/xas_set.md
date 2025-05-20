# Function: <code>xas_set</code>

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
In mm/khugepaged.c (ffffffff8128ff91)
Location: include/linux/xarray.h:1376
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memfd.c (ffffffff812a8fb1)
Location: include/linux/xarray.h:1376
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/fs-writeback.c (ffffffff812e161b)
Location: include/linux/xarray.h:1376
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8130cd5c)
Location: include/linux/xarray.h:1376
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (ffffffff81a08b90)
Location: include/linux/xarray.h:1376
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81a191de)
Location: include/linux/xarray.h:1376
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/khugepaged.c (ffffffff812aae14)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memfd.c (ffffffff812c546c)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff812ffde2)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff813353ff)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (ffffffff81a7855e)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81a88efd)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/khugepaged.c (ffffffff812bc53d)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812d6e40)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff813125e8)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff81348ffb)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (ffffffff81aaf818)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81ac019d)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/khugepaged.c (ffffffff812f1a5a)
Location: include/linux/xarray.h:1540
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff8130bfac)
Location: include/linux/xarray.h:1540
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8134be7b)
Location: include/linux/xarray.h:1540
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8138e37b)
Location: include/linux/xarray.h:1540
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In fs/fuse/file.c (ffffffff81475db1)
Location: include/linux/xarray.h:1540
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
  - fs/fuse/file.c:__readahead_batch
```
```
In lib/idr.c (ffffffff815e96c5)
Location: include/linux/xarray.h:1540
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff815fbedd)
Location: include/linux/xarray.h:1540
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/khugepaged.c (ffffffff812fdfde)
Location: include/linux/xarray.h:1575
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff81317e6c)
Location: include/linux/xarray.h:1575
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff81358c9f)
Location: include/linux/xarray.h:1575
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8139facb)
Location: include/linux/xarray.h:1575
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In fs/fuse/file.c (ffffffff814912e3)
Location: include/linux/xarray.h:1575
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
  - fs/fuse/file.c:__readahead_batch
```
```
In lib/idr.c (ffffffff8160e775)
Location: include/linux/xarray.h:1575
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81620a7d)
Location: include/linux/xarray.h:1575
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (ffffffff81263391)
Location: include/linux/xarray.h:1577
Inline: True
Inline callers:
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:find_lock_entries
```
```
In mm/khugepaged.c (ffffffff81304bce)
Location: include/linux/xarray.h:1577
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff8131e05c)
Location: include/linux/xarray.h:1577
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8135f7ff)
Location: include/linux/xarray.h:1577
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff813a7070)
Location: include/linux/xarray.h:1577
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In fs/fuse/file.c (ffffffff81496433)
Location: include/linux/xarray.h:1577
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
  - fs/fuse/file.c:__readahead_batch
```
```
In lib/idr.c (ffffffff815f1ec7)
Location: include/linux/xarray.h:1577
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff8160425d)
Location: include/linux/xarray.h:1577
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (ffffffff8129fadd)
Location: include/linux/xarray.h:1577
Inline: True
Inline callers:
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_lock_entries
```
```
In mm/khugepaged.c (ffffffff8134e95e)
Location: include/linux/xarray.h:1577
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff8136b458)
Location: include/linux/xarray.h:1577
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff813ae167)
Location: include/linux/xarray.h:1577
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff813f6f33)
Location: include/linux/xarray.h:1577
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In fs/fuse/file.c (ffffffff814eefa4)
Location: include/linux/xarray.h:1577
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/idr.c (ffffffff8165f045)
Location: include/linux/xarray.h:1577
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81672acf)
Location: include/linux/xarray.h:1577
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (ffffffff812f6b54)
Location: include/linux/xarray.h:1581
Inline: True
Inline callers:
  - mm/filemap.c:mapping_seek_hole_data
```
```
In mm/list_lru.c (ffffffff813359e9)
Location: include/linux/xarray.h:1581
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
```
```
In mm/khugepaged.c (ffffffff813c50e0)
Location: include/linux/xarray.h:1581
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff813e94c9)
Location: include/linux/xarray.h:1581
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff81432458)
Location: include/linux/xarray.h:1581
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff81469399)
Location: include/linux/xarray.h:1581
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In fs/fuse/file.c (ffffffff8157ed1e)
Location: include/linux/xarray.h:1581
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/idr.c (ffffffff817789f2)
Location: include/linux/xarray.h:1581
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff8178d3b6)
Location: include/linux/xarray.h:1581
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (ffffffff81360627)
Location: include/linux/xarray.h:1596
Inline: True
Inline callers:
  - mm/filemap.c:mapping_seek_hole_data
```
```
In mm/list_lru.c (ffffffff813ac7a9)
Location: include/linux/xarray.h:1596
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
```
```
In mm/khugepaged.c (ffffffff81449a03)
Location: include/linux/xarray.h:1596
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff814714a9)
Location: include/linux/xarray.h:1596
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff814c050b)
Location: include/linux/xarray.h:1596
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff814f9e29)
Location: include/linux/xarray.h:1596
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In fs/squashfs/file.c (ffffffff815edfce)
Location: include/linux/xarray.h:1596
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff816249de)
Location: include/linux/xarray.h:1596
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/idr.c (ffffffff8202178b)
Location: include/linux/xarray.h:1596
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff8204aa02)
Location: include/linux/xarray.h:1596
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (ffffffff81392ae2)
Location: include/linux/xarray.h:1596
Inline: True
Inline callers:
  - mm/filemap.c:mapping_seek_hole_data
```
```
In mm/list_lru.c (ffffffff813e0b49)
Location: include/linux/xarray.h:1596
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
```
```
In mm/khugepaged.c (ffffffff8147fd2d)
Location: include/linux/xarray.h:1596
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff814a59fb)
Location: include/linux/xarray.h:1596
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff814f595e)
Location: include/linux/xarray.h:1596
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff815312a6)
Location: include/linux/xarray.h:1596
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In fs/squashfs/file.c (ffffffff81625f8e)
Location: include/linux/xarray.h:1596
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff8165cdb5)
Location: include/linux/xarray.h:1596
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/idr.c (ffffffff820a17d1)
Location: include/linux/xarray.h:1596
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff820c9302)
Location: include/linux/xarray.h:1596
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (ffffffff813bc796)
Location: include/linux/xarray.h:1614
Inline: True
Inline callers:
  - mm/filemap.c:mapping_seek_hole_data
```
```
In mm/list_lru.c (ffffffff8140b419)
Location: include/linux/xarray.h:1614
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
```
```
In mm/khugepaged.c (ffffffff814ade39)
Location: include/linux/xarray.h:1614
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff814d69ab)
Location: include/linux/xarray.h:1614
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8152a06b)
Location: include/linux/xarray.h:1614
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff81566186)
Location: include/linux/xarray.h:1614
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_folio
```
```
In fs/squashfs/file.c (ffffffff8165f0ce)
Location: include/linux/xarray.h:1614
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff81696b15)
Location: include/linux/xarray.h:1614
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/idr.c (ffffffff82179849)
Location: include/linux/xarray.h:1614
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff821a3c82)
Location: include/linux/xarray.h:1614
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/khugepaged.c (ffff80001035d848)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffff80001037bdcc)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffff8000103c7654)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffff80001040a6c0)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (ffff800010d89108)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffff800010d9ae74)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (c04dfe08)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/memfd.c (c0566b98)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (c05a4550)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In lib/idr.c (c0e83fc0)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
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
In mm/khugepaged.c (c000000000448ab0)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (c0000000004712b8)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (c0000000004c910c)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (c000000000515a60)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (c000000000ec9d54)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (c000000000ee2048)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (ffffffe0001d848c)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/memfd.c (ffffffe0002525b2)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffe0002862b4)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffe0002b465c)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (ffffffe0008b2eb2)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
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
In mm/khugepaged.c (ffffffff812b4b1d)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812cf420)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8130abc8)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff813415db)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (ffffffff81a4e668)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81a5efed)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/khugepaged.c (ffffffff812a5b6f)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812c00a4)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff812fb7e8)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff81331f95)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (ffffffff81a0b758)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81a1c0bd)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/khugepaged.c (ffffffff812b292d)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812cd230)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff813089b8)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8133f0ab)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (ffffffff81abaa58)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81acb3dd)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/khugepaged.c (ffffffff812c2b66)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812ddfb0)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8131a638)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff81350b41)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
```
```
In lib/idr.c (ffffffff81ac6ea8)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In lib/xarray.c (ffffffff81ad7a3d)
Location: include/linux/xarray.h:1505
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
```
</details>
</li>
</ul>

## Differences
