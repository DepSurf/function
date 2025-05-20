# Function: <code>ep_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ep_alloc(struct eventpoll **pep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81255830)
Location: fs/eventpoll.c:935
Inline: False
Direct callers:
  - fs/eventpoll.c:SyS_epoll_create
```
**Symbols:**

```
ffffffff81255830-ffffffff8125590a: ep_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ep_alloc(struct eventpoll **pep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8127e070)
Location: fs/eventpoll.c:940
Inline: False
Direct callers:
  - fs/eventpoll.c:SyS_epoll_create
```
**Symbols:**

```
ffffffff8127e070-ffffffff8127e14a: ep_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ep_alloc(struct eventpoll **pep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81291c00)
Location: fs/eventpoll.c:940
Inline: False
Direct callers:
  - fs/eventpoll.c:SyS_epoll_create
```
**Symbols:**

```
ffffffff81291c00-ffffffff81291cda: ep_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ep_alloc(struct eventpoll **pep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8129e960)
Location: fs/eventpoll.c:1026
Inline: False
Direct callers:
  - fs/eventpoll.c:SyS_epoll_create
```
**Symbols:**

```
ffffffff8129e960-ffffffff8129ea3a: ep_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ep_alloc(struct eventpoll **pep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812c1dd0)
Location: fs/eventpoll.c:1006
Inline: False
Direct callers:
  - fs/eventpoll.c:SyS_epoll_create
```
**Symbols:**

```
ffffffff812c1dd0-ffffffff812c1eb6: ep_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812eb7bd)
Location: fs/eventpoll.c:1008
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812ff28d)
Location: fs/eventpoll.c:1013
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
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
In fs/eventpoll.c (ffffffff8132042e)
Location: fs/eventpoll.c:1013
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
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
In fs/eventpoll.c (ffffffff813331de)
Location: fs/eventpoll.c:1013
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff8136cfc0)
Location: fs/eventpoll.c:1006
Inline: True
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
```
**Symbols:**

```
ffffffff8136cfc0-ffffffff8136d0e8: ep_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff8137a720)
Location: fs/eventpoll.c:923
Inline: True
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
```
**Symbols:**

```
ffffffff8137a720-ffffffff8137a848: ep_alloc.constprop.0 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff81381b6e)
Location: fs/eventpoll.c:929
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
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
In fs/eventpoll.c (ffffffff813cedbe)
Location: fs/eventpoll.c:929
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
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
In fs/eventpoll.c (ffffffff8145798d)
Location: fs/eventpoll.c:936
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
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
In fs/eventpoll.c (ffffffff814e6c6d)
Location: fs/eventpoll.c:938
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
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
In fs/eventpoll.c (ffffffff8151e77d)
Location: fs/eventpoll.c:976
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
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
In fs/eventpoll.c (ffffffff81552d58)
Location: fs/eventpoll.c:975
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
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
In fs/eventpoll.c (ffff8000103f0514)
Location: fs/eventpoll.c:1013
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
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
In fs/eventpoll.c (c05c783c)
Location: fs/eventpoll.c:1013
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
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
In fs/eventpoll.c (c0000000004f9c98)
Location: fs/eventpoll.c:1013
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
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
In fs/eventpoll.c (ffffffe0002a3ec0)
Location: fs/eventpoll.c:1013
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
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
In fs/eventpoll.c (ffffffff8132b7be)
Location: fs/eventpoll.c:1013
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
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
In fs/eventpoll.c (ffffffff8131d10e)
Location: fs/eventpoll.c:1013
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
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
In fs/eventpoll.c (ffffffff8132928e)
Location: fs/eventpoll.c:1013
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
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
In fs/eventpoll.c (ffffffff8133b9ae)
Location: fs/eventpoll.c:1013
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
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
</ul>
