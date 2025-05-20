# Function: <code>do_epoll_ctl</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_epoll_ctl(int epfd, int op, int fd, struct epoll_event *epds, bool nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8136ed50)
Location: fs/eventpoll.c:2108
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff8136ed50-ffffffff8136f2a8: do_epoll_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_epoll_ctl(int epfd, int op, int fd, struct epoll_event *epds, bool nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8137cb60)
Location: fs/eventpoll.c:2019
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff8137cb60-ffffffff8137d012: do_epoll_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_epoll_ctl(int epfd, int op, int fd, struct epoll_event *epds, bool nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81383500)
Location: fs/eventpoll.c:2025
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81383500-ffffffff81383b32: do_epoll_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_epoll_ctl(int epfd, int op, int fd, struct epoll_event *epds, bool nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff813d07a0)
Location: fs/eventpoll.c:2026
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff813d07a0-ffffffff813d0dd2: do_epoll_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_epoll_ctl(int epfd, int op, int fd, struct epoll_event *epds, bool nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81459770)
Location: fs/eventpoll.c:2055
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - io_uring/io_uring.c:io_epoll_ctl
```
**Symbols:**

```
ffffffff81459770-ffffffff81459fa3: do_epoll_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_epoll_ctl(int epfd, int op, int fd, struct epoll_event *epds, bool nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff814e8be0)
Location: fs/eventpoll.c:2057
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - io_uring/epoll.c:io_epoll_ctl
```
**Symbols:**

```
ffffffff814e8be0-ffffffff814e9413: do_epoll_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_epoll_ctl(int epfd, int op, int fd, struct epoll_event *epds, bool nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8151f940)
Location: fs/eventpoll.c:2119
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - io_uring/epoll.c:io_epoll_ctl
```
**Symbols:**

```
ffffffff8151f940-ffffffff815201be: do_epoll_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_epoll_ctl(int epfd, int op, int fd, struct epoll_event *epds, bool nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81553f50)
Location: fs/eventpoll.c:2110
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - io_uring/epoll.c:io_epoll_ctl
```
**Symbols:**

```
ffffffff81553f50-ffffffff815547ce: do_epoll_ctl (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
