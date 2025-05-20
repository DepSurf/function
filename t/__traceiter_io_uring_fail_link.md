# Function: <code>__traceiter_io_uring_fail_link</code>

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
int __traceiter_io_uring_fail_link(void *__data, void *req, void *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813878a0)
Location: include/trace/events/io_uring.h:268
Inline: False
```
**Symbols:**

```
ffffffff813878a0-ffffffff813878e7: __traceiter_io_uring_fail_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_io_uring_fail_link(void *__data, void *req, void *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138e940)
Location: include/trace/events/io_uring.h:268
Inline: False
```
**Symbols:**

```
ffffffff8138e940-ffffffff8138e985: __traceiter_io_uring_fail_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_io_uring_fail_link(void *__data, void *req, void *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813dc1a0)
Location: include/trace/events/io_uring.h:268
Inline: False
```
**Symbols:**

```
ffffffff813dc1a0-ffffffff813dc1e5: __traceiter_io_uring_fail_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_io_uring_fail_link(void *__data, void *ctx, void *req, long long unsigned int user_data, u8 opcode, void *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c48d0)
Location: include/trace/events/io_uring.h:297
Inline: False
```
**Symbols:**

```
ffffffff816c48d0-ffffffff816c4952: __traceiter_io_uring_fail_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_io_uring_fail_link(void *__data, struct io_kiocb *req, struct io_kiocb *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81785db0)
Location: include/trace/events/io_uring.h:283
Inline: False
```
**Symbols:**

```
ffffffff81785db0-ffffffff81785dff: __traceiter_io_uring_fail_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_io_uring_fail_link(void *__data, struct io_kiocb *req, struct io_kiocb *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817c62c0)
Location: include/trace/events/io_uring.h:283
Inline: False
```
**Symbols:**

```
ffffffff817c62c0-ffffffff817c630f: __traceiter_io_uring_fail_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_io_uring_fail_link(void *__data, struct io_kiocb *req, struct io_kiocb *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8180afe0)
Location: include/trace/events/io_uring.h:283
Inline: False
```
**Symbols:**

```
ffffffff8180afe0-ffffffff8180b02f: __traceiter_io_uring_fail_link (STB_GLOBAL)
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
<code>void *ctx</code>
</li>
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
<code>__data, req, link</code> ➡️ <code>__data, ctx, req, user_data, opcode, link</code>
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
<code>__data, ctx, req, user_data, opcode, link</code> ➡️ <code>__data, req, link</code>
</li>
<li>
<b>Param type changed. </b>
<code>void *req</code> ➡️ <code>struct io_kiocb *req</code>
</li>
<li>
<b>Param type changed. </b>
<code>void *link</code> ➡️ <code>struct io_kiocb *link</code>
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
