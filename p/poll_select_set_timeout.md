# Function: <code>poll_select_set_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec *to, long int sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81220fb0)
Location: fs/select.c:272
Inline: True
Direct callers:
  - fs/select.c:SyS_select
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_poll
  - fs/select.c:SyS_ppoll
  - fs/compat.c:compat_SyS_old_select
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_ppoll
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff81220fb0-ffffffff8122101b: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81248c30)
Location: fs/select.c:272
Inline: True
Direct callers:
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_poll
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_select
  - fs/compat.c:compat_SyS_ppoll
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_old_select
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff81248c30-ffffffff81248c9e: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8125bc60)
Location: fs/select.c:273
Inline: True
Direct callers:
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_poll
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_select
  - fs/compat.c:compat_SyS_ppoll
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_old_select
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff8125bc60-ffffffff8125bcce: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81269cc0)
Location: fs/select.c:273
Inline: True
Direct callers:
  - fs/select.c:compat_SyS_ppoll
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:compat_SyS_old_select
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_poll
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_select
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff81269cc0-ffffffff81269d30: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8128c560)
Location: fs/select.c:274
Inline: True
Direct callers:
  - fs/select.c:compat_SyS_ppoll
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:compat_SyS_old_select
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_poll
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_select
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff8128c560-ffffffff8128c5d0: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec64 *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812b2cf0)
Location: fs/select.c:273
Inline: True
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll
  - fs/select.c:__ia32_compat_sys_ppoll
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_pselect
  - fs/select.c:kern_select
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff812b2cf0-ffffffff812b2d5e: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec64 *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812c7e10)
Location: fs/select.c:273
Inline: True
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll
  - fs/select.c:__ia32_compat_sys_ppoll
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:kern_select
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff812c7e10-ffffffff812c7e7e: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec64 *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812e49b0)
Location: fs/select.c:273
Inline: True
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:__do_sys_pselect6
  - fs/select.c:kern_select
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff812e49b0-ffffffff812e4a22: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec64 *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812f63d0)
Location: fs/select.c:273
Inline: True
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:kern_select
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff812f63d0-ffffffff812f6442: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec64 *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8132f782)
Location: fs/select.c:273
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/select.c:kern_select
Direct callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff8132f9c0-ffffffff8132fa32: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec64 *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8133b0b2)
Location: fs/select.c:273
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/select.c:kern_select
Direct callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff8133b2f0-ffffffff8133b362: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec64 *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81341582)
Location: fs/select.c:273
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/select.c:kern_select
Direct callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff813417c0-ffffffff81341832: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec64 *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8138f092)
Location: fs/select.c:273
Inline: True
Inline callers:
  - fs/select.c:__x64_compat_sys_ppoll_time64
  - fs/select.c:__x64_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x64_compat_sys_ppoll_time32
  - fs/select.c:__x64_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/select.c:kern_select
Direct callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/eventpoll.c:__x64_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff8138f180-ffffffff8138f1f2: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec64 *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81410055)
Location: fs/select.c:274
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/select.c:kern_select
Direct callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff814102b0-ffffffff81410337: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec64 *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8149acd5)
Location: fs/select.c:274
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/select.c:kern_select
Direct callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff8149af50-ffffffff8149afd7: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec64 *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff814cfd85)
Location: fs/select.c:274
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/select.c:kern_select
Direct callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff814d0000-ffffffff814d0087: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec64 *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff815026c5)
Location: fs/select.c:274
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/select.c:kern_select
Direct callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff81502940-ffffffff815029c7: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec64 *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffff8000103a3698)
Location: fs/select.c:273
Inline: True
Direct callers:
  - fs/select.c:__arm64_compat_sys_ppoll_time64
  - fs/select.c:__arm64_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__arm64_sys_ppoll
  - fs/select.c:__arm64_sys_poll
  - fs/select.c:__arm64_sys_pselect6
  - fs/select.c:__arm64_sys_select
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffff8000103a3698-ffff8000103a372c: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec64 *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (c0585e58)
Location: fs/select.c:273
Inline: True
Direct callers:
  - fs/select.c:__se_sys_ppoll_time32
  - fs/select.c:__se_sys_ppoll
  - fs/select.c:__se_sys_poll
  - fs/select.c:do_pselect
  - fs/select.c:kern_select
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
c0585e58-c0585f58: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec64 *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (c00000000049d420)
Location: fs/select.c:273
Inline: True
Direct callers:
  - fs/select.c:__se_compat_sys_ppoll_time64
  - fs/select.c:__se_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__se_sys_ppoll
  - fs/select.c:__se_sys_poll
  - fs/select.c:__se_sys_pselect6
  - fs/select.c:__se_sys_select
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
c00000000049d420-c00000000049d514: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec64 *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffe00026b46c)
Location: fs/select.c:273
Inline: True
Direct callers:
  - fs/select.c:__se_sys_ppoll
  - fs/select.c:__se_sys_poll
  - fs/select.c:__se_sys_pselect6
  - fs/select.c:__se_sys_select
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffe00026b46c-ffffffe00026b4ea: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec64 *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812ee9b0)
Location: fs/select.c:273
Inline: True
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:kern_select
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff812ee9b0-ffffffff812eea22: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec64 *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812df5e0)
Location: fs/select.c:273
Inline: True
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:kern_select
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff812df5e0-ffffffff812df652: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec64 *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812ec7c0)
Location: fs/select.c:273
Inline: True
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:kern_select
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff812ec7c0-ffffffff812ec832: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int poll_select_set_timeout(struct timespec64 *to, time64_t sec, long int nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812fd7c0)
Location: fs/select.c:273
Inline: True
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:kern_select
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff812fd7c0-ffffffff812fd832: poll_select_set_timeout (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long int sec</code> ➡️ <code>time64_t sec</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *to</code> ➡️ <code>struct timespec64 *to</code>
</li>
</ul>
</details>
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
