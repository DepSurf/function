# Function: <code>errseq_set</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t *eseq, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff814989f0)
Location: lib/errseq.c:58
Inline: False
```
**Symbols:**

```
ffffffff814989f0-ffffffff81498a5b: errseq_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t *eseq, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff814cdc40)
Location: lib/errseq.c:58
Inline: False
```
**Symbols:**

```
ffffffff814cdc40-ffffffff814cdcaa: errseq_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t *eseq, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff814e2510)
Location: lib/errseq.c:58
Inline: False
```
**Symbols:**

```
ffffffff814e2510-ffffffff814e257a: errseq_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t *eseq, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff8150e3b0)
Location: lib/errseq.c:58
Inline: False
```
**Symbols:**

```
ffffffff8150e3b0-ffffffff8150e419: errseq_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t *eseq, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff8152c2d0)
Location: lib/errseq.c:58
Inline: False
```
**Symbols:**

```
ffffffff8152c2d0-ffffffff8152c339: errseq_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t *eseq, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff8158fc40)
Location: lib/errseq.c:58
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:page_endio
  - mm/filemap.c:__filemap_set_wb_err
  - mm/page-writeback.c:__writepage
  - mm/vmscan.c:pageout
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
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
ffffffff8158fc40-ffffffff8158fcaf: errseq_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t *eseq, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff815ac7b0)
Location: lib/errseq.c:59
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:page_endio
  - mm/filemap.c:__filemap_set_wb_err
  - mm/page-writeback.c:__writepage
  - mm/vmscan.c:pageout
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
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
ffffffff815ac7b0-ffffffff815ac81f: errseq_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t *eseq, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff815b7420)
Location: lib/errseq.c:59
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:page_endio
  - mm/filemap.c:__filemap_set_wb_err
  - mm/page-writeback.c:__writepage
  - mm/vmscan.c:pageout
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
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
ffffffff815b7420-ffffffff815b748f: errseq_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t *eseq, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff8161da50)
Location: lib/errseq.c:59
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:page_endio
  - mm/filemap.c:__filemap_set_wb_err
  - mm/page-writeback.c:__writepage
  - mm/vmscan.c:pageout
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
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
ffffffff8161da50-ffffffff8161dabf: errseq_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t *eseq, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff816eb5e0)
Location: lib/errseq.c:59
Inline: False
Direct callers:
  - mm/filemap.c:dio_warn_stale_pagecache
  - mm/filemap.c:page_endio
  - mm/filemap.c:__filemap_set_wb_err
  - mm/page-writeback.c:__writepage
  - mm/vmscan.c:pageout
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
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
ffffffff816eb5e0-ffffffff816eb66b: errseq_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t *eseq, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff817dbcf0)
Location: lib/errseq.c:59
Inline: False
Direct callers:
  - mm/filemap.c:dio_warn_stale_pagecache
  - mm/filemap.c:page_endio
  - mm/filemap.c:__filemap_set_wb_err
  - mm/page-writeback.c:__writepage
  - mm/vmscan.c:pageout
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_write_io_error
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
ffffffff817dbcf0-ffffffff817dbd7b: errseq_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t *eseq, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff8181b0b0)
Location: lib/errseq.c:59
Inline: False
Direct callers:
  - mm/filemap.c:dio_warn_stale_pagecache
  - mm/filemap.c:__filemap_set_wb_err
  - mm/page-writeback.c:writepage_cb
  - mm/vmscan.c:pageout
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:mark_buffer_write_io_error
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
ffffffff8181b0b0-ffffffff8181b13b: errseq_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t *eseq, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff818603f0)
Location: lib/errseq.c:59
Inline: False
Direct callers:
  - mm/filemap.c:dio_warn_stale_pagecache
  - mm/filemap.c:__filemap_set_wb_err
  - mm/page-writeback.c:writepage_cb
  - mm/vmscan.c:pageout
  - mm/memory-failure.c:me_pagecache_dirty
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:mark_buffer_write_io_error
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
ffffffff818603f0-ffffffff8186047b: errseq_set (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t *eseq, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffff8000106381d8)
Location: lib/errseq.c:58
Inline: False
```
**Symbols:**

```
ffff8000106381d8-ffff800010638288: errseq_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t *eseq, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (c07ddb2c)
Location: lib/errseq.c:58
Inline: False
```
**Symbols:**

```
c07ddb2c-c07ddbf0: errseq_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t *eseq, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (c0000000007de460)
Location: lib/errseq.c:58
Inline: False
```
**Symbols:**

```
c0000000007de460-c0000000007de548: errseq_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t *eseq, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffe00046501a)
Location: lib/errseq.c:58
Inline: False
```
**Symbols:**

```
ffffffe00046501a-ffffffe0004650a8: errseq_set (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t *eseq, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff815248b0)
Location: lib/errseq.c:58
Inline: False
```
**Symbols:**

```
ffffffff815248b0-ffffffff81524919: errseq_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t *eseq, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff81514b90)
Location: lib/errseq.c:58
Inline: False
```
**Symbols:**

```
ffffffff81514b90-ffffffff81514bf9: errseq_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t *eseq, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff81520940)
Location: lib/errseq.c:58
Inline: False
```
**Symbols:**

```
ffffffff81520940-ffffffff815209a9: errseq_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
errseq_t errseq_set(errseq_t *eseq, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff8153a2c0)
Location: lib/errseq.c:58
Inline: False
```
**Symbols:**

```
ffffffff8153a2c0-ffffffff8153a329: errseq_set (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
