# Function: <code>__bpf_trace_block_bio_bounce</code>

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
void __bpf_trace_block_bio_bounce(void *__data, struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147f4a0)
Location: include/trace/events/block.h:225
Inline: True
```
**Symbols:**

```
ffffffff8147f4a0-ffffffff8147f4ab: __bpf_trace_block_bio_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_bio_bounce(void *__data, struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149cb10)
Location: include/trace/events/block.h:225
Inline: True
```
**Symbols:**

```
ffffffff8149cb10-ffffffff8149cb1b: __bpf_trace_block_bio_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_block_bio_bounce(void *__data, struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cac10)
Location: include/trace/events/block.h:225
Inline: False
```
**Symbols:**

```
ffffffff814cac10-ffffffff814cac1b: __bpf_trace_block_bio_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_block_bio_bounce(void *__data, struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e3df0)
Location: include/trace/events/block.h:225
Inline: False
```
**Symbols:**

```
ffffffff814e3df0-ffffffff814e3dfb: __bpf_trace_block_bio_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_block_bio_bounce(void *__data, struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (0)
Location: include/trace/events/block.h:225
Inline: False
```
**Symbols:**

```
ffffffff81542fd0-ffffffff81542fdb: __bpf_trace_block_bio_bounce (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_bio_bounce(void *__data, struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105dffd8)
Location: include/trace/events/block.h:225
Inline: True
```
**Symbols:**

```
ffff8000105dffd8-ffff8000105dffec: __bpf_trace_block_bio_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_block_bio_bounce(void *__data, struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078df8c)
Location: include/trace/events/block.h:225
Inline: False
```
**Symbols:**

```
c078df8c-c078dfb4: __bpf_trace_block_bio_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_block_bio_bounce(void *__data, struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000773df0)
Location: include/trace/events/block.h:225
Inline: False
```
**Symbols:**

```
c000000000773df0-c000000000773e1c: __bpf_trace_block_bio_bounce (STB_LOCAL)
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
void __bpf_trace_block_bio_bounce(void *__data, struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dc3d0)
Location: include/trace/events/block.h:225
Inline: False
```
**Symbols:**

```
ffffffff814dc3d0-ffffffff814dc3db: __bpf_trace_block_bio_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_block_bio_bounce(void *__data, struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814ccd80)
Location: include/trace/events/block.h:225
Inline: False
```
**Symbols:**

```
ffffffff814ccd80-ffffffff814ccd8b: __bpf_trace_block_bio_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_block_bio_bounce(void *__data, struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d8460)
Location: include/trace/events/block.h:225
Inline: False
```
**Symbols:**

```
ffffffff814d8460-ffffffff814d846b: __bpf_trace_block_bio_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_block_bio_bounce(void *__data, struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f1070)
Location: include/trace/events/block.h:225
Inline: False
```
**Symbols:**

```
ffffffff814f1070-ffffffff814f107b: __bpf_trace_block_bio_bounce (STB_LOCAL)
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
