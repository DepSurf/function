# Function: <code>folio_batch_count</code>

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
In mm/filemap.c (ffffffff812f3282)
Location: include/linux/pagevec.h:117
Inline: True
Inline callers:
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/swap.c (ffffffff81307375)
Location: include/linux/pagevec.h:117
Inline: True
Inline callers:
  - mm/swap.c:folio_batch_remove_exceptionals
```
```
In mm/truncate.c (ffffffff813075c4)
Location: include/linux/pagevec.h:117
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81318b71)
Location: include/linux/pagevec.h:117
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
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
In mm/filemap.c (ffffffff8135d641)
Location: include/linux/pagevec.h:106
Inline: True
Inline callers:
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/swap.c (ffffffff813711f5)
Location: include/linux/pagevec.h:106
Inline: True
Inline callers:
  - mm/swap.c:folio_batch_remove_exceptionals
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:folio_batch_move_lru
```
```
In mm/truncate.c (ffffffff813716f0)
Location: include/linux/pagevec.h:106
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8138ca31)
Location: include/linux/pagevec.h:106
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff814d2816)
Location: include/linux/pagevec.h:106
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6a68)
Location: include/linux/pagevec.h:106
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
In mm/filemap.c (ffffffff81392635)
Location: include/linux/pagevec.h:51
Inline: True
Inline callers:
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff8139a384)
Location: include/linux/pagevec.h:51
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff813a3385)
Location: include/linux/pagevec.h:51
Inline: True
Inline callers:
  - mm/swap.c:folio_batch_remove_exceptionals
  - mm/swap.c:__folio_batch_release
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:folio_batch_move_lru
```
```
In mm/truncate.c (ffffffff813a3800)
Location: include/linux/pagevec.h:51
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_try_invalidate
  - mm/truncate.c:mapping_try_invalidate
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff813bf0e8)
Location: include/linux/pagevec.h:51
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff813f912f)
Location: include/linux/pagevec.h:51
Inline: True
Inline callers:
  - mm/mlock.c:need_mlock_drain
  - mm/mlock.c:mlock_drain_remote
  - mm/mlock.c:mlock_drain_local
  - mm/mlock.c:mlock_folio_batch
  - mm/mlock.c:mlock_folio_batch
```
```
In fs/buffer.c (ffffffff81509124)
Location: include/linux/pagevec.h:51
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/ext4/inode.c (ffffffff815b5d5d)
Location: include/linux/pagevec.h:51
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff8162eb28)
Location: include/linux/pagevec.h:51
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
In mm/filemap.c (ffffffff813bc27e)
Location: include/linux/pagevec.h:51
Inline: True
Inline callers:
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff813c402f)
Location: include/linux/pagevec.h:51
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/swap.c (ffffffff813ccff5)
Location: include/linux/pagevec.h:51
Inline: True
Inline callers:
  - mm/swap.c:folio_batch_remove_exceptionals
  - mm/swap.c:__folio_batch_release
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:folio_batch_move_lru
```
```
In mm/truncate.c (ffffffff813cd3a0)
Location: include/linux/pagevec.h:51
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_try_invalidate
  - mm/truncate.c:mapping_try_invalidate
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff813ea138)
Location: include/linux/pagevec.h:51
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/mlock.c (ffffffff81424cdf)
Location: include/linux/pagevec.h:51
Inline: True
Inline callers:
  - mm/mlock.c:need_mlock_drain
  - mm/mlock.c:mlock_drain_remote
  - mm/mlock.c:mlock_drain_local
  - mm/mlock.c:mlock_folio_batch
  - mm/mlock.c:mlock_folio_batch
```
```
In fs/buffer.c (ffffffff8153dd56)
Location: include/linux/pagevec.h:51
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/ext4/inode.c (ffffffff815eeb08)
Location: include/linux/pagevec.h:51
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff81667fdb)
Location: include/linux/pagevec.h:51
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c2ee)
Location: include/linux/pagevec.h:51
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_put_pages
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
