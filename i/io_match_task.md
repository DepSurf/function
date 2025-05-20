# Function: <code>io_match_task</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool io_match_task(struct io_kiocb *head, struct task_struct *task, struct files_struct *files);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138a230)
Location: fs/io_uring.c:1066
Inline: True
Direct callers:
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_cancel_defer_files
  - fs/io_uring.c:io_cancel_task_cb
  - fs/io_uring.c:io_cancel_task_cb
  - fs/io_uring.c:io_poll_remove_all
  - fs/io_uring.c:__io_cqring_overflow_flush
  - fs/io_uring.c:io_kill_timeouts
```
**Symbols:**

```
ffffffff8138a230-ffffffff8138a298: io_match_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139a2a5)
Location: fs/io_uring.c:1110
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_cancel_task_cb
  - fs/io_uring.c:io_cancel_task_cb
  - fs/io_uring.c:io_cancel_task_cb
  - fs/io_uring.c:io_cancel_task_cb
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_poll_remove_all
  - fs/io_uring.c:io_poll_remove_all
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e5d2e)
Location: fs/io_uring.c:1205
Inline: True
Inline callers:
  - fs/io_uring.c:io_kill_timeouts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e9094d)
Location: io_uring/io_uring.c:1559
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_kill_timeouts
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff81799f0c)
Location: io_uring/timeout.c:600
Inline: True
Inline callers:
  - io_uring/timeout.c:io_kill_timeouts
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff817dafcf)
Location: io_uring/timeout.c:651
Inline: True
Inline callers:
  - io_uring/timeout.c:io_kill_timeouts
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/timeout.c (ffffffff8181f2bf)
Location: io_uring/timeout.c:645
Inline: True
Inline callers:
  - io_uring/timeout.c:io_kill_timeouts
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
</ul>
