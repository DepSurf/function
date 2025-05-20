# Function: <code>__netif_tx_unlock</code>

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
In net/core/dev.c (ffffffff8171d210)
Location: include/linux/netdevice.h:3299
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81738d58)
Location: include/linux/netdevice.h:3299
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/sched/sch_generic.c (ffffffff81741056)
Location: include/linux/netdevice.h:3299
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/packet/af_packet.c (ffffffff8180386c)
Location: include/linux/netdevice.h:3299
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
In net/core/dev.c (ffffffff81785ae6)
Location: include/linux/netdevice.h:3526
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff817a5439)
Location: include/linux/netdevice.h:3526
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff817aeb55)
Location: include/linux/netdevice.h:3526
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/packet/af_packet.c (ffffffff81874aac)
Location: include/linux/netdevice.h:3526
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
In net/core/dev.c (ffffffff817b30ad)
Location: include/linux/netdevice.h:3491
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff817d3ea8)
Location: include/linux/netdevice.h:3491
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff817de1d5)
Location: include/linux/netdevice.h:3491
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/packet/af_packet.c (ffffffff818a8fcb)
Location: include/linux/netdevice.h:3491
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
In net/core/dev.c (ffffffff817d0b55)
Location: include/linux/netdevice.h:3537
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff817f3228)
Location: include/linux/netdevice.h:3537
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff817fd825)
Location: include/linux/netdevice.h:3537
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/packet/af_packet.c (ffffffff818cf992)
Location: include/linux/netdevice.h:3537
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
In net/core/dev.c (ffffffff8184a4fa)
Location: include/linux/netdevice.h:3566
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff8186e646)
Location: include/linux/netdevice.h:3566
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8187b40e)
Location: include/linux/netdevice.h:3566
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/packet/af_packet.c (ffffffff8195490b)
Location: include/linux/netdevice.h:3566
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
In net/core/dev.c (ffffffff8189482b)
Location: include/linux/netdevice.h:3672
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff818bf7da)
Location: include/linux/netdevice.h:3672
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff818cd8be)
Location: include/linux/netdevice.h:3672
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff819583e3)
Location: include/linux/netdevice.h:3672
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
In net/core/dev.c (ffffffff818b5238)
Location: include/linux/netdevice.h:3898
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff818e8600)
Location: include/linux/netdevice.h:3898
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff818f8afe)
Location: include/linux/netdevice.h:3898
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff8198cc33)
Location: include/linux/netdevice.h:3898
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
In net/core/dev.c (ffffffff81901c28)
Location: include/linux/netdevice.h:3919
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81937e99)
Location: include/linux/netdevice.h:3919
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff819582ce)
Location: include/linux/netdevice.h:3919
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff819f8221)
Location: include/linux/netdevice.h:3919
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
In net/core/dev.c (ffffffff81933e68)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff8196ad59)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8198e77e)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2ee71)
Location: include/linux/netdevice.h:3935
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
In net/core/dev.c (ffffffff81a08889)
Location: include/linux/netdevice.h:4114
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81a3e862)
Location: include/linux/netdevice.h:4114
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81a66532)
Location: include/linux/netdevice.h:4114
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81b21d81)
Location: include/linux/netdevice.h:4114
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
In net/core/dev.c (ffffffff81a09e49)
Location: include/linux/netdevice.h:4282
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81a41602)
Location: include/linux/netdevice.h:4282
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81a6e612)
Location: include/linux/netdevice.h:4282
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81b30756)
Location: include/linux/netdevice.h:4282
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
In net/core/dev.c (ffffffff819f07d9)
Location: include/linux/netdevice.h:4412
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81a26272)
Location: include/linux/netdevice.h:4412
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81a56ea2)
Location: include/linux/netdevice.h:4412
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e086)
Location: include/linux/netdevice.h:4412
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
In drivers/net/xen-netfront.c (ffffffff8191f39c)
Location: include/linux/netdevice.h:4440
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In net/core/dev.c (ffffffff81aa1fc6)
Location: include/linux/netdevice.h:4440
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81adafe2)
Location: include/linux/netdevice.h:4440
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81b0fcd2)
Location: include/linux/netdevice.h:4440
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81be2b76)
Location: include/linux/netdevice.h:4440
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
In net/core/dev.c (ffffffff81c1a3aa)
Location: include/linux/netdevice.h:4304
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81c5c4a2)
Location: include/linux/netdevice.h:4304
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81c945aa)
Location: include/linux/netdevice.h:4304
Inline: True
Inline callers:
  - net/sched/sch_generic.c:netif_freeze_queues
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81d79cf0)
Location: include/linux/netdevice.h:4304
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
In net/core/dev.c (ffffffff81dcb3f8)
Location: include/linux/netdevice.h:4348
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81e12b56)
Location: include/linux/netdevice.h:4348
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81e4ffea)
Location: include/linux/netdevice.h:4348
Inline: True
Inline callers:
  - net/sched/sch_generic.c:netif_freeze_queues
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81f46b00)
Location: include/linux/netdevice.h:4348
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
In drivers/net/virtio_net.c (ffffffff81c4c19c)
Location: include/linux/netdevice.h:4407
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
```
```
In drivers/net/net_failover.c (ffffffff81c6fdec)
Location: include/linux/netdevice.h:4407
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_close
  - drivers/net/net_failover.c:net_failover_open
```
```
In net/core/dev.c (ffffffff81e3bf88)
Location: include/linux/netdevice.h:4407
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81e8646e)
Location: include/linux/netdevice.h:4407
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81eab767)
Location: include/linux/netdevice.h:4407
Inline: True
Inline callers:
  - net/sched/sch_generic.c:netif_freeze_queues
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa6440)
Location: include/linux/netdevice.h:4407
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
In drivers/net/virtio_net.c (ffffffff81d01849)
Location: include/linux/netdevice.h:4483
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
```
```
In drivers/net/net_failover.c (ffffffff81d246a9)
Location: include/linux/netdevice.h:4483
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_close
  - drivers/net/net_failover.c:net_failover_open
```
```
In net/core/dev.c (ffffffff81efa4bd)
Location: include/linux/netdevice.h:4483
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81f48487)
Location: include/linux/netdevice.h:4483
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81f6e204)
Location: include/linux/netdevice.h:4483
Inline: True
Inline callers:
  - net/sched/sch_generic.c:netif_freeze_queues
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff82073730)
Location: include/linux/netdevice.h:4483
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
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e46fc)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109ea7ac)
Location: include/linux/netdevice.h:3935
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
In net/core/dev.c (ffff800010bd20e8)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffff800010c113a0)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffff800010c3a0b8)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffff800010cee248)
Location: include/linux/netdevice.h:3935
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
In drivers/net/ethernet/freescale/fec_main.c (c0accbc8)
Location: include/linux/netdevice.h:3935
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
In net/core/dev.c (c0cecd10)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (c0d29260)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (c0d4c2f8)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (c0df5da8)
Location: include/linux/netdevice.h:3935
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
In net/core/dev.c (c000000000cb0708)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (c000000000cfdc04)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (c000000000d330e0)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (c000000000e12710)
Location: include/linux/netdevice.h:3935
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
In net/core/dev.c (ffffffe00075c6a8)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffe00078d4fa)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffe0007ab1fe)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b1fa)
Location: include/linux/netdevice.h:3935
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
In net/core/dev.c (ffffffff818d3e68)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff8190ad29)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8192e5ee)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff819ce501)
Location: include/linux/netdevice.h:3935
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
In net/core/dev.c (ffffffff8188dcf8)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff818c4ac0)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff818e80ee)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b2f1)
Location: include/linux/netdevice.h:3935
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
In net/core/dev.c (ffffffff81924e68)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff8195bd59)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8197f77e)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81a38f81)
Location: include/linux/netdevice.h:3935
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
In net/core/dev.c (ffffffff81946313)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff8197e133)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff819a1cde)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81a449ab)
Location: include/linux/netdevice.h:3935
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
</details>
</li>
</ul>

## Differences
