# Function: <code>dev_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81733ae0)
Location: net/core/dev_ioctl.c:393
Inline: False
Direct callers:
  - net/socket.c:sock_do_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
```
**Symbols:**

```
ffffffff81733ae0-ffffffff8173405e: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff8179f590)
Location: net/core/dev_ioctl.c:393
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff8179f590-ffffffff8179fb22: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff817cdf60)
Location: net/core/dev_ioctl.c:393
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff817cdf60-ffffffff817ce4f2: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff817ed440)
Location: net/core/dev_ioctl.c:397
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff817ed440-ffffffff817ed9a1: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81869670)
Location: net/core/dev_ioctl.c:409
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff81869670-ffffffff81869be1: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr, bool *need_copyout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff818b94e0)
Location: net/core/dev_ioctl.c:382
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff818b94e0-ffffffff818b98b9: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr, bool *need_copyout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff818e0120)
Location: net/core/dev_ioctl.c:377
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff818e0120-ffffffff818e0676: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr, bool *need_copyout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev_ioctl.c (0)
Location: net/core/dev_ioctl.c:378
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff8192ecf5-ffffffff8192ed0e: dev_ioctl.cold (STB_LOCAL)
ffffffff8192e790-ffffffff8192ecf5: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr, bool *need_copyout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81960a10)
Location: net/core/dev_ioctl.c:378
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff81960a10-ffffffff81960f7b: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr, bool *need_copyout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81a341a0)
Location: net/core/dev_ioctl.c:385
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff81a341a0-ffffffff81a344fd: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr, bool *need_copyout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81a36370)
Location: net/core/dev_ioctl.c:389
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff81a36370-ffffffff81a367f7: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr, bool *need_copyout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81a1d4e0)
Location: net/core/dev_ioctl.c:389
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff81a1d4e0-ffffffff81a1d974: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr, void *data, bool *need_copyout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81ad0eb0)
Location: net/core/dev_ioctl.c:470
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff81ad0eb0-ffffffff81ad13f8: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr, void *data, bool *need_copyout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81c4e790)
Location: net/core/dev_ioctl.c:473
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff81c4e790-ffffffff81c4ecdc: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr, void *data, bool *need_copyout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81e03840)
Location: net/core/dev_ioctl.c:473
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff81e03840-ffffffff81e03d8c: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr, void *data, bool *need_copyout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81e76010)
Location: net/core/dev_ioctl.c:490
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff81e76010-ffffffff81e7657d: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr, void *data, bool *need_copyout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81f35fc0)
Location: net/core/dev_ioctl.c:672
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff81f35fc0-ffffffff81f36539: dev_ioctl (STB_GLOBAL)
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
int dev_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr, bool *need_copyout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffff800010c04438)
Location: net/core/dev_ioctl.c:378
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffff800010c04438-ffff800010c047f0: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr, bool *need_copyout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (c0d1d654)
Location: net/core/dev_ioctl.c:378
Inline: False
Direct callers:
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
c0d1d654-c0d1dcb4: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr, bool *need_copyout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (c000000000cedf30)
Location: net/core/dev_ioctl.c:378
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
c000000000cedf30-c000000000cee74c: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr, bool *need_copyout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffe000783102)
Location: net/core/dev_ioctl.c:378
Inline: False
Direct callers:
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffe000783102-ffffffe000783402: dev_ioctl (STB_GLOBAL)
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
int dev_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr, bool *need_copyout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff819009e0)
Location: net/core/dev_ioctl.c:378
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff819009e0-ffffffff81900f4b: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr, bool *need_copyout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff818ba810)
Location: net/core/dev_ioctl.c:378
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff818ba810-ffffffff818bad7b: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr, bool *need_copyout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81951a10)
Location: net/core/dev_ioctl.c:378
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff81951a10-ffffffff81951f7b: dev_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr, bool *need_copyout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81973420)
Location: net/core/dev_ioctl.c:378
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
```
**Symbols:**

```
ffffffff81973420-ffffffff819739ba: dev_ioctl (STB_GLOBAL)
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
<b>Param added. </b>
<code>bool *need_copyout</code>
</li>
<li>
<b>Param removed. </b>
<code>void *arg</code>
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
<code>net, cmd, ifr, need_copyout</code> ➡️ <code>net, cmd, ifr, data, need_copyout</code>
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
