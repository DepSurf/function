# Function: <code>io_cqring_wake</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816cc1b3)
Location: io_uring/io_uring.c:2058
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_rsrc_put_work
  - io_uring/io_uring.c:io_rsrc_put_work
  - io_uring/io_uring.c:io_poll_task_func
  - io_uring/io_uring.c:io_poll_task_func
  - io_uring/io_uring.c:io_poll_check_events
  - io_uring/io_uring.c:io_poll_check_events
  - io_uring/io_uring.c:io_accept
  - io_uring/io_uring.c:io_accept
  - io_uring/io_uring.c:io_msg_ring
  - io_uring/io_uring.c:io_msg_ring
  - io_uring/io_uring.c:io_do_iopoll
  - io_uring/io_uring.c:io_do_iopoll
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:handle_prev_tw_list
  - io_uring/io_uring.c:handle_prev_tw_list
  - io_uring/io_uring.c:handle_prev_tw_list
  - io_uring/io_uring.c:handle_prev_tw_list
  - io_uring/io_uring.c:io_req_complete_post
  - io_uring/io_uring.c:io_req_complete_post
  - io_uring/io_uring.c:__io_cqring_overflow_flush
  - io_uring/io_uring.c:__io_cqring_overflow_flush
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
In io_uring/io_uring.c (ffffffff8178eeb4)
Location: io_uring/io_uring.h:244
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:io_aux_cqe
  - io_uring/io_uring.c:io_cq_unlock_post
```
```
In io_uring/rw.c (ffffffff817a4e8a)
Location: io_uring/io_uring.h:244
Inline: True
Inline callers:
  - io_uring/rw.c:io_do_iopoll
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
In io_uring/io_uring.c (ffffffff817d022b)
Location: io_uring/io_uring.h:240
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:io_aux_cqe
  - io_uring/io_uring.c:io_aux_cqe
  - io_uring/io_uring.c:io_cq_unlock_post
  - io_uring/io_uring.c:io_cq_unlock_post
```
```
In io_uring/rw.c (ffffffff817e5e4c)
Location: io_uring/io_uring.h:240
Inline: True
Inline callers:
  - io_uring/rw.c:io_do_iopoll
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
In io_uring/io_uring.c (ffffffff818134b9)
Location: io_uring/io_uring.h:241
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:io_fill_cqe_req_aux
  - io_uring/io_uring.c:io_fill_cqe_req_aux
  - io_uring/io_uring.c:io_cq_unlock_post
  - io_uring/io_uring.c:io_cq_unlock_post
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
