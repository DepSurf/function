# Function: <code>page_offset</code>

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
In fs/buffer.c (0)
Location: include/linux/pagemap.h:406
Inline: True
```
```
In fs/ext4/file.c (ffffffff812924bb)
Location: include/linux/pagemap.h:406
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/pagemap.h:406
Inline: True
```
```
In fs/fuse/file.c (ffffffff81316853)
Location: include/linux/pagemap.h:406
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepages_fill
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
In fs/buffer.c (ffffffff8126e7cd)
Location: include/linux/pagemap.h:392
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap.c (ffffffff8129c1c9)
Location: include/linux/pagemap.h:392
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff812bfa01)
Location: include/linux/pagemap.h:392
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812cda28)
Location: include/linux/pagemap.h:392
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/file.c (ffffffff8134eec0)
Location: include/linux/pagemap.h:392
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_short_read
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
In fs/buffer.c (ffffffff812819ed)
Location: include/linux/pagemap.h:411
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap.c (ffffffff812b1cf9)
Location: include/linux/pagemap.h:411
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff812d4c11)
Location: include/linux/pagemap.h:411
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812e37f8)
Location: include/linux/pagemap.h:411
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/file.c (ffffffff813647ce)
Location: include/linux/pagemap.h:411
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_short_read
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
In fs/buffer.c (ffffffff812903b9)
Location: include/linux/pagemap.h:427
Inline: True
Inline callers:
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap.c (ffffffff812bf029)
Location: include/linux/pagemap.h:427
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff812f1546)
Location: include/linux/pagemap.h:427
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8130797d)
Location: include/linux/pagemap.h:427
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/file.c (ffffffff81378fa0)
Location: include/linux/pagemap.h:427
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_short_read
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
In fs/buffer.c (ffffffff812b3097)
Location: include/linux/pagemap.h:440
Inline: True
Inline callers:
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap.c (ffffffff812e2a98)
Location: include/linux/pagemap.h:440
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff8132c5cd)
Location: include/linux/pagemap.h:440
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/file.c (ffffffff8139de40)
Location: include/linux/pagemap.h:440
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_short_read
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
In fs/buffer.c (ffffffff812d9ceb)
Location: include/linux/pagemap.h:440
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap.c (ffffffff8130dc0a)
Location: include/linux/pagemap.h:440
Inline: True
Inline callers:
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff8135ab96)
Location: include/linux/pagemap.h:440
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/file.c (ffffffff813cd20f)
Location: include/linux/pagemap.h:440
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_short_read
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
In fs/buffer.c (ffffffff812ef1db)
Location: include/linux/pagemap.h:440
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap.c (ffffffff81324ac0)
Location: include/linux/pagemap.h:440
Inline: True
Inline callers:
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/iomap.c:iomap_page_mkwrite
  - fs/iomap.c:iomap_readpages
  - fs/iomap.c:iomap_readpages
  - fs/iomap.c:iomap_readpages_actor
  - fs/iomap.c:iomap_readpage
```
```
In fs/ext4/inode.c (ffffffff81372e56)
Location: include/linux/pagemap.h:440
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/file.c (ffffffff813e658b)
Location: include/linux/pagemap.h:440
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_short_read
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
In fs/buffer.c (ffffffff81310a31)
Location: include/linux/pagemap.h:424
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap/buffered-io.c (ffffffff8134b3f5)
Location: include/linux/pagemap.h:424
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpage
```
```
In fs/iomap/seek.c (ffffffff8134e287)
Location: include/linux/pagemap.h:424
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff8139c2af)
Location: include/linux/pagemap.h:424
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/file.c (ffffffff814125be)
Location: include/linux/pagemap.h:424
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_short_read
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
In fs/buffer.c (ffffffff81323a11)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap/buffered-io.c (ffffffff813636a5)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpage
```
```
In fs/iomap/seek.c (ffffffff81366577)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813b4dbf)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/file.c (ffffffff8142c3bd)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In fs/buffer.c (ffffffff8135e105)
Location: include/linux/pagemap.h:475
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap/buffered-io.c (ffffffff813ac9f7)
Location: include/linux/pagemap.h:475
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_releasepage
  - fs/iomap/buffered-io.c:iomap_readpage
```
```
In fs/iomap/seek.c (ffffffff813ae0e2)
Location: include/linux/pagemap.h:475
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff81400253)
Location: include/linux/pagemap.h:475
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/file.c (ffffffff8147be24)
Location: include/linux/pagemap.h:475
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_do_readpage
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
In fs/buffer.c (ffffffff8136bc25)
Location: include/linux/pagemap.h:538
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap/buffered-io.c (ffffffff813bd4b2)
Location: include/linux/pagemap.h:538
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_releasepage
  - fs/iomap/buffered-io.c:iomap_readpage
```
```
In fs/iomap/seek.c (ffffffff813bf752)
Location: include/linux/pagemap.h:538
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff81412a57)
Location: include/linux/pagemap.h:538
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/fuse/file.c (ffffffff81496c95)
Location: include/linux/pagemap.h:538
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/filemap.c (ffffffff81262572)
Location: include/linux/pagemap.h:554
Inline: True
Inline callers:
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_update_page
```
```
In fs/buffer.c (ffffffff81372550)
Location: include/linux/pagemap.h:554
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap/buffered-io.c (ffffffff813c3a02)
Location: include/linux/pagemap.h:554
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_releasepage
  - fs/iomap/buffered-io.c:iomap_readpage
```
```
In fs/ext4/inode.c (ffffffff81418eb3)
Location: include/linux/pagemap.h:554
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/fuse/file.c (ffffffff8149bda7)
Location: include/linux/pagemap.h:554
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/filemap.c (ffffffff8129eb89)
Location: include/linux/pagemap.h:553
Inline: True
Inline callers:
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_update_page
```
```
In fs/buffer.c (ffffffff813c1590)
Location: include/linux/pagemap.h:553
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap/buffered-io.c (ffffffff81413f42)
Location: include/linux/pagemap.h:553
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_releasepage
  - fs/iomap/buffered-io.c:iomap_readpage
```
```
In fs/ext4/inode.c (ffffffff8146c0e7)
Location: include/linux/pagemap.h:553
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/fuse/file.c (ffffffff814f37a4)
Location: include/linux/pagemap.h:553
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/filemap.c (ffffffff812f3207)
Location: include/linux/pagemap.h:803
Inline: True
Inline callers:
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_update_page
```
```
In mm/truncate.c (ffffffff81308584)
Location: include/linux/pagemap.h:803
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_partial_folio
```
```
In mm/shmem.c (ffffffff81319cbe)
Location: include/linux/pagemap.h:803
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff814483d2)
Location: include/linux/pagemap.h:803
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap/buffered-io.c (ffffffff8148a4e8)
Location: include/linux/pagemap.h:803
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
```
In fs/ext4/inode.c (ffffffff814ec0e1)
Location: include/linux/pagemap.h:803
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/fuse/file.c (ffffffff81583210)
Location: include/linux/pagemap.h:803
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
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
Location: include/linux/pagemap.h:799
Inline: True
Inline callers:
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_update_page
```
```
In mm/truncate.c (ffffffff813724ba)
Location: include/linux/pagemap.h:799
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_partial_folio
```
```
In mm/shmem.c (ffffffff8138e102)
Location: include/linux/pagemap.h:799
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff814d6faf)
Location: include/linux/pagemap.h:799
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap/buffered-io.c (ffffffff8151dec3)
Location: include/linux/pagemap.h:799
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
```
In fs/ext4/inode.c (ffffffff81585e4b)
Location: include/linux/pagemap.h:799
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/fuse/file.c (ffffffff816291a0)
Location: include/linux/pagemap.h:799
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_do_readpage
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
Location: include/linux/pagemap.h:820
Inline: True
Inline callers:
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_update_page
```
```
In mm/truncate.c (ffffffff813a4637)
Location: include/linux/pagemap.h:820
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_partial_folio
```
```
In mm/shmem.c (ffffffff813c104e)
Location: include/linux/pagemap.h:820
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff8150b80b)
Location: include/linux/pagemap.h:820
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
Location: include/linux/pagemap.h:820
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff81556056)
Location: include/linux/pagemap.h:820
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
Location: include/linux/pagemap.h:820
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
Location: include/linux/pagemap.h:820
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_do_readpage
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
Location: include/linux/pagemap.h:918
Inline: True
Inline callers:
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_update_page
```
```
In mm/truncate.c (ffffffff813ce197)
Location: include/linux/pagemap.h:918
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_partial_folio
```
```
In mm/shmem.c (ffffffff813ebc87)
Location: include/linux/pagemap.h:918
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
```
```
In fs/buffer.c (ffffffff815422ed)
Location: include/linux/pagemap.h:918
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
Location: include/linux/pagemap.h:918
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
```
In fs/iomap/buffered-io.c (ffffffff8158c519)
Location: include/linux/pagemap.h:918
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
Location: include/linux/pagemap.h:918
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
Location: include/linux/pagemap.h:918
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_do_readpage
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
In fs/buffer.c (ffff8000103dcd6c)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap/buffered-io.c (ffff80001042a448)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpage
```
```
In fs/iomap/seek.c (ffff80001042dcfc)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffff800010489560)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/file.c (ffff800010510240)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In fs/buffer.c (c05b622c)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap/buffered-io.c (c05f3268)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpage
```
```
In fs/iomap/seek.c (c05f6c88)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (c064ba68)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/file.c (c06cb990)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_do_readpage
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
In fs/buffer.c (c0000000004e23a8)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap/buffered-io.c (c00000000053ad60)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpage
```
```
In fs/iomap/seek.c (c00000000053efe4)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (c0000000005b05a8)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/file.c (c000000000657b78)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_do_readpage
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
In fs/buffer.c (ffffffe000294f8c)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap/buffered-io.c (ffffffe0002c7f48)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpage
```
```
In fs/iomap/seek.c (ffffffe0002ca744)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffe000310d1a)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/file.c (ffffffe00037aa92)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_do_readpage
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
In fs/buffer.c (ffffffff8131bff1)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap/buffered-io.c (ffffffff8135bc85)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpage
```
```
In fs/iomap/seek.c (ffffffff8135eb57)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813ad39f)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/file.c (ffffffff8142499d)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In fs/buffer.c (ffffffff8130cb91)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap/buffered-io.c (ffffffff8134c925)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpage
```
```
In fs/iomap/seek.c (ffffffff8134f7f7)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff8139de2f)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/file.c (ffffffff8141541d)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In fs/buffer.c (ffffffff81319ac1)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap/buffered-io.c (ffffffff81359755)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpage
```
```
In fs/iomap/seek.c (ffffffff8135c627)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813aabff)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/file.c (ffffffff81420b3d)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In fs/buffer.c (ffffffff8132b77c)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/iomap/buffered-io.c (ffffffff8136ce50)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpage
```
```
In fs/iomap/seek.c (ffffffff8136fd64)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813bf54a)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/fuse/file.c (ffffffff81437933)
Location: include/linux/pagemap.h:434
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
</details>
</li>
</ul>

## Differences
