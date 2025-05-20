# Function: <code>do_epoll_pwait</code>

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
In fs/eventpoll.c (ffffffff8137c2cb)
Location: fs/eventpoll.c:2240
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
**Symbols:**

```
ffffffff8137bde0-ffffffff8137be52: do_epoll_pwait.part.0 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff81382a2b)
Location: fs/eventpoll.c:2246
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
**Symbols:**

```
ffffffff81382540-ffffffff813825b2: do_epoll_pwait.part.0 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff813cfc9b)
Location: fs/eventpoll.c:2247
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
**Symbols:**

```
ffffffff813cf7b0-ffffffff813cf822: do_epoll_pwait.part.0 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff8145868b)
Location: fs/eventpoll.c:2276
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
**Symbols:**

```
ffffffff81458490-ffffffff81458516: do_epoll_pwait.part.0 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff814e7ffb)
Location: fs/eventpoll.c:2278
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
**Symbols:**

```
ffffffff814e7de0-ffffffff814e7e66: do_epoll_pwait.part.0 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff8151e2cb)
Location: fs/eventpoll.c:2346
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
**Symbols:**

```
ffffffff8151e0b0-ffffffff8151e136: do_epoll_pwait.part.0 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff815528ab)
Location: fs/eventpoll.c:2337
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
**Symbols:**

```
ffffffff81552690-ffffffff81552716: do_epoll_pwait.part.0 (STB_LOCAL)
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
