# Function: <code>__bpf_trace_io_uring_complete</code>

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
void __bpf_trace_io_uring_complete(void *__data, void *ctx, u64 user_data, long int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137ae00)
Location: include/trace/events/io_uring.h:295
Inline: False
```
**Symbols:**

```
ffffffff8137ae00-ffffffff8137ae0b: __bpf_trace_io_uring_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_io_uring_complete(void *__data, void *ctx, u64 user_data, long int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81389130)
Location: include/trace/events/io_uring.h:295
Inline: False
```
**Symbols:**

```
ffffffff81389130-ffffffff8138913b: __bpf_trace_io_uring_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_io_uring_complete(void *__data, void *ctx, u64 user_data, long int res, unsigned int cflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81390240)
Location: include/trace/events/io_uring.h:296
Inline: False
```
**Symbols:**

```
ffffffff81390240-ffffffff8139024e: __bpf_trace_io_uring_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_io_uring_complete(void *__data, void *ctx, u64 user_data, int res, unsigned int cflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813dd950)
Location: include/trace/events/io_uring.h:296
Inline: False
```
**Symbols:**

```
ffffffff813dd950-ffffffff813dd960: __bpf_trace_io_uring_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_io_uring_complete(void *__data, void *ctx, void *req, u64 user_data, int res, unsigned int cflags, u64 extra1, u64 extra2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c70b0)
Location: include/trace/events/io_uring.h:340
Inline: False
```
**Symbols:**

```
ffffffff816c70b0-ffffffff816c70dd: __bpf_trace_io_uring_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_io_uring_complete(void *__data, void *ctx, void *req, u64 user_data, int res, unsigned int cflags, u64 extra1, u64 extra2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81788530)
Location: include/trace/events/io_uring.h:326
Inline: False
```
**Symbols:**

```
ffffffff81788530-ffffffff8178855d: __bpf_trace_io_uring_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_io_uring_complete(void *__data, void *ctx, void *req, u64 user_data, int res, unsigned int cflags, u64 extra1, u64 extra2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817c8c10)
Location: include/trace/events/io_uring.h:326
Inline: False
```
**Symbols:**

```
ffffffff817c8c10-ffffffff817c8c3d: __bpf_trace_io_uring_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_io_uring_complete(void *__data, void *ctx, void *req, u64 user_data, int res, unsigned int cflags, u64 extra1, u64 extra2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8180d8e0)
Location: include/trace/events/io_uring.h:326
Inline: False
```
**Symbols:**

```
ffffffff8180d8e0-ffffffff8180d90d: __bpf_trace_io_uring_complete (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int cflags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long int res</code> ➡️ <code>int res</code>
</li>
</ul>
</details>
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
<b>Param added. </b>
<code>u64 extra1</code>
</li>
<li>
<b>Param added. </b>
<code>u64 extra2</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, ctx, user_data, res, cflags</code> ➡️ <code>__data, ctx, req, user_data, res, cflags, extra1, extra2</code>
</li>
</ul>
</details>
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
