# Function: <code>__bpf_trace_block_rq_requeue</code>

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
void __bpf_trace_block_rq_requeue(void *__data, struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147f490)
Location: include/trace/events/block.h:74
Inline: True
```
**Symbols:**

```
ffffffff8147f490-ffffffff8147f49b: __bpf_trace_block_rq_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_rq_requeue(void *__data, struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149cb00)
Location: include/trace/events/block.h:74
Inline: True
```
**Symbols:**

```
ffffffff8149cb00-ffffffff8149cb0b: __bpf_trace_block_rq_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_block_rq_requeue(void *__data, struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cabf0)
Location: include/trace/events/block.h:74
Inline: False
```
**Symbols:**

```
ffffffff814cabf0-ffffffff814cabfb: __bpf_trace_block_rq_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_block_rq_requeue(void *__data, struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e3dd0)
Location: include/trace/events/block.h:74
Inline: False
```
**Symbols:**

```
ffffffff814e3dd0-ffffffff814e3ddb: __bpf_trace_block_rq_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_rq_requeue(void *__data, struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815426b0)
Location: include/trace/events/block.h:74
Inline: True
```
**Symbols:**

```
ffffffff815426b0-ffffffff815426bb: __bpf_trace_block_rq_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_block_rq_requeue(void *__data, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (0)
Location: include/trace/events/block.h:73
Inline: False
```
**Symbols:**

```
ffffffff8155f820-ffffffff8155f82b: __bpf_trace_block_rq_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_block_rq_requeue(void *__data, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (0)
Location: include/trace/events/block.h:73
Inline: False
```
**Symbols:**

```
ffffffff81567f80-ffffffff81567f8b: __bpf_trace_block_rq_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_block_rq_requeue(void *__data, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (0)
Location: include/trace/events/block.h:73
Inline: False
```
**Symbols:**

```
ffffffff815cc690-ffffffff815cc69b: __bpf_trace_block_rq_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_block_rq_requeue(void *__data, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (0)
Location: include/trace/events/block.h:73
Inline: False
```
**Symbols:**

```
ffffffff816783f0-ffffffff81678403: __bpf_trace_block_rq_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_block_rq_requeue(void *__data, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (0)
Location: include/trace/events/block.h:73
Inline: False
```
**Symbols:**

```
ffffffff81734890-ffffffff817348a3: __bpf_trace_block_rq_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_block_rq_requeue(void *__data, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (0)
Location: include/trace/events/block.h:73
Inline: False
```
**Symbols:**

```
ffffffff81770e30-ffffffff81770e43: __bpf_trace_block_rq_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_block_rq_requeue(void *__data, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (0)
Location: include/trace/events/block.h:75
Inline: False
```
**Symbols:**

```
ffffffff817b3080-ffffffff817b3093: __bpf_trace_block_rq_requeue (STB_LOCAL)
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
void __bpf_trace_block_rq_requeue(void *__data, struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105dffc0)
Location: include/trace/events/block.h:74
Inline: True
```
**Symbols:**

```
ffff8000105dffc0-ffff8000105dffd4: __bpf_trace_block_rq_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_block_rq_requeue(void *__data, struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078df4c)
Location: include/trace/events/block.h:74
Inline: False
```
**Symbols:**

```
c078df4c-c078df74: __bpf_trace_block_rq_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_block_rq_requeue(void *__data, struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000773d90)
Location: include/trace/events/block.h:74
Inline: False
```
**Symbols:**

```
c000000000773d90-c000000000773dbc: __bpf_trace_block_rq_requeue (STB_LOCAL)
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
void __bpf_trace_block_rq_requeue(void *__data, struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dc3b0)
Location: include/trace/events/block.h:74
Inline: False
```
**Symbols:**

```
ffffffff814dc3b0-ffffffff814dc3bb: __bpf_trace_block_rq_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_block_rq_requeue(void *__data, struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814ccd60)
Location: include/trace/events/block.h:74
Inline: False
```
**Symbols:**

```
ffffffff814ccd60-ffffffff814ccd6b: __bpf_trace_block_rq_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_block_rq_requeue(void *__data, struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d8440)
Location: include/trace/events/block.h:74
Inline: False
```
**Symbols:**

```
ffffffff814d8440-ffffffff814d844b: __bpf_trace_block_rq_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_block_rq_requeue(void *__data, struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f1050)
Location: include/trace/events/block.h:74
Inline: False
```
**Symbols:**

```
ffffffff814f1050-ffffffff814f105b: __bpf_trace_block_rq_requeue (STB_LOCAL)
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
<code>__data, q, rq</code> ➡️ <code>__data, rq</code>
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
