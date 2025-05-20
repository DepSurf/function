# Function: <code>req_ref_put_and_test</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81395095)
Location: fs/io_uring.c:1531
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_work
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_async_cancel
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_remove_waitqs
  - fs/io_uring.c:io_poll_double_wake
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:io_poll_remove_double
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_req_complete_failed
  - fs/io_uring.c:io_req_complete_post
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
In fs/io_uring.c (ffffffff813e5db2)
Location: fs/io_uring.c:1148
Inline: True
Inline callers:
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_req_task_link_timeout
  - fs/io_uring.c:io_req_task_link_timeout
  - fs/io_uring.c:io_wq_free_work
  - fs/io_uring.c:io_wq_free_work
  - fs/io_uring.c:io_timeout_cancel
  - fs/io_uring.c:io_timeout_cancel
  - fs/io_uring.c:io_poll_double_wake
  - fs/io_uring.c:io_poll_double_wake
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:io_poll_remove_double
  - fs/io_uring.c:io_poll_remove_double
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_disarm_next
  - fs/io_uring.c:io_disarm_next
  - fs/io_uring.c:io_disarm_next
  - fs/io_uring.c:io_disarm_next
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:__io_commit_cqring_flush
  - fs/io_uring.c:__io_commit_cqring_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff8167c106)
Location: block/blk.h:473
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff816879d7)
Location: block/blk.h:473
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_free_request
```
```
In io_uring/io_uring.c (ffffffff816d2b0d)
Location: io_uring/io_uring.c:1338
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_queue_linked_timeout
  - io_uring/io_uring.c:io_queue_linked_timeout
  - io_uring/io_uring.c:io_req_task_link_timeout
  - io_uring/io_uring.c:io_req_task_link_timeout
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_req_complete_put
  - io_uring/io_uring.c:__io_req_complete_put
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81738986)
Location: block/blk.h:478
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff81745d6c)
Location: block/blk.h:478
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_free_request
```
```
In io_uring/io_uring.c (ffffffff81790805)
Location: io_uring/refs.h:20
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_req_complete_post
```
```
In io_uring/timeout.c (ffffffff81799e1d)
Location: io_uring/refs.h:20
Inline: True
Inline callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_req_task_link_timeout
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81774fc6)
Location: block/blk.h:507
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff8178257c)
Location: block/blk.h:507
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_free_request
```
```
In io_uring/io_uring.c (ffffffff817d1a15)
Location: io_uring/refs.h:20
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_req_complete_post
```
```
In io_uring/timeout.c (ffffffff817daeed)
Location: io_uring/refs.h:20
Inline: True
Inline callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_req_task_link_timeout
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff817b72ed)
Location: block/blk.h:503
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff817c491c)
Location: block/blk.h:503
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_free_request
```
```
In io_uring/io_uring.c (ffffffff81814d35)
Location: io_uring/refs.h:20
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_req_complete_post
```
```
In io_uring/timeout.c (ffffffff8181f1dd)
Location: io_uring/refs.h:20
Inline: True
Inline callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_req_task_link_timeout
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
