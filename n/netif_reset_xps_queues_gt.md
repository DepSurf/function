# Function: <code>netif_reset_xps_queues_gt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void netif_reset_xps_queues_gt(struct net_device *dev, u16 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817158d0)
Location: net/core/dev.c:1961
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff817158d0-ffffffff81715a12: netif_reset_xps_queues_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void netif_reset_xps_queues_gt(struct net_device *dev, u16 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177d900)
Location: net/core/dev.c:1982
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
```
**Symbols:**

```
ffffffff8177d900-ffffffff8177da42: netif_reset_xps_queues_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ac076)
Location: net/core/dev.c:2070
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ca5df)
Location: net/core/dev.c:2104
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818440c9)
Location: net/core/dev.c:2124
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81898008)
Location: net/core/dev.c:2168
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ba34a)
Location: net/core/dev.c:2266
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fc7ff)
Location: net/core/dev.c:2276
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192ee2d)
Location: net/core/dev.c:2194
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0d970)
Location: net/core/dev.c:2554
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a05b99)
Location: net/core/dev.c:2579
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ec4e3)
Location: net/core/dev.c:2624
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9d3d3)
Location: net/core/dev.c:2499
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c16bca)
Location: net/core/dev.c:2476
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dd0eda)
Location: net/core/dev.c:2461
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e41b08)
Location: net/core/dev.c:2487
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
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
In net/core/dev.c (ffffffff81f004ff)
Location: net/core/dev.c:2490
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcbc8c)
Location: net/core/dev.c:2194
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce9c50)
Location: net/core/dev.c:2194
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void netif_reset_xps_queues_gt(struct net_device *dev, u16 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca7c40)
Location: net/core/dev.c:2194
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
**Symbols:**

```
c000000000ca7c40-c000000000ca7c70: netif_reset_xps_queues_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007595c2)
Location: net/core/dev.c:2194
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cee2d)
Location: net/core/dev.c:2194
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81888f4d)
Location: net/core/dev.c:2194
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191fe2d)
Location: net/core/dev.c:2194
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81941b8d)
Location: net/core/dev.c:2194
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:netdev_unbind_sb_channel
  - net/core/dev.c:netdev_set_num_tc
  - net/core/dev.c:netdev_reset_tc
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
</ul>
<b>Arch</b>
<ul>
</ul>
