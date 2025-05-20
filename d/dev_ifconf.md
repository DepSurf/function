# Function: <code>dev_ifconf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fc23c)
Location: net/socket.c:2601
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
```
```
In net/core/dev_ioctl.c (ffffffff81733e0f)
Location: net/core/dev_ioctl.c:67
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81762cab)
Location: net/socket.c:2603
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
```
```
In net/core/dev_ioctl.c (ffffffff8179f8bd)
Location: net/core/dev_ioctl.c:67
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8178fd9b)
Location: net/socket.c:2650
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
```
```
In net/core/dev_ioctl.c (ffffffff817ce28d)
Location: net/core/dev_ioctl.c:67
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817afc25)
Location: net/socket.c:2700
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
```
In net/core/dev_ioctl.c (ffffffff817ed594)
Location: net/core/dev_ioctl.c:68
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81827d95)
Location: net/socket.c:2702
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
```
In net/core/dev_ioctl.c (ffffffff818697ca)
Location: net/core/dev_ioctl.c:69
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_ifconf(struct net *net, struct ifconf *ifc, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff818b9400)
Location: net/core/dev_ioctl.c:53
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff818b9400-ffffffff818b94d1: dev_ifconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_ifconf(struct net *net, struct ifconf *ifc, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff818e0040)
Location: net/core/dev_ioctl.c:53
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff818e0040-ffffffff818e0111: dev_ifconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dev_ifconf(struct net *net, struct ifconf *ifc, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff8192e6c0)
Location: net/core/dev_ioctl.c:53
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff8192e6c0-ffffffff8192e78e: dev_ifconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_ifconf(struct net *net, struct ifconf *ifc, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81960940)
Location: net/core/dev_ioctl.c:53
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff81960940-ffffffff81960a0e: dev_ifconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dev_ifconf(struct net *net, struct ifconf *ifc, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81a340d0)
Location: net/core/dev_ioctl.c:53
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff81a340d0-ffffffff81a3419e: dev_ifconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dev_ifconf(struct net *net, struct ifconf *ifc, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81a362a0)
Location: net/core/dev_ioctl.c:54
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff81a362a0-ffffffff81a3636e: dev_ifconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_ifconf(struct net *net, struct ifconf *ifc, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81a1d410)
Location: net/core/dev_ioctl.c:54
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff81a1d410-ffffffff81a1d4de: dev_ifconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_ifconf(struct net *net, struct ifconf *uifc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81ad0d60)
Location: net/core/dev_ioctl.c:35
Inline: False
Direct callers:
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81ad0d60-ffffffff81ad0ea2: dev_ifconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_ifconf(struct net *net, struct ifconf *uifc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81c4e640)
Location: net/core/dev_ioctl.c:37
Inline: False
Direct callers:
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81c4e640-ffffffff81c4e790: dev_ifconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_ifconf(struct net *net, struct ifconf *uifc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81e036e0)
Location: net/core/dev_ioctl.c:37
Inline: False
Direct callers:
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81e036e0-ffffffff81e03830: dev_ifconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_ifconf(struct net *net, struct ifconf *uifc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81e75eb0)
Location: net/core/dev_ioctl.c:37
Inline: False
Direct callers:
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81e75eb0-ffffffff81e76000: dev_ifconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_ifconf(struct net *net, struct ifconf *uifc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81f35e50)
Location: net/core/dev_ioctl.c:38
Inline: False
Direct callers:
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81f35e50-ffffffff81f35fad: dev_ifconf (STB_GLOBAL)
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
int dev_ifconf(struct net *net, struct ifconf *ifc, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffff800010c04348)
Location: net/core/dev_ioctl.c:53
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffff800010c04348-ffff800010c04434: dev_ifconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_ifconf(struct net *net, struct ifconf *ifc, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (c0d1d58c)
Location: net/core/dev_ioctl.c:53
Inline: False
Direct callers:
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
c0d1d58c-c0d1d654: dev_ifconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_ifconf(struct net *net, struct ifconf *ifc, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (c000000000ceddb0)
Location: net/core/dev_ioctl.c:53
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
c000000000ceddb0-c000000000cedf2c: dev_ifconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_ifconf(struct net *net, struct ifconf *ifc, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffe000783050)
Location: net/core/dev_ioctl.c:53
Inline: False
Direct callers:
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffe000783050-ffffffe000783102: dev_ifconf (STB_GLOBAL)
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
int dev_ifconf(struct net *net, struct ifconf *ifc, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81900910)
Location: net/core/dev_ioctl.c:53
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff81900910-ffffffff819009de: dev_ifconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_ifconf(struct net *net, struct ifconf *ifc, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff818ba740)
Location: net/core/dev_ioctl.c:53
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff818ba740-ffffffff818ba80e: dev_ifconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_ifconf(struct net *net, struct ifconf *ifc, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81951940)
Location: net/core/dev_ioctl.c:53
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff81951940-ffffffff81951a0e: dev_ifconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_ifconf(struct net *net, struct ifconf *ifc, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81973350)
Location: net/core/dev_ioctl.c:53
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff81973350-ffffffff8197341e: dev_ifconf (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ifconf *uifc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ifconf *ifc</code>
</li>
<li>
<b>Param removed. </b>
<code>int size</code>
</li>
</ul>
</details>
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
