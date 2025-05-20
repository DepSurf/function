# Function: <code>ep_loop_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812562ea)
Location: fs/eventpoll.c:1732
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8127ec00)
Location: fs/eventpoll.c:1761
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81292790)
Location: fs/eventpoll.c:1761
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8129f809)
Location: fs/eventpoll.c:1922
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812c2c82)
Location: fs/eventpoll.c:1904
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ep_loop_check(struct eventpoll *ep, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812ea1f0)
Location: fs/eventpoll.c:1906
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
**Symbols:**

```
ffffffff812ea1f0-ffffffff812ea28f: ep_loop_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ep_loop_check(struct eventpoll *ep, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812fed60)
Location: fs/eventpoll.c:1932
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
**Symbols:**

```
ffffffff812fed60-ffffffff812fedff: ep_loop_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81321676)
Location: fs/eventpoll.c:2010
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81335466)
Location: fs/eventpoll.c:2010
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8136f1e7)
Location: fs/eventpoll.c:2017
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8137cf95)
Location: fs/eventpoll.c:1931
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
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
In fs/eventpoll.c (ffffffff81383a00)
Location: fs/eventpoll.c:1937
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
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
In fs/eventpoll.c (ffffffff813d0ca0)
Location: fs/eventpoll.c:1938
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
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
In fs/eventpoll.c (ffffffff81459d3e)
Location: fs/eventpoll.c:1967
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
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
In fs/eventpoll.c (ffffffff814e91ae)
Location: fs/eventpoll.c:1969
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
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
In fs/eventpoll.c (ffffffff8151ff4d)
Location: fs/eventpoll.c:2018
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
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
In fs/eventpoll.c (ffffffff8155455d)
Location: fs/eventpoll.c:2009
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffff8000103f23e0)
Location: fs/eventpoll.c:2010
Inline: True
Inline callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
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
In fs/eventpoll.c (c05c7ec0)
Location: fs/eventpoll.c:2010
Inline: True
Inline callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (c0000000004fa55c)
Location: fs/eventpoll.c:2010
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
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
In fs/eventpoll.c (ffffffe0002a49f4)
Location: fs/eventpoll.c:2010
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8132da46)
Location: fs/eventpoll.c:2010
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8131ddd7)
Location: fs/eventpoll.c:2010
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8132b516)
Location: fs/eventpoll.c:2010
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8133c3ff)
Location: fs/eventpoll.c:2010
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
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
</ul>
