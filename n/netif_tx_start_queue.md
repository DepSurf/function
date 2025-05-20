# Function: <code>netif_tx_start_queue</code>

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
In drivers/net/tun.c (ffffffff815ed995)
Location: include/linux/netdevice.h:2627
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/virtio_net.c (ffffffff815f2761)
Location: include/linux/netdevice.h:2627
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff815fd5b9)
Location: include/linux/netdevice.h:2627
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_open
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
In drivers/net/tun.c (ffffffff8164c846)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/virtio_net.c (ffffffff816520a7)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff8165d4a8)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_open
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
In drivers/net/tun.c (ffffffff8167e552)
Location: include/linux/netdevice.h:2789
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/xen-netfront.c (ffffffff8168b296)
Location: include/linux/netdevice.h:2789
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_open
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
In drivers/net/tun.c (ffffffff81693682)
Location: include/linux/netdevice.h:2816
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/xen-netfront.c (ffffffff816a04c9)
Location: include/linux/netdevice.h:2816
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_open
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
In drivers/net/tun.c (ffffffff816fd599)
Location: include/linux/netdevice.h:2841
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/xen-netfront.c (ffffffff8170b689)
Location: include/linux/netdevice.h:2841
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_open
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
In drivers/net/tun.c (ffffffff8173b708)
Location: include/linux/netdevice.h:2950
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/xen-netfront.c (ffffffff8174a38e)
Location: include/linux/netdevice.h:2950
Inline: True
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
In drivers/net/tun.c (ffffffff8175eec8)
Location: include/linux/netdevice.h:3044
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/xen-netfront.c (ffffffff8176e518)
Location: include/linux/netdevice.h:3044
Inline: True
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
In drivers/net/tun.c (ffffffff8179c5c5)
Location: include/linux/netdevice.h:3061
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/xen-netfront.c (ffffffff817ab4e1)
Location: include/linux/netdevice.h:3061
Inline: True
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
In drivers/net/tun.c (ffffffff817c0075)
Location: include/linux/netdevice.h:3074
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/xen-netfront.c (ffffffff817cef21)
Location: include/linux/netdevice.h:3074
Inline: True
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
In drivers/net/tun.c (ffffffff8188b005)
Location: include/linux/netdevice.h:3188
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/xen-netfront.c (ffffffff8189900b)
Location: include/linux/netdevice.h:3188
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_open
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
In drivers/net/tun.c (ffffffff818991a5)
Location: include/linux/netdevice.h:3342
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/xen-netfront.c (ffffffff818a750b)
Location: include/linux/netdevice.h:3342
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_open
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
In drivers/net/tun.c (ffffffff8187a5c5)
Location: include/linux/netdevice.h:3409
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/xen-netfront.c (ffffffff8188adc1)
Location: include/linux/netdevice.h:3409
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_open
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
In drivers/net/tun.c (ffffffff8190bae5)
Location: include/linux/netdevice.h:3421
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/xen-netfront.c (ffffffff8191e136)
Location: include/linux/netdevice.h:3421
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_open
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
In drivers/net/tun.c (ffffffff81a5f415)
Location: include/linux/netdevice.h:3212
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/xen-netfront.c (ffffffff81a725fd)
Location: include/linux/netdevice.h:3212
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_open
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
In drivers/net/tun.c (ffffffff81bea7e5)
Location: include/linux/netdevice.h:3237
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/xen-netfront.c (ffffffff81c07ca4)
Location: include/linux/netdevice.h:3237
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_open
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
In drivers/net/tun.c (ffffffff81c42c27)
Location: include/linux/netdevice.h:3300
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/virtio_net.c (ffffffff81c4f0ae)
Location: include/linux/netdevice.h:3300
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d3bf)
Location: include/linux/netdevice.h:3300
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_open
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
In drivers/net/tun.c (ffffffff81cf82e7)
Location: include/linux/netdevice.h:3379
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/virtio_net.c (ffffffff81d04da7)
Location: include/linux/netdevice.h:3379
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81d21d13)
Location: include/linux/netdevice.h:3379
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_open
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
In drivers/net/tun.c (ffff8000109db5a0)
Location: include/linux/netdevice.h:3074
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e41b4)
Location: include/linux/netdevice.h:3074
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109ea508)
Location: include/linux/netdevice.h:3074
Inline: True
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fad3c)
Location: include/linux/netdevice.h:3074
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_open
```
```
In drivers/net/xen-netfront.c (ffff800010a07460)
Location: include/linux/netdevice.h:3074
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_open
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
In drivers/net/tun.c (c0ac1ed4)
Location: include/linux/netdevice.h:3074
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acc604)
Location: include/linux/netdevice.h:3074
Inline: True
```
```
In drivers/net/ethernet/ti/cpsw_ethtool.c (c0ada88c)
Location: include/linux/netdevice.h:3074
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_resume_data_pass
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
In drivers/net/tun.c (c000000000a9c740)
Location: include/linux/netdevice.h:3074
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
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
In drivers/net/tun.c (ffffffe000625518)
Location: include/linux/netdevice.h:3074
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
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
In drivers/net/tun.c (ffffffff81784b45)
Location: include/linux/netdevice.h:3074
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/xen-netfront.c (ffffffff81793b41)
Location: include/linux/netdevice.h:3074
Inline: True
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
In drivers/net/tun.c (ffffffff81764495)
Location: include/linux/netdevice.h:3074
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
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
In drivers/net/tun.c (ffffffff817b4ef5)
Location: include/linux/netdevice.h:3074
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/xen-netfront.c (ffffffff817c3da1)
Location: include/linux/netdevice.h:3074
Inline: True
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
In drivers/net/tun.c (ffffffff817ceec5)
Location: include/linux/netdevice.h:3074
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_open
```
```
In drivers/net/xen-netfront.c (ffffffff817de051)
Location: include/linux/netdevice.h:3074
Inline: True
```
</details>
</li>
</ul>

## Differences
