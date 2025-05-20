# Function: <code>netdev_get_prio_tc_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171552b)
Location: include/linux/netdevice.h:1855
Inline: True
Inline callers:
  - net/core/dev.c:__skb_tx_hash
  - net/core/dev.c:netif_set_real_num_tx_queues
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177d55c)
Location: include/linux/netdevice.h:1895
Inline: True
Inline callers:
  - net/core/dev.c:__skb_tx_hash
  - net/core/dev.c:netif_set_real_num_tx_queues
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
In net/core/dev.c (ffffffff817aabe4)
Location: include/linux/netdevice.h:1901
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__skb_tx_hash
  - net/core/dev.c:netif_set_real_num_tx_queues
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
In net/core/dev.c (ffffffff817c9214)
Location: include/linux/netdevice.h:1925
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__skb_tx_hash
  - net/core/dev.c:netif_set_real_num_tx_queues
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
In net/core/dev.c (ffffffff81842eb4)
Location: include/linux/netdevice.h:1941
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__skb_tx_hash
  - net/core/dev.c:netif_set_real_num_tx_queues
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
In net/core/dev.c (ffffffff8188d26f)
Location: include/linux/netdevice.h:2009
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:netif_set_real_num_tx_queues
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
In net/core/dev.c (ffffffff818ae5c7)
Location: include/linux/netdevice.h:2063
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/dev.c:netif_set_real_num_tx_queues
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
In net/core/dev.c (ffffffff818f9ef6)
Location: include/linux/netdevice.h:2052
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/dev.c:netif_set_real_num_tx_queues
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
In net/core/dev.c (ffffffff8192c056)
Location: include/linux/netdevice.h:2082
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/dev.c:netif_set_real_num_tx_queues
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
In net/core/dev.c (ffffffff819ff62a)
Location: include/linux/netdevice.h:2150
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/dev.c:netif_set_real_num_tx_queues
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
In net/core/dev.c (ffffffff819ff395)
Location: include/linux/netdevice.h:2198
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/dev.c:netif_set_real_num_tx_queues
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
In net/core/dev.c (ffffffff819e5b8a)
Location: include/linux/netdevice.h:2262
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/dev.c:netif_set_real_num_tx_queues
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
In net/core/dev.c (ffffffff81a95f07)
Location: include/linux/netdevice.h:2282
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/dev.c:netif_set_real_num_tx_queues
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
In net/core/dev.c (ffffffff81c0c91e)
Location: include/linux/netdevice.h:2362
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/dev.c:netif_set_real_num_tx_queues
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
In net/core/dev.c (ffffffff81dbc77e)
Location: include/linux/netdevice.h:2389
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/dev.c:netif_set_real_num_tx_queues
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
In net/core/dev.c (ffffffff81e2cf8e)
Location: include/linux/netdevice.h:2441
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/dev.c:netif_set_real_num_tx_queues
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
In net/core/dev.c (ffffffff81eeb2c7)
Location: include/linux/netdevice.h:2500
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/dev.c:netif_set_real_num_tx_queues
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
In net/core/dev.c (ffff800010bc8744)
Location: include/linux/netdevice.h:2082
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/dev.c:netif_set_real_num_tx_queues
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/ti/cpsw.c (c0ad64c8)
Location: include/linux/netdevice.h:2082
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
```
```
In net/core/dev.c (c0ce3f84)
Location: include/linux/netdevice.h:2082
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/dev.c:netif_set_real_num_tx_queues
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca4740)
Location: include/linux/netdevice.h:2082
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/dev.c:netif_set_real_num_tx_queues
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
In net/core/dev.c (ffffffe000754ba8)
Location: include/linux/netdevice.h:2082
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/dev.c:netif_set_real_num_tx_queues
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
In net/core/dev.c (ffffffff818cc056)
Location: include/linux/netdevice.h:2082
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/dev.c:netif_set_real_num_tx_queues
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
In net/core/dev.c (ffffffff81885f96)
Location: include/linux/netdevice.h:2082
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/dev.c:netif_set_real_num_tx_queues
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
In net/core/dev.c (ffffffff8191d056)
Location: include/linux/netdevice.h:2082
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/dev.c:netif_set_real_num_tx_queues
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
In net/core/dev.c (ffffffff8193e55d)
Location: include/linux/netdevice.h:2082
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/dev.c:netif_set_real_num_tx_queues
```
</details>
</li>
</ul>

## Differences
