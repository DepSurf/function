# Function: <code>netdev_state_change</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81716d60)
Location: net/core/dev.c:1275
Inline: True
Direct callers:
  - net/core/rtnetlink.c:set_operstate
  - net/core/rtnetlink.c:do_setlink
  - net/core/link_watch.c:linkwatch_do_dev
```
**Symbols:**

```
ffffffff81716d60-ffffffff81716dd0: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177ed30)
Location: net/core/dev.c:1279
Inline: True
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
```
**Symbols:**

```
ffffffff8177ed30-ffffffff8177eda0: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ac440)
Location: net/core/dev.c:1278
Inline: True
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
```
**Symbols:**

```
ffffffff817ac440-ffffffff817ac4b0: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cabe0)
Location: net/core/dev.c:1311
Inline: True
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
```
**Symbols:**

```
ffffffff817cabe0-ffffffff817cac50: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81844400)
Location: net/core/dev.c:1332
Inline: True
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
```
**Symbols:**

```
ffffffff81844400-ffffffff8184448f: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188e170)
Location: net/core/dev.c:1333
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
```
**Symbols:**

```
ffffffff8188e170-ffffffff8188e1f2: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818af030)
Location: net/core/dev.c:1335
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
```
**Symbols:**

```
ffffffff818af030-ffffffff818af0b2: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fae70)
Location: net/core/dev.c:1345
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
```
**Symbols:**

```
ffffffff818fae70-ffffffff818faef3: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192cfc0)
Location: net/core/dev.c:1263
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
```
**Symbols:**

```
ffffffff8192cfc0-ffffffff8192d043: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a004b0)
Location: net/core/dev.c:1455
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_close
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/net-sysfs.c:ifalias_store
```
**Symbols:**

```
ffffffff81a004b0-ffffffff81a0052c: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a00a80)
Location: net/core/dev.c:1457
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_close
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/net-sysfs.c:ifalias_store
```
**Symbols:**

```
ffffffff81a00a80-ffffffff81a00afc: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e6f90)
Location: net/core/dev.c:1505
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/net-sysfs.c:ifalias_store
```
**Symbols:**

```
ffffffff819e6f90-ffffffff819e7013: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a979d0)
Location: net/core/dev.c:1380
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/net-sysfs.c:ifalias_store
```
**Symbols:**

```
ffffffff81a979d0-ffffffff81a97a53: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0ee20)
Location: net/core/dev.c:1327
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/net-sysfs.c:ifalias_store
```
**Symbols:**

```
ffffffff81c0ee20-ffffffff81c0eeb0: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbebc0)
Location: net/core/dev.c:1312
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/net-sysfs.c:ifalias_store
```
**Symbols:**

```
ffffffff81dbebc0-ffffffff81dbec5c: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e37e30)
Location: net/core/dev.c:1337
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/net-sysfs.c:ifalias_store
```
**Symbols:**

```
ffffffff81e37e30-ffffffff81e37ecc: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef5e80)
Location: net/core/dev.c:1341
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/net-sysfs.c:ifalias_store
```
**Symbols:**

```
ffffffff81ef5e80-ffffffff81ef5f1c: netdev_state_change (STB_GLOBAL)
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
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc91d8)
Location: net/core/dev.c:1263
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
```
**Symbols:**

```
ffff800010bc91d8-ffff800010bc9258: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce5cfc)
Location: net/core/dev.c:1263
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_close
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
```
**Symbols:**

```
c0ce5cfc-c0ce5d90: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca6970)
Location: net/core/dev.c:1263
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
```
**Symbols:**

```
c000000000ca6970-c000000000ca6a2c: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000755d68)
Location: net/core/dev.c:1263
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_close
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/net-sysfs.c:ifalias_store
```
**Symbols:**

```
ffffffe000755d68-ffffffe000755dc8: netdev_state_change (STB_GLOBAL)
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
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ccfc0)
Location: net/core/dev.c:1263
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
```
**Symbols:**

```
ffffffff818ccfc0-ffffffff818cd043: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81887050)
Location: net/core/dev.c:1263
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
  - net/ipv4/ip_tunnel.c:ip_tunnel_update
```
**Symbols:**

```
ffffffff81887050-ffffffff818870d3: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191dfc0)
Location: net/core/dev.c:1263
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
```
**Symbols:**

```
ffffffff8191dfc0-ffffffff8191e043: netdev_state_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void netdev_state_change(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193f650)
Location: net/core/dev.c:1263
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
  - net/core/link_watch.c:linkwatch_do_dev
```
**Symbols:**

```
ffffffff8193f650-ffffffff8193f6d3: netdev_state_change (STB_GLOBAL)
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
