# Function: <code>__filemap_set_wb_err</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b65f3)
Location: mm/filemap.c:581
Inline: True
Direct callers:
  - mm/page-writeback.c:__writepage
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/ext4/inode.c:__writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff811b6920-ffffffff811b698d: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ca973)
Location: mm/filemap.c:675
Inline: True
Direct callers:
  - mm/page-writeback.c:__writepage
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/ext4/inode.c:__writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff811cac70-ffffffff811cace0: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811eb9c3)
Location: mm/filemap.c:675
Inline: True
Direct callers:
  - mm/page-writeback.c:__writepage
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/dax.c:dax_writeback_mapping_range
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff811ebed0-ffffffff811ebf40: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fc545)
Location: mm/filemap.c:652
Inline: True
Direct callers:
  - mm/page-writeback.c:__writepage
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/dax.c:dax_writeback_mapping_range
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff811fc9b0-ffffffff811fca1d: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81213c5e)
Location: mm/filemap.c:691
Inline: True
Direct callers:
  - mm/page-writeback.c:__writepage
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/dax.c:dax_writeback_mapping_range
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff81214460-ffffffff812144cd: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81221456)
Location: mm/filemap.c:700
Inline: True
Direct callers:
  - mm/page-writeback.c:__writepage
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/dax.c:dax_writeback_mapping_range
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff81221c90-ffffffff81221cfd: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124eda0)
Location: mm/filemap.c:678
Inline: False
Direct callers:
  - mm/filemap.c:page_endio
  - mm/page-writeback.c:__writepage
  - mm/vmscan.c:pageout
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/dax.c:dax_writeback_mapping_range
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_page_writeback
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff8124eda0-ffffffff8124ee0d: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81258f60)
Location: mm/filemap.c:679
Inline: False
Direct callers:
  - mm/filemap.c:page_endio
  - mm/page-writeback.c:__writepage
  - mm/vmscan.c:pageout
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/dax.c:dax_writeback_mapping_range
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_page_writeback
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff81258f60-ffffffff81258fb5: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125d250)
Location: mm/filemap.c:710
Inline: False
Direct callers:
  - mm/filemap.c:page_endio
  - mm/page-writeback.c:__writepage
  - mm/vmscan.c:pageout
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/dax.c:dax_writeback_mapping_range
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff8125d250-ffffffff8125d2a5: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812991a0)
Location: mm/filemap.c:728
Inline: False
Direct callers:
  - mm/filemap.c:page_endio
  - mm/page-writeback.c:__writepage
  - mm/vmscan.c:pageout
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/dax.c:dax_writeback_mapping_range
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/dir.c:fuse_flush_time_update
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff812991a0-ffffffff812991f5: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812ef9c0)
Location: mm/filemap.c:697
Inline: False
Direct callers:
  - mm/filemap.c:page_endio
  - mm/page-writeback.c:__writepage
  - mm/vmscan.c:pageout
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/dax.c:dax_writeback_mapping_range
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/dir.c:fuse_flush_time_update
  - fs/fuse/file.c:fuse_vma_close
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff812ef9c0-ffffffff812efa31: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135a650)
Location: mm/filemap.c:692
Inline: False
Direct callers:
  - mm/filemap.c:page_endio
  - mm/page-writeback.c:__writepage
  - mm/vmscan.c:pageout
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/dax.c:dax_writeback_mapping_range
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/dir.c:fuse_flush_time_update
  - fs/fuse/file.c:fuse_vma_close
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff8135a650-ffffffff8135a6c1: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138c090)
Location: mm/filemap.c:699
Inline: False
Direct callers:
  - mm/page-writeback.c:writepage_cb
  - mm/vmscan.c:pageout
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_write_end_io
  - fs/dax.c:dax_writeback_mapping_range
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/dir.c:fuse_flush_time_update
  - fs/fuse/file.c:fuse_vma_close
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff8138c090-ffffffff8138c101: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b5c00)
Location: mm/filemap.c:694
Inline: False
Direct callers:
  - mm/page-writeback.c:writepage_cb
  - mm/vmscan.c:pageout
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_write_end_io
  - fs/dax.c:dax_writeback_mapping_range
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/dir.c:fuse_flush_time_update
  - fs/fuse/file.c:fuse_vma_close
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff813b5c00-ffffffff813b5c71: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102ae8f8)
Location: mm/filemap.c:700
Inline: True
Direct callers:
  - mm/page-writeback.c:__writepage
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/dax.c:dax_writeback_mapping_range
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffff8000102ae8f8-ffff8000102ae9b0: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04db68c)
Location: mm/filemap.c:700
Inline: True
Direct callers:
  - mm/page-writeback.c:__writepage
  - mm/vmscan.c:shrink_page_list
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
c04dbbbc-c04dbc60: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000363330)
Location: mm/filemap.c:700
Inline: True
Direct callers:
  - mm/page-writeback.c:__writepage
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/dax.c:dax_writeback_mapping_range
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
c000000000363d10-c000000000363df4: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d4c38)
Location: mm/filemap.c:700
Inline: True
Direct callers:
  - mm/page-writeback.c:__writepage
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/dax.c:dax_writeback_mapping_range
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffe0001d50de-ffffffe0001d5172: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219aa6)
Location: mm/filemap.c:700
Inline: True
Direct callers:
  - mm/page-writeback.c:__writepage
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/dax.c:dax_writeback_mapping_range
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff8121a2e0-ffffffff8121a34d: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120ccb6)
Location: mm/filemap.c:700
Inline: True
Direct callers:
  - mm/page-writeback.c:__writepage
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/dax.c:dax_writeback_mapping_range
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff8120d4f0-ffffffff8120d55d: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81217846)
Location: mm/filemap.c:700
Inline: True
Direct callers:
  - mm/page-writeback.c:__writepage
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/dax.c:dax_writeback_mapping_range
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff81218080-ffffffff812180ed: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __filemap_set_wb_err(struct address_space *mapping, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812268f6)
Location: mm/filemap.c:700
Inline: True
Direct callers:
  - mm/page-writeback.c:__writepage
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/buffer.c:mark_buffer_write_io_error
  - fs/mpage.c:__mpage_writepage
  - fs/dax.c:dax_writeback_mapping_range
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff81227140-ffffffff812271bd: __filemap_set_wb_err (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
