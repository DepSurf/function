# Function: <code>folio_batch_release</code>

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
In mm/truncate.c (ffffffff81307728)
Location: include/linux/pagevec.h:144
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81319c64)
Location: include/linux/pagevec.h:144
Inline: True
Inline callers:
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
In mm/truncate.c (ffffffff81371886)
Location: include/linux/pagevec.h:133
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8138ded4)
Location: include/linux/pagevec.h:133
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In fs/buffer.c (ffffffff814d28e7)
Location: include/linux/pagevec.h:133
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/ext4/inode.c (ffffffff815798d5)
Location: include/linux/pagevec.h:133
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6b77)
Location: include/linux/pagevec.h:133
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
In mm/filemap.c (ffffffff813926e2)
Location: include/linux/pagevec.h:80
Inline: True
Inline callers:
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff8139a384)
Location: include/linux/pagevec.h:80
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff813a3993)
Location: include/linux/pagevec.h:80
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_try_invalidate
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff813c0e54)
Location: include/linux/pagevec.h:80
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In fs/buffer.c (ffffffff815091f5)
Location: include/linux/pagevec.h:80
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/ext4/inode.c (ffffffff815b5d5d)
Location: include/linux/pagevec.h:80
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff8162ec31)
Location: include/linux/pagevec.h:80
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
In mm/filemap.c (ffffffff813bc32b)
Location: include/linux/pagevec.h:80
Inline: True
Inline callers:
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff813c402f)
Location: include/linux/pagevec.h:80
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff813cd63b)
Location: include/linux/pagevec.h:80
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_try_invalidate
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff813ebaa4)
Location: include/linux/pagevec.h:80
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In fs/buffer.c (ffffffff8153de27)
Location: include/linux/pagevec.h:80
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/ext4/inode.c (ffffffff815eeb08)
Location: include/linux/pagevec.h:80
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/hugetlbfs/inode.c (ffffffff816680f9)
Location: include/linux/pagevec.h:80
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
