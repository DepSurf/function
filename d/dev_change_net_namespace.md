# Function: <code>dev_change_net_namespace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81718610)
Location: net/core/dev.c:7309
Inline: True
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_newlink
```
**Symbols:**

```
ffffffff81718610-ffffffff817189e4: dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81780e60)
Location: net/core/dev.c:7827
Inline: True
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81780e60-ffffffff81781257: dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ae3b0)
Location: net/core/dev.c:7998
Inline: True
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff817ae3b0-ffffffff817ae7a7: dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ccd30)
Location: net/core/dev.c:8192
Inline: True
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff817ccd30-ffffffff817cd0ec: dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81846600)
Location: net/core/dev.c:8371
Inline: True
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81846600-ffffffff81846a27: dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188fcc0)
Location: net/core/dev.c:8621
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff8188fcc0-ffffffff818900c1: dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b0620)
Location: net/core/dev.c:9251
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff818b0620-ffffffff818b0a2f: dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9356
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff819072d7-ffffffff819072ea: dev_change_net_namespace.cold (STB_LOCAL)
ffffffff818fd380-ffffffff818fd790: dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192f990)
Location: net/core/dev.c:9700
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff8192f990-ffffffff8192fddb: dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a04b00)
Location: net/core/dev.c:10155
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81a04b00-ffffffff81a04f1d: dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a05120)
Location: net/core/dev.c:10864
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81a05120-ffffffff81a0553d: dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819edb39)
Location: include/linux/netdevice.h:4036
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit
```
```
In net/core/rtnetlink.c (ffffffff81a049ad)
Location: include/linux/netdevice.h:4036
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9ed6e)
Location: include/linux/netdevice.h:4054
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit
```
```
In net/core/rtnetlink.c (ffffffff81ab6fb0)
Location: include/linux/netdevice.h:4054
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c17b2c)
Location: include/linux/netdevice.h:3844
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_net
```
```
In net/core/rtnetlink.c (ffffffff81c2dcf8)
Location: include/linux/netdevice.h:3844
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc8b4c)
Location: include/linux/netdevice.h:3888
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_net
```
```
In net/core/rtnetlink.c (ffffffff81de0ee9)
Location: include/linux/netdevice.h:3888
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e38f47)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_net
```
```
In net/core/rtnetlink.c (ffffffff81e525d9)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef7249)
Location: include/linux/netdevice.h:4026
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_net
```
```
In net/core/rtnetlink.c (ffffffff81f115a9)
Location: include/linux/netdevice.h:4026
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink_create
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
int dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcce88)
Location: net/core/dev.c:9700
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffff800010bcce88-ffff800010bcd24c: dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce88a4)
Location: net/core/dev.c:9700
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
c0ce88a4-c0ce8ce0: dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000caac20)
Location: net/core/dev.c:9700
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
c000000000caac20-c000000000cab0cc: dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007575aa)
Location: net/core/dev.c:9700
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffe0007575aa-ffffffe0007578f6: dev_change_net_namespace (STB_GLOBAL)
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
int dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cf990)
Location: net/core/dev.c:9700
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff818cf990-ffffffff818cfddb: dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81889ab0)
Location: net/core/dev.c:9700
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81889ab0-ffffffff81889efb: dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81920990)
Location: net/core/dev.c:9700
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81920990-ffffffff81920ddb: dev_change_net_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_change_net_namespace(struct net_device *dev, struct net *net, const char *pat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81942720)
Location: net/core/dev.c:9700
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81942720-ffffffff81942b6b: dev_change_net_namespace (STB_GLOBAL)
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
