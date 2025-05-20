# Function: <code>dev_set_mtu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81714880)
Location: net/core/dev.c:6028
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_mtu
```
**Symbols:**

```
ffffffff81714880-ffffffff817149b0: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177c810)
Location: net/core/dev.c:6479
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_mtu
```
**Symbols:**

```
ffffffff8177c810-ffffffff8177c940: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817aacc0)
Location: net/core/dev.c:6623
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_mtu
```
**Symbols:**

```
ffffffff817aacc0-ffffffff817aae5d: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c9320)
Location: net/core/dev.c:6789
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_mtu
```
**Symbols:**

```
ffffffff817c9320-ffffffff817c94ca: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81842fc0)
Location: net/core/dev.c:6953
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_mtu
```
**Symbols:**

```
ffffffff81842fc0-ffffffff8184318b: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7089
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_mtu
```
**Symbols:**

```
ffffffff81898e5b-ffffffff81898ea1: dev_set_mtu.cold.146 (STB_LOCAL)
ffffffff8188d3f0-ffffffff8188d57f: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7714
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_mtu
```
**Symbols:**

```
ffffffff818bb6f6-ffffffff818bb70e: dev_set_mtu.cold.176 (STB_LOCAL)
ffffffff818b9140-ffffffff818b91cc: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7724
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_mtu
```
**Symbols:**

```
ffffffff81907619-ffffffff81907631: dev_set_mtu.cold (STB_LOCAL)
ffffffff819052f0-ffffffff81905380: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8023
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_mtu
```
**Symbols:**

```
ffffffff81939c00-ffffffff81939c18: dev_set_mtu.cold (STB_LOCAL)
ffffffff819379b0-ffffffff81937a40: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8436
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:mtu_store
```
**Symbols:**

```
ffffffff81a0f1a0-ffffffff81a0f1b8: dev_set_mtu.cold (STB_LOCAL)
ffffffff81a0c4f0-ffffffff81a0c580: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8681
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:mtu_store
```
**Symbols:**

```
ffffffff81c314eb-ffffffff81c31503: dev_set_mtu.cold (STB_LOCAL)
ffffffff81a0dbc0-ffffffff81a0dc36: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8940
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_mtu
```
**Symbols:**

```
ffffffff81c237d0-ffffffff81c237e8: dev_set_mtu.cold (STB_LOCAL)
ffffffff819f48d0-ffffffff819f4946: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8930
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_mtu
```
**Symbols:**

```
ffffffff81d366fd-ffffffff81d36715: dev_set_mtu.cold (STB_LOCAL)
ffffffff81aa6200-ffffffff81aa6276: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8695
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:mtu_store
```
**Symbols:**

```
ffffffff81f02ecf-ffffffff81f02ee7: dev_set_mtu.cold (STB_LOCAL)
ffffffff81c1dcd0-ffffffff81c1dd4e: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dcf010)
Location: net/core/dev.c:8682
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:mtu_store
```
**Symbols:**

```
ffffffff81dcf010-ffffffff81dcf0ae: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3fc40)
Location: net/core/dev.c:8688
Inline: False
Direct callers:
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_change_mtu
  - drivers/net/net_failover.c:net_failover_change_mtu
  - drivers/net/net_failover.c:net_failover_change_mtu
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:mtu_store
```
**Symbols:**

```
ffffffff81e3fc40-ffffffff81e3fcde: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81efe590)
Location: net/core/dev.c:8806
Inline: False
Direct callers:
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_change_mtu
  - drivers/net/net_failover.c:net_failover_change_mtu
  - drivers/net/net_failover.c:net_failover_change_mtu
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:mtu_store
```
**Symbols:**

```
ffffffff81efe590-ffffffff81efe633: dev_set_mtu (STB_GLOBAL)
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
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd63c8)
Location: net/core/dev.c:8023
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_mtu
```
**Symbols:**

```
ffff800010bd63c8-ffff800010bd6470: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cf0f70)
Location: net/core/dev.c:8023
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_mtu
```
**Symbols:**

```
c0cf0f70-c0cf1024: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb5d50)
Location: net/core/dev.c:8023
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_mtu
```
**Symbols:**

```
c000000000cb5d50-c000000000cb5e1c: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075fb48)
Location: net/core/dev.c:8023
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_mtu
```
**Symbols:**

```
ffffffe00075fb48-ffffffe00075fbc0: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8023
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_mtu
```
**Symbols:**

```
ffffffff818d9bd0-ffffffff818d9be8: dev_set_mtu.cold (STB_LOCAL)
ffffffff818d7980-ffffffff818d7a10: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8023
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_mtu
  - net/ipv4/ip_tunnel.c:ip_tunnel_newlink
  - net/ipv4/ip_tunnel.c:ip_tunnel_ioctl
```
**Symbols:**

```
ffffffff81893a10-ffffffff81893a28: dev_set_mtu.cold (STB_LOCAL)
ffffffff818917c0-ffffffff81891850: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8023
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_mtu
```
**Symbols:**

```
ffffffff8192ac00-ffffffff8192ac18: dev_set_mtu.cold (STB_LOCAL)
ffffffff819289b0-ffffffff81928a40: dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8023
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/net-sysfs.c:change_mtu
```
**Symbols:**

```
ffffffff8194c2d0-ffffffff8194c2e8: dev_set_mtu.cold (STB_LOCAL)
ffffffff8194a080-ffffffff8194a110: dev_set_mtu (STB_GLOBAL)
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
