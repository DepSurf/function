# Function: <code>netif_tx_wake_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81719040)
Location: net/core/dev.c:2301
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff81719040-ffffffff81719060: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81781770)
Location: net/core/dev.c:2323
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff81781770-ffffffff81781790: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817af080)
Location: net/core/dev.c:2455
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff817af080-ffffffff817af0a0: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cd980)
Location: net/core/dev.c:2467
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff817cd980-ffffffff817cd9a1: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81847000)
Location: net/core/dev.c:2494
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff81847000-ffffffff81847021: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81890660)
Location: net/core/dev.c:2538
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff81890660-ffffffff81890682: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b0f20)
Location: net/core/dev.c:2773
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff818b0f20-ffffffff818b0f42: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fdf30)
Location: net/core/dev.c:2783
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff818fdf30-ffffffff818fdf51: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81930260)
Location: net/core/dev.c:2701
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff81930260-ffffffff81930281: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a05230)
Location: net/core/dev.c:3061
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff81a05230-ffffffff81a05251: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a06840)
Location: net/core/dev.c:3086
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff81a06840-ffffffff81a06866: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ee2f0)
Location: net/core/dev.c:3154
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff819ee2f0-ffffffff819ee316: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9f590)
Location: net/core/dev.c:3075
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
**Symbols:**

```
ffffffff81a9f590-ffffffff81a9f5b6: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c147f0)
Location: net/core/dev.c:3110
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
**Symbols:**

```
ffffffff81c147f0-ffffffff81c1484c: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc63aa)
Location: net/core/dev.c:3095
Inline: True
Inline callers:
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_device_attach
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
```
**Symbols:**

```
ffffffff81dc59e0-ffffffff81dc5a3c: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e35888)
Location: net/core/dev.c:3125
Inline: True
Inline callers:
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_device_attach
Direct callers:
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:skb_xmit_done
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
  - drivers/net/net_failover.c:net_failover_slave_link_change
  - drivers/net/net_failover.c:net_failover_open
```
**Symbols:**

```
ffffffff81e34ca0-ffffffff81e34cfc: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef391b)
Location: net/core/dev.c:3128
Inline: True
Inline callers:
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_device_attach
Direct callers:
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:skb_xmit_done
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
  - drivers/net/net_failover.c:net_failover_slave_link_change
  - drivers/net/net_failover.c:net_failover_open
```
**Symbols:**

```
ffffffff81ef2370-ffffffff81ef23cc: netif_tx_wake_queue (STB_GLOBAL)
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
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bce338)
Location: net/core/dev.c:2701
Inline: True
Direct callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_poll
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffff800010bce338-ffff800010bce3c0: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce6550)
Location: net/core/dev.c:2701
Inline: True
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_tx_timeout
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_start_xmit
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_start_xmit
  - drivers/net/ethernet/ti/cpsw.c:cpsw_adjust_link
  - drivers/net/ethernet/ti/cpsw.c:cpsw_tx_handler
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
c0ce6550-c0ce6588: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca6e60)
Location: net/core/dev.c:2701
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
c000000000ca6e60-c000000000ca6ebc: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffe000755f6e)
Location: net/core/dev.c:2701
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffe000755f6e-ffffffe000755fb0: netif_tx_wake_queue.part.0 (STB_LOCAL)
ffffffe000755fb0-ffffffe000755fe8: netif_tx_wake_queue (STB_GLOBAL)
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
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d0260)
Location: net/core/dev.c:2701
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff818d0260-ffffffff818d0281: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818873f0)
Location: net/core/dev.c:2701
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff818873f0-ffffffff81887411: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81921260)
Location: net/core/dev.c:2701
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff81921260-ffffffff81921281: netif_tx_wake_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void netif_tx_wake_queue(struct netdev_queue *dev_queue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81943160)
Location: net/core/dev.c:2701
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff81943160-ffffffff81943190: netif_tx_wake_queue (STB_GLOBAL)
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
