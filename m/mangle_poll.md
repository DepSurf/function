# Function: <code>mangle_poll</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812ae44d)
Location: include/linux/poll.h:124
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In fs/select.c (0)
Location: include/linux/poll.h:124
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/poll.h:124
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812c3550)
Location: include/linux/poll.h:124
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In fs/select.c (0)
Location: include/linux/poll.h:124
Inline: True
```
```
In fs/aio.c (ffffffff81309b03)
Location: include/linux/poll.h:124
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
```
```
In fs/fuse/file.c (0)
Location: include/linux/poll.h:124
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812dff6d)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In fs/select.c (0)
Location: include/linux/poll.h:128
Inline: True
```
```
In fs/aio.c (ffffffff8132ae5c)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
```
```
In fs/io_uring.c (ffffffff8132e4e9)
Location: include/linux/poll.h:128
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/poll.h:128
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812f1a0d)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In fs/select.c (0)
Location: include/linux/poll.h:128
Inline: True
```
```
In fs/aio.c (ffffffff8133bf6a)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
```
```
In fs/io_uring.c (ffffffff81342dc2)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
```
```
In fs/fuse/file.c (0)
Location: include/linux/poll.h:128
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81329b94)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In fs/select.c (0)
Location: include/linux/poll.h:128
Inline: True
```
```
In fs/aio.c (ffffffff81377e88)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/aio.c:aio_poll
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/io_uring.c (ffffffff81382bb2)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/io_uring.c:io_poll_add
```
```
In fs/fuse/file.c (ffffffff8147784b)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
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
In fs/fcntl.c (ffffffff813350fe)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In fs/select.c (0)
Location: include/linux/poll.h:128
Inline: True
```
```
In fs/aio.c (ffffffff81385b78)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/aio.c:aio_poll
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/io_uring.c (ffffffff81398b27)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_poll_task_func
```
```
In fs/fuse/file.c (ffffffff81492ccd)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
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
In fs/fcntl.c (ffffffff8133b28e)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In fs/select.c (0)
Location: include/linux/poll.h:128
Inline: True
```
```
In fs/aio.c (ffffffff8138c5d5)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/io_uring.c (ffffffff81393cb2)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/io_uring.c:io_poll_complete
```
```
In fs/fuse/file.c (ffffffff81497c3d)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
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
In fs/fcntl.c (ffffffff81388eb7)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In fs/select.c (ffffffff8138e497)
Location: include/linux/poll.h:128
Inline: True
```
```
In fs/aio.c (ffffffff813d9c05)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/io_uring.c (ffffffff813e1053)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/io_uring.c:__io_poll_complete
```
```
In fs/fuse/file.c (ffffffff814ef84e)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
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
In fs/fcntl.c (ffffffff8140a15a)
Location: include/linux/poll.h:126
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In fs/select.c (ffffffff8140f73b)
Location: include/linux/poll.h:126
Inline: True
```
```
In fs/aio.c (ffffffff8146408b)
Location: include/linux/poll.h:126
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/fuse/file.c (ffffffff8157cca8)
Location: include/linux/poll.h:126
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In io_uring/io_uring.c (ffffffff816d2861)
Location: include/linux/poll.h:126
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_poll_task_func
  - io_uring/io_uring.c:io_poll_check_events
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
In fs/fcntl.c (ffffffff81494a7a)
Location: include/linux/poll.h:126
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In fs/select.c (ffffffff8149a353)
Location: include/linux/poll.h:126
Inline: True
```
```
In fs/aio.c (ffffffff814f439b)
Location: include/linux/poll.h:126
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/fuse/file.c (ffffffff816227f8)
Location: include/linux/poll.h:126
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In io_uring/poll.c (ffffffff8179d194)
Location: include/linux/poll.h:126
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_check_events
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
In fs/fcntl.c (ffffffff814c9ada)
Location: include/linux/poll.h:126
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In fs/select.c (ffffffff814cf426)
Location: include/linux/poll.h:126
Inline: True
```
```
In fs/aio.c (ffffffff8152b165)
Location: include/linux/poll.h:126
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/fuse/file.c (ffffffff8165ac38)
Location: include/linux/poll.h:126
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In io_uring/poll.c (ffffffff817de3c4)
Location: include/linux/poll.h:126
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_check_events
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
In fs/fcntl.c (ffffffff814fc39a)
Location: include/linux/poll.h:126
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In fs/select.c (ffffffff81501d66)
Location: include/linux/poll.h:126
Inline: True
```
```
In fs/aio.c (ffffffff81560035)
Location: include/linux/poll.h:126
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/fuse/file.c (ffffffff81694908)
Location: include/linux/poll.h:126
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In io_uring/poll.c (ffffffff81822771)
Location: include/linux/poll.h:126
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_check_events
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffff80001039b3ac)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In fs/select.c (0)
Location: include/linux/poll.h:128
Inline: True
```
```
In fs/aio.c (ffff8000103fe028)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/io_uring.c (ffff800010404908)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
```
```
In fs/fuse/file.c (0)
Location: include/linux/poll.h:128
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c0581940)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In fs/select.c (0)
Location: include/linux/poll.h:128
Inline: True
```
```
In fs/aio.c (c05d029c)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
```
```
In fs/io_uring.c (c05d3788)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/io_uring.c:io_poll_complete
```
```
In fs/fuse/file.c (0)
Location: include/linux/poll.h:128
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c000000000496830)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In fs/select.c (0)
Location: include/linux/poll.h:128
Inline: True
```
```
In fs/aio.c (c000000000507510)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
```
```
In fs/io_uring.c (c00000000050d1ac)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
```
```
In fs/fuse/file.c (0)
Location: include/linux/poll.h:128
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffe0002687ea)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In fs/select.c (0)
Location: include/linux/poll.h:128
Inline: True
```
```
In fs/aio.c (ffffffe0002a9fe4)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
```
```
In fs/io_uring.c (ffffffe0002af16a)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
```
```
In fs/fuse/file.c (0)
Location: include/linux/poll.h:128
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812e9fed)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In fs/select.c (0)
Location: include/linux/poll.h:128
Inline: True
```
```
In fs/aio.c (ffffffff8133454a)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
```
```
In fs/io_uring.c (ffffffff8133b3a2)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
```
```
In fs/fuse/file.c (0)
Location: include/linux/poll.h:128
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812dad8d)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In fs/select.c (0)
Location: include/linux/poll.h:128
Inline: True
```
```
In fs/aio.c (ffffffff81327e3c)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
```
```
In fs/io_uring.c (ffffffff8132c080)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
```
```
In fs/fuse/file.c (0)
Location: include/linux/poll.h:128
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812e7dfd)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In fs/select.c (0)
Location: include/linux/poll.h:128
Inline: True
```
```
In fs/aio.c (ffffffff8133201a)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
```
```
In fs/io_uring.c (ffffffff81338e72)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
```
```
In fs/fuse/file.c (0)
Location: include/linux/poll.h:128
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812f9072)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In fs/select.c (0)
Location: include/linux/poll.h:128
Inline: True
```
```
In fs/aio.c (ffffffff81347e60)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
```
```
In fs/io_uring.c (ffffffff8134b70e)
Location: include/linux/poll.h:128
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
```
```
In fs/fuse/file.c (0)
Location: include/linux/poll.h:128
Inline: True
```
</details>
</li>
</ul>

## Differences
