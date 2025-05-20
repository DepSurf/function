# Function: <code>folio_lock</code>

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
In mm/filemap.c (ffffffff812f1b68)
Location: include/linux/pagemap.h:938
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/truncate.c (ffffffff81307627)
Location: include/linux/pagemap.h:938
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8130de78)
Location: include/linux/pagemap.h:938
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff813185e2)
Location: include/linux/pagemap.h:938
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff813375f1)
Location: include/linux/pagemap.h:938
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In fs/splice.c (ffffffff81437ef2)
Location: include/linux/pagemap.h:938
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff81441e9a)
Location: include/linux/pagemap.h:938
Inline: True
```
```
In fs/buffer.c (ffffffff81446c20)
Location: include/linux/pagemap.h:938
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
```
```
In fs/iomap/buffered-io.c (ffffffff8148a874)
Location: include/linux/pagemap.h:938
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
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
In kernel/events/uprobes.c (ffffffff8134fba4)
Location: include/linux/pagemap.h:934
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8135cc22)
Location: include/linux/pagemap.h:934
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/truncate.c (ffffffff81371745)
Location: include/linux/pagemap.h:934
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8137919b)
Location: include/linux/pagemap.h:934
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8138c4d6)
Location: include/linux/pagemap.h:934
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff813ae71b)
Location: include/linux/pagemap.h:934
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/swapfile.c (ffffffff813ffcd5)
Location: include/linux/pagemap.h:934
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/migrate.c (ffffffff81435276)
Location: include/linux/pagemap.h:934
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:writeout
```
```
In mm/huge_memory.c (ffffffff814416f6)
Location: include/linux/pagemap.h:934
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In fs/splice.c (ffffffff814c6b15)
Location: include/linux/pagemap.h:934
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff814d0977)
Location: include/linux/pagemap.h:934
Inline: True
```
```
In fs/buffer.c (ffffffff814d284e)
Location: include/linux/pagemap.h:934
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff8151e121)
Location: include/linux/pagemap.h:934
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6b26)
Location: include/linux/pagemap.h:934
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/events/uprobes.c (ffffffff81380d63)
Location: include/linux/pagemap.h:955
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8138ec50)
Location: include/linux/pagemap.h:955
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/page-writeback.c (ffffffff8139a349)
Location: include/linux/pagemap.h:955
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff813a3855)
Location: include/linux/pagemap.h:955
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813ad765)
Location: include/linux/pagemap.h:955
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff813bf843)
Location: include/linux/pagemap.h:955
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_get_partial_folio
```
```
In mm/gup.c (ffffffff813e301b)
Location: include/linux/pagemap.h:955
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/madvise.c (ffffffff81427f19)
Location: include/linux/pagemap.h:955
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff81432b7a)
Location: include/linux/pagemap.h:955
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81444583)
Location: include/linux/pagemap.h:955
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/migrate.c (ffffffff8146a7e4)
Location: include/linux/pagemap.h:955
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:writeout
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff81478339)
Location: include/linux/pagemap.h:955
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memory-failure.c (ffffffff81498db6)
Location: include/linux/pagemap.h:955
Inline: True
Inline callers:
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
```
In fs/splice.c (ffffffff814fbbb5)
Location: include/linux/pagemap.h:955
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff81507077)
Location: include/linux/pagemap.h:955
Inline: True
```
```
In fs/buffer.c (ffffffff8150d3b5)
Location: include/linux/pagemap.h:955
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff81556287)
Location: include/linux/pagemap.h:955
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff815bc6fa)
Location: include/linux/pagemap.h:955
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff8162ebe1)
Location: include/linux/pagemap.h:955
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/futex/core.c (ffffffff8121ef0a)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff813aa124)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff813b8040)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/page-writeback.c (ffffffff813c3ff4)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff813cd3ba)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813d6b72)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff813ea85c)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_get_partial_folio
```
```
In mm/gup.c (ffffffff8140d852)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/memory.c (ffffffff8141af69)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_page_mkwrite
```
```
In mm/madvise.c (ffffffff81461b83)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8146bf99)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8147e658)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/migrate.c (ffffffff814997c4)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:writeout
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff814a7a69)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memory-failure.c (ffffffff814c63fd)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
```
In mm/userfaultfd.c (ffffffff814d2e2d)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
```
```
In fs/splice.c (ffffffff815301f4)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff8153c39d)
Location: include/linux/pagemap.h:1044
Inline: True
```
```
In fs/buffer.c (ffffffff81541f65)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff8158c757)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff815f54d7)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff816680a8)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In block/bio.c (ffffffff817abafb)
Location: include/linux/pagemap.h:1044
Inline: True
Inline callers:
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:__bio_release_pages
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
