# Function: <code>io_wq_is_hashed</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81381aae)
Location: fs/io-wq.h:120
Inline: True
Inline callers:
  - fs/io_uring.c:io_queue_async_work
```
```
In fs/io-wq.c (ffffffff81389ef1)
Location: fs/io-wq.h:120
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_cancel_pending_work
  - fs/io-wq.c:io_wqe_enqueue
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_get_next_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138bdbb)
Location: fs/io-wq.h:126
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_async_work
```
```
In fs/io-wq.c (ffffffff8139ad30)
Location: fs/io-wq.h:126
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_cancel_pending_work
  - fs/io-wq.c:io_wqe_enqueue
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_get_next_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813992b4)
Location: fs/io-wq.h:130
Inline: True
Inline callers:
  - fs/io_uring.c:io_queue_async_work
```
```
In fs/io-wq.c (ffffffff813a2100)
Location: fs/io-wq.h:130
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_cancel_pending_work
  - fs/io-wq.c:io_wqe_enqueue
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e9560)
Location: fs/io-wq.h:133
Inline: True
Inline callers:
  - fs/io_uring.c:io_queue_async_work
```
```
In fs/io-wq.c (ffffffff813f1fd0)
Location: fs/io-wq.h:133
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_enqueue
  - fs/io-wq.c:io_worker_handle_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d2bbf)
Location: io_uring/io-wq.h:201
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_queue_iowq
```
```
In io_uring/io-wq.c (ffffffff816d9e9c)
Location: io_uring/io-wq.h:201
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_acct_cancel_pending_work
  - io_uring/io-wq.c:io_wqe_enqueue
  - io_uring/io-wq.c:io_worker_handle_work
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
In io_uring/io_uring.c (ffffffff8179032d)
Location: io_uring/io-wq.h:56
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_queue_iowq
```
```
In io_uring/io-wq.c (ffffffff817a5f0c)
Location: io_uring/io-wq.h:56
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_acct_cancel_pending_work
  - io_uring/io-wq.c:io_wqe_enqueue
  - io_uring/io-wq.c:io_worker_handle_work
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
In io_uring/io_uring.c (ffffffff817ce3dd)
Location: io_uring/io-wq.h:57
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_queue_iowq
```
```
In io_uring/io-wq.c (ffffffff817e6a8c)
Location: io_uring/io-wq.h:57
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_acct_cancel_pending_work
  - io_uring/io-wq.c:io_wq_enqueue
  - io_uring/io-wq.c:io_worker_handle_work
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
In io_uring/io_uring.c (ffffffff8181168d)
Location: io_uring/io-wq.h:57
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_queue_iowq
```
```
In io_uring/io-wq.c (ffffffff8182c84c)
Location: io_uring/io-wq.h:57
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_acct_cancel_pending_work
  - io_uring/io-wq.c:io_wq_enqueue
  - io_uring/io-wq.c:io_worker_handle_work
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
