# Function: <code>io_poll_remove_all</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132ed92)
Location: fs/io_uring.c:1545
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81344866)
Location: fs/io_uring.c:1726
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
In fs/io_uring.c (ffffffff813854a9)
Location: fs/io_uring.c:4638
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
bool io_poll_remove_all(struct io_ring_ctx *ctx, struct task_struct *tsk, struct files_struct *files);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813914b0)
Location: fs/io_uring.c:5562
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff813914b0-ffffffff813915c3: io_poll_remove_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool io_poll_remove_all(struct io_ring_ctx *ctx, struct task_struct *tsk, bool cancel_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813975c0)
Location: fs/io_uring.c:5294
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff813975c0-ffffffff813976d4: io_poll_remove_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool io_poll_remove_all(struct io_ring_ctx *ctx, struct task_struct *tsk, bool cancel_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:5753
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff813e7180-ffffffff813e7275: io_poll_remove_all (STB_LOCAL)
ffffffff81cc5b5c-ffffffff81cc5b7a: io_poll_remove_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool io_poll_remove_all(struct io_ring_ctx *ctx, struct task_struct *tsk, bool cancel_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e90d48)
Location: io_uring/io_uring.c:7045
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff81e90d48-ffffffff81e90e6d: io_poll_remove_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool io_poll_remove_all(struct io_ring_ctx *ctx, struct task_struct *tsk, bool cancel_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff8179dbe0)
Location: io_uring/poll.c:768
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff8179dbe0-ffffffff8179dc37: io_poll_remove_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool io_poll_remove_all(struct io_ring_ctx *ctx, struct task_struct *tsk, bool cancel_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff817dede0)
Location: io_uring/poll.c:771
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff817dede0-ffffffff817dee37: io_poll_remove_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool io_poll_remove_all(struct io_ring_ctx *ctx, struct task_struct *tsk, bool cancel_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/poll.c (ffffffff818231c0)
Location: io_uring/poll.c:792
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff818231c0-ffffffff81823217: io_poll_remove_all (STB_GLOBAL)
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
In fs/io_uring.c (ffff800010402c04)
Location: fs/io_uring.c:1726
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
In fs/io_uring.c (c05d610c)
Location: fs/io_uring.c:1726
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
In fs/io_uring.c (c00000000050f4d0)
Location: fs/io_uring.c:1726
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
In fs/io_uring.c (ffffffe0002b0444)
Location: fs/io_uring.c:1726
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
In fs/io_uring.c (ffffffff8133ce46)
Location: fs/io_uring.c:1726
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
In fs/io_uring.c (ffffffff8132db10)
Location: fs/io_uring.c:1726
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
In fs/io_uring.c (ffffffff8133a916)
Location: fs/io_uring.c:1726
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
In fs/io_uring.c (ffffffff8134dad5)
Location: fs/io_uring.c:1726
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
