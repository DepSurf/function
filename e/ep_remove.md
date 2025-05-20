# Function: <code>ep_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81254af0)
Location: fs/eventpoll.c:692
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:SyS_epoll_ctl
```
**Symbols:**

```
ffffffff81254af0-ffffffff81254baf: ep_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8127d320)
Location: fs/eventpoll.c:697
Inline: False
Direct callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffff8127d320-ffffffff8127d3e3: ep_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81290eb0)
Location: fs/eventpoll.c:697
Inline: False
Direct callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffff81290eb0-ffffffff81290f73: ep_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8129dda0)
Location: fs/eventpoll.c:779
Inline: False
Direct callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffff8129dda0-ffffffff8129de63: ep_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812c0f90)
Location: fs/eventpoll.c:763
Inline: False
Direct callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffff812c0f90-ffffffff812c1053: ep_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812eb5c0)
Location: fs/eventpoll.c:765
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffff812eb5c0-ffffffff812eb683: ep_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812ff090)
Location: fs/eventpoll.c:774
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffff812ff090-ffffffff812ff15e: ep_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81320200)
Location: fs/eventpoll.c:774
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffff81320200-ffffffff813202f5: ep_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81332fb0)
Location: fs/eventpoll.c:774
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffff81332fb0-ffffffff813330a5: ep_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8136d3a0)
Location: fs/eventpoll.c:767
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffff8136d3a0-ffffffff8136d495: ep_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8137ad70)
Location: fs/eventpoll.c:673
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffff8137ad70-ffffffff8137aee2: ep_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff813818e0)
Location: fs/eventpoll.c:679
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffff813818e0-ffffffff81381a3c: ep_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff813ceb20)
Location: fs/eventpoll.c:679
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffff813ceb20-ffffffff813cec8d: ep_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81457620)
Location: fs/eventpoll.c:686
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffff81457620-ffffffff8145780e: ep_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff814e68d0)
Location: fs/eventpoll.c:688
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffff814e68d0-ffffffff814e6abe: ep_remove (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffff8000103f0220)
Location: fs/eventpoll.c:774
Inline: False
Direct callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffff8000103f0220-ffff8000103f03e0: ep_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (c05c7608)
Location: fs/eventpoll.c:774
Inline: False
Direct callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
c05c7608-c05c7728: ep_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (c0000000004f9950)
Location: fs/eventpoll.c:774
Inline: False
Direct callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
c0000000004f9950-c0000000004f9ae0: ep_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffe0002a3c8a)
Location: fs/eventpoll.c:774
Inline: False
Direct callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffe0002a3c8a-ffffffe0002a3d9a: ep_remove (STB_LOCAL)
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
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8132b590)
Location: fs/eventpoll.c:774
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffff8132b590-ffffffff8132b685: ep_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8131cef0)
Location: fs/eventpoll.c:774
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffff8131cef0-ffffffff8131cfdf: ep_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81329060)
Location: fs/eventpoll.c:774
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffff81329060-ffffffff81329155: ep_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ep_remove(struct eventpoll *ep, struct epitem *epi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8133b790)
Location: fs/eventpoll.c:774
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffff8133b790-ffffffff8133b883: ep_remove (STB_LOCAL)
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
