# Function: <code>netdev_cap_txqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171cd03)
Location: include/linux/netdevice.h:2863
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
```
```
In net/packet/af_packet.c (ffffffff818036cf)
Location: include/linux/netdevice.h:2863
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_pick_tx_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81785498)
Location: include/linux/netdevice.h:3086
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
```
```
In net/packet/af_packet.c (ffffffff8187478f)
Location: include/linux/netdevice.h:3086
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_pick_tx_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b2aa8)
Location: include/linux/netdevice.h:3025
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
```
```
In net/packet/af_packet.c (ffffffff818a8d7f)
Location: include/linux/netdevice.h:3025
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_pick_tx_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d0298)
Location: include/linux/netdevice.h:3052
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
```
```
In net/packet/af_packet.c (ffffffff818cf8fe)
Location: include/linux/netdevice.h:3052
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81849bfb)
Location: include/linux/netdevice.h:3077
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
```
```
In net/packet/af_packet.c (ffffffff81954871)
Location: include/linux/netdevice.h:3077
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81893de3)
Location: include/linux/netdevice.h:3186
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
```
```
In net/packet/af_packet.c (ffffffff819adb5e)
Location: include/linux/netdevice.h:3186
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b47e3)
Location: include/linux/netdevice.h:3308
Inline: True
Inline callers:
  - net/core/dev.c:netdev_pick_tx
```
```
In net/packet/af_packet.c (ffffffff819e44ef)
Location: include/linux/netdevice.h:3308
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8190110c)
Location: include/linux/netdevice.h:3325
Inline: True
Inline callers:
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/packet/af_packet.c (ffffffff81a534b8)
Location: include/linux/netdevice.h:3325
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193343c)
Location: include/linux/netdevice.h:3339
Inline: True
Inline callers:
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/packet/af_packet.c (ffffffff81a8a0a8)
Location: include/linux/netdevice.h:3339
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a082af)
Location: include/linux/netdevice.h:3452
Inline: True
Inline callers:
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/packet/af_packet.c (ffffffff81b85760)
Location: include/linux/netdevice.h:3452
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_pick_tx_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0983f)
Location: include/linux/netdevice.h:3606
Inline: True
Inline callers:
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/packet/af_packet.c (ffffffff81b95150)
Location: include/linux/netdevice.h:3606
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_pick_tx_queue
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
In net/core/dev.c (ffffffff819f01af)
Location: include/linux/netdevice.h:3691
Inline: True
Inline callers:
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/packet/af_packet.c (ffffffff81b841c8)
Location: include/linux/netdevice.h:3691
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/dev.c (ffffffff81aa15df)
Location: include/linux/netdevice.h:3703
Inline: True
Inline callers:
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/packet/af_packet.c (ffffffff81c502b8)
Location: include/linux/netdevice.h:3703
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/dev.c (ffffffff81c19cb1)
Location: include/linux/netdevice.h:3494
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/packet/af_packet.c (ffffffff81df17db)
Location: include/linux/netdevice.h:3494
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/dev.c (ffffffff81dca989)
Location: include/linux/netdevice.h:3539
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/packet/af_packet.c (ffffffff81fc578b)
Location: include/linux/netdevice.h:3539
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/dev.c (ffffffff81e3b514)
Location: include/linux/netdevice.h:3603
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/packet/af_packet.c (ffffffff82027765)
Location: include/linux/netdevice.h:3603
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_xmit
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
In net/core/dev.c (ffffffff81ef9b58)
Location: include/linux/netdevice.h:3692
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/packet/af_packet.c (ffffffff820f6fbb)
Location: include/linux/netdevice.h:3692
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_xmit
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd1510)
Location: include/linux/netdevice.h:3339
Inline: True
Inline callers:
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/packet/af_packet.c (ffff800010d576f0)
Location: include/linux/netdevice.h:3339
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/dev.c (c0cec158)
Location: include/linux/netdevice.h:3339
Inline: True
Inline callers:
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/packet/af_packet.c (c0e57764)
Location: include/linux/netdevice.h:3339
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000caf82c)
Location: include/linux/netdevice.h:3339
Inline: True
Inline callers:
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/packet/af_packet.c (c000000000e90598)
Location: include/linux/netdevice.h:3339
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075ba1e)
Location: include/linux/netdevice.h:3339
Inline: True
Inline callers:
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/packet/af_packet.c (ffffffe00088e882)
Location: include/linux/netdevice.h:3339
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d343c)
Location: include/linux/netdevice.h:3339
Inline: True
Inline callers:
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/packet/af_packet.c (ffffffff81a29738)
Location: include/linux/netdevice.h:3339
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188d2cc)
Location: include/linux/netdevice.h:3339
Inline: True
Inline callers:
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/packet/af_packet.c (ffffffff819e6928)
Location: include/linux/netdevice.h:3339
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192443c)
Location: include/linux/netdevice.h:3339
Inline: True
Inline callers:
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/packet/af_packet.c (ffffffff81a952e8)
Location: include/linux/netdevice.h:3339
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819458cc)
Location: include/linux/netdevice.h:3339
Inline: True
Inline callers:
  - net/core/dev.c:netdev_core_pick_tx
```
```
In net/packet/af_packet.c (ffffffff81aa1708)
Location: include/linux/netdevice.h:3339
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
</details>
</li>
</ul>

## Differences
