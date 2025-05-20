# Function: <code>netif_tx_wake_all_queues</code>

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
In drivers/net/tun.c (ffffffff815f03e6)
Location: include/linux/netdevice.h:2667
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/virtio_net.c (ffffffff815f3c65)
Location: include/linux/netdevice.h:2667
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_config_changed_work
```
```
In net/core/dev.c (ffffffff8171907c)
Location: include/linux/netdevice.h:2667
Inline: True
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
In drivers/net/tun.c (ffffffff8164fbbb)
Location: include/linux/netdevice.h:2890
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/virtio_net.c (ffffffff816521f1)
Location: include/linux/netdevice.h:2890
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_config_changed_work
```
```
In net/core/dev.c (ffffffff817817ac)
Location: include/linux/netdevice.h:2890
Inline: True
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
In drivers/net/tun.c (ffffffff81681d71)
Location: include/linux/netdevice.h:2829
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/core/dev.c (ffffffff817af0bc)
Location: include/linux/netdevice.h:2829
Inline: True
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
In drivers/net/tun.c (ffffffff81696ce5)
Location: include/linux/netdevice.h:2856
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/core/dev.c (ffffffff817cd9cc)
Location: include/linux/netdevice.h:2856
Inline: True
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
In drivers/net/tun.c (ffffffff81701b7e)
Location: include/linux/netdevice.h:2881
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/core/dev.c (ffffffff8184704c)
Location: include/linux/netdevice.h:2881
Inline: True
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
In drivers/net/tun.c (ffffffff8173df7c)
Location: include/linux/netdevice.h:2990
Inline: True
```
```
In net/core/dev.c (ffffffff818906ad)
Location: include/linux/netdevice.h:2990
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
In drivers/net/tun.c (ffffffff81761ee8)
Location: include/linux/netdevice.h:3084
Inline: True
```
```
In net/core/dev.c (ffffffff818b0f6d)
Location: include/linux/netdevice.h:3084
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
In drivers/net/tun.c (ffffffff8179fbf5)
Location: include/linux/netdevice.h:3101
Inline: True
```
```
In net/core/dev.c (ffffffff818fdf80)
Location: include/linux/netdevice.h:3101
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
In drivers/net/tun.c (ffffffff817c3e85)
Location: include/linux/netdevice.h:3114
Inline: True
```
```
In net/core/dev.c (ffffffff819302b0)
Location: include/linux/netdevice.h:3114
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
In drivers/net/tun.c (ffffffff8188fc76)
Location: include/linux/netdevice.h:3228
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/netdevice.h:3228
Inline: True
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
In drivers/net/tun.c (ffffffff8189e02f)
Location: include/linux/netdevice.h:3382
Inline: True
```
```
In net/core/dev.c (ffffffff81a06896)
Location: include/linux/netdevice.h:3382
Inline: True
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
In drivers/net/tun.c (ffffffff818807ab)
Location: include/linux/netdevice.h:3449
Inline: True
```
```
In net/core/dev.c (ffffffff819ee346)
Location: include/linux/netdevice.h:3449
Inline: True
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
In drivers/net/tun.c (ffffffff81911f43)
Location: include/linux/netdevice.h:3461
Inline: True
```
```
In net/core/dev.c (ffffffff81a9f5e6)
Location: include/linux/netdevice.h:3461
Inline: True
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
In drivers/net/tun.c (ffffffff81a64eb0)
Location: include/linux/netdevice.h:3252
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/netdevice.h:3252
Inline: True
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
In drivers/net/tun.c (ffffffff81bf0101)
Location: include/linux/netdevice.h:3277
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/netdevice.h:3277
Inline: True
Inline callers:
  - net/core/dev.c:netif_device_attach
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
In drivers/net/tun.c (ffffffff81c4867e)
Location: include/linux/netdevice.h:3340
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81c4d2f2)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_config_changed_work
```
```
In drivers/net/net_failover.c (ffffffff81c6fa61)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_link_change
  - drivers/net/net_failover.c:net_failover_open
```
```
In net/core/dev.c (0)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/core/dev.c:netif_device_attach
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
In drivers/net/tun.c (ffffffff81cfe03c)
Location: include/linux/netdevice.h:3419
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81d02e82)
Location: include/linux/netdevice.h:3419
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_config_changed_work
```
```
In drivers/net/net_failover.c (ffffffff81d24311)
Location: include/linux/netdevice.h:3419
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_link_change
  - drivers/net/net_failover.c:net_failover_open
```
```
In net/core/dev.c (0)
Location: include/linux/netdevice.h:3419
Inline: True
Inline callers:
  - net/core/dev.c:netif_device_attach
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
In drivers/net/tun.c (ffff8000109de96c)
Location: include/linux/netdevice.h:3114
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109eab00)
Location: include/linux/netdevice.h:3114
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
```
```
In net/core/dev.c (ffff800010bce438)
Location: include/linux/netdevice.h:3114
Inline: True
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
In drivers/net/tun.c (c0ac3bb8)
Location: include/linux/netdevice.h:3114
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acc9bc)
Location: include/linux/netdevice.h:3114
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad25e0)
Location: include/linux/netdevice.h:3114
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_tx_timeout
  - drivers/net/ethernet/ti/cpsw.c:cpsw_adjust_link
```
```
In net/core/dev.c (c0ce6630)
Location: include/linux/netdevice.h:3114
Inline: True
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
In drivers/net/tun.c (c000000000aa0134)
Location: include/linux/netdevice.h:3114
Inline: True
```
```
In net/core/dev.c (c000000000ca6f18)
Location: include/linux/netdevice.h:3114
Inline: True
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
In drivers/net/tun.c (ffffffe000629180)
Location: include/linux/netdevice.h:3114
Inline: True
```
```
In net/core/dev.c (ffffffe000756024)
Location: include/linux/netdevice.h:3114
Inline: True
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
In drivers/net/tun.c (ffffffff81788965)
Location: include/linux/netdevice.h:3114
Inline: True
```
```
In net/core/dev.c (ffffffff818d02b0)
Location: include/linux/netdevice.h:3114
Inline: True
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
In drivers/net/tun.c (ffffffff817682b5)
Location: include/linux/netdevice.h:3114
Inline: True
```
```
In net/core/dev.c (ffffffff81887440)
Location: include/linux/netdevice.h:3114
Inline: True
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
In drivers/net/tun.c (ffffffff817b8d05)
Location: include/linux/netdevice.h:3114
Inline: True
```
```
In net/core/dev.c (ffffffff819212b0)
Location: include/linux/netdevice.h:3114
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
In drivers/net/tun.c (ffffffff817d39d5)
Location: include/linux/netdevice.h:3114
Inline: True
```
```
In net/core/dev.c (ffffffff819431b0)
Location: include/linux/netdevice.h:3114
Inline: True
```
</details>
</li>
</ul>

## Differences
