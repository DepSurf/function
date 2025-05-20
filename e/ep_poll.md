# Function: <code>ep_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812553b0)
Location: fs/eventpoll.c:1585
Inline: False
Direct callers:
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:compat_SyS_epoll_pwait
```
**Symbols:**

```
ffffffff812553b0-ffffffff8125577b: ep_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8127d730)
Location: fs/eventpoll.c:1614
Inline: False
Direct callers:
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
```
**Symbols:**

```
ffffffff8127d730-ffffffff8127da75: ep_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812912c0)
Location: fs/eventpoll.c:1614
Inline: False
Direct callers:
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
```
**Symbols:**

```
ffffffff812912c0-ffffffff81291610: ep_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8129e1b0)
Location: fs/eventpoll.c:1754
Inline: False
Direct callers:
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
```
**Symbols:**

```
ffffffff8129e1b0-ffffffff8129e558: ep_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812c16a0)
Location: fs/eventpoll.c:1736
Inline: False
Direct callers:
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
```
**Symbols:**

```
ffffffff812c16a0-ffffffff812c1a3e: ep_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812ea4a0)
Location: fs/eventpoll.c:1738
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
ffffffff812ea4a0-ffffffff812ea853: ep_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81300630)
Location: fs/eventpoll.c:1747
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
ffffffff81300630-ffffffff81300a72: ep_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81321900)
Location: fs/eventpoll.c:1825
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
ffffffff81321900-ffffffff81321d1e: ep_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81333e60)
Location: fs/eventpoll.c:1825
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
ffffffff81333e60-ffffffff81334275: ep_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8136e3b0)
Location: fs/eventpoll.c:1818
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
ffffffff8136e3b0-ffffffff8136e827: ep_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8137b880)
Location: fs/eventpoll.c:1753
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
ffffffff8137b880-ffffffff8137bbf0: ep_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81382000)
Location: fs/eventpoll.c:1759
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
ffffffff81382000-ffffffff81382370: ep_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff813cf270)
Location: fs/eventpoll.c:1760
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
ffffffff813cf270-ffffffff813cf5de: ep_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81458020)
Location: fs/eventpoll.c:1782
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
ffffffff81458020-ffffffff814583b0: ep_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff814e7950)
Location: fs/eventpoll.c:1784
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
ffffffff814e7950-ffffffff814e7cdd: ep_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8151dc00)
Location: fs/eventpoll.c:1833
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
ffffffff8151dc00-ffffffff8151df90: ep_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff815521e0)
Location: fs/eventpoll.c:1824
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
ffffffff815521e0-ffffffff81552570: ep_poll (STB_LOCAL)
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
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffff8000103f2608)
Location: fs/eventpoll.c:1825
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
ffff8000103f2608-ffff8000103f2aac: ep_poll (STB_LOCAL)
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
In fs/eventpoll.c (c05c64cc)
Location: fs/eventpoll.c:1825
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (c0000000004f8190)
Location: fs/eventpoll.c:1825
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
c0000000004f8190-c0000000004f8630: ep_poll (STB_LOCAL)
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
In fs/eventpoll.c (ffffffe0002a32aa)
Location: fs/eventpoll.c:1825
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
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
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8132c440)
Location: fs/eventpoll.c:1825
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
ffffffff8132c440-ffffffff8132c855: ep_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8131bd30)
Location: fs/eventpoll.c:1825
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
ffffffff8131bd30-ffffffff8131c126: ep_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81329f10)
Location: fs/eventpoll.c:1825
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
ffffffff81329f10-ffffffff8132a325: ep_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ep_poll(struct eventpoll *ep, struct epoll_event *events, int maxevents, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8133a9f0)
Location: fs/eventpoll.c:1825
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
ffffffff8133a9f0-ffffffff8133adf8: ep_poll (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long int timeout</code> ➡️ <code>struct timespec64 *timeout</code>
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
