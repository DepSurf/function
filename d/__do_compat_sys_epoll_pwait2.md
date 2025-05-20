# Function: <code>__do_compat_sys_epoll_pwait2</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8137c1d1)
Location: fs/eventpoll.c:2326
Inline: True
Inline callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
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
In fs/eventpoll.c (ffffffff81382931)
Location: fs/eventpoll.c:2332
Inline: True
Inline callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
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
In fs/eventpoll.c (ffffffff813cfba1)
Location: fs/eventpoll.c:2333
Inline: True
Inline callers:
  - fs/eventpoll.c:__x64_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
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
In fs/eventpoll.c (ffffffff8145856c)
Location: fs/eventpoll.c:2362
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
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
In fs/eventpoll.c (ffffffff814e7ecc)
Location: fs/eventpoll.c:2364
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
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
In fs/eventpoll.c (ffffffff8151e19c)
Location: fs/eventpoll.c:2432
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
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
In fs/eventpoll.c (ffffffff8155277c)
Location: fs/eventpoll.c:2423
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
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
