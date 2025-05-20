# Function: <code>io_queue_async_work</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134343d)
Location: fs/io_uring.c:490
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void io_queue_async_work(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813819b0)
Location: fs/io_uring.c:1115
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_cancel_defer_files
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_put_req
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
ffffffff813819b0-ffffffff81381c53: io_queue_async_work (STB_LOCAL)
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
In fs/io_uring.c (ffffffff81399317)
Location: fs/io_uring.c:1585
Inline: True
Inline callers:
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_iopoll_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_queue_async_work(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81399210)
Location: fs/io_uring.c:1275
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:io_iopoll_complete
```
**Symbols:**

```
ffffffff81399210-ffffffff81399340: io_queue_async_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_queue_async_work(struct io_kiocb *req, bool *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e94e0)
Location: fs/io_uring.c:1482
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_drain_req
```
**Symbols:**

```
ffffffff813e94e0-ffffffff813e95ee: io_queue_async_work (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff80001040516c)
Location: fs/io_uring.c:490
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d4abc)
Location: fs/io_uring.c:490
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050dac4)
Location: fs/io_uring.c:490
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002af36e)
Location: fs/io_uring.c:490
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133ba1d)
Location: fs/io_uring.c:490
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132c6fd)
Location: fs/io_uring.c:490
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813394ed)
Location: fs/io_uring.c:490
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134bd1d)
Location: fs/io_uring.c:490
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *locked</code>
</li>
</ul>
</details>
</li>
</ul>
