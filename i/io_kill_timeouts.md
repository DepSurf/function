# Function: <code>io_kill_timeouts</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81344806)
Location: fs/io_uring.c:520
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81385438)
Location: fs/io_uring.c:1144
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool io_kill_timeouts(struct io_ring_ctx *ctx, struct task_struct *tsk, struct files_struct *files);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81390700)
Location: fs/io_uring.c:1615
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff81390700-ffffffff813908a1: io_kill_timeouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool io_kill_timeouts(struct io_ring_ctx *ctx, struct task_struct *tsk, bool cancel_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813970e0)
Location: fs/io_uring.c:8831
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff813970e0-ffffffff8139725a: io_kill_timeouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool io_kill_timeouts(struct io_ring_ctx *ctx, struct task_struct *tsk, bool cancel_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e5ca0)
Location: fs/io_uring.c:9527
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff813e5ca0-ffffffff813e5e83: io_kill_timeouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool io_kill_timeouts(struct io_ring_ctx *ctx, struct task_struct *tsk, bool cancel_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e908ec)
Location: io_uring/io_uring.c:10911
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff81e908ec-ffffffff81e909ee: io_kill_timeouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool io_kill_timeouts(struct io_ring_ctx *ctx, struct task_struct *tsk, bool cancel_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff81799e80)
Location: io_uring/timeout.c:619
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff81799e80-ffffffff81799ffd: io_kill_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool io_kill_timeouts(struct io_ring_ctx *ctx, struct task_struct *tsk, bool cancel_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff817daf50)
Location: io_uring/timeout.c:670
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff817daf50-ffffffff817db05f: io_kill_timeouts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool io_kill_timeouts(struct io_ring_ctx *ctx, struct task_struct *tsk, bool cancel_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff8181f240)
Location: io_uring/timeout.c:664
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff8181f240-ffffffff8181f34f: io_kill_timeouts (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010402b70)
Location: fs/io_uring.c:520
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d60a0)
Location: fs/io_uring.c:520
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050f434)
Location: fs/io_uring.c:520
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002b03b4)
Location: fs/io_uring.c:520
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133cde6)
Location: fs/io_uring.c:520
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132dab6)
Location: fs/io_uring.c:520
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133a8b6)
Location: fs/io_uring.c:520
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134da76)
Location: fs/io_uring.c:520
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
