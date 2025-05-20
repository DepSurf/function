# Function: <code>io_match_task_safe</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool io_match_task_safe(struct io_kiocb *head, struct task_struct *task, bool cancel_all);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e7080)
Location: fs/io_uring.c:1238
Inline: True
Direct callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_cancel_task_cb
  - fs/io_uring.c:io_poll_remove_all
```
**Symbols:**

```
ffffffff813e7080-ffffffff813e713d: io_match_task_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool io_match_task_safe(struct io_kiocb *head, struct task_struct *task, bool cancel_all);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c8fb0)
Location: io_uring/io_uring.c:1592
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_cancel_task_cb
  - io_uring/io_uring.c:io_poll_remove_all
```
**Symbols:**

```
ffffffff816c8fb0-ffffffff816c9092: io_match_task_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool io_match_task_safe(struct io_kiocb *head, struct task_struct *task, bool cancel_all);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178d0d0)
Location: io_uring/io_uring.c:201
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_cancel_task_cb
  - io_uring/poll.c:io_poll_remove_all_table
```
**Symbols:**

```
ffffffff8178d0d0-ffffffff8178d1b2: io_match_task_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool io_match_task_safe(struct io_kiocb *head, struct task_struct *task, bool cancel_all);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817ce210)
Location: io_uring/io_uring.c:200
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_cancel_task_cb
  - io_uring/poll.c:io_poll_remove_all_table
```
**Symbols:**

```
ffffffff817ce210-ffffffff817ce2f2: io_match_task_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool io_match_task_safe(struct io_kiocb *head, struct task_struct *task, bool cancel_all);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff818114c0)
Location: io_uring/io_uring.c:213
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_cancel_task_cb
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/waitid.c:io_waitid_remove_all
  - io_uring/futex.c:io_futex_remove_all
```
**Symbols:**

```
ffffffff818114c0-ffffffff818115a2: io_match_task_safe (STB_GLOBAL)
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
