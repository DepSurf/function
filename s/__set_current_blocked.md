# Function: <code>__set_current_blocked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810909e0)
Location: kernel/signal.c:2484
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:SyS_ssetmask
```
**Symbols:**

```
ffffffff810909e0-ffffffff81090a37: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81093a80)
Location: kernel/signal.c:2484
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:SyS_ssetmask
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
```
**Symbols:**

```
ffffffff81093a80-ffffffff81093ad7: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81098a70)
Location: kernel/signal.c:2490
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:SyS_ssetmask
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
```
**Symbols:**

```
ffffffff81098a70-ffffffff81098ad3: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095d00)
Location: kernel/signal.c:2511
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:SyS_ssetmask
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
```
**Symbols:**

```
ffffffff81095d00-ffffffff81095d63: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109cb50)
Location: kernel/signal.c:2512
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:SyS_ssetmask
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
```
**Symbols:**

```
ffffffff8109cb50-ffffffff8109cbb3: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a0f30)
Location: kernel/signal.c:2645
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
```
**Symbols:**

```
ffffffff810a0f30-ffffffff810a0f93: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9370)
Location: kernel/signal.c:2744
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
```
**Symbols:**

```
ffffffff810a9370-ffffffff810a93d3: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810abe00)
Location: kernel/signal.c:2903
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
  - fs/select.c:poll_select_finish
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810abe00-ffffffff810abe55: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2410)
Location: kernel/signal.c:2908
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
  - fs/select.c:poll_select_finish
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810b2410-ffffffff810b2465: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8d3d)
Location: kernel/signal.c:2926
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
  - fs/select.c:poll_select_finish
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810baf90-ffffffff810bafe5: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b3fed)
Location: kernel/signal.c:2946
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
  - fs/select.c:poll_select_finish
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810b6240-ffffffff810b6295: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b566f)
Location: kernel/signal.c:2968
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - fs/select.c:poll_select_finish
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810b7e40-ffffffff810b7e95: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c7c6f)
Location: kernel/signal.c:3053
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:signal_setup_done
  - fs/select.c:poll_select_finish
  - fs/aio.c:__x64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x64_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810ca2d0-ffffffff810ca325: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810def4f)
Location: kernel/signal.c:3033
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - fs/select.c:poll_select_finish
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - io_uring/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810e1e30-ffffffff810e1e89: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ffcef)
Location: kernel/signal.c:3035
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - fs/select.c:poll_select_finish
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - io_uring/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff81102190-ffffffff811021e9: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110bd7f)
Location: kernel/signal.c:3059
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - fs/select.c:poll_select_finish
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - io_uring/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff8110e3d0-ffffffff8110e429: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111572f)
Location: kernel/signal.c:3070
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - fs/select.c:poll_select_finish
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - io_uring/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff81117d50-ffffffff81117da9: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010e150)
Location: kernel/signal.c:2908
Inline: False
Direct callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__arm64_sys_ssetmask
  - kernel/signal.c:__arm64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
  - fs/select.c:poll_select_finish
  - fs/eventpoll.c:__arm64_compat_sys_epoll_pwait
  - fs/eventpoll.c:__arm64_sys_epoll_pwait
  - fs/aio.c:__arm64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__arm64_compat_sys_io_pgetevents
  - fs/aio.c:__arm64_sys_io_pgetevents
  - fs/io_uring.c:__arm64_sys_io_uring_enter
```
**Symbols:**

```
ffff80001010e150-ffff80001010e1fc: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c03664bc)
Location: kernel/signal.c:2908
Inline: False
Direct callers:
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__se_sys_ssetmask
  - kernel/signal.c:__se_sys_sigprocmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
  - fs/select.c:poll_select_finish
  - fs/eventpoll.c:__se_sys_epoll_pwait
  - fs/aio.c:__se_sys_io_pgetevents_time32
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/io_uring.c:__se_sys_io_uring_enter
```
**Symbols:**

```
c03664bc-c0366540: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0000000001555d0)
Location: kernel/signal.c:2908
Inline: False
Direct callers:
  - arch/powerpc/kernel/signal.c:do_notify_resume
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__se_sys_ssetmask
  - kernel/signal.c:__se_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
  - fs/select.c:poll_select_finish
  - fs/eventpoll.c:__se_compat_sys_epoll_pwait
  - fs/eventpoll.c:__se_sys_epoll_pwait
  - fs/aio.c:__se_compat_sys_io_pgetevents_time64
  - fs/aio.c:__se_compat_sys_io_pgetevents
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/io_uring.c:__se_sys_io_uring_enter
```
**Symbols:**

```
c0000000001555d0-c000000000155690: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cf0ca)
Location: kernel/signal.c:2908
Inline: False
Direct callers:
  - arch/riscv/kernel/signal.c:do_notify_resume
  - kernel/signal.c:__se_sys_rt_sigsuspend
  - kernel/signal.c:__se_sys_ssetmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
  - fs/select.c:poll_select_finish
  - fs/eventpoll.c:__se_sys_epoll_pwait
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/io_uring.c:__se_sys_io_uring_enter
```
**Symbols:**

```
ffffffe0000cf0ca-ffffffe0000cf15a: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ac780)
Location: kernel/signal.c:2908
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
  - fs/select.c:poll_select_finish
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810ac780-ffffffff810ac7d5: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109b110)
Location: kernel/signal.c:2908
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
  - fs/select.c:poll_select_finish
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff8109b110-ffffffff8109b15f: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810abce0)
Location: kernel/signal.c:2908
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
  - fs/select.c:poll_select_finish
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810abce0-ffffffff810abd35: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b3e60)
Location: kernel/signal.c:2908
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
  - fs/select.c:poll_select_finish
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810b3e60-ffffffff810b3eac: __set_current_blocked (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
