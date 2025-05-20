# Function: <code>io_queue_next</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81391184)
Location: fs/io_uring.c:2250
Inline: True
Inline callers:
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:__io_req_task_cancel
  - fs/io_uring.c:io_fail_links
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
In fs/io_uring.c (ffffffff813a03f0)
Location: fs/io_uring.c:2093
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_async_cancel
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:io_req_complete_failed
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
In fs/io_uring.c (ffffffff813e9481)
Location: fs/io_uring.c:2310
Inline: True
Inline callers:
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_req_task_link_timeout
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:io_free_req_work
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
In io_uring/io_uring.c (ffffffff816d59a6)
Location: io_uring/io_uring.c:2870
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_free_batch_list
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_queue_next(struct io_kiocb *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178eaf0)
Location: io_uring/io_uring.c:1393
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_req_task_link_timeout
```
**Symbols:**

```
ffffffff8178eaf0-ffffffff8178eb68: io_queue_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_queue_next(struct io_kiocb *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817cfee0)
Location: io_uring/io_uring.c:1501
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_req_task_link_timeout
```
**Symbols:**

```
ffffffff817cfee0-ffffffff817cff74: io_queue_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_queue_next(struct io_kiocb *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81813070)
Location: io_uring/io_uring.c:1522
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_req_task_link_timeout
```
**Symbols:**

```
ffffffff81813070-ffffffff81813104: io_queue_next (STB_GLOBAL)
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
