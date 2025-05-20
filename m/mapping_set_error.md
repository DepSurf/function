# Function: <code>mapping_set_error</code>

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
In mm/filemap.c (ffffffff8118d901)
Location: include/linux/pagemap.h:30
Inline: True
```
```
In mm/page-writeback.c (ffffffff81198513)
Location: include/linux/pagemap.h:30
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff811a0b8c)
Location: include/linux/pagemap.h:30
Inline: True
```
```
In mm/memory-failure.c (ffffffff81202290)
Location: include/linux/pagemap.h:30
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff81246cb9)
Location: include/linux/pagemap.h:30
Inline: True
```
```
In fs/mpage.c (ffffffff8124d8ad)
Location: include/linux/pagemap.h:30
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/inode.c (ffffffff8129afe2)
Location: include/linux/pagemap.h:30
Inline: True
Inline callers:
  - fs/ext4/inode.c:__writepage
```
```
In fs/ext4/page-io.c (ffffffff8129fcce)
Location: include/linux/pagemap.h:30
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
```
```
In fs/fuse/file.c (ffffffff813171c3)
Location: include/linux/pagemap.h:30
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (ffffffff811a0541)
Location: include/linux/pagemap.h:30
Inline: True
```
```
In mm/page-writeback.c (ffffffff811ad463)
Location: include/linux/pagemap.h:30
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff811b6fb5)
Location: include/linux/pagemap.h:30
Inline: True
```
```
In mm/memory-failure.c (ffffffff812267c0)
Location: include/linux/pagemap.h:30
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8126d3b4)
Location: include/linux/pagemap.h:30
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff81276007)
Location: include/linux/pagemap.h:30
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/inode.c (ffffffff812c90f2)
Location: include/linux/pagemap.h:30
Inline: True
Inline callers:
  - fs/ext4/inode.c:__writepage
```
```
In fs/ext4/page-io.c (ffffffff812ce57e)
Location: include/linux/pagemap.h:30
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
```
```
In fs/fuse/file.c (ffffffff8134bae3)
Location: include/linux/pagemap.h:30
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (ffffffff811af73a)
Location: include/linux/pagemap.h:31
Inline: True
```
```
In mm/page-writeback.c (ffffffff811bd9c3)
Location: include/linux/pagemap.h:31
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff811c75b5)
Location: include/linux/pagemap.h:31
Inline: True
```
```
In mm/memory-failure.c (ffffffff81238d90)
Location: include/linux/pagemap.h:31
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8127f899)
Location: include/linux/pagemap.h:31
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/mpage.c (ffffffff81289d02)
Location: include/linux/pagemap.h:31
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/inode.c (ffffffff812ded32)
Location: include/linux/pagemap.h:31
Inline: True
Inline callers:
  - fs/ext4/inode.c:__writepage
```
```
In fs/ext4/page-io.c (ffffffff812e436e)
Location: include/linux/pagemap.h:31
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/jbd2/commit.c (ffffffff8132dec0)
Location: include/linux/pagemap.h:31
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/file.c (ffffffff813613f3)
Location: include/linux/pagemap.h:31
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (ffffffff811b65f3)
Location: include/linux/pagemap.h:45
Inline: True
```
```
In mm/page-writeback.c (ffffffff811c5f77)
Location: include/linux/pagemap.h:45
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff811cfd27)
Location: include/linux/pagemap.h:45
Inline: True
```
```
In mm/memory-failure.c (ffffffff812451a2)
Location: include/linux/pagemap.h:45
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8128dedc)
Location: include/linux/pagemap.h:45
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff812969cd)
Location: include/linux/pagemap.h:45
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff812aa56c)
Location: include/linux/pagemap.h:45
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/inode.c (ffffffff81302d56)
Location: include/linux/pagemap.h:45
Inline: True
Inline callers:
  - fs/ext4/inode.c:__writepage
```
```
In fs/ext4/page-io.c (ffffffff8131dfc6)
Location: include/linux/pagemap.h:45
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff81378960)
Location: include/linux/pagemap.h:45
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (ffffffff811ca973)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/page-writeback.c (ffffffff811dad8d)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff811e51a3)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/memory-failure.c (ffffffff812650c2)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff812b0aeb)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff812b9c33)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff812cdd98)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/inode.c (ffffffff81327746)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/ext4/inode.c:__writepage
```
```
In fs/ext4/page-io.c (ffffffff813425d6)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff8139d800)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (ffffffff811eb9c3)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/page-writeback.c (ffffffff811fbe8d)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff812068d4)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/memory-failure.c (ffffffff812893ed)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff812d891b)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff812e27c8)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff812f8837)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (ffffffff81370466)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff813ccbdf)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (ffffffff811fc545)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/page-writeback.c (ffffffff8120e76d)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff81219496)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/memory-failure.c (ffffffff8129e33e)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff812eddf0)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff812f7434)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff8130ef25)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (ffffffff813888f7)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff813e5f0f)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (ffffffff81213c5e)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/page-writeback.c (ffffffff8121e27d)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff81228c90)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/memory-failure.c (ffffffff812b9510)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8130f5c2)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff81317a63)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff81334c56)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (ffffffff813b29d4)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff81411e81)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (ffffffff81221456)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/page-writeback.c (ffffffff8122bd1d)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff81236b30)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/memory-failure.c (ffffffff812cb406)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff81322537)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff8132a8de)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff813487dd)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (ffffffff813cba34)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff8142bb71)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (ffffffff8124f47b)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
```
```
In mm/page-writeback.c (ffffffff8125896e)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff81265dde)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/memory-failure.c (ffffffff81301736)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8135c7c5)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff8136456b)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff8138e21e)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/iomap/buffered-io.c (ffffffff813ab894)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_page_writeback
  - fs/iomap/buffered-io.c:iomap_finish_page_writeback
```
```
In fs/ext4/page-io.c (ffffffff81417b8f)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff8147b8f2)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (ffffffff81259e1b)
Location: include/linux/pagemap.h:49
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
```
```
In mm/page-writeback.c (ffffffff81262f4e)
Location: include/linux/pagemap.h:49
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff81270771)
Location: include/linux/pagemap.h:49
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/memory-failure.c (ffffffff8130d7f6)
Location: include/linux/pagemap.h:49
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8136ac65)
Location: include/linux/pagemap.h:49
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff8137156d)
Location: include/linux/pagemap.h:49
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff8139f96a)
Location: include/linux/pagemap.h:49
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/iomap/buffered-io.c (ffffffff813bc289)
Location: include/linux/pagemap.h:49
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_page_writeback
  - fs/iomap/buffered-io.c:iomap_finish_page_writeback
```
```
In fs/ext4/page-io.c (ffffffff8142b68f)
Location: include/linux/pagemap.h:49
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff814966ea)
Location: include/linux/pagemap.h:49
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (ffffffff8125e05b)
Location: include/linux/pagemap.h:54
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
```
```
In mm/page-writeback.c (ffffffff8126797e)
Location: include/linux/pagemap.h:54
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff81274d11)
Location: include/linux/pagemap.h:54
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/memory-failure.c (ffffffff81313b46)
Location: include/linux/pagemap.h:54
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff81370379)
Location: include/linux/pagemap.h:54
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff8137883d)
Location: include/linux/pagemap.h:54
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff813a66e2)
Location: include/linux/pagemap.h:54
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/iomap/buffered-io.c (ffffffff813c3767)
Location: include/linux/pagemap.h:54
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
```
```
In fs/ext4/page-io.c (ffffffff814322b3)
Location: include/linux/pagemap.h:54
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff8149b779)
Location: include/linux/pagemap.h:54
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (ffffffff8129a77b)
Location: include/linux/pagemap.h:54
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
```
```
In mm/page-writeback.c (ffffffff812a43f1)
Location: include/linux/pagemap.h:54
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff812b1fbe)
Location: include/linux/pagemap.h:54
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/memory-failure.c (ffffffff8135ee36)
Location: include/linux/pagemap.h:54
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff813beeef)
Location: include/linux/pagemap.h:54
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff813c515b)
Location: include/linux/pagemap.h:54
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff813f615c)
Location: include/linux/pagemap.h:54
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/iomap/buffered-io.c (ffffffff81413dcf)
Location: include/linux/pagemap.h:54
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
```
```
In fs/ext4/page-io.c (ffffffff81485ad6)
Location: include/linux/pagemap.h:54
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/dir.c (ffffffff814ec039)
Location: include/linux/pagemap.h:54
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_flush_time_update
```
```
In fs/fuse/file.c (ffffffff814f318f)
Location: include/linux/pagemap.h:54
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (ffffffff812f1f08)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
```
```
In mm/page-writeback.c (ffffffff812fc530)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff8130dfa1)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/memory-failure.c (ffffffff813d966a)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff81447642)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff8144c0db)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff81469d54)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/iomap/buffered-io.c (ffffffff81489a04)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
```
```
In fs/ext4/page-io.c (ffffffff81508ff8)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/dir.c (ffffffff8157ad09)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_flush_time_update
```
```
In fs/fuse/file.c (ffffffff8157deaa)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_vma_close
  - fs/fuse/file.c:fuse_vma_close
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (ffffffff8135bd75)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
```
```
In mm/page-writeback.c (ffffffff81366800)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff81379259)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/memory-failure.c (ffffffff8145f95a)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff814d6270)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff814da589)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff814fa497)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/iomap/buffered-io.c (ffffffff8151d8a7)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
```
```
In fs/ext4/page-io.c (ffffffff815a3b88)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/dir.c (ffffffff816204e9)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_flush_time_update
```
```
In fs/fuse/file.c (ffffffff81623a87)
Location: include/linux/pagemap.h:218
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_vma_close
  - fs/fuse/file.c:fuse_vma_close
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/page-writeback.c (ffffffff81398e7d)
Location: include/linux/pagemap.h:222
Inline: True
Inline callers:
  - mm/page-writeback.c:writepage_cb
```
```
In mm/vmscan.c (ffffffff813ad823)
Location: include/linux/pagemap.h:222
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/memory-failure.c (ffffffff81495b6b)
Location: include/linux/pagemap.h:222
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8150b6a2)
Location: include/linux/pagemap.h:222
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff8150ea5c)
Location: include/linux/pagemap.h:222
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_write_end_io
```
```
In fs/dax.c (ffffffff81531907)
Location: include/linux/pagemap.h:222
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/iomap/buffered-io.c (ffffffff81555b48)
Location: include/linux/pagemap.h:222
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
```
```
In fs/ext4/page-io.c (ffffffff815da618)
Location: include/linux/pagemap.h:222
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/dir.c (ffffffff81658939)
Location: include/linux/pagemap.h:222
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_flush_time_update
```
```
In fs/fuse/file.c (ffffffff8165be6a)
Location: include/linux/pagemap.h:222
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_vma_close
  - fs/fuse/file.c:fuse_vma_close
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/page-writeback.c (ffffffff813c2c7d)
Location: include/linux/pagemap.h:226
Inline: True
Inline callers:
  - mm/page-writeback.c:writepage_cb
```
```
In mm/vmscan.c (ffffffff813d6c2c)
Location: include/linux/pagemap.h:226
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/memory-failure.c (ffffffff814c5337)
Location: include/linux/pagemap.h:226
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff81540463)
Location: include/linux/pagemap.h:226
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff81543368)
Location: include/linux/pagemap.h:226
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_write_end_io
```
```
In fs/dax.c (ffffffff815667e7)
Location: include/linux/pagemap.h:226
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/iomap/buffered-io.c (ffffffff8158be26)
Location: include/linux/pagemap.h:226
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
```
```
In fs/ext4/page-io.c (ffffffff81612dd8)
Location: include/linux/pagemap.h:226
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/dir.c (ffffffff81692689)
Location: include/linux/pagemap.h:226
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_flush_time_update
```
```
In fs/fuse/file.c (ffffffff81695aaa)
Location: include/linux/pagemap.h:226
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_vma_close
  - fs/fuse/file.c:fuse_vma_close
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (ffff8000102b097c)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/page-writeback.c (ffff8000102bbe1c)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffff8000102c88b8)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/memory-failure.c (ffff80001036e8e8)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffff8000103db410)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffff8000103e6098)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffff8000104096d0)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (ffff8000104a3ac4)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffff80001050f9a0)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (c04db68c)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/page-writeback.c (c04e6938)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (c04f51f4)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In fs/buffer.c (c05b4820)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (c05bde58)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (c06659e0)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (c06cb238)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (c000000000363330)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/page-writeback.c (c000000000372ed0)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (c0000000003849bc)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/memory-failure.c (c00000000045fe1c)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (c0000000004e0700)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (c0000000004ec21c)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (c000000000514e84)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (c0000000005d0b38)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (c000000000657048)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (ffffffe0001d4c38)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/page-writeback.c (ffffffe0001dd98c)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffe0001e721c)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In fs/buffer.c (ffffffe000293c50)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffe00029b464)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffe0002b43a6)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (ffffffe000324f16)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffe00037a282)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (ffffffff81219aa6)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/page-writeback.c (ffffffff8122436d)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff8122f180)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/memory-failure.c (ffffffff812c39e6)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8131ab17)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff81322ebe)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff81340dbd)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (ffffffff813c4014)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff81424151)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (ffffffff8120ccb6)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/page-writeback.c (ffffffff8121751d)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff81222240)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/memory-failure.c (ffffffff812b4a26)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8130b6b7)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff81313a5e)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff8133179b)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (ffffffff813b4a94)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff81414bd1)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (ffffffff81217846)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/page-writeback.c (ffffffff8122210d)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff8122cf20)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/memory-failure.c (ffffffff812c17f6)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff813185e7)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff8132098e)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff8133e88d)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (ffffffff813c14a4)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff814202f1)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
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
In mm/filemap.c (ffffffff812268f6)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/page-writeback.c (ffffffff8123155d)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff8123c364)
Location: include/linux/pagemap.h:48
Inline: True
```
```
In mm/memory-failure.c (ffffffff812d22b6)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8132a1f9)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff813326ae)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff8135172e)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (ffffffff813d6604)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff814370a0)
Location: include/linux/pagemap.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_writepage_end
```
</details>
</li>
</ul>

## Differences
