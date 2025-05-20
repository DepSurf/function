# Function: <code>pagevec_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118cb04)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff8119909b)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff8119e948)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/shmem.c (ffffffff811a667a)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff811c2ea3)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/ext4/file.c (ffffffff812925dc)
Location: include/linux/pagevec.h:66
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812960d6)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8119fae8)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff811af9a3)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff811b4424)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811bd0f7)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff811deb63)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/ext4/file.c (ffffffff812bfbb2)
Location: include/linux/pagevec.h:66
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812c5385)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811afd4d)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff811c0063)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff811c4ab0)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811cd807)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff811ee983)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff8127efd1)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/ext4/file.c (ffffffff812d4dc2)
Location: include/linux/pagevec.h:66
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812daa35)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b6dcd)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/page-writeback.c (ffffffff811c8229)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff811cce83)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811d6905)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff811f998d)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff81290513)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/ext4/file.c (ffffffff812f16c3)
Location: include/linux/pagevec.h:66
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812fe844)
Location: include/linux/pagevec.h:66
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811caf47)
Location: include/linux/pagevec.h:83
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff811dd07e)
Location: include/linux/pagevec.h:83
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff811e2086)
Location: include/linux/pagevec.h:83
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811ebe21)
Location: include/linux/pagevec.h:83
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff81211db9)
Location: include/linux/pagevec.h:83
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff812b31df)
Location: include/linux/pagevec.h:83
Inline: True
Inline callers:
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/ext4/inode.c (ffffffff81323028)
Location: include/linux/pagevec.h:83
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ec1a2)
Location: include/linux/pagevec.h:83
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff811fe1e2)
Location: include/linux/pagevec.h:83
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff812037f3)
Location: include/linux/pagevec.h:83
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8120d5a1)
Location: include/linux/pagevec.h:83
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff81232ae5)
Location: include/linux/pagevec.h:83
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff812d700c)
Location: include/linux/pagevec.h:83
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/dax.c (ffffffff812f7a89)
Location: include/linux/pagevec.h:83
Inline: True
```
```
In fs/iomap.c (ffffffff8130dd6d)
Location: include/linux/pagevec.h:83
Inline: True
Inline callers:
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/iomap.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff81350df6)
Location: include/linux/pagevec.h:83
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fe506)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff81210e3d)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff812160c3)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81220171)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff812462b5)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff812ec38f)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap.c (ffffffff81324c1b)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/iomap.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff81368d97)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
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
In mm/filemap.c (ffffffff812135d3)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff812204d2)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff81225ac7)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8122f918)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff812584ea)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff8130d9ce)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (ffffffff8134e3d3)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813921b0)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
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
In mm/filemap.c (ffffffff81220da4)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff8122df82)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff81233917)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8123dae8)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff812669ba)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff8132099e)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (ffffffff813666c3)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813aab40)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
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
In mm/filemap.c (ffffffff8124e802)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff81259a56)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff8126103c)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8126c20b)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff81296c73)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff81359c29)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (ffffffff813ae21b)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813f5e2c)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
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
In mm/filemap.c (ffffffff81258cc2)
Location: include/linux/pagevec.h:82
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff81263fbc)
Location: include/linux/pagevec.h:82
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff8126b43a)
Location: include/linux/pagevec.h:82
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81276c5b)
Location: include/linux/pagevec.h:82
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff812a1b1a)
Location: include/linux/pagevec.h:82
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff81367d59)
Location: include/linux/pagevec.h:82
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (ffffffff813bf88b)
Location: include/linux/pagevec.h:82
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff8140878e)
Location: include/linux/pagevec.h:82
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
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
In mm/filemap.c (ffffffff8125d172)
Location: include/linux/pagevec.h:78
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff81269b8c)
Location: include/linux/pagevec.h:78
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff812705ed)
Location: include/linux/pagevec.h:78
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff812801d5)
Location: include/linux/pagevec.h:78
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff812a72ef)
Location: include/linux/pagevec.h:78
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff8136e569)
Location: include/linux/pagevec.h:78
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/ext4/inode.c (ffffffff8140ef1f)
Location: include/linux/pagevec.h:78
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
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
In mm/filemap.c (ffffffff812990b3)
Location: include/linux/pagevec.h:78
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff812a67f3)
Location: include/linux/pagevec.h:78
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff812ae278)
Location: include/linux/pagevec.h:78
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff812be518)
Location: include/linux/pagevec.h:78
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff812e892c)
Location: include/linux/pagevec.h:78
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff813bd154)
Location: include/linux/pagevec.h:78
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/ext4/inode.c (ffffffff81461c62)
Location: include/linux/pagevec.h:78
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
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
In mm/filemap.c (ffffffff812efd07)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff812fd413)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff81307728)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81319c64)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In fs/buffer.c (ffffffff81443f72)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/ext4/inode.c (ffffffff814e1ff6)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
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
In mm/filemap.c (ffffffff8135aea2)
Location: include/linux/pagevec.h:68
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff81367d33)
Location: include/linux/pagevec.h:68
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff81371886)
Location: include/linux/pagevec.h:68
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8138ded4)
Location: include/linux/pagevec.h:68
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In fs/buffer.c (ffffffff814d28e7)
Location: include/linux/pagevec.h:68
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/ext4/inode.c (ffffffff8157b35f)
Location: include/linux/pagevec.h:68
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6b77)
Location: include/linux/pagevec.h:68
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102ae7d8)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffff8000102bce64)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffff8000102c3d80)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffff8000102cf578)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffff8000102fda10)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffff8000103d7cac)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (ffff80001042ddf8)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffff80001047e174)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
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
In mm/filemap.c (c04dad54)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (c04e9380)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (c04ee970)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (c04f8dac)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (c051cd84)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (c05b2654)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (c05f6e00)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (c0640ae8)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_release_unused_pages
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
In mm/filemap.c (c000000000362654)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (c00000000037591c)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (c00000000037e26c)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (c00000000038cf1c)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (c0000000003c8f34)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (c0000000004ddee4)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (c00000000053f0f4)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (c0000000005a2d14)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
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
In mm/filemap.c (ffffffe0001d455c)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffe0001dfd10)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffe0001e49f4)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffe0001ecde4)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffe00020c246)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffe000292252)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (ffffffe0002ca816)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffe000307dc0)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
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
In mm/filemap.c (ffffffff812193f4)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff812265d2)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff8122bf67)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81236138)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff8125f00a)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff81318f7e)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (ffffffff8135eca3)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813a3120)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
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
In mm/filemap.c (ffffffff8120c604)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff81219742)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff8121f047)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81229198)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff81251434)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff81309b6e)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (ffffffff8134f943)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff81393bb0)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
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
In mm/filemap.c (ffffffff81217194)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff81224372)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff81229d07)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81233ed8)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff8125cdaa)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff81316a4e)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (ffffffff8135c773)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813a0980)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
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
In mm/filemap.c (ffffffff81226224)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff8123363d)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff81239102)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff812434a8)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff8126c785)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff8132898d)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (ffffffff8136febe)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813b51b5)
Location: include/linux/pagevec.h:85
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
</details>
</li>
</ul>

## Differences
