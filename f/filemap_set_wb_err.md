# Function: <code>filemap_set_wb_err</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b65f3)
Location: include/linux/fs.h:2593
Inline: True
```
```
In mm/page-writeback.c (ffffffff811c5f82)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff811cfd27)
Location: include/linux/fs.h:2593
Inline: True
```
```
In mm/memory-failure.c (ffffffff812451a2)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8128dedc)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff81296e6b)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff812aa56c)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/inode.c (ffffffff81302d61)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - fs/ext4/inode.c:__writepage
```
```
In fs/ext4/page-io.c (ffffffff8131dfd6)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff81378960)
Location: include/linux/fs.h:2593
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
Location: include/linux/fs.h:2654
Inline: True
```
```
In mm/page-writeback.c (ffffffff811dad98)
Location: include/linux/fs.h:2654
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff811e51a3)
Location: include/linux/fs.h:2654
Inline: True
```
```
In mm/memory-failure.c (ffffffff812650c2)
Location: include/linux/fs.h:2654
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff812b0aeb)
Location: include/linux/fs.h:2654
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff812ba199)
Location: include/linux/fs.h:2654
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff812cdd98)
Location: include/linux/fs.h:2654
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/inode.c (ffffffff81327751)
Location: include/linux/fs.h:2654
Inline: True
Inline callers:
  - fs/ext4/inode.c:__writepage
```
```
In fs/ext4/page-io.c (ffffffff813425e6)
Location: include/linux/fs.h:2654
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff8139d800)
Location: include/linux/fs.h:2654
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
Location: include/linux/fs.h:2677
Inline: True
```
```
In mm/page-writeback.c (ffffffff811fbe98)
Location: include/linux/fs.h:2677
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff812068d4)
Location: include/linux/fs.h:2677
Inline: True
```
```
In mm/memory-failure.c (ffffffff812893ed)
Location: include/linux/fs.h:2677
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff812d891b)
Location: include/linux/fs.h:2677
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff812e2cfb)
Location: include/linux/fs.h:2677
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff812f8837)
Location: include/linux/fs.h:2677
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (ffffffff81370476)
Location: include/linux/fs.h:2677
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff813ccbdf)
Location: include/linux/fs.h:2677
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
Location: include/linux/fs.h:2761
Inline: True
```
```
In mm/page-writeback.c (ffffffff8120e778)
Location: include/linux/fs.h:2761
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff81219496)
Location: include/linux/fs.h:2761
Inline: True
```
```
In mm/memory-failure.c (ffffffff8129e33e)
Location: include/linux/fs.h:2761
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff812eddf0)
Location: include/linux/fs.h:2761
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff812f795d)
Location: include/linux/fs.h:2761
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff8130ef25)
Location: include/linux/fs.h:2761
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (ffffffff81388907)
Location: include/linux/fs.h:2761
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff813e5f0f)
Location: include/linux/fs.h:2761
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
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
Location: include/linux/fs.h:2764
Inline: True
```
```
In mm/page-writeback.c (ffffffff8121e288)
Location: include/linux/fs.h:2764
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff81228c90)
Location: include/linux/fs.h:2764
Inline: True
```
```
In mm/memory-failure.c (ffffffff812b9510)
Location: include/linux/fs.h:2764
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8130f5c2)
Location: include/linux/fs.h:2764
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff81317f99)
Location: include/linux/fs.h:2764
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff81334c56)
Location: include/linux/fs.h:2764
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (ffffffff813b29e4)
Location: include/linux/fs.h:2764
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff81411e81)
Location: include/linux/fs.h:2764
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
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
Location: include/linux/fs.h:2799
Inline: True
```
```
In mm/page-writeback.c (ffffffff8122bd28)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff81236b30)
Location: include/linux/fs.h:2799
Inline: True
```
```
In mm/memory-failure.c (ffffffff812cb406)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff81322537)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff8132ae0f)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff813487dd)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (ffffffff813cba44)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff8142bb71)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
In mm/filemap.c (ffff8000102b097c)
Location: include/linux/fs.h:2799
Inline: True
```
```
In mm/page-writeback.c (ffff8000102bbe34)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffff8000102c88b8)
Location: include/linux/fs.h:2799
Inline: True
```
```
In mm/memory-failure.c (ffff80001036e8e8)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffff8000103db410)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffff8000103e648c)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffff8000104096d0)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (ffff8000104a3af0)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffff80001050f9a0)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
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
Location: include/linux/fs.h:2799
Inline: True
```
```
In mm/page-writeback.c (c04e6948)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (c04f51f4)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In fs/buffer.c (c05b4820)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (c05be0d4)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/page-io.c (c06659e8)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (c06cb238)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
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
Location: include/linux/fs.h:2799
Inline: True
```
```
In mm/page-writeback.c (c000000000372f00)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (c0000000003849bc)
Location: include/linux/fs.h:2799
Inline: True
```
```
In mm/memory-failure.c (c00000000045fe1c)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (c0000000004e0700)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (c0000000004ec790)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (c000000000514e84)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (c0000000005d0b80)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (c000000000657048)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
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
Location: include/linux/fs.h:2799
Inline: True
```
```
In mm/page-writeback.c (ffffffe0001dd99e)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffe0001e721c)
Location: include/linux/fs.h:2799
Inline: True
```
```
In fs/buffer.c (ffffffe000293c50)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffe00029b862)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffe0002b43a6)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (ffffffe000324f18)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffe00037a282)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
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
Location: include/linux/fs.h:2799
Inline: True
```
```
In mm/page-writeback.c (ffffffff81224378)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff8122f180)
Location: include/linux/fs.h:2799
Inline: True
```
```
In mm/memory-failure.c (ffffffff812c39e6)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8131ab17)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff813233ef)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff81340dbd)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (ffffffff813c4024)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff81424151)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
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
Location: include/linux/fs.h:2799
Inline: True
```
```
In mm/page-writeback.c (ffffffff81217528)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff81222240)
Location: include/linux/fs.h:2799
Inline: True
```
```
In mm/memory-failure.c (ffffffff812b4a26)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8130b6b7)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff81313f8f)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff8133179b)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (ffffffff813b4aa4)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff81414bd1)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
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
Location: include/linux/fs.h:2799
Inline: True
```
```
In mm/page-writeback.c (ffffffff81222118)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff8122cf20)
Location: include/linux/fs.h:2799
Inline: True
```
```
In mm/memory-failure.c (ffffffff812c17f6)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff813185e7)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff81320ebf)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff8133e88d)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (ffffffff813c14b4)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff814202f1)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
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
Location: include/linux/fs.h:2799
Inline: True
```
```
In mm/page-writeback.c (ffffffff81231568)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - mm/page-writeback.c:__writepage
```
```
In mm/vmscan.c (ffffffff8123c364)
Location: include/linux/fs.h:2799
Inline: True
```
```
In mm/memory-failure.c (ffffffff812d22b6)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - mm/memory-failure.c:me_pagecache_dirty
```
```
In fs/buffer.c (ffffffff8132a1f9)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/mpage.c (ffffffff81332bf8)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff8135172e)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/ext4/page-io.c (ffffffff813d6614)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/fuse/file.c (ffffffff814370a0)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
</details>
</li>
</ul>

## Differences
