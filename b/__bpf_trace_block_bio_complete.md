# Function: <code>__bpf_trace_block_bio_complete</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_bio_complete(void *__data, struct request_queue *q, struct bio *bio, int error);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147f4c0)
Location: include/trace/events/block.h:262
Inline: True
```
**Symbols:**

```
ffffffff8147f4c0-ffffffff8147f4cd: __bpf_trace_block_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_bio_complete(void *__data, struct request_queue *q, struct bio *bio, int error);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149cb30)
Location: include/trace/events/block.h:262
Inline: True
```
**Symbols:**

```
ffffffff8149cb30-ffffffff8149cb3d: __bpf_trace_block_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_block_bio_complete(void *__data, struct request_queue *q, struct bio *bio, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cac40)
Location: include/trace/events/block.h:262
Inline: False
```
**Symbols:**

```
ffffffff814cac40-ffffffff814cac4d: __bpf_trace_block_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_block_bio_complete(void *__data, struct request_queue *q, struct bio *bio, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e3e20)
Location: include/trace/events/block.h:262
Inline: False
```
**Symbols:**

```
ffffffff814e3e20-ffffffff814e3e2d: __bpf_trace_block_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_block_bio_complete(void *__data, struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (0)
Location: include/trace/events/block.h:261
Inline: False
```
**Symbols:**

```
ffffffff81542fe0-ffffffff81542feb: __bpf_trace_block_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_block_bio_complete(void *__data, struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155edb0)
Location: include/trace/events/block.h:233
Inline: False
```
**Symbols:**

```
ffffffff8155edb0-ffffffff8155edbb: __bpf_trace_block_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_block_bio_complete(void *__data, struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81567600)
Location: include/trace/events/block.h:233
Inline: False
```
**Symbols:**

```
ffffffff81567600-ffffffff8156760b: __bpf_trace_block_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_block_bio_complete(void *__data, struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cbd20)
Location: include/trace/events/block.h:233
Inline: False
```
**Symbols:**

```
ffffffff815cbd20-ffffffff815cbd2b: __bpf_trace_block_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_block_bio_complete(void *__data, struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81678110)
Location: include/trace/events/block.h:256
Inline: False
```
**Symbols:**

```
ffffffff81678110-ffffffff81678125: __bpf_trace_block_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_block_bio_complete(void *__data, struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817337a0)
Location: include/trace/events/block.h:256
Inline: False
```
**Symbols:**

```
ffffffff817337a0-ffffffff817337b5: __bpf_trace_block_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_block_bio_complete(void *__data, struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8176fbc0)
Location: include/trace/events/block.h:282
Inline: False
```
**Symbols:**

```
ffffffff8176fbc0-ffffffff8176fbd5: __bpf_trace_block_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_block_bio_complete(void *__data, struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b1e30)
Location: include/trace/events/block.h:284
Inline: False
```
**Symbols:**

```
ffffffff817b1e30-ffffffff817b1e45: __bpf_trace_block_bio_complete (STB_LOCAL)
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
void __bpf_trace_block_bio_complete(void *__data, struct request_queue *q, struct bio *bio, int error);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e0010)
Location: include/trace/events/block.h:262
Inline: True
```
**Symbols:**

```
ffff8000105e0010-ffff8000105e0028: __bpf_trace_block_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_block_bio_complete(void *__data, struct request_queue *q, struct bio *bio, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078e004)
Location: include/trace/events/block.h:262
Inline: False
```
**Symbols:**

```
c078e004-c078e03c: __bpf_trace_block_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_block_bio_complete(void *__data, struct request_queue *q, struct bio *bio, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000773e80)
Location: include/trace/events/block.h:262
Inline: False
```
**Symbols:**

```
c000000000773e80-c000000000773eb0: __bpf_trace_block_bio_complete (STB_LOCAL)
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
void __bpf_trace_block_bio_complete(void *__data, struct request_queue *q, struct bio *bio, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dc400)
Location: include/trace/events/block.h:262
Inline: False
```
**Symbols:**

```
ffffffff814dc400-ffffffff814dc40d: __bpf_trace_block_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_block_bio_complete(void *__data, struct request_queue *q, struct bio *bio, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814ccdb0)
Location: include/trace/events/block.h:262
Inline: False
```
**Symbols:**

```
ffffffff814ccdb0-ffffffff814ccdbd: __bpf_trace_block_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_block_bio_complete(void *__data, struct request_queue *q, struct bio *bio, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d8490)
Location: include/trace/events/block.h:262
Inline: False
```
**Symbols:**

```
ffffffff814d8490-ffffffff814d849d: __bpf_trace_block_bio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_block_bio_complete(void *__data, struct request_queue *q, struct bio *bio, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f10a0)
Location: include/trace/events/block.h:262
Inline: False
```
**Symbols:**

```
ffffffff814f10a0-ffffffff814f10ad: __bpf_trace_block_bio_complete (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int error</code>
</li>
</ul>
</details>
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
