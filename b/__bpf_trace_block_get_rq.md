# Function: <code>__bpf_trace_block_get_rq</code>

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
void __bpf_trace_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (0)
Location: include/trace/events/block.h:385
Inline: False
```
**Symbols:**

```
ffffffff81480670-ffffffff8148067d: __bpf_trace_block_get_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (0)
Location: include/trace/events/block.h:385
Inline: False
```
**Symbols:**

```
ffffffff8149d3a0-ffffffff8149d3ad: __bpf_trace_block_get_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cac60)
Location: include/trace/events/block.h:385
Inline: False
```
**Symbols:**

```
ffffffff814cac60-ffffffff814cac6d: __bpf_trace_block_get_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e3e40)
Location: include/trace/events/block.h:385
Inline: False
```
**Symbols:**

```
ffffffff814e3e40-ffffffff814e3e4d: __bpf_trace_block_get_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815426e0)
Location: include/trace/events/block.h:384
Inline: False
```
**Symbols:**

```
ffffffff815426e0-ffffffff815426ed: __bpf_trace_block_get_rq (STB_LOCAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void __bpf_trace_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (0)
Location: include/trace/events/block.h:385
Inline: False
```
**Symbols:**

```
ffff8000105e0b38-ffff8000105e0b50: __bpf_trace_block_get_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (0)
Location: include/trace/events/block.h:385
Inline: False
```
**Symbols:**

```
c078e03c-c078e054: __bpf_trace_block_get_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000773ee0)
Location: include/trace/events/block.h:385
Inline: False
```
**Symbols:**

```
c000000000773ee0-c000000000773f10: __bpf_trace_block_get_rq (STB_LOCAL)
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
void __bpf_trace_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dc420)
Location: include/trace/events/block.h:385
Inline: False
```
**Symbols:**

```
ffffffff814dc420-ffffffff814dc42d: __bpf_trace_block_get_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814ccdd0)
Location: include/trace/events/block.h:385
Inline: False
```
**Symbols:**

```
ffffffff814ccdd0-ffffffff814ccddd: __bpf_trace_block_get_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d84b0)
Location: include/trace/events/block.h:385
Inline: False
```
**Symbols:**

```
ffffffff814d84b0-ffffffff814d84bd: __bpf_trace_block_get_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f10c0)
Location: include/trace/events/block.h:385
Inline: False
```
**Symbols:**

```
ffffffff814f10c0-ffffffff814f10cd: __bpf_trace_block_get_rq (STB_LOCAL)
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
