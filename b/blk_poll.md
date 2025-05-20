# Function: <code>blk_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool blk_poll(struct request_queue *q, blk_qc_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813bbb90)
Location: block/blk-core.c:3328
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
ffffffff813bbb90-ffffffff813bbd11: blk_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool blk_poll(struct request_queue *q, blk_qc_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813ff9a0)
Location: block/blk-core.c:3300
Inline: True
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
ffffffff813ff9a0-ffffffff813ffb21: blk_poll (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool blk_poll(struct request_queue *q, blk_qc_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81452330)
Location: block/blk-core.c:2429
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff81452330-ffffffff8145238e: blk_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool blk_poll(struct request_queue *q, blk_qc_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81485570)
Location: block/blk-core.c:2572
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff81485570-ffffffff814855ce: blk_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int blk_poll(struct request_queue *q, blk_qc_t cookie, bool spin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a8d50)
Location: block/blk-mq.c:3436
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff814a8d50-ffffffff814a908f: blk_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int blk_poll(struct request_queue *q, blk_qc_t cookie, bool spin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d66e0)
Location: block/blk-mq.c:3471
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_iopoll
```
**Symbols:**

```
ffffffff814d66e0-ffffffff814d6a29: blk_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int blk_poll(struct request_queue *q, blk_qc_t cookie, bool spin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814efa50)
Location: block/blk-mq.c:3490
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_iopoll
```
**Symbols:**

```
ffffffff814efa50-ffffffff814efd82: blk_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int blk_poll(struct request_queue *q, blk_qc_t cookie, bool spin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff8154ee90)
Location: block/blk-mq.c:3711
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_await_one
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_iopoll
```
**Symbols:**

```
ffffffff8154ee90-ffffffff8154f192: blk_poll.part.0 (STB_LOCAL)
ffffffff8154f1a0-ffffffff8154f1c7: blk_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int blk_poll(struct request_queue *q, blk_qc_t cookie, bool spin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff8156cd40)
Location: block/blk-mq.c:3841
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:dio_await_one
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_iopoll
```
**Symbols:**

```
ffffffff8156cd40-ffffffff8156ceaf: blk_poll.part.0 (STB_LOCAL)
ffffffff8156ceb0-ffffffff8156ced7: blk_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int blk_poll(struct request_queue *q, blk_qc_t cookie, bool spin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff81574be0)
Location: block/blk-mq.c:3903
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_iopoll
```
**Symbols:**

```
ffffffff81574be0-ffffffff81574d4f: blk_poll.part.0 (STB_LOCAL)
ffffffff81574d50-ffffffff81574d77: blk_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int blk_poll(struct request_queue *q, blk_qc_t cookie, bool spin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff815d9130)
Location: block/blk-mq.c:3960
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_iopoll
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:blkdev_iopoll
  - block/fops.c:__blkdev_direct_IO_simple
  - block/blk-exec.c:blk_execute_rq
```
**Symbols:**

```
ffffffff815d9130-ffffffff815d9296: blk_poll.part.0 (STB_LOCAL)
ffffffff815d92a0-ffffffff815d92c7: blk_poll (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int blk_poll(struct request_queue *q, blk_qc_t cookie, bool spin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ed850)
Location: block/blk-mq.c:3490
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_iopoll
```
**Symbols:**

```
ffff8000105ed850-ffff8000105edb38: blk_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int blk_poll(struct request_queue *q, blk_qc_t cookie, bool spin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079b15c)
Location: block/blk-mq.c:3490
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_iopoll
```
**Symbols:**

```
c079b15c-c079b4b8: blk_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int blk_poll(struct request_queue *q, blk_qc_t cookie, bool spin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000784f20)
Location: block/blk-mq.c:3490
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_iopoll
```
**Symbols:**

```
c000000000784f20-c000000000785304: blk_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int blk_poll(struct request_queue *q, blk_qc_t cookie, bool spin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042e070)
Location: block/blk-mq.c:3490
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_iopoll
```
**Symbols:**

```
ffffffe00042e070-ffffffe00042e288: blk_poll (STB_GLOBAL)
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
int blk_poll(struct request_queue *q, blk_qc_t cookie, bool spin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e8030)
Location: block/blk-mq.c:3490
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_iopoll
  - drivers/nvme/host/core.c:__nvme_submit_sync_cmd
```
**Symbols:**

```
ffffffff814e8030-ffffffff814e8362: blk_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int blk_poll(struct request_queue *q, blk_qc_t cookie, bool spin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d85a0)
Location: block/blk-mq.c:3490
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_iopoll
  - drivers/nvme/host/core.c:__nvme_submit_sync_cmd
```
**Symbols:**

```
ffffffff814d85a0-ffffffff814d88d2: blk_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int blk_poll(struct request_queue *q, blk_qc_t cookie, bool spin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e40c0)
Location: block/blk-mq.c:3490
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_iopoll
```
**Symbols:**

```
ffffffff814e40c0-ffffffff814e43f2: blk_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int blk_poll(struct request_queue *q, blk_qc_t cookie, bool spin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fd640)
Location: block/blk-mq.c:3490
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_iopoll
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_iopoll
```
**Symbols:**

```
ffffffff814fd640-ffffffff814fd972: blk_poll (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool spin</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
