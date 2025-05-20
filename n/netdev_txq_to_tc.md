# Function: <code>netdev_txq_to_tc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ad59b)
Location: net/core/dev.c:1968
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:show_xps_map
  - net/core/net-sysfs.c:show_traffic_class
```
**Symbols:**

```
ffffffff817b1ea0-ffffffff817b1ee4: netdev_txq_to_tc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cc14a)
Location: net/core/dev.c:2002
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:show_xps_map
  - net/core/net-sysfs.c:show_traffic_class
```
**Symbols:**

```
ffffffff817cf510-ffffffff817cf558: netdev_txq_to_tc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184581a)
Location: net/core/dev.c:2021
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
**Symbols:**

```
ffffffff81845eb0-ffffffff81845ef8: netdev_txq_to_tc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188edfa)
Location: net/core/dev.c:2065
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
**Symbols:**

```
ffffffff8188f700-ffffffff8188f744: netdev_txq_to_tc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b2958)
Location: net/core/dev.c:2113
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
**Symbols:**

```
ffffffff818aff20-ffffffff818aff65: netdev_txq_to_tc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ff657)
Location: net/core/dev.c:2123
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
**Symbols:**

```
ffffffff818fbcf0-ffffffff818fbd38: netdev_txq_to_tc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81931977)
Location: net/core/dev.c:2041
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
**Symbols:**

```
ffffffff8192e490-ffffffff8192e4d8: netdev_txq_to_tc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0573f)
Location: net/core/dev.c:2401
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
**Symbols:**

```
ffffffff81a00c90-ffffffff81a00cd8: netdev_txq_to_tc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a06f3f)
Location: net/core/dev.c:2426
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
**Symbols:**

```
ffffffff81a010a0-ffffffff81a010e8: netdev_txq_to_tc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ea999)
Location: net/core/dev.c:2491
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
**Symbols:**

```
ffffffff819e7900-ffffffff819e7948: netdev_txq_to_tc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9b849)
Location: net/core/dev.c:2366
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
**Symbols:**

```
ffffffff81a98020-ffffffff81a98068: netdev_txq_to_tc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c12e66)
Location: net/core/dev.c:2343
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
**Symbols:**

```
ffffffff81c0fc00-ffffffff81c0fc4c: netdev_txq_to_tc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc4d24)
Location: net/core/dev.c:2328
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
**Symbols:**

```
ffffffff81dbf700-ffffffff81dbf74c: netdev_txq_to_tc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e33904)
Location: net/core/dev.c:2354
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
**Symbols:**

```
ffffffff81e2f3b0-ffffffff81e2f3fc: netdev_txq_to_tc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef244e)
Location: net/core/dev.c:2358
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
**Symbols:**

```
ffffffff81eee140-ffffffff81eee183: netdev_txq_to_tc (STB_GLOBAL)
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
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bca3a0)
Location: net/core/dev.c:2041
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
**Symbols:**

```
ffff800010bc9858-ffff800010bc98cc: netdev_txq_to_tc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cea3a4)
Location: net/core/dev.c:2041
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
Direct callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_setup_tc
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
**Symbols:**

```
c0ce7c94-c0ce7cf8: netdev_txq_to_tc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cad064)
Location: net/core/dev.c:2041
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
**Symbols:**

```
c000000000ca77d0-c000000000ca7838: netdev_txq_to_tc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075a2fc)
Location: net/core/dev.c:2041
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
**Symbols:**

```
ffffffe000756f2e-ffffffe000756f7e: netdev_txq_to_tc (STB_GLOBAL)
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
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d1977)
Location: net/core/dev.c:2041
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
**Symbols:**

```
ffffffff818ce490-ffffffff818ce4d8: netdev_txq_to_tc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188b807)
Location: net/core/dev.c:2041
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
**Symbols:**

```
ffffffff818885b0-ffffffff818885f8: netdev_txq_to_tc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81922977)
Location: net/core/dev.c:2041
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
**Symbols:**

```
ffffffff8191f490-ffffffff8191f4d8: netdev_txq_to_tc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int netdev_txq_to_tc(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81943da7)
Location: net/core/dev.c:2041
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
Direct callers:
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:traffic_class_show
```
**Symbols:**

```
ffffffff819411f0-ffffffff81941238: netdev_txq_to_tc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
