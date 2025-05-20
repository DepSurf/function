# Function: <code>dev_get_valid_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81718530)
Location: net/core/dev.c:1114
Inline: True
Direct callers:
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
ffffffff81718530-ffffffff8171860a: dev_get_valid_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81780d80)
Location: net/core/dev.c:1118
Inline: True
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff81780d80-ffffffff81780e58: dev_get_valid_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ae2d0)
Location: net/core/dev.c:1117
Inline: True
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff817ae2d0-ffffffff817ae3a8: dev_get_valid_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ccc20)
Location: net/core/dev.c:1149
Inline: True
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff817ccc20-ffffffff817ccd2d: dev_get_valid_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81846560)
Location: net/core/dev.c:1146
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff81846560-ffffffff818465f7: dev_get_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188fc20)
Location: net/core/dev.c:1146
Inline: True
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff8188fc20-ffffffff8188fcb9: dev_get_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b0390)
Location: net/core/dev.c:1148
Inline: True
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff818b0390-ffffffff818b0429: dev_get_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fd0e0)
Location: net/core/dev.c:1144
Inline: True
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff818fd0e0-ffffffff818fd180: dev_get_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192f6f0)
Location: net/core/dev.c:1062
Inline: True
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff8192f6f0-ffffffff8192f790: dev_get_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a02f70)
Location: net/core/dev.c:1255
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff81a02f70-ffffffff81a03017: dev_get_valid_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a04b50)
Location: net/core/dev.c:1257
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff81a04b50-ffffffff81a04c94: dev_get_valid_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e9d70)
Location: net/core/dev.c:1305
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff819e9d70-ffffffff819e9eb3: dev_get_valid_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9aa40)
Location: net/core/dev.c:1180
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff81a9aa40-ffffffff81a9ab83: dev_get_valid_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c141d0)
Location: net/core/dev.c:1127
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff81c141d0-ffffffff81c1431e: dev_get_valid_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc48b0)
Location: net/core/dev.c:1127
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff81dc48b0-ffffffff81dc4995: dev_get_valid_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e34910)
Location: net/core/dev.c:1152
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff81e34910-ffffffff81e349f5: dev_get_valid_name (STB_LOCAL)
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
In net/core/dev.c (ffffffff81f00a0c)
Location: net/core/dev.c:1165
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bccdc0)
Location: net/core/dev.c:1062
Inline: True
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffff800010bccdc0-ffff800010bcce84: dev_get_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce86ac)
Location: net/core/dev.c:1062
Inline: True
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
c0ce86ac-c0ce8758: dev_get_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca9d60)
Location: net/core/dev.c:1062
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
c000000000ca9d60-c000000000ca9e68: dev_get_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007573f8)
Location: net/core/dev.c:1062
Inline: True
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffe0007573f8-ffffffe000757492: dev_get_valid_name (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cf6f0)
Location: net/core/dev.c:1062
Inline: True
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff818cf6f0-ffffffff818cf790: dev_get_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81889810)
Location: net/core/dev.c:1062
Inline: True
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff81889810-ffffffff818898b0: dev_get_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819206f0)
Location: net/core/dev.c:1062
Inline: True
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff819206f0-ffffffff81920790: dev_get_valid_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int dev_get_valid_name(struct net *net, struct net_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81942450)
Location: net/core/dev.c:1062
Inline: True
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff81942450-ffffffff819424f0: dev_get_valid_name (STB_GLOBAL)
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
