# Function: <code>file_can_poll</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812ebe72)
Location: include/linux/poll.h:77
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff813000c2)
Location: include/linux/poll.h:77
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81321143)
Location: include/linux/poll.h:81
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81334f33)
Location: include/linux/poll.h:81
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
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
In fs/eventpoll.c (ffffffff8136eda5)
Location: include/linux/poll.h:81
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/io_uring.c (ffffffff81386e30)
Location: include/linux/poll.h:81
Inline: True
Inline callers:
  - fs/io_uring.c:io_arm_poll_handler
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
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
In fs/eventpoll.c (ffffffff8137cbb6)
Location: include/linux/poll.h:81
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/io_uring.c (ffffffff813903a0)
Location: include/linux/poll.h:81
Inline: True
Inline callers:
  - fs/io_uring.c:io_arm_poll_handler
  - fs/io_uring.c:io_read
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
In fs/eventpoll.c (ffffffff81383565)
Location: include/linux/poll.h:81
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/io_uring.c (ffffffff8139d43d)
Location: include/linux/poll.h:81
Inline: True
Inline callers:
  - fs/io_uring.c:io_arm_poll_handler
  - fs/io_uring.c:io_read
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
In fs/eventpoll.c (ffffffff813d0805)
Location: include/linux/poll.h:81
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
```
```
In fs/io_uring.c (ffffffff813ec1b7)
Location: include/linux/poll.h:81
Inline: True
Inline callers:
  - fs/io_uring.c:io_arm_poll_handler
  - fs/io_uring.c:io_read
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
In fs/eventpoll.c (ffffffff814597db)
Location: include/linux/poll.h:79
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
```
```
In io_uring/io_uring.c (ffffffff816d7187)
Location: include/linux/poll.h:79
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_arm_poll_handler
  - io_uring/io_uring.c:io_read
  - io_uring/io_uring.c:io_read
  - io_uring/io_uring.c:io_buffer_select
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
In fs/eventpoll.c (ffffffff814e8c4b)
Location: include/linux/poll.h:79
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
```
```
In io_uring/io_uring.c (ffffffff8179145e)
Location: include/linux/poll.h:79
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_submit_work
```
```
In io_uring/poll.c (ffffffff8179d977)
Location: include/linux/poll.h:79
Inline: True
Inline callers:
  - io_uring/poll.c:io_arm_poll_handler
```
```
In io_uring/kbuf.c (ffffffff8179f2a6)
Location: include/linux/poll.h:79
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_buffer_select
```
```
In io_uring/rw.c (ffffffff817a4524)
Location: include/linux/poll.h:79
Inline: True
Inline callers:
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
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
In fs/eventpoll.c (ffffffff8151f9ab)
Location: include/linux/poll.h:79
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
```
```
In io_uring/io_uring.c (ffffffff817d26b6)
Location: include/linux/poll.h:79
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_submit_work
```
```
In io_uring/poll.c (ffffffff817deb90)
Location: include/linux/poll.h:79
Inline: True
Inline callers:
  - io_uring/poll.c:io_arm_poll_handler
```
```
In io_uring/kbuf.c (ffffffff817e0519)
Location: include/linux/poll.h:79
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_buffer_select
```
```
In io_uring/rw.c (ffffffff817e5529)
Location: include/linux/poll.h:79
Inline: True
Inline callers:
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
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
In fs/eventpoll.c (ffffffff81553fbb)
Location: include/linux/poll.h:79
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
```
```
In io_uring/io_uring.c (ffffffff818158fc)
Location: include/linux/poll.h:79
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_submit_work
```
```
In io_uring/poll.c (ffffffff81822f30)
Location: include/linux/poll.h:79
Inline: True
Inline callers:
  - io_uring/poll.c:io_arm_poll_handler
```
```
In io_uring/kbuf.c (ffffffff81824996)
Location: include/linux/poll.h:79
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_buffer_select
```
```
In io_uring/rw.c (ffffffff81829925)
Location: include/linux/poll.h:79
Inline: True
Inline callers:
  - io_uring/rw.c:io_read_mshot
  - io_uring/rw.c:__io_read
  - io_uring/rw.c:__io_read
```
</details>
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
In fs/eventpoll.c (ffff8000103f1e24)
Location: include/linux/poll.h:81
Inline: True
Inline callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
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
In fs/eventpoll.c (c05c7a1c)
Location: include/linux/poll.h:81
Inline: True
Inline callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
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
In fs/eventpoll.c (c0000000004f9fb8)
Location: include/linux/poll.h:81
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
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
In fs/eventpoll.c (ffffffe0002a4650)
Location: include/linux/poll.h:81
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
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
In fs/eventpoll.c (ffffffff8132d513)
Location: include/linux/poll.h:81
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
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
In fs/eventpoll.c (ffffffff8131d822)
Location: include/linux/poll.h:81
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
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
In fs/eventpoll.c (ffffffff8132afe3)
Location: include/linux/poll.h:81
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
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
In fs/eventpoll.c (ffffffff8133bc1e)
Location: include/linux/poll.h:81
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
</details>
</li>
</ul>

## Differences
