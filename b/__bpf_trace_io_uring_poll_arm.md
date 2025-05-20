# Function: <code>__bpf_trace_io_uring_poll_arm</code>

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
In <code>4.18</code>: Absent ⚠️
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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_io_uring_poll_arm(void *__data, void *ctx, u8 opcode, u64 user_data, int mask, int events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137ad10)
Location: include/trace/events/io_uring.h:360
Inline: False
```
**Symbols:**

```
ffffffff8137ad10-ffffffff8137ad24: __bpf_trace_io_uring_poll_arm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_io_uring_poll_arm(void *__data, void *ctx, u8 opcode, u64 user_data, int mask, int events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81388fe0)
Location: include/trace/events/io_uring.h:360
Inline: False
```
**Symbols:**

```
ffffffff81388fe0-ffffffff81388ff4: __bpf_trace_io_uring_poll_arm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_io_uring_poll_arm(void *__data, void *ctx, u8 opcode, u64 user_data, int mask, int events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813900f0)
Location: include/trace/events/io_uring.h:363
Inline: False
```
**Symbols:**

```
ffffffff813900f0-ffffffff81390104: __bpf_trace_io_uring_poll_arm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_io_uring_poll_arm(void *__data, void *ctx, void *req, u8 opcode, u64 user_data, int mask, int events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813dd8f0)
Location: include/trace/events/io_uring.h:381
Inline: False
```
**Symbols:**

```
ffffffff813dd8f0-ffffffff813dd906: __bpf_trace_io_uring_poll_arm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_io_uring_poll_arm(void *__data, void *ctx, void *req, u64 user_data, u8 opcode, int mask, int events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c7160)
Location: include/trace/events/io_uring.h:440
Inline: False
```
**Symbols:**

```
ffffffff816c7160-ffffffff816c718b: __bpf_trace_io_uring_poll_arm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_io_uring_poll_arm(void *__data, struct io_kiocb *req, int mask, int events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81788570)
Location: include/trace/events/io_uring.h:417
Inline: False
```
**Symbols:**

```
ffffffff81788570-ffffffff8178858b: __bpf_trace_io_uring_poll_arm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_io_uring_poll_arm(void *__data, struct io_kiocb *req, int mask, int events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817c8c50)
Location: include/trace/events/io_uring.h:414
Inline: False
```
**Symbols:**

```
ffffffff817c8c50-ffffffff817c8c6b: __bpf_trace_io_uring_poll_arm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_io_uring_poll_arm(void *__data, struct io_kiocb *req, int mask, int events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8180d920)
Location: include/trace/events/io_uring.h:414
Inline: False
```
**Symbols:**

```
ffffffff8180d920-ffffffff8180d93b: __bpf_trace_io_uring_poll_arm (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *req</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, ctx, opcode, user_data, mask, events</code> ➡️ <code>__data, ctx, req, opcode, user_data, mask, events</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param reordered. </b>
<code>__data, ctx, req, opcode, user_data, mask, events</code> ➡️ <code>__data, ctx, req, user_data, opcode, mask, events</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void *ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 user_data</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 opcode</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, ctx, req, user_data, opcode, mask, events</code> ➡️ <code>__data, req, mask, events</code>
</li>
<li>
<b>Param type changed. </b>
<code>void *req</code> ➡️ <code>struct io_kiocb *req</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
