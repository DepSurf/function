# Function: <code>__bpf_trace_io_uring_file_get</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_io_uring_file_get(void *__data, void *ctx, int fd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137adc0)
Location: include/trace/events/io_uring.h:108
Inline: True
```
**Symbols:**

```
ffffffff8137adc0-ffffffff8137adcd: __bpf_trace_io_uring_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_io_uring_file_get(void *__data, void *ctx, int fd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813890f0)
Location: include/trace/events/io_uring.h:108
Inline: True
```
**Symbols:**

```
ffffffff813890f0-ffffffff813890fd: __bpf_trace_io_uring_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_io_uring_file_get(void *__data, void *ctx, int fd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813901f0)
Location: include/trace/events/io_uring.h:108
Inline: True
```
**Symbols:**

```
ffffffff813901f0-ffffffff813901fd: __bpf_trace_io_uring_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_io_uring_file_get(void *__data, void *ctx, int fd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813dd910)
Location: include/trace/events/io_uring.h:108
Inline: True
```
**Symbols:**

```
ffffffff813dd910-ffffffff813dd91d: __bpf_trace_io_uring_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_io_uring_file_get(void *__data, void *ctx, void *req, long long unsigned int user_data, int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c7020)
Location: include/trace/events/io_uring.h:109
Inline: False
```
**Symbols:**

```
ffffffff816c7020-ffffffff816c703d: __bpf_trace_io_uring_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_io_uring_file_get(void *__data, struct io_kiocb *req, int fd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81788470)
Location: include/trace/events/io_uring.h:108
Inline: True
```
**Symbols:**

```
ffffffff81788470-ffffffff81788487: __bpf_trace_io_uring_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_io_uring_file_get(void *__data, struct io_kiocb *req, int fd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817c8b80)
Location: include/trace/events/io_uring.h:108
Inline: True
```
**Symbols:**

```
ffffffff817c8b80-ffffffff817c8b97: __bpf_trace_io_uring_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_io_uring_file_get(void *__data, struct io_kiocb *req, int fd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8180d850)
Location: include/trace/events/io_uring.h:108
Inline: True
```
**Symbols:**

```
ffffffff8180d850-ffffffff8180d867: __bpf_trace_io_uring_file_get (STB_LOCAL)
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
<b>Param added. </b>
<code>long long unsigned int user_data</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, ctx, fd</code> ➡️ <code>__data, ctx, req, user_data, fd</code>
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
<b>Param reordered. </b>
<code>__data, ctx, req, user_data, fd</code> ➡️ <code>__data, req, fd</code>
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
