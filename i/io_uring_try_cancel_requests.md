# Function: <code>io_uring_try_cancel_requests</code>

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
void io_uring_try_cancel_requests(struct io_ring_ctx *ctx, struct task_struct *task, struct files_struct *files);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81396f10)
Location: fs/io_uring.c:8918
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_cancel_task_requests
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_ring_exit_work
```
**Symbols:**

```
ffffffff81396f10-ffffffff81397106: io_uring_try_cancel_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_uring_try_cancel_requests(struct io_ring_ctx *ctx, struct task_struct *task, bool cancel_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139a180)
Location: fs/io_uring.c:8965
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_cancel
  - fs/io_uring.c:io_uring_cancel_sqpoll
  - fs/io_uring.c:io_ring_exit_work
```
**Symbols:**

```
ffffffff8139a180-ffffffff8139a561: io_uring_try_cancel_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_uring_try_cancel_requests(struct io_ring_ctx *ctx, struct task_struct *task, bool cancel_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e9920)
Location: fs/io_uring.c:9651
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_cancel_generic
  - fs/io_uring.c:io_uring_cancel_generic
  - fs/io_uring.c:io_ring_exit_work
```
**Symbols:**

```
ffffffff813e9920-ffffffff813e9c8a: io_uring_try_cancel_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_uring_try_cancel_requests(struct io_ring_ctx *ctx, struct task_struct *task, bool cancel_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e91e4f)
Location: io_uring/io_uring.c:11037
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_ring_exit_work
```
**Symbols:**

```
ffffffff81e91e4f-ffffffff81e9215e: io_uring_try_cancel_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool io_uring_try_cancel_requests(struct io_ring_ctx *ctx, struct task_struct *task, bool cancel_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178f250)
Location: io_uring/io_uring.c:3031
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_ring_exit_work
```
**Symbols:**

```
ffffffff8178f250-ffffffff8178f5f7: io_uring_try_cancel_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool io_uring_try_cancel_requests(struct io_ring_ctx *ctx, struct task_struct *task, bool cancel_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817d0550)
Location: io_uring/io_uring.c:3246
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_ring_exit_work
```
**Symbols:**

```
ffffffff817d0550-ffffffff817d0924: io_uring_try_cancel_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool io_uring_try_cancel_requests(struct io_ring_ctx *ctx, struct task_struct *task, bool cancel_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81813d70)
Location: io_uring/io_uring.c:3264
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_ring_exit_work
```
**Symbols:**

```
ffffffff81813d70-ffffffff8181421a: io_uring_try_cancel_requests (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool cancel_all</code>
</li>
<li>
<b>Param removed. </b>
<code>struct files_struct *files</code>
</li>
</ul>
</details>
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
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
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
