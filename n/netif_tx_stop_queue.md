# Function: <code>netif_tx_stop_queue</code>

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
In drivers/net/virtio_net.c (ffffffff815f2729)
Location: include/linux/netdevice.h:2677
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f7aa9)
Location: include/linux/netdevice.h:2677
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff815faf0c)
Location: include/linux/netdevice.h:2677
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81713cb5)
Location: include/linux/netdevice.h:2677
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
In drivers/net/virtio_net.c (ffffffff8165206f)
Location: include/linux/netdevice.h:2900
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81657c58)
Location: include/linux/netdevice.h:2900
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff8165adf4)
Location: include/linux/netdevice.h:2900
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff8177baa6)
Location: include/linux/netdevice.h:2900
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
In drivers/net/ppp/ppp_generic.c (ffffffff81685938)
Location: include/linux/netdevice.h:2839
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81688b67)
Location: include/linux/netdevice.h:2839
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff817a9246)
Location: include/linux/netdevice.h:2839
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
In drivers/net/ppp/ppp_generic.c (ffffffff8169ad64)
Location: include/linux/netdevice.h:2866
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff8169e35e)
Location: include/linux/netdevice.h:2866
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff817c77e6)
Location: include/linux/netdevice.h:2866
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
In drivers/net/ppp/ppp_generic.c (ffffffff81705527)
Location: include/linux/netdevice.h:2891
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81709501)
Location: include/linux/netdevice.h:2891
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff818413c6)
Location: include/linux/netdevice.h:2891
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
In drivers/net/ppp/ppp_generic.c (ffffffff817449a8)
Location: include/linux/netdevice.h:3000
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81747fc7)
Location: include/linux/netdevice.h:3000
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff8188bac5)
Location: include/linux/netdevice.h:3000
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
In drivers/net/ppp/ppp_generic.c (ffffffff81768aa2)
Location: include/linux/netdevice.h:3094
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff8176c094)
Location: include/linux/netdevice.h:3094
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff818acc25)
Location: include/linux/netdevice.h:3094
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
In drivers/net/ppp/ppp_generic.c (ffffffff817a68dd)
Location: include/linux/netdevice.h:3111
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff817a9ea0)
Location: include/linux/netdevice.h:3111
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff818f83a5)
Location: include/linux/netdevice.h:3111
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
In drivers/net/ppp/ppp_generic.c (ffffffff817ca322)
Location: include/linux/netdevice.h:3124
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff817cd908)
Location: include/linux/netdevice.h:3124
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff8192a535)
Location: include/linux/netdevice.h:3124
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
In drivers/net/ppp/ppp_generic.c (ffffffff81895372)
Location: include/linux/netdevice.h:3238
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff818994a3)
Location: include/linux/netdevice.h:3238
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81a01245)
Location: include/linux/netdevice.h:3238
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
In drivers/net/ppp/ppp_generic.c (ffffffff818a3a94)
Location: include/linux/netdevice.h:3392
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff818a79c6)
Location: include/linux/netdevice.h:3392
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81a01655)
Location: include/linux/netdevice.h:3392
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
In drivers/net/ppp/ppp_generic.c (ffffffff8188576f)
Location: include/linux/netdevice.h:3459
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff8188b25b)
Location: include/linux/netdevice.h:3459
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff819e7b85)
Location: include/linux/netdevice.h:3459
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
In drivers/net/ppp/ppp_generic.c (ffffffff819170ff)
Location: include/linux/netdevice.h:3471
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff8191df2c)
Location: include/linux/netdevice.h:3471
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81a98b25)
Location: include/linux/netdevice.h:3471
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
In drivers/net/ppp/ppp_generic.c (ffffffff81a6b4bf)
Location: include/linux/netdevice.h:3262
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81a755c8)
Location: include/linux/netdevice.h:3262
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81c0b965)
Location: include/linux/netdevice.h:3262
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
In drivers/net/ppp/ppp_generic.c (ffffffff81bfe35f)
Location: include/linux/netdevice.h:3287
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81c07026)
Location: include/linux/netdevice.h:3287
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81dc27a2)
Location: include/linux/netdevice.h:3287
Inline: True
Inline callers:
  - net/core/dev.c:netif_device_detach
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
In drivers/net/virtio_net.c (ffffffff81c52d75)
Location: include/linux/netdevice.h:3350
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_ringparam
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c639b4)
Location: include/linux/netdevice.h:3350
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81c6c6fa)
Location: include/linux/netdevice.h:3350
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/net/net_failover.c (ffffffff81c6fde4)
Location: include/linux/netdevice.h:3350
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_close
  - drivers/net/net_failover.c:net_failover_open
```
```
In net/core/dev.c (ffffffff81e31bb6)
Location: include/linux/netdevice.h:3350
Inline: True
Inline callers:
  - net/core/dev.c:netif_device_detach
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
In drivers/net/virtio_net.c (ffffffff81d0919e)
Location: include/linux/netdevice.h:3429
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_ringparam
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1a3d4)
Location: include/linux/netdevice.h:3429
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81d210a6)
Location: include/linux/netdevice.h:3429
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/net/net_failover.c (ffffffff81d246a1)
Location: include/linux/netdevice.h:3429
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_close
  - drivers/net/net_failover.c:net_failover_open
```
```
In net/core/dev.c (ffffffff81ef003c)
Location: include/linux/netdevice.h:3429
Inline: True
Inline callers:
  - net/core/dev.c:netif_device_detach
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
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e4628)
Location: include/linux/netdevice.h:3124
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e7aec)
Location: include/linux/netdevice.h:3124
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_start_xmit
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fa070)
Location: include/linux/netdevice.h:3124
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_close
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a01e24)
Location: include/linux/netdevice.h:3124
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffff800010a09740)
Location: include/linux/netdevice.h:3124
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffff800010bcacb8)
Location: include/linux/netdevice.h:3124
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
In drivers/net/ethernet/freescale/fec_main.c (c0ac99c4)
Location: include/linux/netdevice.h:3124
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_start_xmit
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad2ad8)
Location: include/linux/netdevice.h:3124
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_start_xmit
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_start_xmit
```
```
In drivers/net/ppp/ppp_generic.c (c0adf0a8)
Location: include/linux/netdevice.h:3124
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In net/core/dev.c (c0ce2ec8)
Location: include/linux/netdevice.h:3124
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
In drivers/net/ppp/ppp_generic.c (c000000000aaa79c)
Location: include/linux/netdevice.h:3124
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In net/core/dev.c (c000000000ca1bf0)
Location: include/linux/netdevice.h:3124
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
In drivers/net/ppp/ppp_generic.c (ffffffe00062e99c)
Location: include/linux/netdevice.h:3124
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In net/core/dev.c (ffffffe000753404)
Location: include/linux/netdevice.h:3124
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
In drivers/net/ppp/ppp_generic.c (ffffffff8178ee02)
Location: include/linux/netdevice.h:3124
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81792528)
Location: include/linux/netdevice.h:3124
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff818ca535)
Location: include/linux/netdevice.h:3124
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
In drivers/net/ppp/ppp_generic.c (ffffffff81777bd2)
Location: include/linux/netdevice.h:3124
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In net/core/dev.c (ffffffff81884475)
Location: include/linux/netdevice.h:3124
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
In drivers/net/ppp/ppp_generic.c (ffffffff817bf1a2)
Location: include/linux/netdevice.h:3124
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff817c2788)
Location: include/linux/netdevice.h:3124
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff8191b535)
Location: include/linux/netdevice.h:3124
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
In drivers/net/ppp/ppp_generic.c (ffffffff817d9432)
Location: include/linux/netdevice.h:3124
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff817dca48)
Location: include/linux/netdevice.h:3124
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff8193c735)
Location: include/linux/netdevice.h:3124
Inline: True
```
</details>
</li>
</ul>

## Differences
