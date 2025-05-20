# Function: <code>__bpf_trace_io_uring_submit_sqe</code>

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
void __bpf_trace_io_uring_submit_sqe(void *__data, void *ctx, u8 opcode, u64 user_data, bool force_nonblock, bool sq_thread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137acf0)
Location: include/trace/events/io_uring.h:331
Inline: False
```
**Symbols:**

```
ffffffff8137acf0-ffffffff8137ad06: __bpf_trace_io_uring_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_io_uring_submit_sqe(void *__data, void *ctx, u8 opcode, u64 user_data, bool force_nonblock, bool sq_thread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81388fc0)
Location: include/trace/events/io_uring.h:331
Inline: False
```
**Symbols:**

```
ffffffff81388fc0-ffffffff81388fd6: __bpf_trace_io_uring_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_io_uring_submit_sqe(void *__data, void *ctx, u8 opcode, u64 user_data, bool force_nonblock, bool sq_thread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813900d0)
Location: include/trace/events/io_uring.h:334
Inline: False
```
**Symbols:**

```
ffffffff813900d0-ffffffff813900e6: __bpf_trace_io_uring_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_io_uring_submit_sqe(void *__data, void *ctx, void *req, u8 opcode, u64 user_data, u32 flags, bool force_nonblock, bool sq_thread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813dd990)
Location: include/trace/events/io_uring.h:335
Inline: False
```
**Symbols:**

```
ffffffff813dd990-ffffffff813dd9ad: __bpf_trace_io_uring_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_io_uring_submit_sqe(void *__data, void *ctx, void *req, long long unsigned int user_data, u8 opcode, u32 flags, bool force_nonblock, bool sq_thread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c70e0)
Location: include/trace/events/io_uring.h:390
Inline: False
```
**Symbols:**

```
ffffffff816c70e0-ffffffff816c7112: __bpf_trace_io_uring_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_io_uring_submit_sqe(void *__data, struct io_kiocb *req, bool force_nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817884d0)
Location: include/trace/events/io_uring.h:371
Inline: False
```
**Symbols:**

```
ffffffff817884d0-ffffffff817884e8: __bpf_trace_io_uring_submit_sqe (STB_LOCAL)
```
</details>
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
<b>Param added. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, ctx, opcode, user_data, force_nonblock, sq_thread</code> ➡️ <code>__data, ctx, req, opcode, user_data, flags, force_nonblock, sq_thread</code>
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
<code>__data, ctx, req, opcode, user_data, flags, force_nonblock, sq_thread</code> ➡️ <code>__data, ctx, req, user_data, opcode, flags, force_nonblock, sq_thread</code>
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
<b>Param removed. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool sq_thread</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, ctx, req, user_data, opcode, flags, force_nonblock, sq_thread</code> ➡️ <code>__data, req, force_nonblock</code>
</li>
<li>
<b>Param type changed. </b>
<code>void *req</code> ➡️ <code>struct io_kiocb *req</code>
</li>
</ul>
</details>
</li>
</ul>
