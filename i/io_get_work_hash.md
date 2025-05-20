# Function: <code>io_get_work_hash</code>

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
In fs/io-wq.c (ffffffff81389eec)
Location: fs/io-wq.c:381
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_cancel_pending_work
  - fs/io-wq.c:io_wqe_cancel_pending_work
  - fs/io-wq.c:io_wqe_enqueue
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_get_next_work
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
In fs/io-wq.c (ffffffff8139ad2b)
Location: fs/io-wq.c:396
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_cancel_pending_work
  - fs/io-wq.c:io_wqe_cancel_pending_work
  - fs/io-wq.c:io_wqe_enqueue
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_get_next_work
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
In fs/io-wq.c (ffffffff813a20fb)
Location: fs/io-wq.c:400
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_cancel_pending_work
  - fs/io-wq.c:io_wqe_cancel_pending_work
  - fs/io-wq.c:io_wqe_enqueue
  - fs/io-wq.c:io_worker_handle_work
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
In fs/io-wq.c (ffffffff813f1fd9)
Location: fs/io-wq.c:434
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_enqueue
  - fs/io-wq.c:io_worker_handle_work
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
In io_uring/io-wq.c (ffffffff816d9e9c)
Location: io_uring/io-wq.c:441
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_acct_cancel_pending_work
  - io_uring/io-wq.c:io_acct_cancel_pending_work
  - io_uring/io-wq.c:io_wqe_enqueue
  - io_uring/io-wq.c:io_worker_handle_work
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
In io_uring/io-wq.c (ffffffff817a5f0c)
Location: io_uring/io-wq.c:443
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_acct_cancel_pending_work
  - io_uring/io-wq.c:io_acct_cancel_pending_work
  - io_uring/io-wq.c:io_wqe_enqueue
  - io_uring/io-wq.c:io_worker_handle_work
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
In io_uring/io-wq.c (ffffffff817e6a8c)
Location: io_uring/io-wq.c:441
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_acct_cancel_pending_work
  - io_uring/io-wq.c:io_acct_cancel_pending_work
  - io_uring/io-wq.c:io_wq_enqueue
  - io_uring/io-wq.c:io_worker_handle_work
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
In io_uring/io-wq.c (ffffffff8182c84c)
Location: io_uring/io-wq.c:453
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_acct_cancel_pending_work
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
