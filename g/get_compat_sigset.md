# Function: <code>get_compat_sigset</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_compat_sigset(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8112bb20)
Location: kernel/compat.c:471
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_rt_sigsuspend
  - kernel/signal.c:compat_SyS_rt_sigaction
  - kernel/signal.c:C_SYSC_rt_sigtimedwait
  - kernel/signal.c:compat_SyS_rt_sigprocmask
  - fs/select.c:compat_SyS_ppoll
  - fs/select.c:compat_SyS_pselect6
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/signalfd.c:compat_SyS_signalfd
```
**Symbols:**

```
ffffffff8112bb20-ffffffff8112bb40: get_compat_sigset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_compat_sigset(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8113a350)
Location: kernel/compat.c:436
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigtimedwait
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - fs/select.c:__x32_compat_sys_ppoll
  - fs/select.c:__ia32_compat_sys_ppoll
  - fs/select.c:do_compat_pselect
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/signalfd.c:do_compat_signalfd4
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
```
**Symbols:**

```
ffffffff8113a350-ffffffff8113a370: get_compat_sigset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_compat_sigset(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81145c20)
Location: kernel/compat.c:405
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - fs/signalfd.c:do_compat_signalfd4
```
**Symbols:**

```
ffffffff81145c20-ffffffff81145c40: get_compat_sigset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_compat_sigset(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81150fe0)
Location: kernel/compat.c:338
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - fs/signalfd.c:do_compat_signalfd4
```
**Symbols:**

```
ffffffff81150fe0-ffffffff81151000: get_compat_sigset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_compat_sigset(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8115cc50)
Location: kernel/compat.c:338
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - fs/signalfd.c:do_compat_signalfd4
```
**Symbols:**

```
ffffffff8115cc50-ffffffff8115cc70: get_compat_sigset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_compat_sigset(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116da50)
Location: kernel/compat.c:250
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - fs/signalfd.c:__x32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__x32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
```
**Symbols:**

```
ffffffff8116da50-ffffffff8116da70: get_compat_sigset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_compat_sigset(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116a030)
Location: kernel/compat.c:250
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - fs/signalfd.c:__x32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__x32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
```
**Symbols:**

```
ffffffff8116a030-ffffffff8116a050: get_compat_sigset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_compat_sigset(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116ad10)
Location: kernel/compat.c:250
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - fs/signalfd.c:__x32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__x32_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
```
**Symbols:**

```
ffffffff8116ad10-ffffffff8116ad2d: get_compat_sigset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_compat_sigset(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81190970)
Location: kernel/compat.c:250
Inline: False
Direct callers:
  - kernel/signal.c:__x64_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__x64_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__x64_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__x64_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - fs/signalfd.c:__x64_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__x64_compat_sys_signalfd4
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
```
**Symbols:**

```
ffffffff81190970-ffffffff8119098d: get_compat_sigset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_compat_sigset(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811c0260)
Location: kernel/compat.c:250
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
```
**Symbols:**

```
ffffffff811c0260-ffffffff811c0287: get_compat_sigset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_compat_sigset(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81202500)
Location: kernel/compat.c:250
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
```
**Symbols:**

```
ffffffff81202500-ffffffff81202527: get_compat_sigset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_compat_sigset(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff812178e0)
Location: kernel/compat.c:250
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
```
**Symbols:**

```
ffffffff812178e0-ffffffff81217907: get_compat_sigset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_compat_sigset(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8122f4a0)
Location: kernel/compat.c:250
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - fs/signalfd.c:__ia32_compat_sys_signalfd
  - fs/signalfd.c:__ia32_compat_sys_signalfd4
```
**Symbols:**

```
ffffffff8122f4a0-ffffffff8122f4c7: get_compat_sigset (STB_GLOBAL)
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
int get_compat_sigset(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffff8000101cc408)
Location: kernel/compat.c:338
Inline: False
Direct callers:
  - kernel/signal.c:__arm64_compat_sys_rt_sigsuspend
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__arm64_compat_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - fs/signalfd.c:__arm64_compat_sys_signalfd
  - fs/signalfd.c:__arm64_compat_sys_signalfd4
```
**Symbols:**

```
ffff8000101cc408-ffff8000101cc588: get_compat_sigset (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_compat_sigset(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (c0000000002365d0)
Location: kernel/compat.c:338
Inline: False
Direct callers:
  - arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn
  - arch/powerpc/kernel/signal_32.c:do_setcontext
  - kernel/signal.c:__se_compat_sys_rt_sigsuspend
  - kernel/signal.c:__se_compat_sys_rt_sigaction
  - kernel/signal.c:__se_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__se_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__se_compat_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - fs/signalfd.c:__se_compat_sys_signalfd
  - fs/signalfd.c:__se_compat_sys_signalfd4
```
**Symbols:**

```
c0000000002365d0-c000000000236618: get_compat_sigset (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int get_compat_sigset(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81155270)
Location: kernel/compat.c:338
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - fs/signalfd.c:do_compat_signalfd4
```
**Symbols:**

```
ffffffff81155270-ffffffff81155290: get_compat_sigset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_compat_sigset(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81148590)
Location: kernel/compat.c:338
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - fs/signalfd.c:do_compat_signalfd4
```
**Symbols:**

```
ffffffff81148590-ffffffff811485b0: get_compat_sigset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_compat_sigset(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81153040)
Location: kernel/compat.c:338
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - fs/signalfd.c:do_compat_signalfd4
```
**Symbols:**

```
ffffffff81153040-ffffffff81153060: get_compat_sigset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_compat_sigset(sigset_t *set, const compat_sigset_t *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8115ff40)
Location: kernel/compat.c:338
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - fs/signalfd.c:do_compat_signalfd4
```
**Symbols:**

```
ffffffff8115ff40-ffffffff8115ff60: get_compat_sigset (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
