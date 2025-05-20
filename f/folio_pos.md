# Function: <code>folio_pos</code>

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
In mm/filemap.c (ffffffff812f3207)
Location: include/linux/pagemap.h:817
Inline: True
Inline callers:
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_update_page
```
```
In mm/truncate.c (ffffffff81308584)
Location: include/linux/pagemap.h:817
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_partial_folio
```
```
In mm/shmem.c (ffffffff81319cbe)
Location: include/linux/pagemap.h:817
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
```
```
In fs/iomap/buffered-io.c (ffffffff8148a4e8)
Location: include/linux/pagemap.h:817
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:iomap_read_folio
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
In mm/filemap.c (ffffffff8135d5c8)
Location: include/linux/pagemap.h:813
Inline: True
Inline callers:
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_update_page
```
```
In mm/truncate.c (ffffffff813724ba)
Location: include/linux/pagemap.h:813
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_partial_folio
```
```
In mm/shmem.c (ffffffff8138e102)
Location: include/linux/pagemap.h:813
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
```
```
In fs/iomap/buffered-io.c (ffffffff8151dec3)
Location: include/linux/pagemap.h:813
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:iomap_read_folio
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
In mm/filemap.c (ffffffff813926cd)
Location: include/linux/pagemap.h:834
Inline: True
Inline callers:
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_update_page
```
```
In mm/truncate.c (ffffffff813a4637)
Location: include/linux/pagemap.h:834
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_partial_folio
```
```
In mm/shmem.c (ffffffff813c104e)
Location: include/linux/pagemap.h:834
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff8150b80b)
Location: include/linux/pagemap.h:834
Inline: True
Inline callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_write_end
```
```
In fs/mpage.c (ffffffff8150edce)
Location: include/linux/pagemap.h:834
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff81556056)
Location: include/linux/pagemap.h:834
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:iomap_read_folio
```
```
In fs/ext4/inode.c (ffffffff815bc71f)
Location: include/linux/pagemap.h:834
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_journal_folio_buffers
  - fs/ext4/inode.c:mpage_submit_folio
```
```
In fs/fuse/file.c (ffffffff816613c2)
Location: include/linux/pagemap.h:834
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In mm/filemap.c (ffffffff813bc316)
Location: include/linux/pagemap.h:932
Inline: True
Inline callers:
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_update_page
```
```
In mm/truncate.c (ffffffff813ce197)
Location: include/linux/pagemap.h:932
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_partial_folio
```
```
In mm/shmem.c (ffffffff813ebc87)
Location: include/linux/pagemap.h:932
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff815422ed)
Location: include/linux/pagemap.h:932
Inline: True
Inline callers:
  - fs/buffer.c:block_write_full_folio
  - fs/buffer.c:block_write_full_folio
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:folio_init_buffers
```
```
In fs/mpage.c (ffffffff81543684)
Location: include/linux/pagemap.h:932
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff8158c519)
Location: include/linux/pagemap.h:932
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:iomap_read_folio
```
```
In fs/ext4/inode.c (ffffffff815f54fc)
Location: include/linux/pagemap.h:932
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_journal_folio_buffers
  - fs/ext4/inode.c:mpage_submit_folio
```
```
In fs/fuse/file.c (ffffffff8169b282)
Location: include/linux/pagemap.h:932
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
