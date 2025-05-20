# Function: <code>__bpf_trace_io_uring_task_add</code>

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
void __bpf_trace_io_uring_task_add(void *__data, void *ctx, u8 opcode, u64 user_data, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (0)
Location: include/trace/events/io_uring.h:414
Inline: False
```
**Symbols:**

```
ffffffff8137c3f0-ffffffff8137c401: __bpf_trace_io_uring_task_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_io_uring_task_add(void *__data, void *ctx, u8 opcode, u64 user_data, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (0)
Location: include/trace/events/io_uring.h:414
Inline: False
```
**Symbols:**

```
ffffffff8138a5c0-ffffffff8138a5d1: __bpf_trace_io_uring_task_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_io_uring_task_add(void *__data, void *ctx, u8 opcode, u64 user_data, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (0)
Location: include/trace/events/io_uring.h:417
Inline: False
```
**Symbols:**

```
ffffffff81391670-ffffffff81391681: __bpf_trace_io_uring_task_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_io_uring_task_add(void *__data, void *ctx, u8 opcode, u64 user_data, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (0)
Location: include/trace/events/io_uring.h:438
Inline: False
```
**Symbols:**

```
ffffffff813df490-ffffffff813df4a1: __bpf_trace_io_uring_task_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_io_uring_task_add(void *__data, void *ctx, void *req, long long unsigned int user_data, u8 opcode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c6e70)
Location: include/trace/events/io_uring.h:485
Inline: False
```
**Symbols:**

```
ffffffff816c6e70-ffffffff816c6e94: __bpf_trace_io_uring_task_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_io_uring_task_add(void *__data, struct io_kiocb *req, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (0)
Location: include/trace/events/io_uring.h:458
Inline: False
```
**Symbols:**

```
ffffffff81789f50-ffffffff81789f67: __bpf_trace_io_uring_task_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_io_uring_task_add(void *__data, struct io_kiocb *req, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (0)
Location: include/trace/events/io_uring.h:455
Inline: False
```
**Symbols:**

```
ffffffff817ca7e0-ffffffff817ca7f7: __bpf_trace_io_uring_task_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_io_uring_task_add(void *__data, struct io_kiocb *req, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (0)
Location: include/trace/events/io_uring.h:455
Inline: False
```
**Symbols:**

```
ffffffff8180f2c0-ffffffff8180f2d7: __bpf_trace_io_uring_task_add (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *req</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, ctx, opcode, user_data, mask</code> ➡️ <code>__data, ctx, req, user_data, opcode, mask</code>
</li>
<li>
<b>Param type changed. </b>
<code>u64 user_data</code> ➡️ <code>long long unsigned int user_data</code>
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
<code>long long unsigned int user_data</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 opcode</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, ctx, req, user_data, opcode, mask</code> ➡️ <code>__data, req, mask</code>
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
