# Function: <code>wq_list_add_tail</code>

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
In fs/io-wq.c (ffffffff8138a2e3)
Location: fs/io-wq.h:43
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_enqueue
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
In fs/io-wq.c (ffffffff8139b221)
Location: fs/io-wq.h:51
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_enqueue
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
In fs/io_uring.c (ffffffff81391e60)
Location: fs/io-wq.h:44
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_task_work_add
```
```
In fs/io-wq.c (ffffffff813a2b48)
Location: fs/io-wq.h:44
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_enqueue
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
In fs/io_uring.c (ffffffff813dedf1)
Location: fs/io-wq.h:44
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_task_work_add
```
```
In fs/io-wq.c (ffffffff813f2128)
Location: fs/io-wq.h:44
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_enqueue
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
In io_uring/io_uring.c (ffffffff816d63c1)
Location: io_uring/io-wq.h:77
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_poll_remove
  - io_uring/io_uring.c:__io_req_task_work_add
```
```
In io_uring/io-wq.c (ffffffff816dabaf)
Location: io_uring/io-wq.h:77
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wqe_enqueue
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
In io_uring/io_uring.c (ffffffff81790b5e)
Location: io_uring/slist.h:52
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_req_defer_failed
```
```
In io_uring/io-wq.c (ffffffff817a6cad)
Location: io_uring/slist.h:52
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wqe_enqueue
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
In io_uring/io_uring.c (ffffffff817d2066)
Location: io_uring/slist.h:33
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_req_defer_failed
```
```
In io_uring/io-wq.c (ffffffff817e7db0)
Location: io_uring/slist.h:33
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_enqueue
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
In io_uring/io_uring.c (ffffffff818153fa)
Location: io_uring/slist.h:33
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_req_defer_failed
```
```
In io_uring/io-wq.c (ffffffff8182db92)
Location: io_uring/slist.h:33
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_enqueue
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
