# Function: <code>set_restore_sigmask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090b59)
Location: arch/x86/include/asm/thread_info.h:232
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
```
```
In fs/select.c (ffffffff81221de1)
Location: arch/x86/include/asm/thread_info.h:232
Inline: True
Inline callers:
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_ppoll
```
```
In fs/eventpoll.c (ffffffff81256ac0)
Location: arch/x86/include/asm/thread_info.h:232
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:compat_SyS_epoll_pwait
```
```
In fs/compat.c (ffffffff812657a1)
Location: arch/x86/include/asm/thread_info.h:232
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_ppoll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81093c01)
Location: include/linux/sched.h:2724
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
```
```
In fs/select.c (ffffffff8124a36c)
Location: include/linux/sched.h:2724
Inline: True
Inline callers:
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_pselect6
```
```
In fs/eventpoll.c (ffffffff8127f61f)
Location: include/linux/sched.h:2724
Inline: True
Inline callers:
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
```
```
In fs/compat.c (ffffffff81291c89)
Location: include/linux/sched.h:2724
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_ppoll
  - fs/compat.c:compat_SyS_pselect6
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81098bf8)
Location: include/linux/sched.h:2824
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
```
```
In fs/select.c (ffffffff8125d32c)
Location: include/linux/sched.h:2824
Inline: True
Inline callers:
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_pselect6
```
```
In fs/eventpoll.c (ffffffff8129319f)
Location: include/linux/sched.h:2824
Inline: True
Inline callers:
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
```
```
In fs/compat.c (ffffffff812a6a09)
Location: include/linux/sched.h:2824
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_ppoll
  - fs/compat.c:compat_SyS_pselect6
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095e88)
Location: include/linux/sched/signal.h:395
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
```
```
In fs/select.c (ffffffff8126abc5)
Location: include/linux/sched/signal.h:395
Inline: True
Inline callers:
  - fs/select.c:compat_SyS_ppoll
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_pselect6
```
```
In fs/eventpoll.c (ffffffff812a0495)
Location: include/linux/sched/signal.h:395
Inline: True
Inline callers:
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109cce1)
Location: include/linux/sched/signal.h:396
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
```
```
In fs/select.c (ffffffff8128d43c)
Location: include/linux/sched/signal.h:396
Inline: True
Inline callers:
  - fs/select.c:compat_SyS_ppoll
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_pselect6
```
```
In fs/eventpoll.c (ffffffff812c3872)
Location: include/linux/sched/signal.h:396
Inline: True
Inline callers:
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a12a1)
Location: include/linux/sched/signal.h:424
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
```
```
In fs/select.c (ffffffff812b38c1)
Location: include/linux/sched/signal.h:424
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_ppoll
  - fs/select.c:__ia32_compat_sys_ppoll
  - fs/select.c:do_compat_pselect
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:do_pselect
```
```
In fs/eventpoll.c (ffffffff812eb42d)
Location: include/linux/sched/signal.h:424
Inline: True
Inline callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
```
In fs/aio.c (ffffffff812f3960)
Location: include/linux/sched/signal.h:424
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
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
In kernel/signal.c (ffffffff810a9821)
Location: include/linux/sched/signal.h:436
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:sigsuspend
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
In kernel/signal.c (ffffffff810ac0a8)
Location: include/linux/sched/signal.h:450
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
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
In kernel/signal.c (ffffffff810b26b8)
Location: include/linux/sched/signal.h:442
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bb138)
Location: include/linux/sched/signal.h:465
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
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
In kernel/signal.c (ffffffff810b63fd)
Location: include/linux/sched/signal.h:478
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
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
In kernel/signal.c (ffffffff810b56e0)
Location: include/linux/sched/signal.h:479
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
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
In kernel/signal.c (ffffffff810c7cdf)
Location: include/linux/sched/signal.h:477
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
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
In kernel/signal.c (ffffffff810defb6)
Location: include/linux/sched/signal.h:517
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
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
In kernel/signal.c (ffffffff810ffd56)
Location: include/linux/sched/signal.h:518
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
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
In kernel/signal.c (ffffffff8110bde6)
Location: include/linux/sched/signal.h:518
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
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
In kernel/signal.c (ffffffff81115796)
Location: include/linux/sched/signal.h:509
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
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
In kernel/signal.c (ffff80001010e4f8)
Location: include/linux/sched/signal.h:412
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
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
In kernel/signal.c (c0366608)
Location: include/linux/sched/signal.h:412
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:set_user_sigmask
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
In kernel/signal.c (c000000000155950)
Location: include/linux/sched/signal.h:442
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
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
In kernel/signal.c (ffffffe0000d1f20)
Location: include/linux/sched/signal.h:412
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigsuspend
  - kernel/signal.c:set_user_sigmask
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
In kernel/signal.c (ffffffff810aca28)
Location: include/linux/sched/signal.h:442
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
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
In kernel/signal.c (ffffffff8109b3a8)
Location: include/linux/sched/signal.h:442
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
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
In kernel/signal.c (ffffffff810abf88)
Location: include/linux/sched/signal.h:442
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
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
In kernel/signal.c (ffffffff810b40f8)
Location: include/linux/sched/signal.h:442
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
```
</details>
</li>
</ul>

## Differences
