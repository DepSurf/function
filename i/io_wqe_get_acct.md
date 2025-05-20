# Function: <code>io_wqe_get_acct</code>

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
In fs/io-wq.c (ffffffff8138b04c)
Location: fs/io-wq.c:190
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_worker_running
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:__io_worker_busy
  - fs/io-wq.c:io_worker_exit
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
In fs/io-wq.c (ffffffff8139c2ac)
Location: fs/io-wq.c:209
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_worker_running
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:__io_worker_busy
  - fs/io-wq.c:io_worker_exit
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
In fs/io-wq.c (ffffffff813a33f3)
Location: fs/io-wq.c:158
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_worker_running
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:io_worker_handle_work
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
In fs/io-wq.c (ffffffff813f1a06)
Location: fs/io-wq.c:168
Inline: True
Inline callers:
  - fs/io-wq.c:io_workqueue_create
  - fs/io-wq.c:create_worker_cont
  - fs/io-wq.c:io_wq_worker_running
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_wqe_dec_running
  - fs/io-wq.c:io_wqe_activate_free_worker
  - fs/io-wq.c:io_worker_cancel_cb
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
In io_uring/io-wq.c (ffffffff816da4d5)
Location: io_uring/io-wq.c:171
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_workqueue_create
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_wq_worker_running
  - io_uring/io-wq.c:io_wqe_worker
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_wqe_dec_running
  - io_uring/io-wq.c:io_wqe_activate_free_worker
  - io_uring/io-wq.c:io_worker_cancel_cb
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
In io_uring/io-wq.c (ffffffff817a65a5)
Location: io_uring/io-wq.c:173
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_workqueue_create
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_wq_worker_running
  - io_uring/io-wq.c:io_wqe_worker
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_wqe_dec_running
  - io_uring/io-wq.c:io_wqe_activate_free_worker
  - io_uring/io-wq.c:io_worker_cancel_cb
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
