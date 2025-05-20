# Function: <code>restore_saved_sigmask_unless</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff812e34fe)
Location: include/linux/sched/signal.h:487
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff81322009)
Location: include/linux/sched/signal.h:487
Inline: True
Inline callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
Direct callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
```
In fs/aio.c (ffffffff8132a72d)
Location: include/linux/sched/signal.h:487
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffff8132d443)
Location: include/linux/sched/signal.h:487
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff81322a72-ffffffff81322a86: restore_saved_sigmask_unless.part.0 (STB_LOCAL)
ffffffff8132d01e-ffffffff8132d032: restore_saved_sigmask_unless.part.0 (STB_LOCAL)
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
In fs/select.c (ffffffff812f4f8e)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff81334569)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
```
In fs/aio.c (ffffffff8133d434)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffff813404aa)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
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
In fs/select.c (ffffffff8132d5ee)
Location: include/linux/sched/signal.h:502
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff8136eb19)
Location: include/linux/sched/signal.h:502
Inline: True
Inline callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
```
In fs/aio.c (ffffffff81376804)
Location: include/linux/sched/signal.h:502
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffff81386c77)
Location: include/linux/sched/signal.h:502
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
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
In fs/select.c (ffffffff81338ede)
Location: include/linux/sched/signal.h:515
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff8137bdf3)
Location: include/linux/sched/signal.h:515
Inline: True
```
```
In fs/aio.c (ffffffff8138448b)
Location: include/linux/sched/signal.h:515
Inline: True
Inline callers:
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/aio.c:__do_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffff8139213d)
Location: include/linux/sched/signal.h:515
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
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
In fs/select.c (ffffffff8133f49e)
Location: include/linux/sched/signal.h:516
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff81382553)
Location: include/linux/sched/signal.h:516
Inline: True
```
```
In fs/aio.c (ffffffff8138b0db)
Location: include/linux/sched/signal.h:516
Inline: True
Inline callers:
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/aio.c:__do_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffff81395795)
Location: include/linux/sched/signal.h:516
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
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
In fs/select.c (ffffffff8138ce2e)
Location: include/linux/sched/signal.h:514
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff813cf7c3)
Location: include/linux/sched/signal.h:514
Inline: True
```
```
In fs/aio.c (ffffffff813d865b)
Location: include/linux/sched/signal.h:514
Inline: True
Inline callers:
  - fs/aio.c:__x64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x64_compat_sys_io_pgetevents
  - fs/aio.c:__x64_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffff813e585d)
Location: include/linux/sched/signal.h:514
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
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
In fs/select.c (ffffffff8140e150)
Location: include/linux/sched/signal.h:554
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff814584a1)
Location: include/linux/sched/signal.h:554
Inline: True
```
```
In fs/aio.c (ffffffff81462b17)
Location: include/linux/sched/signal.h:554
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In io_uring/io_uring.c (ffffffff816cf92d)
Location: include/linux/sched/signal.h:554
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
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
In fs/select.c (ffffffff81498cb0)
Location: include/linux/sched/signal.h:555
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff814e7df1)
Location: include/linux/sched/signal.h:555
Inline: True
```
```
In fs/aio.c (ffffffff814f31a3)
Location: include/linux/sched/signal.h:555
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In io_uring/io_uring.c (ffffffff81791b5e)
Location: include/linux/sched/signal.h:555
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
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
In fs/select.c (ffffffff814cdd40)
Location: include/linux/sched/signal.h:555
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff8151e0c1)
Location: include/linux/sched/signal.h:555
Inline: True
```
```
In fs/aio.c (ffffffff81529f61)
Location: include/linux/sched/signal.h:555
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In io_uring/io_uring.c (ffffffff817d11d6)
Location: include/linux/sched/signal.h:555
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
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
In fs/select.c (ffffffff81500680)
Location: include/linux/sched/signal.h:546
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff815526a1)
Location: include/linux/sched/signal.h:546
Inline: True
```
```
In fs/aio.c (ffffffff8155ee31)
Location: include/linux/sched/signal.h:546
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In io_uring/io_uring.c (ffffffff81813c09)
Location: include/linux/sched/signal.h:546
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
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
In fs/select.c (ffff8000103a2274)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffff8000103f2d9c)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/eventpoll.c:__arm64_compat_sys_epoll_pwait
  - fs/eventpoll.c:__arm64_compat_sys_epoll_pwait
  - fs/eventpoll.c:__arm64_sys_epoll_pwait
  - fs/eventpoll.c:__arm64_sys_epoll_pwait
```
```
In fs/aio.c (ffff8000103fcda4)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/aio.c:__arm64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__arm64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__arm64_compat_sys_io_pgetevents
  - fs/aio.c:__arm64_compat_sys_io_pgetevents
  - fs/aio.c:__arm64_sys_io_pgetevents
  - fs/aio.c:__arm64_sys_io_pgetevents
```
```
In fs/io_uring.c (ffff800010405b98)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
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
In fs/select.c (c0584db0)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (c05c85b4)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_pwait
```
```
In fs/aio.c (c05d1b14)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_pgetevents_time32
  - fs/aio.c:__se_sys_io_pgetevents_time32
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/aio.c:__se_sys_io_pgetevents
```
```
In fs/io_uring.c (c05d7370)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
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
In fs/select.c (c00000000049bb88)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (c0000000004fa80c)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_compat_sys_epoll_pwait
  - fs/eventpoll.c:__se_compat_sys_epoll_pwait
  - fs/eventpoll.c:__se_sys_epoll_pwait
  - fs/eventpoll.c:__se_sys_epoll_pwait
```
```
In fs/aio.c (c000000000505988)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/aio.c:__se_compat_sys_io_pgetevents_time64
  - fs/aio.c:__se_compat_sys_io_pgetevents_time64
  - fs/aio.c:__se_compat_sys_io_pgetevents
  - fs/aio.c:__se_compat_sys_io_pgetevents
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/aio.c:__se_sys_io_pgetevents
```
```
In fs/io_uring.c (c00000000050e88c)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
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
In fs/select.c (ffffffe00026a88e)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffe0002a4bb6)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_pwait
```
```
In fs/aio.c (ffffffe0002ac554)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffe0002b0f5e)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
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
In fs/select.c (ffffffff812ed56e)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff8132cb49)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
```
In fs/aio.c (ffffffff81335a14)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffff81338a8a)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
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
In fs/select.c (ffffffff812de19e)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff8131ca69)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
```
In fs/aio.c (ffffffff81326254)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffff813297ba)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
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
In fs/select.c (ffffffff812eb37e)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff8132a619)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
```
In fs/aio.c (ffffffff813334e4)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffff8133655a)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
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
In fs/select.c (ffffffff812fc36e)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff8133cc49)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
```
In fs/aio.c (ffffffff81346534)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffff8134962a)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
```
</details>
</li>
</ul>

## Differences
