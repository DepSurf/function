# Function: <code>__bpf_trace_block_bio_remap</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bpf_trace_block_bio_remap(void *__data, struct request_queue *q, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147f500)
Location: include/trace/events/block.h:559
Inline: False
```
**Symbols:**

```
ffffffff8147f500-ffffffff8147f50d: __bpf_trace_block_bio_remap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_block_bio_remap(void *__data, struct request_queue *q, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149cb70)
Location: include/trace/events/block.h:559
Inline: False
```
**Symbols:**

```
ffffffff8149cb70-ffffffff8149cb7d: __bpf_trace_block_bio_remap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_block_bio_remap(void *__data, struct request_queue *q, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cac90)
Location: include/trace/events/block.h:559
Inline: False
```
**Symbols:**

```
ffffffff814cac90-ffffffff814cac9d: __bpf_trace_block_bio_remap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_block_bio_remap(void *__data, struct request_queue *q, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e3e70)
Location: include/trace/events/block.h:559
Inline: False
```
**Symbols:**

```
ffffffff814e3e70-ffffffff814e3e7d: __bpf_trace_block_bio_remap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_bio_remap(void *__data, struct request_queue *q, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81542710)
Location: include/trace/events/block.h:558
Inline: True
```
**Symbols:**

```
ffffffff81542710-ffffffff8154271d: __bpf_trace_block_bio_remap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_bio_remap(void *__data, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155eda0)
Location: include/trace/events/block.h:456
Inline: True
```
**Symbols:**

```
ffffffff8155eda0-ffffffff8155edad: __bpf_trace_block_bio_remap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_bio_remap(void *__data, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815675f0)
Location: include/trace/events/block.h:456
Inline: True
```
**Symbols:**

```
ffffffff815675f0-ffffffff815675fd: __bpf_trace_block_bio_remap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_bio_remap(void *__data, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cbd10)
Location: include/trace/events/block.h:456
Inline: True
```
**Symbols:**

```
ffffffff815cbd10-ffffffff815cbd1d: __bpf_trace_block_bio_remap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_bio_remap(void *__data, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff816780f0)
Location: include/trace/events/block.h:479
Inline: True
```
**Symbols:**

```
ffffffff816780f0-ffffffff81678109: __bpf_trace_block_bio_remap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_bio_remap(void *__data, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81733770)
Location: include/trace/events/block.h:479
Inline: True
```
**Symbols:**

```
ffffffff81733770-ffffffff81733789: __bpf_trace_block_bio_remap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_bio_remap(void *__data, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8176fb90)
Location: include/trace/events/block.h:505
Inline: True
```
**Symbols:**

```
ffffffff8176fb90-ffffffff8176fba9: __bpf_trace_block_bio_remap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_bio_remap(void *__data, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b1e00)
Location: include/trace/events/block.h:507
Inline: True
```
**Symbols:**

```
ffffffff817b1e00-ffffffff817b1e19: __bpf_trace_block_bio_remap (STB_LOCAL)
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
void __bpf_trace_block_bio_remap(void *__data, struct request_queue *q, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e0078)
Location: include/trace/events/block.h:559
Inline: False
```
**Symbols:**

```
ffff8000105e0078-ffff8000105e0090: __bpf_trace_block_bio_remap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_block_bio_remap(void *__data, struct request_queue *q, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078e0fc)
Location: include/trace/events/block.h:559
Inline: False
```
**Symbols:**

```
c078e0fc-c078e13c: __bpf_trace_block_bio_remap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_block_bio_remap(void *__data, struct request_queue *q, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000773f70)
Location: include/trace/events/block.h:559
Inline: False
```
**Symbols:**

```
c000000000773f70-c000000000773f9c: __bpf_trace_block_bio_remap (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_trace_block_bio_remap(void *__data, struct request_queue *q, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dc450)
Location: include/trace/events/block.h:559
Inline: False
```
**Symbols:**

```
ffffffff814dc450-ffffffff814dc45d: __bpf_trace_block_bio_remap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_block_bio_remap(void *__data, struct request_queue *q, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cce00)
Location: include/trace/events/block.h:559
Inline: False
```
**Symbols:**

```
ffffffff814cce00-ffffffff814cce0d: __bpf_trace_block_bio_remap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_block_bio_remap(void *__data, struct request_queue *q, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d84e0)
Location: include/trace/events/block.h:559
Inline: False
```
**Symbols:**

```
ffffffff814d84e0-ffffffff814d84ed: __bpf_trace_block_bio_remap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_block_bio_remap(void *__data, struct request_queue *q, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f10f0)
Location: include/trace/events/block.h:559
Inline: False
```
**Symbols:**

```
ffffffff814f10f0-ffffffff814f10fd: __bpf_trace_block_bio_remap (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, q, bio, dev, from</code> ➡️ <code>__data, bio, dev, from</code>
</li>
</ul>
</details>
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
