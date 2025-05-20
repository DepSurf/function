# Function: <code>io_wq_current_is_worker</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81387926)
Location: fs/io-wq.h:147
Inline: True
Inline callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_cqring_ev_posted
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813982b4)
Location: fs/io-wq.h:150
Inline: True
Inline callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:io_iopoll_queue
  - fs/io_uring.c:io_cqring_ev_posted_iopoll
  - fs/io_uring.c:io_cqring_ev_posted
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
In fs/io_uring.c (ffffffff8139f33d)
Location: fs/io-wq.h:152
Inline: True
Inline callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_rw_should_reissue
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_cqring_ev_posted
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
In fs/io_uring.c (ffffffff813ed112)
Location: fs/io-wq.h:155
Inline: True
Inline callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_try_cancel_userdata
  - fs/io_uring.c:io_rw_should_reissue
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_cqring_ev_posted
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
In io_uring/io_uring.c (ffffffff816d314d)
Location: io_uring/io-wq.h:223
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_try_cancel
  - io_uring/io_uring.c:io_rw_should_reissue
  - io_uring/io_uring.c:__io_commit_cqring_flush
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
In io_uring/io_uring.c (ffffffff817888ff)
Location: io_uring/io-wq.h:78
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_signal
```
```
In io_uring/cancel.c (ffffffff8179e33b)
Location: io_uring/io-wq.h:78
Inline: True
Inline callers:
  - io_uring/cancel.c:io_try_cancel
```
```
In io_uring/rw.c (ffffffff817a306a)
Location: io_uring/io-wq.h:78
Inline: True
Inline callers:
  - io_uring/rw.c:io_rw_should_reissue
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
In io_uring/io_uring.c (ffffffff817c8fdf)
Location: io_uring/io-wq.h:79
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_signal
```
```
In io_uring/cancel.c (ffffffff817df52b)
Location: io_uring/io-wq.h:79
Inline: True
Inline callers:
  - io_uring/cancel.c:io_try_cancel
```
```
In io_uring/rw.c (ffffffff817e401d)
Location: io_uring/io-wq.h:79
Inline: True
Inline callers:
  - io_uring/rw.c:io_rw_should_reissue
```
```
In io_uring/io-wq.c (ffffffff817e7a46)
Location: io_uring/io-wq.h:79
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_stopped
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
In io_uring/io_uring.c (ffffffff8180dc17)
Location: io_uring/io-wq.h:79
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_signal
```
```
In io_uring/cancel.c (ffffffff8182397b)
Location: io_uring/io-wq.h:79
Inline: True
Inline callers:
  - io_uring/cancel.c:io_try_cancel
```
```
In io_uring/rw.c (ffffffff818280cd)
Location: io_uring/io-wq.h:79
Inline: True
Inline callers:
  - io_uring/rw.c:io_rw_should_reissue
```
```
In io_uring/io-wq.c (ffffffff8182d856)
Location: io_uring/io-wq.h:79
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_stopped
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
