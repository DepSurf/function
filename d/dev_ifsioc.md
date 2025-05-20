# Function: <code>dev_ifsioc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int dev_ifsioc(struct net *net, struct socket *sock, unsigned int cmd, struct compat_ifreq *uifr32);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fc21c)
Location: net/socket.c:2867
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
```
```
In net/core/dev_ioctl.c (ffffffff81733720)
Location: net/core/dev_ioctl.c:241
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81733720-ffffffff81733add: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int dev_ifsioc(struct net *net, struct socket *sock, unsigned int cmd, struct compat_ifreq *uifr32);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81762c8b)
Location: net/socket.c:2869
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
```
```
In net/core/dev_ioctl.c (ffffffff8179f160)
Location: net/core/dev_ioctl.c:241
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff8179f160-ffffffff8179f51d: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int dev_ifsioc(struct net *net, struct socket *sock, unsigned int cmd, struct compat_ifreq *uifr32);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8178fd7b)
Location: net/socket.c:2916
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
```
```
In net/core/dev_ioctl.c (ffffffff817cdb30)
Location: net/core/dev_ioctl.c:241
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff817cdb30-ffffffff817cdeed: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int dev_ifsioc(struct net *net, struct socket *sock, unsigned int cmd, struct compat_ifreq *uifr32);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817afb62)
Location: net/socket.c:2966
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
```
In net/core/dev_ioctl.c (ffffffff817ecff0)
Location: net/core/dev_ioctl.c:243
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff817ecff0-ffffffff817ed3cf: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int dev_ifsioc(struct net *net, struct socket *sock, unsigned int cmd, struct compat_ifreq *uifr32);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81827cd2)
Location: net/socket.c:2968
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
```
In net/core/dev_ioctl.c (ffffffff818691e0)
Location: net/core/dev_ioctl.c:244
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff818691e0-ffffffff818695fe: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_ifsioc(struct net *net, struct ifreq *ifr, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff818b8fb0)
Location: net/core/dev_ioctl.c:224
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff818b8fb0-ffffffff818b9383: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_ifsioc(struct net *net, struct ifreq *ifr, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff818dfc00)
Location: net/core/dev_ioctl.c:224
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff818dfc00-ffffffff818dffca: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dev_ifsioc(struct net *net, struct ifreq *ifr, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff8192e270)
Location: net/core/dev_ioctl.c:224
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff8192e270-ffffffff8192e650: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_ifsioc(struct net *net, struct ifreq *ifr, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff819604f0)
Location: net/core/dev_ioctl.c:224
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff819604f0-ffffffff819608d0: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dev_ifsioc(struct net *net, struct ifreq *ifr, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81a33cf0)
Location: net/core/dev_ioctl.c:231
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81a33cf0-ffffffff81a340cc: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dev_ifsioc(struct net *net, struct ifreq *ifr, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81a35e80)
Location: net/core/dev_ioctl.c:241
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81a35e80-ffffffff81a36291: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_ifsioc(struct net *net, struct ifreq *ifr, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81a1cfe0)
Location: net/core/dev_ioctl.c:241
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81a1cfe0-ffffffff81a1d402: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_ifsioc(struct net *net, struct ifreq *ifr, void *data, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81ad0830)
Location: net/core/dev_ioctl.c:310
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81ad0830-ffffffff81ad0d56: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_ifsioc(struct net *net, struct ifreq *ifr, void *data, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81c4e130)
Location: net/core/dev_ioctl.c:312
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81c4e130-ffffffff81c4e63d: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_ifsioc(struct net *net, struct ifreq *ifr, void *data, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81e031c0)
Location: net/core/dev_ioctl.c:312
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81e031c0-ffffffff81e036c5: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_ifsioc(struct net *net, struct ifreq *ifr, void *data, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81e759b0)
Location: net/core/dev_ioctl.c:333
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81e759b0-ffffffff81e75e91: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dev_ifsioc(struct net *net, struct ifreq *ifr, void *data, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev_ioctl.c (0)
Location: net/core/dev_ioctl.c:515
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81f35880-ffffffff81f35e3a: dev_ifsioc (STB_LOCAL)
ffffffff8220fbe8-ffffffff8220fbfd: dev_ifsioc.cold (STB_LOCAL)
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
int dev_ifsioc(struct net *net, struct ifreq *ifr, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffff800010c040a8)
Location: net/core/dev_ioctl.c:224
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffff800010c040a8-ffff800010c04348: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_ifsioc(struct net *net, struct ifreq *ifr, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (c0d1d1c8)
Location: net/core/dev_ioctl.c:224
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
c0d1d1c8-c0d1d58c: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_ifsioc(struct net *net, struct ifreq *ifr, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (c000000000ced870)
Location: net/core/dev_ioctl.c:224
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
c000000000ced870-c000000000cedccc: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_ifsioc(struct net *net, struct ifreq *ifr, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffe000782d88)
Location: net/core/dev_ioctl.c:224
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffe000782d88-ffffffe000782fcc: dev_ifsioc (STB_LOCAL)
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
int dev_ifsioc(struct net *net, struct ifreq *ifr, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff819004c0)
Location: net/core/dev_ioctl.c:224
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff819004c0-ffffffff819008a0: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_ifsioc(struct net *net, struct ifreq *ifr, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff818ba2f0)
Location: net/core/dev_ioctl.c:224
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff818ba2f0-ffffffff818ba6d0: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_ifsioc(struct net *net, struct ifreq *ifr, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff819514f0)
Location: net/core/dev_ioctl.c:224
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff819514f0-ffffffff819518d0: dev_ifsioc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_ifsioc(struct net *net, struct ifreq *ifr, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81972ee0)
Location: net/core/dev_ioctl.c:224
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81972ee0-ffffffff819732c0: dev_ifsioc (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ifreq *ifr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct socket *sock</code>
</li>
<li>
<b>Param removed. </b>
<code>struct compat_ifreq *uifr32</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *data</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, ifr, cmd</code> ➡️ <code>net, ifr, data, cmd</code>
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
