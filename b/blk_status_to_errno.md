# Function: <code>blk_status_to_errno</code>

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
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81425703)
Location: block/blk-core.c:168
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - kernel/power/swap.c:hib_wait_io
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_end_io
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - block/bio.c:bio_endio
  - block/bio.c:submit_bio_wait_endio
```
**Symbols:**

```
ffffffff81421700-ffffffff81421728: blk_status_to_errno (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144c250)
Location: block/blk-core.c:168
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_wait_io
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_end_io
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - block/bio.c:bio_endio
  - block/bio.c:submit_bio_wait
  - block/blk-core.c:blk_update_request
```
**Symbols:**

```
ffffffff8144c250-ffffffff8144c277: blk_status_to_errno (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147d870)
Location: block/blk-core.c:241
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_wait_io
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_end_io
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - block/bio.c:bio_endio
  - block/bio.c:submit_bio_wait
  - block/blk-core.c:blk_update_request
```
**Symbols:**

```
ffffffff8147d870-ffffffff8147d897: blk_status_to_errno (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149afa0)
Location: block/blk-core.c:159
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_wait_io
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/mpage.c:mpage_end_io
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/iomap.c:iomap_read_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - block/bio.c:bio_endio
  - block/bio.c:submit_bio_wait
  - block/blk-core.c:blk_update_request
```
**Symbols:**

```
ffffffff8149afa0-ffffffff8149afc7: blk_status_to_errno (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cad50)
Location: block/blk-core.c:197
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_wait_io
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/mpage.c:mpage_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - block/bio.c:bio_endio
  - block/bio.c:submit_bio_wait
  - block/blk-core.c:blk_update_request
```
**Symbols:**

```
ffffffff814cad50-ffffffff814cad78: blk_status_to_errno (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e64e9)
Location: block/blk-core.c:200
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - kernel/power/swap.c:hib_wait_io
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/mpage.c:mpage_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - block/bio.c:bio_endio
  - block/bio.c:submit_bio_wait
```
**Symbols:**

```
ffffffff814e3f30-ffffffff814e3f58: blk_status_to_errno (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8154377a)
Location: block/blk-core.c:208
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
Direct callers:
  - kernel/power/swap.c:hib_wait_io
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio_complete
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/mpage.c:mpage_end_io
  - fs/iomap/buffered-io.c:iomap_writepage_end_bio
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - block/bio.c:submit_bio_wait
```
**Symbols:**

```
ffffffff815427c0-ffffffff815427e8: blk_status_to_errno (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8156064e)
Location: block/blk-core.c:211
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
Direct callers:
  - kernel/power/swap.c:hib_wait_io
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio_complete
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/mpage.c:mpage_end_io
  - fs/iomap/buffered-io.c:iomap_writepage_end_bio
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - block/bio.c:submit_bio_wait
  - drivers/md/md.c:super_written
```
**Symbols:**

```
ffffffff8155ee70-ffffffff8155ee98: blk_status_to_errno (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81568ca4)
Location: block/blk-core.c:212
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
Direct callers:
  - kernel/power/swap.c:hib_wait_io
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio_complete
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/mpage.c:mpage_end_io
  - fs/iomap/buffered-io.c:iomap_writepage_end_bio
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - block/bio.c:submit_bio_wait
  - drivers/md/md.c:super_written
```
**Symbols:**

```
ffffffff815676c0-ffffffff815676e8: blk_status_to_errno (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815ccf34)
Location: block/blk-core.c:207
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
Direct callers:
  - kernel/power/swap.c:hib_wait_io
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio_complete
  - fs/mpage.c:mpage_end_io
  - fs/iomap/buffered-io.c:iomap_writepage_end_bio
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:__blkdev_direct_IO_simple
  - block/bio.c:submit_bio_wait
  - drivers/md/md.c:super_written
```
**Symbols:**

```
ffffffff815cbde0-ffffffff815cbe24: blk_status_to_errno (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81676e6c)
Location: block/blk-core.c:192
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq_completion
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_completion
Direct callers:
  - kernel/power/swap.c:hib_wait_io
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - fs/mpage.c:mpage_end_io
  - fs/iomap/buffered-io.c:iomap_writepage_end_bio
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:__blkdev_direct_IO_simple
  - block/bio.c:submit_bio_wait
  - drivers/md/md.c:super_written
```
**Symbols:**

```
ffffffff81676050-ffffffff816760a4: blk_status_to_errno (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81732fd9)
Location: block/blk-core.c:190
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq_completion
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_completion
Direct callers:
  - kernel/power/swap.c:hib_wait_io
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - fs/mpage.c:mpage_end_io
  - fs/iomap/buffered-io.c:iomap_writepage_end_bio
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:__blkdev_direct_IO_simple
  - block/bio.c:submit_bio_wait
  - drivers/md/md.c:super_written
```
**Symbols:**

```
ffffffff817320b0-ffffffff81732104: blk_status_to_errno (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8176f3f6)
Location: block/blk-core.c:193
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq_completion
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_completion
Direct callers:
  - kernel/power/swap.c:hib_wait_io
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_read_end_io
  - fs/direct-io.c:dio_send_cur_page
  - fs/direct-io.c:dio_send_cur_page
  - fs/iomap/buffered-io.c:iomap_writepage_end_bio
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:__blkdev_direct_IO_simple
  - block/bio.c:submit_bio_wait
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/md/md.c:super_written
```
**Symbols:**

```
ffffffff8176e4c0-ffffffff8176e514: blk_status_to_errno (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b1666)
Location: block/blk-core.c:194
Inline: True
Inline callers:
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_rq_completion
  - block/blk-core.c:trace_event_raw_event_block_bio_complete
  - block/blk-core.c:trace_event_raw_event_block_rq_completion
Direct callers:
  - kernel/power/swap.c:hib_wait_io
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_read_end_io
  - fs/direct-io.c:dio_send_cur_page
  - fs/direct-io.c:dio_send_cur_page
  - fs/iomap/buffered-io.c:iomap_writepage_end_bio
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:__blkdev_direct_IO_simple
  - block/bio.c:submit_bio_wait
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/md/md.c:super_written
```
**Symbols:**

```
ffffffff817b06e0-ffffffff817b0734: blk_status_to_errno (STB_GLOBAL)
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
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e3bb4)
Location: block/blk-core.c:200
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/mpage.c:mpage_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - block/bio.c:bio_endio
  - block/bio.c:submit_bio_wait
```
**Symbols:**

```
ffff8000105e00a8-ffff8000105e00f8: blk_status_to_errno (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078e25c)
Location: block/blk-core.c:200
Inline: False
Direct callers:
  - kernel/power/swap.c:hib_wait_io
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/mpage.c:mpage_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - block/bio.c:bio_endio
  - block/bio.c:submit_bio_wait
  - block/blk-core.c:blk_update_request
```
**Symbols:**

```
c078e25c-c078e2cc: blk_status_to_errno (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0000000007776ec)
Location: block/blk-core.c:200
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/mpage.c:mpage_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - block/bio.c:bio_endio
  - block/bio.c:submit_bio_wait
```
**Symbols:**

```
c000000000774070-c0000000007740bc: blk_status_to_errno (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe00042559a)
Location: block/blk-core.c:200
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/mpage.c:mpage_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - block/bio.c:bio_endio
  - block/bio.c:submit_bio_wait
```
**Symbols:**

```
ffffffe00042351a-ffffffe000423562: blk_status_to_errno (STB_GLOBAL)
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
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814deac9)
Location: block/blk-core.c:200
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - kernel/power/swap.c:hib_wait_io
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/mpage.c:mpage_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - block/bio.c:bio_endio
  - block/bio.c:submit_bio_wait
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
  - drivers/nvme/host/core.c:nvme_revalidate_disk
```
**Symbols:**

```
ffffffff814dc510-ffffffff814dc538: blk_status_to_errno (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cf469)
Location: block/blk-core.c:200
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - kernel/power/swap.c:hib_wait_io
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/mpage.c:mpage_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - block/bio.c:bio_endio
  - block/bio.c:submit_bio_wait
  - drivers/nvdimm/pmem.c:pmem_rw_page
  - drivers/nvdimm/pmem.c:pmem_rw_page
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
  - drivers/nvme/host/core.c:nvme_revalidate_disk
```
**Symbols:**

```
ffffffff814ccec0-ffffffff814ccee8: blk_status_to_errno (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dab59)
Location: block/blk-core.c:200
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - kernel/power/swap.c:hib_wait_io
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/mpage.c:mpage_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - block/bio.c:bio_endio
  - block/bio.c:submit_bio_wait
```
**Symbols:**

```
ffffffff814d85a0-ffffffff814d85c8: blk_status_to_errno (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int blk_status_to_errno(blk_status_t status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f38d9)
Location: block/blk-core.c:200
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - kernel/power/swap.c:hib_wait_io
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/mpage.c:mpage_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/ext4/page-io.c:ext4_end_bio
  - block/bio.c:bio_endio
  - block/bio.c:submit_bio_wait
```
**Symbols:**

```
ffffffff814f11b0-ffffffff814f11d8: blk_status_to_errno (STB_GLOBAL)
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
