# Function: <code>blk_mq_poll</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_poll(struct request_queue *q, blk_qc_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81421fc0)
Location: block/blk-mq.c:2628
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff81421fc0-ffffffff81422184: blk_mq_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_poll(struct request_queue *q, blk_qc_t cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81430600)
Location: block/blk-mq.c:2822
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
ffffffff81430600-ffffffff81430979: blk_mq_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_poll(struct request_queue *q, blk_qc_t cookie);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145bb30)
Location: block/blk-mq.c:2988
Inline: True
```
**Symbols:**

```
ffffffff8145bb30-ffffffff8145be5b: blk_mq_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool blk_mq_poll(struct request_queue *q, blk_qc_t cookie);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148f2b0)
Location: block/blk-mq.c:3053
Inline: True
```
**Symbols:**

```
ffffffff8148f2b0-ffffffff8148f602: blk_mq_poll (STB_LOCAL)
```
</details>
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
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_mq_poll(struct request_queue *q, blk_qc_t cookie, struct io_comp_batch *iob, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8168bd10)
Location: block/blk-mq.c:4726
Inline: False
Direct callers:
  - block/blk-core.c:bio_poll
```
**Symbols:**

```
ffffffff8168bd10-ffffffff8168be75: blk_mq_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_mq_poll(struct request_queue *q, blk_qc_t cookie, struct io_comp_batch *iob, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8174a400)
Location: block/blk-mq.c:4935
Inline: False
Direct callers:
  - block/blk-core.c:bio_poll
```
**Symbols:**

```
ffffffff8174a400-ffffffff8174a466: blk_mq_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_mq_poll(struct request_queue *q, blk_qc_t cookie, struct io_comp_batch *iob, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81786b00)
Location: block/blk-mq.c:4807
Inline: False
Direct callers:
  - block/blk-core.c:bio_poll
```
**Symbols:**

```
ffffffff81786b00-ffffffff81786b46: blk_mq_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_mq_poll(struct request_queue *q, blk_qc_t cookie, struct io_comp_batch *iob, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c91e0)
Location: block/blk-mq.c:4837
Inline: False
Direct callers:
  - block/blk-core.c:bio_poll
```
**Symbols:**

```
ffffffff817c91e0-ffffffff817c9226: blk_mq_poll (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
