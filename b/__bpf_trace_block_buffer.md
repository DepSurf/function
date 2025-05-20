# Function: <code>__bpf_trace_block_buffer</code>

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
void __bpf_trace_block_buffer(void *__data, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147f470)
Location: include/trace/events/block.h:15
Inline: False
```
**Symbols:**

```
ffffffff8147f470-ffffffff8147f47b: __bpf_trace_block_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_block_buffer(void *__data, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149cae0)
Location: include/trace/events/block.h:15
Inline: False
```
**Symbols:**

```
ffffffff8149cae0-ffffffff8149caeb: __bpf_trace_block_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_block_buffer(void *__data, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cabd0)
Location: include/trace/events/block.h:15
Inline: False
```
**Symbols:**

```
ffffffff814cabd0-ffffffff814cabdb: __bpf_trace_block_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_block_buffer(void *__data, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e3db0)
Location: include/trace/events/block.h:15
Inline: False
```
**Symbols:**

```
ffffffff814e3db0-ffffffff814e3dbb: __bpf_trace_block_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_buffer(void *__data, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815426a0)
Location: include/trace/events/block.h:15
Inline: True
```
**Symbols:**

```
ffffffff815426a0-ffffffff815426ab: __bpf_trace_block_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_buffer(void *__data, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155ed70)
Location: include/trace/events/block.h:15
Inline: True
```
**Symbols:**

```
ffffffff8155ed70-ffffffff8155ed7b: __bpf_trace_block_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_buffer(void *__data, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815675c0)
Location: include/trace/events/block.h:15
Inline: True
```
**Symbols:**

```
ffffffff815675c0-ffffffff815675cb: __bpf_trace_block_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_buffer(void *__data, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cbce0)
Location: include/trace/events/block.h:15
Inline: True
```
**Symbols:**

```
ffffffff815cbce0-ffffffff815cbceb: __bpf_trace_block_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_buffer(void *__data, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81678090)
Location: include/trace/events/block.h:15
Inline: True
```
**Symbols:**

```
ffffffff81678090-ffffffff816780a3: __bpf_trace_block_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_buffer(void *__data, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817336e0)
Location: include/trace/events/block.h:15
Inline: True
```
**Symbols:**

```
ffffffff817336e0-ffffffff817336f3: __bpf_trace_block_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_buffer(void *__data, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8176fb00)
Location: include/trace/events/block.h:15
Inline: True
```
**Symbols:**

```
ffffffff8176fb00-ffffffff8176fb13: __bpf_trace_block_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_block_buffer(void *__data, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b1d70)
Location: include/trace/events/block.h:16
Inline: True
```
**Symbols:**

```
ffffffff817b1d70-ffffffff817b1d83: __bpf_trace_block_buffer (STB_LOCAL)
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
void __bpf_trace_block_buffer(void *__data, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105dff90)
Location: include/trace/events/block.h:15
Inline: False
```
**Symbols:**

```
ffff8000105dff90-ffff8000105dffa4: __bpf_trace_block_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_block_buffer(void *__data, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078df14)
Location: include/trace/events/block.h:15
Inline: False
```
**Symbols:**

```
c078df14-c078df30: __bpf_trace_block_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_block_buffer(void *__data, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000773d30)
Location: include/trace/events/block.h:15
Inline: False
```
**Symbols:**

```
c000000000773d30-c000000000773d5c: __bpf_trace_block_buffer (STB_LOCAL)
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
void __bpf_trace_block_buffer(void *__data, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dc390)
Location: include/trace/events/block.h:15
Inline: False
```
**Symbols:**

```
ffffffff814dc390-ffffffff814dc39b: __bpf_trace_block_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_block_buffer(void *__data, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814ccd40)
Location: include/trace/events/block.h:15
Inline: False
```
**Symbols:**

```
ffffffff814ccd40-ffffffff814ccd4b: __bpf_trace_block_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_block_buffer(void *__data, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d8420)
Location: include/trace/events/block.h:15
Inline: False
```
**Symbols:**

```
ffffffff814d8420-ffffffff814d842b: __bpf_trace_block_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_block_buffer(void *__data, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f1030)
Location: include/trace/events/block.h:15
Inline: False
```
**Symbols:**

```
ffffffff814f1030-ffffffff814f103b: __bpf_trace_block_buffer (STB_LOCAL)
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
