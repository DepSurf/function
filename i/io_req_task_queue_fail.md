# Function: <code>io_req_task_queue_fail</code>

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
In fs/io_uring.c (ffffffff813a1bbc)
Location: fs/io_uring.c:2076
Inline: True
Inline callers:
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:io_req_free_batch
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
In fs/io_uring.c (ffffffff813ee2e1)
Location: fs/io_uring.c:2291
Inline: True
Inline callers:
  - fs/io_uring.c:io_wq_submit_work
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
In io_uring/io_uring.c (ffffffff816d707d)
Location: io_uring/io_uring.c:2851
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_try_cancel
  - io_uring/io_uring.c:io_timeout_remove
  - io_uring/io_uring.c:kiocb_done
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void io_req_task_queue_fail(struct io_kiocb *req, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178f40b)
Location: io_uring/io_uring.c:1380
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_wq_submit_work
Direct callers:
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/rw.c:kiocb_done
```
**Symbols:**

```
ffffffff8178ea60-ffffffff8178ea92: io_req_task_queue_fail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void io_req_task_queue_fail(struct io_kiocb *req, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817d0753)
Location: io_uring/io_uring.c:1488
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_wq_submit_work
Direct callers:
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/rw.c:kiocb_done
```
**Symbols:**

```
ffffffff817cfe20-ffffffff817cfe6d: io_req_task_queue_fail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void io_req_task_queue_fail(struct io_kiocb *req, int ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81813f76)
Location: io_uring/io_uring.c:1509
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_wq_submit_work
Direct callers:
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/rw.c:kiocb_done
```
**Symbols:**

```
ffffffff81812fb0-ffffffff81812ffd: io_req_task_queue_fail (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
