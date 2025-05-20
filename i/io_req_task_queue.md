# Function: <code>io_req_task_queue</code>

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
void io_req_task_queue(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813911d1)
Location: fs/io_uring.c:2238
Inline: True
Inline callers:
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:__io_req_task_cancel
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_commit_cqring
Direct callers:
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:io_req_free_batch
```
**Symbols:**

```
ffffffff8138be20-ffffffff8138bea6: io_req_task_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void io_req_task_queue(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139529e)
Location: fs/io_uring.c:2085
Inline: True
Inline callers:
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_req_free_batch
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_async_cancel
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_async_buf_func
  - fs/io_uring.c:io_req_complete_failed
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
ffffffff81393650-ffffffff813936cf: io_req_task_queue (STB_LOCAL)
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
In fs/io_uring.c (ffffffff813e94c0)
Location: fs/io_uring.c:2298
Inline: True
Inline callers:
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_req_task_link_timeout
  - fs/io_uring.c:io_async_buf_func
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:io_free_req_work
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:__io_commit_cqring_flush
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
In io_uring/io_uring.c (ffffffff816d2d7d)
Location: io_uring/io_uring.c:2858
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_async_buf_func
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_req_complete_put
  - io_uring/io_uring.c:__io_commit_cqring_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void io_req_task_queue(struct io_kiocb *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81790447)
Location: io_uring/io_uring.c:1387
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_queue_next
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_commit_cqring_flush
Direct callers:
  - io_uring/rw.c:io_async_buf_func
```
**Symbols:**

```
ffffffff8178eab0-ffffffff8178ead8: io_req_task_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void io_req_task_queue(struct io_kiocb *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817cf827)
Location: io_uring/io_uring.c:1495
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_queue_next
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_commit_cqring_flush
Direct callers:
  - io_uring/rw.c:io_async_buf_func
```
**Symbols:**

```
ffffffff817cfe80-ffffffff817cfec3: io_req_task_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void io_req_task_queue(struct io_kiocb *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8181296b)
Location: io_uring/io_uring.c:1516
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_queue_next
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_commit_cqring_flush
Direct callers:
  - io_uring/rw.c:io_async_buf_func
```
**Symbols:**

```
ffffffff81813010-ffffffff81813053: io_req_task_queue (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
