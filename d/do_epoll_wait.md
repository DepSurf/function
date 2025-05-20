# Function: <code>do_epoll_wait</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_epoll_wait(int epfd, struct epoll_event *events, int maxevents, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812ea860)
Location: fs/eventpoll.c:2155
Inline: False
Direct callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff812ea860-ffffffff812ea92d: do_epoll_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_epoll_wait(int epfd, struct epoll_event *events, int maxevents, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81300a80)
Location: fs/eventpoll.c:2181
Inline: False
Direct callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff81300a80-ffffffff81300b4d: do_epoll_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_epoll_wait(int epfd, struct epoll_event *events, int maxevents, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81321d20)
Location: fs/eventpoll.c:2259
Inline: False
Direct callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff81321d20-ffffffff81321dee: do_epoll_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_epoll_wait(int epfd, struct epoll_event *events, int maxevents, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81334280)
Location: fs/eventpoll.c:2259
Inline: False
Direct callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff81334280-ffffffff8133434e: do_epoll_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_epoll_wait(int epfd, struct epoll_event *events, int maxevents, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8136e830)
Location: fs/eventpoll.c:2288
Inline: False
Direct callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff8136e830-ffffffff8136e8fe: do_epoll_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_epoll_wait(int epfd, struct epoll_event *events, int maxevents, struct timespec64 *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8137bbf0)
Location: fs/eventpoll.c:2185
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff8137bbf0-ffffffff8137bce0: do_epoll_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_epoll_wait(int epfd, struct epoll_event *events, int maxevents, struct timespec64 *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81382370)
Location: fs/eventpoll.c:2191
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff81382370-ffffffff81382438: do_epoll_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_epoll_wait(int epfd, struct epoll_event *events, int maxevents, struct timespec64 *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff813cf5e0)
Location: fs/eventpoll.c:2192
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff813cf5e0-ffffffff813cf6a8: do_epoll_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_epoll_wait(int epfd, struct epoll_event *events, int maxevents, struct timespec64 *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff814583b0)
Location: fs/eventpoll.c:2221
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff814583b0-ffffffff8145848a: do_epoll_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_epoll_wait(int epfd, struct epoll_event *events, int maxevents, struct timespec64 *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff814e7cf0)
Location: fs/eventpoll.c:2223
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff814e7cf0-ffffffff814e7dca: do_epoll_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_epoll_wait(int epfd, struct epoll_event *events, int maxevents, struct timespec64 *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8151dfa0)
Location: fs/eventpoll.c:2291
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff8151dfa0-ffffffff8151e09d: do_epoll_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_epoll_wait(int epfd, struct epoll_event *events, int maxevents, struct timespec64 *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81552580)
Location: fs/eventpoll.c:2282
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff81552580-ffffffff8155267d: do_epoll_wait (STB_LOCAL)
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
int do_epoll_wait(int epfd, struct epoll_event *events, int maxevents, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffff8000103f2ab0)
Location: fs/eventpoll.c:2259
Inline: False
Direct callers:
  - fs/eventpoll.c:__arm64_compat_sys_epoll_pwait
  - fs/eventpoll.c:__arm64_sys_epoll_pwait
  - fs/eventpoll.c:__arm64_sys_epoll_wait
```
**Symbols:**

```
ffff8000103f2ab0-ffff8000103f2bd0: do_epoll_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_epoll_wait(int epfd, struct epoll_event *events, int maxevents, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (c05c63fc)
Location: fs/eventpoll.c:2259
Inline: False
Direct callers:
  - fs/eventpoll.c:__se_sys_epoll_pwait
  - fs/eventpoll.c:__se_sys_epoll_wait
```
**Symbols:**

```
c05c63fc-c05c68e0: do_epoll_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_epoll_wait(int epfd, struct epoll_event *events, int maxevents, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (c0000000004f8630)
Location: fs/eventpoll.c:2259
Inline: False
Direct callers:
  - fs/eventpoll.c:__se_compat_sys_epoll_pwait
  - fs/eventpoll.c:__se_sys_epoll_pwait
  - fs/eventpoll.c:__se_sys_epoll_wait
```
**Symbols:**

```
c0000000004f8630-c0000000004f8774: do_epoll_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_epoll_wait(int epfd, struct epoll_event *events, int maxevents, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffe0002a31fc)
Location: fs/eventpoll.c:2259
Inline: False
Direct callers:
  - fs/eventpoll.c:__se_sys_epoll_pwait
  - fs/eventpoll.c:__se_sys_epoll_wait
```
**Symbols:**

```
ffffffe0002a31fc-ffffffe0002a3520: do_epoll_wait (STB_LOCAL)
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
int do_epoll_wait(int epfd, struct epoll_event *events, int maxevents, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8132c860)
Location: fs/eventpoll.c:2259
Inline: False
Direct callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff8132c860-ffffffff8132c92e: do_epoll_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_epoll_wait(int epfd, struct epoll_event *events, int maxevents, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8131c130)
Location: fs/eventpoll.c:2259
Inline: False
Direct callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff8131c130-ffffffff8131c1fe: do_epoll_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_epoll_wait(int epfd, struct epoll_event *events, int maxevents, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8132a330)
Location: fs/eventpoll.c:2259
Inline: False
Direct callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff8132a330-ffffffff8132a3fe: do_epoll_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_epoll_wait(int epfd, struct epoll_event *events, int maxevents, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8133ae00)
Location: fs/eventpoll.c:2259
Inline: False
Direct callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
```
**Symbols:**

```
ffffffff8133ae00-ffffffff8133aece: do_epoll_wait (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct timespec64 *to</code>
</li>
<li>
<b>Param removed. </b>
<code>int timeout</code>
</li>
</ul>
</details>
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
