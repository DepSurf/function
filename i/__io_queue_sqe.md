# Function: <code>__io_queue_sqe</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __io_queue_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81343340)
Location: fs/io_uring.c:2398
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
```
**Symbols:**

```
ffffffff81343340-ffffffff8134356d: __io_queue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __io_queue_sqe(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81388250)
Location: fs/io_uring.c:5736
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
```
**Symbols:**

```
ffffffff81388250-ffffffff81388566: __io_queue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __io_queue_sqe(struct io_kiocb *req, struct io_comp_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81398bd0)
Location: fs/io_uring.c:6565
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:__io_req_task_submit
```
**Symbols:**

```
ffffffff81398bd0-ffffffff81398e39: __io_queue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __io_queue_sqe(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813a0350)
Location: fs/io_uring.c:6449
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:__io_req_task_submit
```
**Symbols:**

```
ffffffff813a0350-ffffffff813a045b: __io_queue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __io_queue_sqe(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813ede10)
Location: fs/io_uring.c:7016
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff813ede10-ffffffff813edf57: __io_queue_sqe (STB_LOCAL)
```
</details>
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
int __io_queue_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010405008)
Location: fs/io_uring.c:2398
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
```
**Symbols:**

```
ffff800010405008-ffff80001040525c: __io_queue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __io_queue_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d4944)
Location: fs/io_uring.c:2398
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
```
**Symbols:**

```
c05d4944-c05d4b7c: __io_queue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __io_queue_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050d9a0)
Location: fs/io_uring.c:2398
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
```
**Symbols:**

```
c00000000050d9a0-c00000000050dc80: __io_queue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __io_queue_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002af1d0)
Location: fs/io_uring.c:2398
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
```
**Symbols:**

```
ffffffe0002af1d0-ffffffe0002af3ec: __io_queue_sqe (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __io_queue_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133b920)
Location: fs/io_uring.c:2398
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
```
**Symbols:**

```
ffffffff8133b920-ffffffff8133bb4d: __io_queue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __io_queue_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132c600)
Location: fs/io_uring.c:2398
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
```
**Symbols:**

```
ffffffff8132c600-ffffffff8132c82d: __io_queue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __io_queue_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813393f0)
Location: fs/io_uring.c:2398
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
```
**Symbols:**

```
ffffffff813393f0-ffffffff8133961d: __io_queue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __io_queue_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134bc20)
Location: fs/io_uring.c:2398
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
```
**Symbols:**

```
ffffffff8134bc20-ffffffff8134be4c: __io_queue_sqe (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct io_uring_sqe *sqe</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_ring_ctx *ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct sqe_submit *s</code>
</li>
<li>
<b>Param reordered. </b>
<code>ctx, req, s</code> ➡️ <code>req, sqe</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_comp_state *cs</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct io_uring_sqe *sqe</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct io_comp_state *cs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
