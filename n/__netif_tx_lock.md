# Function: <code>__netif_tx_lock</code>

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
In net/core/dev.c (ffffffff8171d1e4)
Location: include/linux/netdevice.h:3279
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81738d80)
Location: include/linux/netdevice.h:3279
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81741038)
Location: include/linux/netdevice.h:3279
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/packet/af_packet.c (ffffffff81803818)
Location: include/linux/netdevice.h:3279
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/dev.c (ffffffff81785a91)
Location: include/linux/netdevice.h:3506
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff817a5040)
Location: include/linux/netdevice.h:3506
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff817aeb33)
Location: include/linux/netdevice.h:3506
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/packet/af_packet.c (ffffffff81874a58)
Location: include/linux/netdevice.h:3506
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/dev.c (ffffffff817b3058)
Location: include/linux/netdevice.h:3460
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff817d3ab0)
Location: include/linux/netdevice.h:3460
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff817de1b3)
Location: include/linux/netdevice.h:3460
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/packet/af_packet.c (ffffffff818a8f97)
Location: include/linux/netdevice.h:3460
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/dev.c (ffffffff817d0cb8)
Location: include/linux/netdevice.h:3506
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff817f2e08)
Location: include/linux/netdevice.h:3506
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff817fd803)
Location: include/linux/netdevice.h:3506
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/packet/af_packet.c (ffffffff818cf9d2)
Location: include/linux/netdevice.h:3506
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
In net/core/dev.c (ffffffff8184a52f)
Location: include/linux/netdevice.h:3535
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff8186ec2b)
Location: include/linux/netdevice.h:3535
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8187b3f0)
Location: include/linux/netdevice.h:3535
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/packet/af_packet.c (ffffffff8195494b)
Location: include/linux/netdevice.h:3535
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
In net/core/dev.c (ffffffff818947fe)
Location: include/linux/netdevice.h:3641
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff818bf38c)
Location: include/linux/netdevice.h:3641
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff818cd8a0)
Location: include/linux/netdevice.h:3641
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff819583ae)
Location: include/linux/netdevice.h:3641
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/dev.c (ffffffff818b520b)
Location: include/linux/netdevice.h:3867
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff818e81a9)
Location: include/linux/netdevice.h:3867
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff818f8ae0)
Location: include/linux/netdevice.h:3867
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff8198cbf7)
Location: include/linux/netdevice.h:3867
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/dev.c (ffffffff81901bfd)
Location: include/linux/netdevice.h:3888
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff819383ea)
Location: include/linux/netdevice.h:3888
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff819582b0)
Location: include/linux/netdevice.h:3888
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff819f81ed)
Location: include/linux/netdevice.h:3888
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/dev.c (ffffffff81933e3d)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff8196b2aa)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8198e760)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2ee3d)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/dev.c (ffffffff81a0885e)
Location: include/linux/netdevice.h:4083
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81a3ea5a)
Location: include/linux/netdevice.h:4083
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81a66514)
Location: include/linux/netdevice.h:4083
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81b21d4d)
Location: include/linux/netdevice.h:4083
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/dev.c (ffffffff81a09e1e)
Location: include/linux/netdevice.h:4251
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81a417fa)
Location: include/linux/netdevice.h:4251
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81a6e5f4)
Location: include/linux/netdevice.h:4251
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81b30722)
Location: include/linux/netdevice.h:4251
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/dev.c (ffffffff819f07ae)
Location: include/linux/netdevice.h:4381
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81a26894)
Location: include/linux/netdevice.h:4381
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81a56e84)
Location: include/linux/netdevice.h:4381
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e052)
Location: include/linux/netdevice.h:4381
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In drivers/net/xen-netfront.c (ffffffff8191f37c)
Location: include/linux/netdevice.h:4404
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In net/core/dev.c (ffffffff81aa1f9b)
Location: include/linux/netdevice.h:4404
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81adb614)
Location: include/linux/netdevice.h:4404
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81b0fcb4)
Location: include/linux/netdevice.h:4404
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81be2b42)
Location: include/linux/netdevice.h:4404
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/dev.c (ffffffff81c1a379)
Location: include/linux/netdevice.h:4268
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81c5cad2)
Location: include/linux/netdevice.h:4268
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81c9458c)
Location: include/linux/netdevice.h:4268
Inline: True
Inline callers:
  - net/sched/sch_generic.c:netif_freeze_queues
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81d79cb5)
Location: include/linux/netdevice.h:4268
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/dev.c (ffffffff81dcb413)
Location: include/linux/netdevice.h:4312
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81e131d2)
Location: include/linux/netdevice.h:4312
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81e4ffcc)
Location: include/linux/netdevice.h:4312
Inline: True
Inline callers:
  - net/sched/sch_generic.c:netif_freeze_queues
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81f46ac5)
Location: include/linux/netdevice.h:4312
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In drivers/net/virtio_net.c (ffffffff81c4c140)
Location: include/linux/netdevice.h:4371
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
```
```
In drivers/net/net_failover.c (ffffffff81c6fdce)
Location: include/linux/netdevice.h:4371
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_close
  - drivers/net/net_failover.c:net_failover_open
```
```
In net/core/dev.c (ffffffff81e3bfa3)
Location: include/linux/netdevice.h:4371
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81e86b12)
Location: include/linux/netdevice.h:4371
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81eab749)
Location: include/linux/netdevice.h:4371
Inline: True
Inline callers:
  - net/sched/sch_generic.c:netif_freeze_queues
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa6405)
Location: include/linux/netdevice.h:4371
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In drivers/net/virtio_net.c (ffffffff81d017ed)
Location: include/linux/netdevice.h:4447
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
```
```
In drivers/net/net_failover.c (ffffffff81d2468b)
Location: include/linux/netdevice.h:4447
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_close
  - drivers/net/net_failover.c:net_failover_open
```
```
In net/core/dev.c (ffffffff81efa4d8)
Location: include/linux/netdevice.h:4447
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81f48b22)
Location: include/linux/netdevice.h:4447
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81f6e1e6)
Location: include/linux/netdevice.h:4447
Inline: True
Inline callers:
  - net/sched/sch_generic.c:netif_freeze_queues
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff820736f5)
Location: include/linux/netdevice.h:4447
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e46b8)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109ea768)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
```
```
In net/core/dev.c (ffff800010bd2114)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffff800010c10e70)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffff800010c3a078)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffff800010cee1ec)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In drivers/net/ethernet/freescale/fec_main.c (c0accbb0)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
```
```
In net/core/dev.c (c0cecce4)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (c0d28cdc)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (c0d4c2e0)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (c0df5d68)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/dev.c (c000000000cb06dc)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (c000000000cfdf58)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (c000000000d330bc)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (c000000000e126cc)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/dev.c (ffffffe00075c676)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffe00078daf0)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffe0007ab294)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b1be)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/dev.c (ffffffff818d3e3d)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff8190b27a)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8192e5d0)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff819ce4cd)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/dev.c (ffffffff8188dccd)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff818c5042)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff818e80d0)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b2bd)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/dev.c (ffffffff81924e3d)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff8195c2aa)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8197f760)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81a38f4d)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
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
In net/core/dev.c (ffffffff819462ed)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff8197dc5a)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff819a1cc0)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81a44977)
Location: include/linux/netdevice.h:3904
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
</details>
</li>
</ul>

## Differences
