# Function: <code>__traceiter_io_uring_link</code>

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
int __traceiter_io_uring_link(void *__data, void *ctx, void *req, void *target_req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813877f0)
Location: include/trace/events/io_uring.h:208
Inline: False
```
**Symbols:**

```
ffffffff813877f0-ffffffff81387841: __traceiter_io_uring_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_io_uring_link(void *__data, void *ctx, void *req, void *target_req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138e8a0)
Location: include/trace/events/io_uring.h:208
Inline: False
```
**Symbols:**

```
ffffffff8138e8a0-ffffffff8138e8ef: __traceiter_io_uring_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_io_uring_link(void *__data, void *ctx, void *req, void *target_req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813dc100)
Location: include/trace/events/io_uring.h:208
Inline: False
```
**Symbols:**

```
ffffffff813dc100-ffffffff813dc14f: __traceiter_io_uring_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_io_uring_link(void *__data, void *ctx, void *req, void *target_req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c4820)
Location: include/trace/events/io_uring.h:234
Inline: False
```
**Symbols:**

```
ffffffff816c4820-ffffffff816c487b: __traceiter_io_uring_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_io_uring_link(void *__data, struct io_kiocb *req, struct io_kiocb *target_req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81785cf0)
Location: include/trace/events/io_uring.h:223
Inline: False
```
**Symbols:**

```
ffffffff81785cf0-ffffffff81785d3f: __traceiter_io_uring_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_io_uring_link(void *__data, struct io_kiocb *req, struct io_kiocb *target_req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817c61e0)
Location: include/trace/events/io_uring.h:223
Inline: False
```
**Symbols:**

```
ffffffff817c61e0-ffffffff817c622f: __traceiter_io_uring_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_io_uring_link(void *__data, struct io_kiocb *req, struct io_kiocb *target_req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8180af00)
Location: include/trace/events/io_uring.h:223
Inline: False
```
**Symbols:**

```
ffffffff8180af00-ffffffff8180af4f: __traceiter_io_uring_link (STB_GLOBAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
<b>Param reordered. </b>
<code>__data, ctx, req, target_req</code> ➡️ <code>__data, req, target_req</code>
</li>
<li>
<b>Param type changed. </b>
<code>void *req</code> ➡️ <code>struct io_kiocb *req</code>
</li>
<li>
<b>Param type changed. </b>
<code>void *target_req</code> ➡️ <code>struct io_kiocb *target_req</code>
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
