# Function: <code>set_compat_user_sigmask</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int set_compat_user_sigmask(const compat_sigset_t *usigmask, sigset_t *set, sigset_t *oldset, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9520)
Location: kernel/signal.c:2821
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll
  - fs/select.c:__ia32_compat_sys_ppoll
  - fs/select.c:do_compat_pselect
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
```
**Symbols:**

```
ffffffff810a9520-ffffffff810a959b: set_compat_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_compat_user_sigmask(const compat_sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ac8a0)
Location: kernel/signal.c:2983
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810ac8a0-ffffffff810ac93f: set_compat_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_compat_user_sigmask(const compat_sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2eb0)
Location: kernel/signal.c:2988
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810b2eb0-ffffffff810b2f4f: set_compat_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_compat_user_sigmask(const compat_sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bb940)
Location: kernel/signal.c:3006
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810bb940-ffffffff810bb9dd: set_compat_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_compat_user_sigmask(const compat_sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6c00)
Location: kernel/signal.c:3026
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810b6c00-ffffffff810b6c9d: set_compat_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_compat_user_sigmask(const compat_sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8180)
Location: kernel/signal.c:3048
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810b8180-ffffffff810b8260: set_compat_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_compat_user_sigmask(const compat_sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ca610)
Location: kernel/signal.c:3133
Inline: False
Direct callers:
  - fs/select.c:__x64_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x64_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/eventpoll.c:__x64_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/aio.c:__x64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x64_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810ca610-ffffffff810ca6f0: set_compat_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_compat_user_sigmask(const compat_sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e1f70)
Location: kernel/signal.c:3113
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - io_uring/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810e1f70-ffffffff810e2045: set_compat_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_compat_user_sigmask(const compat_sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811022f0)
Location: kernel/signal.c:3115
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - io_uring/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff811022f0-ffffffff811023c5: set_compat_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_compat_user_sigmask(const compat_sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110e530)
Location: kernel/signal.c:3139
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - io_uring/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff8110e530-ffffffff8110e605: set_compat_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_compat_user_sigmask(const compat_sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81117eb0)
Location: kernel/signal.c:3150
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - io_uring/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff81117eb0-ffffffff81117f85: set_compat_user_sigmask (STB_GLOBAL)
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
int set_compat_user_sigmask(const compat_sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010ec88)
Location: kernel/signal.c:2988
Inline: False
Direct callers:
  - fs/select.c:__arm64_compat_sys_ppoll_time64
  - fs/select.c:__arm64_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/eventpoll.c:__arm64_compat_sys_epoll_pwait
  - fs/aio.c:__arm64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__arm64_compat_sys_io_pgetevents
  - fs/io_uring.c:__arm64_sys_io_uring_enter
```
**Symbols:**

```
ffff80001010ec88-ffff80001010ed60: set_compat_user_sigmask (STB_GLOBAL)
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
int set_compat_user_sigmask(const compat_sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000156000)
Location: kernel/signal.c:2988
Inline: False
Direct callers:
  - fs/select.c:__se_compat_sys_ppoll_time64
  - fs/select.c:__se_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/eventpoll.c:__se_compat_sys_epoll_pwait
  - fs/aio.c:__se_compat_sys_io_pgetevents_time64
  - fs/aio.c:__se_compat_sys_io_pgetevents
  - fs/io_uring.c:__se_sys_io_uring_enter
```
**Symbols:**

```
c000000000156000-c000000000156100: set_compat_user_sigmask (STB_GLOBAL)
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
int set_compat_user_sigmask(const compat_sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad220)
Location: kernel/signal.c:2988
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810ad220-ffffffff810ad2bf: set_compat_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_compat_user_sigmask(const compat_sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109bba0)
Location: kernel/signal.c:2988
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff8109bba0-ffffffff8109bc3f: set_compat_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_compat_user_sigmask(const compat_sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ac780)
Location: kernel/signal.c:2988
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810ac780-ffffffff810ac81f: set_compat_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_compat_user_sigmask(const compat_sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b48f0)
Location: kernel/signal.c:2988
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810b48f0-ffffffff810b498f: set_compat_user_sigmask (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const compat_sigset_t *umask</code>
</li>
<li>
<b>Param removed. </b>
<code>const compat_sigset_t *usigmask</code>
</li>
<li>
<b>Param removed. </b>
<code>sigset_t *set</code>
</li>
<li>
<b>Param removed. </b>
<code>sigset_t *oldset</code>
</li>
<li>
<b>Param reordered. </b>
<code>usigmask, set, oldset, sigsetsize</code> ➡️ <code>umask, sigsetsize</code>
</li>
</ul>
</details>
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
