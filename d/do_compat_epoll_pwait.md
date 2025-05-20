# Function: <code>do_compat_epoll_pwait</code>

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
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff8137c1fc)
Location: fs/eventpoll.c:2291
Inline: True
Inline callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
```
**Symbols:**

```
ffffffff8137bde0-ffffffff8137be52: do_compat_epoll_pwait.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff8138295c)
Location: fs/eventpoll.c:2297
Inline: True
Inline callers:
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
```
**Symbols:**

```
ffffffff81382540-ffffffff813825b2: do_compat_epoll_pwait.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff813cfbcc)
Location: fs/eventpoll.c:2298
Inline: True
Inline callers:
  - fs/eventpoll.c:__x64_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
```
**Symbols:**

```
ffffffff813cf7b0-ffffffff813cf822: do_compat_epoll_pwait.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff8145859b)
Location: fs/eventpoll.c:2327
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
```
**Symbols:**

```
ffffffff81458490-ffffffff81458516: do_compat_epoll_pwait.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff814e7efb)
Location: fs/eventpoll.c:2329
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
```
**Symbols:**

```
ffffffff814e7de0-ffffffff814e7e66: do_compat_epoll_pwait.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff8151e1cb)
Location: fs/eventpoll.c:2397
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
```
**Symbols:**

```
ffffffff8151e0b0-ffffffff8151e136: do_compat_epoll_pwait.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff815527ab)
Location: fs/eventpoll.c:2388
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
```
**Symbols:**

```
ffffffff81552690-ffffffff81552716: do_compat_epoll_pwait.part.0 (STB_LOCAL)
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
