# Function: <code>set_user_sigmask</code>

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
int set_user_sigmask(const sigset_t *usigmask, sigset_t *set, sigset_t *oldset, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a94b0)
Location: kernel/signal.c:2802
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
```
**Symbols:**

```
ffffffff810a94b0-ffffffff810a951c: set_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_user_sigmask(const sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ac800)
Location: kernel/signal.c:2964
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__do_sys_pselect6
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810ac800-ffffffff810ac896: set_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_user_sigmask(const sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2e10)
Location: kernel/signal.c:2969
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810b2e10-ffffffff810b2ea6: set_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_user_sigmask(const sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bb8a0)
Location: kernel/signal.c:2987
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810bb8a0-ffffffff810bb936: set_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_user_sigmask(const sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6b60)
Location: kernel/signal.c:3007
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810b6b60-ffffffff810b6bf6: set_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_user_sigmask(const sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b80a0)
Location: kernel/signal.c:3029
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810b80a0-ffffffff810b8176: set_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_user_sigmask(const sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ca530)
Location: kernel/signal.c:3114
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810ca530-ffffffff810ca606: set_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_user_sigmask(const sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e1e90)
Location: kernel/signal.c:3094
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - io_uring/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810e1e90-ffffffff810e1f6b: set_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_user_sigmask(const sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81102200)
Location: kernel/signal.c:3096
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - io_uring/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff81102200-ffffffff811022db: set_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_user_sigmask(const sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110e440)
Location: kernel/signal.c:3120
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - io_uring/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff8110e440-ffffffff8110e51b: set_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_user_sigmask(const sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81117dc0)
Location: kernel/signal.c:3131
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - io_uring/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff81117dc0-ffffffff81117e9b: set_user_sigmask (STB_GLOBAL)
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
int set_user_sigmask(const sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010eb48)
Location: kernel/signal.c:2969
Inline: False
Direct callers:
  - fs/select.c:__arm64_sys_ppoll
  - fs/select.c:__arm64_sys_pselect6
  - fs/eventpoll.c:__arm64_sys_epoll_pwait
  - fs/aio.c:__arm64_sys_io_pgetevents
  - fs/io_uring.c:__arm64_sys_io_uring_enter
```
**Symbols:**

```
ffff80001010eb48-ffff80001010ec88: set_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int set_user_sigmask(const sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0366718)
Location: kernel/signal.c:2969
Inline: False
Direct callers:
  - fs/select.c:__se_sys_ppoll_time32
  - fs/select.c:__se_sys_ppoll
  - fs/select.c:do_pselect
  - fs/eventpoll.c:__se_sys_epoll_pwait
  - fs/aio.c:__se_sys_io_pgetevents_time32
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/io_uring.c:__se_sys_io_uring_enter
```
**Symbols:**

```
c0366718-c0366834: set_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int set_user_sigmask(const sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000155f10)
Location: kernel/signal.c:2969
Inline: False
Direct callers:
  - fs/select.c:__se_sys_ppoll
  - fs/select.c:__se_sys_pselect6
  - fs/eventpoll.c:__se_sys_epoll_pwait
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/io_uring.c:__se_sys_io_uring_enter
```
**Symbols:**

```
c000000000155f10-c000000000156000: set_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int set_user_sigmask(const sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cf224)
Location: kernel/signal.c:2969
Inline: False
Direct callers:
  - fs/select.c:__se_sys_ppoll
  - fs/select.c:__se_sys_pselect6
  - fs/eventpoll.c:__se_sys_epoll_pwait
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/io_uring.c:__se_sys_io_uring_enter
```
**Symbols:**

```
ffffffe0000cf224-ffffffe0000cf2a8: set_user_sigmask (STB_GLOBAL)
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
int set_user_sigmask(const sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad180)
Location: kernel/signal.c:2969
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810ad180-ffffffff810ad216: set_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_user_sigmask(const sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109bb00)
Location: kernel/signal.c:2969
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff8109bb00-ffffffff8109bb96: set_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_user_sigmask(const sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ac6e0)
Location: kernel/signal.c:2969
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810ac6e0-ffffffff810ac776: set_user_sigmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_user_sigmask(const sigset_t *umask, size_t sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4850)
Location: kernel/signal.c:2969
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff810b4850-ffffffff810b48e6: set_user_sigmask (STB_GLOBAL)
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
<code>const sigset_t *umask</code>
</li>
<li>
<b>Param removed. </b>
<code>const sigset_t *usigmask</code>
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
