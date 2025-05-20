# Function: <code>pagevec_init</code>

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
In mm/filemap.c (ffffffff8118ca4d)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff81198e60)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff8119e7e8)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/shmem.c (ffffffff811a65ae)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff811c2e01)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_pages_range
```
```
In fs/ext4/file.c (ffffffff8129239d)
Location: include/linux/pagevec.h:36
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8129600a)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/hugetlbfs/inode.c (ffffffff812f379a)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/filemap.c (ffffffff8119fa2d)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff811af730)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff811b42cd)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811bd01a)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff811df0f2)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/dax.c (ffffffff81287324)
Location: include/linux/pagevec.h:36
Inline: True
```
```
In fs/ext4/file.c (ffffffff812bf95b)
Location: include/linux/pagevec.h:36
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812c51ba)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff81327c1d)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/filemap.c (ffffffff811afc6d)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff811bfdf0)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff811c493d)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811cd72a)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff811eef01)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff8127ee49)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/dax.c (ffffffff8129b5eb)
Location: include/linux/pagevec.h:36
Inline: True
```
```
In fs/ext4/file.c (ffffffff812d4b6b)
Location: include/linux/pagevec.h:36
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812da86a)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff8133d95d)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/filemap.c (ffffffff811b6d06)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/page-writeback.c (ffffffff811c7fe0)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff811ccc8e)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811d682a)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff811f9ec4)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff81290300)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/dax.c (ffffffff812aa403)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/file.c (ffffffff812f1482)
Location: include/linux/pagevec.h:36
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812fe67a)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff81352692)
Location: include/linux/pagevec.h:36
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/filemap.c (ffffffff811cae8a)
Location: include/linux/pagevec.h:53
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff811dce20)
Location: include/linux/pagevec.h:53
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff811e1f1e)
Location: include/linux/pagevec.h:53
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811ebd4a)
Location: include/linux/pagevec.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff81212318)
Location: include/linux/pagevec.h:53
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff812b3026)
Location: include/linux/pagevec.h:53
Inline: True
Inline callers:
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/dax.c (ffffffff812cdc33)
Location: include/linux/pagevec.h:53
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/inode.c (ffffffff81322e64)
Location: include/linux/pagevec.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff813771f2)
Location: include/linux/pagevec.h:53
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/filemap.c (ffffffff811ec0f7)
Location: include/linux/pagevec.h:53
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff811fdf82)
Location: include/linux/pagevec.h:53
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff81203687)
Location: include/linux/pagevec.h:53
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8121227b)
Location: include/linux/pagevec.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff8123302e)
Location: include/linux/pagevec.h:53
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff812d6edb)
Location: include/linux/pagevec.h:53
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/dax.c (ffffffff812f836e)
Location: include/linux/pagevec.h:53
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/iomap.c (ffffffff8130db5a)
Location: include/linux/pagevec.h:53
Inline: True
Inline callers:
  - fs/iomap.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff81350c3d)
Location: include/linux/pagevec.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff813a5e9d)
Location: include/linux/pagevec.h:53
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/filemap.c (ffffffff811fe457)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff81210c1e)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff81215f57)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81223d3b)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff81246803)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff812ec25e)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap.c (ffffffff81324a11)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/iomap.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff81368bde)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff813be8c3)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/filemap.c (ffffffff81213577)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff812202d3)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff81225967)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81235dd4)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff81258a14)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff8130d8ae)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (ffffffff8134e1f1)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff8139200e)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff813e914c)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/filemap.c (ffffffff81220d3b)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff8122dd83)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff812337b7)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81244014)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff81266ee4)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff8132087e)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (ffffffff813664e1)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813aa99e)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff814031ec)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/filemap.c (ffffffff8124e799)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff8125981e)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff81260ee7)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8126decd)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff8129715a)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff81359afc)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (ffffffff813ae03f)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813f5c8e)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff81450e49)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/filemap.c (ffffffff81258c59)
Location: include/linux/pagevec.h:52
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff81263dce)
Location: include/linux/pagevec.h:52
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff8126b2e7)
Location: include/linux/pagevec.h:52
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8127c0cd)
Location: include/linux/pagevec.h:52
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff812a210a)
Location: include/linux/pagevec.h:52
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff81367c2c)
Location: include/linux/pagevec.h:52
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (ffffffff813bf6af)
Location: include/linux/pagevec.h:52
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff814085ee)
Location: include/linux/pagevec.h:52
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff8146d369)
Location: include/linux/pagevec.h:52
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/filemap.c (ffffffff812623f6)
Location: include/linux/pagevec.h:48
Inline: True
Inline callers:
  - mm/filemap.c:filemap_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff8126999e)
Location: include/linux/pagevec.h:48
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff812703c4)
Location: include/linux/pagevec.h:48
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8128128d)
Location: include/linux/pagevec.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff812a799a)
Location: include/linux/pagevec.h:48
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff8136e43c)
Location: include/linux/pagevec.h:48
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/ext4/inode.c (ffffffff8140ed7f)
Location: include/linux/pagevec.h:48
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff814729da)
Location: include/linux/pagevec.h:48
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/filemap.c (ffffffff8129e9f6)
Location: include/linux/pagevec.h:48
Inline: True
Inline callers:
  - mm/filemap.c:filemap_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff812a65fe)
Location: include/linux/pagevec.h:48
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff812ae044)
Location: include/linux/pagevec.h:48
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff812bc88d)
Location: include/linux/pagevec.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff812e8fba)
Location: include/linux/pagevec.h:48
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff813bd020)
Location: include/linux/pagevec.h:48
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/ext4/inode.c (ffffffff81461aa0)
Location: include/linux/pagevec.h:48
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff814c94ae)
Location: include/linux/pagevec.h:48
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/filemap.c (ffffffff812efca1)
Location: include/linux/pagevec.h:49
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff812fd22f)
Location: include/linux/pagevec.h:49
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/shmem.c (ffffffff8131c462)
Location: include/linux/pagevec.h:49
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unlock_mapping
```
```
In fs/buffer.c (ffffffff81443e04)
Location: include/linux/pagevec.h:49
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/ext4/inode.c (ffffffff814e1e15)
Location: include/linux/pagevec.h:49
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff815555cc)
Location: include/linux/pagevec.h:49
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/filemap.c (ffffffff8135ae40)
Location: include/linux/pagevec.h:38
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff81367b4f)
Location: include/linux/pagevec.h:38
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In fs/ext4/inode.c (ffffffff8157b15b)
Location: include/linux/pagevec.h:38
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
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
In mm/filemap.c (ffff8000102ae764)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffff8000102bccd8)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffff8000102c3c90)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffff8000102d62a4)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffff8000102fe148)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffff8000103d7b58)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (ffff80001042dcac)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffff80001047dfc0)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffff8000104e1ce8)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/filemap.c (c04dacec)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (c04e916c)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (c04ee840)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (c04fe504)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (c051d2ac)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (c05b24e8)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (c05f6c0c)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (c0640904)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
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
In mm/filemap.c (c0000000003625a8)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (c000000000375760)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (c00000000037e090)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (c00000000039649c)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (c0000000003c9860)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (c0000000004ddd54)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (c00000000053ef18)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (c0000000005a2b0c)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (c00000000061e644)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/filemap.c (ffffffe0001d4502)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffe0001dfba2)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffe0001e48e6)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffe0001f1b40)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffe00020c78c)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffe000292136)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (ffffffe0002ca6ec)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffe000307c9a)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffe00035587a)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/filemap.c (ffffffff8121938b)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff812263d3)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff8122be07)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8123c664)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff8125f534)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff81318e5e)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (ffffffff8135eac1)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813a2f7e)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff813fb7cc)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/filemap.c (ffffffff8120c59b)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff81219543)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff8121eee7)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8122f664)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff81251954)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff81309a4e)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (ffffffff8134f761)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff81393a0e)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff813ec24c)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/filemap.c (ffffffff8121712b)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff81224173)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff81229ba7)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8123a404)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff8125d2d4)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff8131692e)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (ffffffff8135c591)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813a07de)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff813f8b4c)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/filemap.c (ffffffff812261bb)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff81233443)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff81238fa7)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81249af4)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff8126ccbf)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In fs/buffer.c (ffffffff8132887a)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/seek.c (ffffffff8136fcdd)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813b500e)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff8140e99c)
Location: include/linux/pagevec.h:55
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
</details>
</li>
</ul>

## Differences
