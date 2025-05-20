# Function: <code>netif_reset_xps_queues</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
void netif_reset_xps_queues(struct net_device *dev, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817aaff0)
Location: net/core/dev.c:2040
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff817aaff0-ffffffff817ab157: netif_reset_xps_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void netif_reset_xps_queues(struct net_device *dev, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c9660)
Location: net/core/dev.c:2074
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff817c9660-ffffffff817c97cf: netif_reset_xps_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void netif_reset_xps_queues(struct net_device *dev, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818431f0)
Location: net/core/dev.c:2094
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff818431f0-ffffffff81843359: netif_reset_xps_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void netif_reset_xps_queues(struct net_device *dev, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188d5e0)
Location: net/core/dev.c:2138
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff8188d5e0-ffffffff8188d75c: netif_reset_xps_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void netif_reset_xps_queues(struct net_device *dev, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b3200)
Location: net/core/dev.c:2229
Inline: True
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff818b3200-ffffffff818b32e2: netif_reset_xps_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void netif_reset_xps_queues(struct net_device *dev, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fc0e0)
Location: net/core/dev.c:2239
Inline: True
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff818fc0e0-ffffffff818fc1a4: netif_reset_xps_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void netif_reset_xps_queues(struct net_device *dev, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192e6d0)
Location: net/core/dev.c:2157
Inline: True
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff8192e6d0-ffffffff8192e78d: netif_reset_xps_queues (STB_LOCAL)
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
In net/core/dev.c (ffffffff81a0d970)
Location: net/core/dev.c:2517
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff81a01670-ffffffff81a0172c: netif_reset_xps_queues.part.0 (STB_LOCAL)
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
In net/core/dev.c (ffffffff81a05b99)
Location: net/core/dev.c:2542
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff81a019a0-ffffffff81a01a5c: netif_reset_xps_queues.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void netif_reset_xps_queues(struct net_device *dev, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e86f0)
Location: net/core/dev.c:2606
Inline: True
Direct callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff819e86f0-ffffffff819e8764: netif_reset_xps_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void netif_reset_xps_queues(struct net_device *dev, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a99740)
Location: net/core/dev.c:2481
Inline: True
Direct callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff81a99740-ffffffff81a997ae: netif_reset_xps_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void netif_reset_xps_queues(struct net_device *dev, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c10890)
Location: net/core/dev.c:2458
Inline: True
Direct callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff81c10890-ffffffff81c10911: netif_reset_xps_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void netif_reset_xps_queues(struct net_device *dev, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc0450)
Location: net/core/dev.c:2443
Inline: True
Direct callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff81dc0450-ffffffff81dc04d1: netif_reset_xps_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void netif_reset_xps_queues(struct net_device *dev, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2ffd0)
Location: net/core/dev.c:2469
Inline: True
Direct callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff81e2ffd0-ffffffff81e3005d: netif_reset_xps_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void netif_reset_xps_queues(struct net_device *dev, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eeeba0)
Location: net/core/dev.c:2472
Inline: True
Direct callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff81eeeba0-ffffffff81eeec2d: netif_reset_xps_queues (STB_LOCAL)
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
void netif_reset_xps_queues(struct net_device *dev, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc9c68)
Location: net/core/dev.c:2157
Inline: True
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffff800010bc9c68-ffff800010bc9d4c: netif_reset_xps_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void netif_reset_xps_queues(struct net_device *dev, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce949c)
Location: net/core/dev.c:2157
Inline: True
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
c0ce949c-c0ce9590: netif_reset_xps_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (c000000000ca81f0)
Location: net/core/dev.c:2157
Inline: True
Inline callers:
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netif_reset_xps_queues_gt
Direct callers:
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netif_reset_xps_queues_gt
```
**Symbols:**

```
c000000000ca7b10-c000000000ca7c3c: netif_reset_xps_queues.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void netif_reset_xps_queues(struct net_device *dev, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000758ed4)
Location: net/core/dev.c:2157
Inline: True
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffe000758ed4-ffffffe000758fa2: netif_reset_xps_queues (STB_LOCAL)
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
void netif_reset_xps_queues(struct net_device *dev, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ce6d0)
Location: net/core/dev.c:2157
Inline: True
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff818ce6d0-ffffffff818ce78d: netif_reset_xps_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void netif_reset_xps_queues(struct net_device *dev, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818887f0)
Location: net/core/dev.c:2157
Inline: True
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff818887f0-ffffffff818888ad: netif_reset_xps_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void netif_reset_xps_queues(struct net_device *dev, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191f6d0)
Location: net/core/dev.c:2157
Inline: True
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff8191f6d0-ffffffff8191f78d: netif_reset_xps_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void netif_reset_xps_queues(struct net_device *dev, u16 offset, u16 count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81941430)
Location: net/core/dev.c:2157
Inline: True
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_set_tc_queue
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
ffffffff81941430-ffffffff819414ed: netif_reset_xps_queues (STB_LOCAL)
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
