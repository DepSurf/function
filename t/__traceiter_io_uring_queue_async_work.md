# Function: <code>__traceiter_io_uring_queue_async_work</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_io_uring_queue_async_work(void *__data, void *ctx, int rw, void *req, struct io_wq_work *work, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81387720)
Location: include/trace/events/io_uring.h:137
Inline: False
```
**Symbols:**

```
ffffffff81387720-ffffffff8138778b: __traceiter_io_uring_queue_async_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_io_uring_queue_async_work(void *__data, void *ctx, int rw, void *req, struct io_wq_work *work, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138e7e0)
Location: include/trace/events/io_uring.h:137
Inline: False
```
**Symbols:**

```
ffffffff8138e7e0-ffffffff8138e849: __traceiter_io_uring_queue_async_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_io_uring_queue_async_work(void *__data, void *ctx, int rw, void *req, struct io_wq_work *work, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813dc040)
Location: include/trace/events/io_uring.h:137
Inline: False
```
**Symbols:**

```
ffffffff813dc040-ffffffff813dc0a9: __traceiter_io_uring_queue_async_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_io_uring_queue_async_work(void *__data, void *ctx, void *req, long long unsigned int user_data, u8 opcode, unsigned int flags, struct io_wq_work *work, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c4710)
Location: include/trace/events/io_uring.h:146
Inline: False
```
**Symbols:**

```
ffffffff816c4710-ffffffff816c47a8: __traceiter_io_uring_queue_async_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_io_uring_queue_async_work(void *__data, struct io_kiocb *req, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81785c30)
Location: include/trace/events/io_uring.h:140
Inline: False
```
**Symbols:**

```
ffffffff81785c30-ffffffff81785c7f: __traceiter_io_uring_queue_async_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_io_uring_queue_async_work(void *__data, struct io_kiocb *req, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817c6100)
Location: include/trace/events/io_uring.h:140
Inline: False
```
**Symbols:**

```
ffffffff817c6100-ffffffff817c614f: __traceiter_io_uring_queue_async_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_io_uring_queue_async_work(void *__data, struct io_kiocb *req, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8180ae20)
Location: include/trace/events/io_uring.h:140
Inline: False
```
**Symbols:**

```
ffffffff8180ae20-ffffffff8180ae6f: __traceiter_io_uring_queue_async_work (STB_GLOBAL)
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
<code>long long unsigned int user_data</code>
</li>
<li>
<b>Param added. </b>
<code>u8 opcode</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, ctx, rw, req, work, flags</code> ➡️ <code>__data, ctx, req, user_data, opcode, flags, work, rw</code>
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
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_wq_work *work</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, ctx, req, user_data, opcode, flags, work, rw</code> ➡️ <code>__data, req, rw</code>
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
