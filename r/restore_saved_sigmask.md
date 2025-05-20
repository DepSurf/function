# Function: <code>restore_saved_sigmask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102e54f)
Location: include/linux/sched.h:2515
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102d4ff)
Location: include/linux/sched.h:2746
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102d3a0)
Location: include/linux/sched.h:2846
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102b610)
Location: include/linux/sched/signal.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102c339)
Location: include/linux/sched/signal.h:418
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102d5f9)
Location: include/linux/sched/signal.h:446
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff8102e846)
Location: include/linux/sched/signal.h:458
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff81030aa6)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In fs/select.c (ffffffff812e362a)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff81322031)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
```
In fs/aio.c (ffffffff8132a770)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffff8132d446)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
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
In arch/x86/kernel/signal.c (ffffffff81030f26)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In fs/select.c (ffffffff812f50ba)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff81334584)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
```
In fs/aio.c (ffffffff8133d473)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffff813404aa)
Location: include/linux/sched/signal.h:471
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
In arch/x86/kernel/signal.c (ffffffff81033c71)
Location: include/linux/sched/signal.h:494
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In fs/select.c (ffffffff8132d709)
Location: include/linux/sched/signal.h:494
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff8136eb34)
Location: include/linux/sched/signal.h:494
Inline: True
Inline callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
```
In fs/aio.c (ffffffff81376808)
Location: include/linux/sched/signal.h:494
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffff81386c77)
Location: include/linux/sched/signal.h:494
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
In arch/x86/kernel/signal.c (ffffffff810346d9)
Location: include/linux/sched/signal.h:507
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
```
```
In fs/select.c (ffffffff81339004)
Location: include/linux/sched/signal.h:507
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff8137be1c)
Location: include/linux/sched/signal.h:507
Inline: True
```
```
In fs/aio.c (ffffffff8138448f)
Location: include/linux/sched/signal.h:507
Inline: True
Inline callers:
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__do_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffff8139213d)
Location: include/linux/sched/signal.h:507
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
In arch/x86/kernel/signal.c (ffffffff81036264)
Location: include/linux/sched/signal.h:508
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
```
```
In fs/select.c (ffffffff8133f5c4)
Location: include/linux/sched/signal.h:508
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff8138257c)
Location: include/linux/sched/signal.h:508
Inline: True
```
```
In fs/aio.c (ffffffff8138b0df)
Location: include/linux/sched/signal.h:508
Inline: True
Inline callers:
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__do_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffff81395795)
Location: include/linux/sched/signal.h:508
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
In arch/x86/kernel/signal.c (ffffffff8103b505)
Location: include/linux/sched/signal.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
```
```
In fs/select.c (ffffffff8138cf54)
Location: include/linux/sched/signal.h:506
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff813cf7ec)
Location: include/linux/sched/signal.h:506
Inline: True
```
```
In fs/aio.c (ffffffff813d865f)
Location: include/linux/sched/signal.h:506
Inline: True
Inline callers:
  - fs/aio.c:__x64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x64_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffff813e585d)
Location: include/linux/sched/signal.h:506
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
In arch/x86/kernel/signal.c (ffffffff810422b6)
Location: include/linux/sched/signal.h:546
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
```
```
In fs/select.c (ffffffff8140e259)
Location: include/linux/sched/signal.h:546
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff814584d5)
Location: include/linux/sched/signal.h:546
Inline: True
```
```
In fs/aio.c (ffffffff81462b1c)
Location: include/linux/sched/signal.h:546
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In io_uring/io_uring.c (ffffffff816cf92f)
Location: include/linux/sched/signal.h:546
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
In arch/x86/kernel/signal.c (ffffffff8104b616)
Location: include/linux/sched/signal.h:547
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
```
```
In fs/select.c (ffffffff81498dc2)
Location: include/linux/sched/signal.h:547
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff814e7e25)
Location: include/linux/sched/signal.h:547
Inline: True
```
```
In fs/aio.c (ffffffff814f31a7)
Location: include/linux/sched/signal.h:547
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In io_uring/io_uring.c (ffffffff81791d12)
Location: include/linux/sched/signal.h:547
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
In arch/x86/kernel/signal.c (ffffffff8104bea6)
Location: include/linux/sched/signal.h:547
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
```
```
In fs/select.c (ffffffff814cde50)
Location: include/linux/sched/signal.h:547
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff8151e0f5)
Location: include/linux/sched/signal.h:547
Inline: True
```
```
In fs/aio.c (ffffffff81529f66)
Location: include/linux/sched/signal.h:547
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In io_uring/io_uring.c (ffffffff817d0e9c)
Location: include/linux/sched/signal.h:547
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
In arch/x86/kernel/signal.c (ffffffff81053126)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
```
```
In fs/select.c (ffffffff81500790)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff815526d5)
Location: include/linux/sched/signal.h:538
Inline: True
```
```
In fs/aio.c (ffffffff8155ee36)
Location: include/linux/sched/signal.h:538
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In io_uring/io_uring.c (ffffffff818139ea)
Location: include/linux/sched/signal.h:538
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
In arch/arm64/kernel/signal.c (ffff80001009340c)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
```
```
In fs/select.c (ffff8000103a2378)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffff8000103f2db4)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/eventpoll.c:__arm64_compat_sys_epoll_pwait
  - fs/eventpoll.c:__arm64_sys_epoll_pwait
```
```
In fs/aio.c (ffff8000103fce00)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/aio.c:__arm64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__arm64_compat_sys_io_pgetevents
  - fs/aio.c:__arm64_sys_io_pgetevents
```
```
In fs/io_uring.c (ffff800010405b98)
Location: include/linux/sched/signal.h:471
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
In arch/arm/kernel/signal.c (c030e9d0)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - arch/arm/kernel/signal.c:do_work_pending
```
```
In fs/select.c (c0584f14)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (c05c85ec)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_pwait
```
```
In fs/aio.c (c05d1b68)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_pgetevents_time32
  - fs/aio.c:__se_sys_io_pgetevents
```
```
In fs/io_uring.c (c05d7370)
Location: include/linux/sched/signal.h:471
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
In arch/powerpc/kernel/signal.c (c000000000023a70)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal.c:do_notify_resume
```
```
In fs/select.c (c00000000049bd00)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (c0000000004fa850)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_compat_sys_epoll_pwait
  - fs/eventpoll.c:__se_sys_epoll_pwait
```
```
In fs/aio.c (c000000000505a10)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/aio.c:__se_compat_sys_io_pgetevents_time64
  - fs/aio.c:__se_compat_sys_io_pgetevents
  - fs/aio.c:__se_sys_io_pgetevents
```
```
In fs/io_uring.c (c00000000050e88c)
Location: include/linux/sched/signal.h:471
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
In arch/riscv/kernel/signal.c (ffffffe0000b6a30)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - arch/riscv/kernel/signal.c:do_notify_resume
```
```
In fs/select.c (ffffffe00026a92c)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffe0002a4bcc)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_pwait
```
```
In fs/aio.c (ffffffe0002ac580)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffe0002b0f5e)
Location: include/linux/sched/signal.h:471
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
In arch/x86/kernel/signal.c (ffffffff81031086)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In fs/select.c (ffffffff812ed69a)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff8132cb64)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
```
In fs/aio.c (ffffffff81335a53)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffff81338a8a)
Location: include/linux/sched/signal.h:471
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
In arch/x86/kernel/signal.c (ffffffff81020aa6)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In fs/select.c (ffffffff812de2ca)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff8131ca84)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
```
In fs/aio.c (ffffffff81326293)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffff813297ba)
Location: include/linux/sched/signal.h:471
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
In arch/x86/kernel/signal.c (ffffffff81030ee6)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In fs/select.c (ffffffff812eb4aa)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff8132a634)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
```
In fs/aio.c (ffffffff81333523)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffff8133655a)
Location: include/linux/sched/signal.h:471
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
In arch/x86/kernel/signal.c (ffffffff81031d76)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In fs/select.c (ffffffff812fc49a)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
```
```
In fs/eventpoll.c (ffffffff8133cc64)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
```
In fs/aio.c (ffffffff81346573)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
```
In fs/io_uring.c (ffffffff8134962a)
Location: include/linux/sched/signal.h:471
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
```
</details>
</li>
</ul>

## Differences
