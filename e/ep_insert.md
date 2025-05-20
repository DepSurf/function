# Function: <code>ep_insert</code>

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
In fs/eventpoll.c (ffffffff8125610f)
Location: fs/eventpoll.c:1264
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
In fs/eventpoll.c (ffffffff8127ea25)
Location: fs/eventpoll.c:1293
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
In fs/eventpoll.c (ffffffff812925b5)
Location: fs/eventpoll.c:1293
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
In fs/eventpoll.c (ffffffff8129f627)
Location: fs/eventpoll.c:1430
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
In fs/eventpoll.c (ffffffff812c2a81)
Location: fs/eventpoll.c:1412
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
int ep_insert(struct eventpoll *ep, const struct epoll_event *event, struct file *tfile, int fd, int full_check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812eb990)
Location: fs/eventpoll.c:1415
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
**Symbols:**

```
ffffffff812eb990-ffffffff812ebde3: ep_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ep_insert(struct eventpoll *ep, const struct epoll_event *event, struct file *tfile, int fd, int full_check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812ffbd0)
Location: fs/eventpoll.c:1418
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
**Symbols:**

```
ffffffff812ffbd0-ffffffff81300033: ep_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ep_insert(struct eventpoll *ep, const struct epoll_event *event, struct file *tfile, int fd, int full_check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81320c00)
Location: fs/eventpoll.c:1496
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
**Symbols:**

```
ffffffff81320c00-ffffffff813210b7: ep_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ep_insert(struct eventpoll *ep, const struct epoll_event *event, struct file *tfile, int fd, int full_check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff813339a0)
Location: fs/eventpoll.c:1496
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
**Symbols:**

```
ffffffff813339a0-ffffffff81333e57: ep_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ep_insert(struct eventpoll *ep, const struct epoll_event *event, struct file *tfile, int fd, int full_check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8136df00)
Location: fs/eventpoll.c:1490
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
```
**Symbols:**

```
ffffffff8136df00-ffffffff8136e3aa: ep_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ep_insert(struct eventpoll *ep, const struct epoll_event *event, struct file *tfile, int fd, int full_check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8137b110)
Location: fs/eventpoll.c:1431
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
```
**Symbols:**

```
ffffffff8137b110-ffffffff8137b60b: ep_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ep_insert(struct eventpoll *ep, const struct epoll_event *event, struct file *tfile, int fd, int full_check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81382ec0)
Location: fs/eventpoll.c:1437
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
```
**Symbols:**

```
ffffffff81382ec0-ffffffff813833d3: ep_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ep_insert(struct eventpoll *ep, const struct epoll_event *event, struct file *tfile, int fd, int full_check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff813d0130)
Location: fs/eventpoll.c:1437
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
```
**Symbols:**

```
ffffffff813d0130-ffffffff813d067e: ep_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ep_insert(struct eventpoll *ep, const struct epoll_event *event, struct file *tfile, int fd, int full_check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81458850)
Location: fs/eventpoll.c:1444
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
```
**Symbols:**

```
ffffffff81458850-ffffffff81458dd7: ep_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ep_insert(struct eventpoll *ep, const struct epoll_event *event, struct file *tfile, int fd, int full_check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff814e7380)
Location: fs/eventpoll.c:1446
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
```
**Symbols:**

```
ffffffff814e7380-ffffffff814e7907: ep_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ep_insert(struct eventpoll *ep, const struct epoll_event *event, struct file *tfile, int fd, int full_check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8151f1a0)
Location: fs/eventpoll.c:1485
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
```
**Symbols:**

```
ffffffff8151f1a0-ffffffff8151f7a3: ep_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ep_insert(struct eventpoll *ep, const struct epoll_event *event, struct file *tfile, int fd, int full_check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff815537b0)
Location: fs/eventpoll.c:1476
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
```
**Symbols:**

```
ffffffff815537b0-ffffffff81553db3: ep_insert (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffff8000103f1750)
Location: fs/eventpoll.c:1496
Inline: True
Direct callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
```
**Symbols:**

```
ffff8000103f1750-ffff8000103f1ce8: ep_insert.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ep_insert(struct eventpoll *ep, const struct epoll_event *event, struct file *tfile, int fd, int full_check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (c05c7120)
Location: fs/eventpoll.c:1496
Inline: False
Direct callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
```
**Symbols:**

```
c05c7120-c05c7608: ep_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (c0000000004f8f70)
Location: fs/eventpoll.c:1496
Inline: True
Direct callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
```
**Symbols:**

```
c0000000004f8f70-c0000000004f95dc: ep_insert.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ep_insert(struct eventpoll *ep, const struct epoll_event *event, struct file *tfile, int fd, int full_check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffe0002a3ff2)
Location: fs/eventpoll.c:1496
Inline: False
Direct callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
```
**Symbols:**

```
ffffffe0002a3ff2-ffffffe0002a4450: ep_insert (STB_LOCAL)
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
int ep_insert(struct eventpoll *ep, const struct epoll_event *event, struct file *tfile, int fd, int full_check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8132bf80)
Location: fs/eventpoll.c:1496
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
**Symbols:**

```
ffffffff8132bf80-ffffffff8132c437: ep_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ep_insert(struct eventpoll *ep, const struct epoll_event *event, struct file *tfile, int fd, int full_check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8131d2f0)
Location: fs/eventpoll.c:1496
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
**Symbols:**

```
ffffffff8131d2f0-ffffffff8131d79b: ep_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ep_insert(struct eventpoll *ep, const struct epoll_event *event, struct file *tfile, int fd, int full_check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81329a50)
Location: fs/eventpoll.c:1496
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
**Symbols:**

```
ffffffff81329a50-ffffffff81329f07: ep_insert (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff8133bea9)
Location: fs/eventpoll.c:1496
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
</ul>
