# Function: <code>io_tw_lock</code>

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
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e9ebe)
Location: fs/io_uring.c:1124
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_task_cancel
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
In io_uring/io_uring.c (ffffffff816cdfa0)
Location: io_uring/io_uring.c:1314
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_poll_check_events
  - io_uring/io_uring.c:io_req_task_cancel
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81790ebe)
Location: io_uring/io_uring.h:333
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_poll_issue
  - io_uring/io_uring.c:io_req_task_cancel
```
```
In io_uring/timeout.c (ffffffff81798fce)
Location: io_uring/io_uring.h:333
Inline: True
Inline callers:
  - io_uring/timeout.c:io_req_tw_fail_links
```
```
In io_uring/poll.c (ffffffff8179cfca)
Location: io_uring/io_uring.h:333
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_task_func
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817d24ae)
Location: io_uring/io_uring.h:306
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_poll_issue
  - io_uring/io_uring.c:io_req_task_cancel
```
```
In io_uring/timeout.c (ffffffff817d9e7e)
Location: io_uring/io_uring.h:306
Inline: True
Inline callers:
  - io_uring/timeout.c:io_req_tw_fail_links
```
```
In io_uring/poll.c (ffffffff817de1fa)
Location: io_uring/io_uring.h:306
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_task_func
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff818156ee)
Location: io_uring/io_uring.h:307
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_poll_issue
  - io_uring/io_uring.c:io_req_task_cancel
```
```
In io_uring/timeout.c (ffffffff8181e16e)
Location: io_uring/io_uring.h:307
Inline: True
Inline callers:
  - io_uring/timeout.c:io_req_tw_fail_links
```
```
In io_uring/poll.c (ffffffff818225a3)
Location: io_uring/io_uring.h:307
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_task_func
```
```
In io_uring/waitid.c (ffffffff8182a907)
Location: io_uring/io_uring.h:307
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid_cb
```
```
In io_uring/futex.c (ffffffff8182ee07)
Location: io_uring/io_uring.h:307
Inline: True
Inline callers:
  - io_uring/futex.c:io_futexv_complete
  - io_uring/futex.c:io_futex_complete
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
