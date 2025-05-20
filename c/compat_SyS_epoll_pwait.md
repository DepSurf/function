# Function: <code>compat_SyS_epoll_pwait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int compat_SyS_epoll_pwait(long int epfd, long int events, long int maxevents, long int timeout, long int sigmask, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81256b90)
Location: fs/eventpoll.c:2048
Inline: False
```
**Symbols:**

```
ffffffff81256b90-ffffffff81256da9: compat_SyS_epoll_pwait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int compat_SyS_epoll_pwait(long int epfd, long int events, long int maxevents, long int timeout, long int sigmask, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8127f4d0)
Location: fs/eventpoll.c:2092
Inline: False
```
**Symbols:**

```
ffffffff8127f4d0-ffffffff8127f6e9: compat_SyS_epoll_pwait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int compat_SyS_epoll_pwait(long int epfd, long int events, long int maxevents, long int timeout, long int sigmask, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81293050)
Location: fs/eventpoll.c:2092
Inline: False
```
**Symbols:**

```
ffffffff81293050-ffffffff81293258: compat_SyS_epoll_pwait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int compat_SyS_epoll_pwait(long int epfd, long int events, long int maxevents, long int timeout, long int sigmask, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812a02c0)
Location: fs/eventpoll.c:2253
Inline: False
```
**Symbols:**

```
ffffffff812a02c0-ffffffff812a04f1: compat_SyS_epoll_pwait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int compat_SyS_epoll_pwait(long int epfd, long int events, long int maxevents, long int timeout, long int sigmask, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812c36b0)
Location: fs/eventpoll.c:2235
Inline: False
```
**Symbols:**

```
ffffffff812c36b0-ffffffff812c38ce: compat_SyS_epoll_pwait (STB_GLOBAL)
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
