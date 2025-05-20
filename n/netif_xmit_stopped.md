# Function: <code>netif_xmit_stopped</code>

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
In drivers/net/virtio_net.c (0)
Location: include/linux/netdevice.h:2712
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/netdevice.h:2712
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/netdevice.h:2712
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2712
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
In drivers/net/virtio_net.c (0)
Location: include/linux/netdevice.h:2935
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/netdevice.h:2935
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/netdevice.h:2935
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2935
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
In net/core/dev.c (0)
Location: include/linux/netdevice.h:2874
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/netdevice.h:2874
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2874
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
In net/core/dev.c (0)
Location: include/linux/netdevice.h:2901
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/netdevice.h:2901
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2901
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
In net/core/dev.c (0)
Location: include/linux/netdevice.h:2926
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/netdevice.h:2926
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:2926
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
In net/core/dev.c (ffffffff8189479d)
Location: include/linux/netdevice.h:3035
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff818bf775)
Location: include/linux/netdevice.h:3035
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/sched/sch_generic.c (ffffffff818cc74f)
Location: include/linux/netdevice.h:3035
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
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
In net/core/dev.c (ffffffff818b51ad)
Location: include/linux/netdevice.h:3129
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff818e859b)
Location: include/linux/netdevice.h:3129
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/sched/sch_generic.c (ffffffff818f7a9f)
Location: include/linux/netdevice.h:3129
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
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
In net/core/dev.c (ffffffff81901b9e)
Location: include/linux/netdevice.h:3146
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81937ddc)
Location: include/linux/netdevice.h:3146
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/sched/sch_generic.c (ffffffff819571df)
Location: include/linux/netdevice.h:3146
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
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
In net/core/dev.c (ffffffff81933dde)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff8196ac9c)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/sched/sch_generic.c (ffffffff8198d67f)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
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
In net/core/dev.c (ffffffff81a087fe)
Location: include/linux/netdevice.h:3273
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netif_schedule_queue
```
```
In net/core/netpoll.c (ffffffff81a3e7d7)
Location: include/linux/netdevice.h:3273
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
```
```
In net/sched/sch_generic.c (ffffffff81a65372)
Location: include/linux/netdevice.h:3273
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
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
In net/core/dev.c (ffffffff81a09dbe)
Location: include/linux/netdevice.h:3427
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netif_schedule_queue
```
```
In net/core/netpoll.c (ffffffff81a41577)
Location: include/linux/netdevice.h:3427
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
```
```
In net/sched/sch_generic.c (ffffffff81a6d4a2)
Location: include/linux/netdevice.h:3427
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
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
In net/core/dev.c (ffffffff819f074e)
Location: include/linux/netdevice.h:3494
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netif_schedule_queue
```
```
In net/core/netpoll.c (ffffffff81a261e7)
Location: include/linux/netdevice.h:3494
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
```
```
In net/sched/sch_generic.c (ffffffff81a55d22)
Location: include/linux/netdevice.h:3494
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
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
In net/core/dev.c (ffffffff81aa1f3e)
Location: include/linux/netdevice.h:3506
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netif_schedule_queue
```
```
In net/core/netpoll.c (ffffffff81adaf57)
Location: include/linux/netdevice.h:3506
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
```
```
In net/sched/sch_generic.c (ffffffff81b0eab4)
Location: include/linux/netdevice.h:3506
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
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
In net/core/dev.c (ffffffff81c197d8)
Location: include/linux/netdevice.h:3297
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netif_schedule_queue
```
```
In net/core/netpoll.c (ffffffff81c5c413)
Location: include/linux/netdevice.h:3297
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
```
```
In net/sched/sch_generic.c (ffffffff81c957c5)
Location: include/linux/netdevice.h:3297
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
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
In net/core/dev.c (ffffffff81dca818)
Location: include/linux/netdevice.h:3322
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netif_schedule_queue
```
```
In net/core/netpoll.c (ffffffff81e12ac7)
Location: include/linux/netdevice.h:3322
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
```
```
In net/sched/sch_generic.c (ffffffff81e51325)
Location: include/linux/netdevice.h:3322
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
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
In drivers/net/virtio_net.c (ffffffff81c50f0a)
Location: include/linux/netdevice.h:3386
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In net/core/dev.c (ffffffff81e3b399)
Location: include/linux/netdevice.h:3386
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netif_schedule_queue
```
```
In net/core/netpoll.c (ffffffff81e86407)
Location: include/linux/netdevice.h:3386
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
```
```
In net/sched/sch_generic.c (ffffffff81eacb5b)
Location: include/linux/netdevice.h:3386
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
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
In drivers/net/virtio_net.c (ffffffff81d06f47)
Location: include/linux/netdevice.h:3465
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In net/core/dev.c (ffffffff81ef9808)
Location: include/linux/netdevice.h:3465
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netif_schedule_queue
```
```
In net/core/netpoll.c (ffffffff81f48420)
Location: include/linux/netdevice.h:3465
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
```
```
In net/sched/sch_generic.c (ffffffff81f6f618)
Location: include/linux/netdevice.h:3465
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
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
In net/core/dev.c (ffff800010bd20a0)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffff800010c112fc)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/sched/sch_generic.c (ffff800010c38b20)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
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
In net/core/dev.c (c0cecc80)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (c0d29188)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/sched/sch_generic.c (c0d4a684)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
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
In net/core/dev.c (c000000000cb063c)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (c000000000cfdb28)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/sched/sch_generic.c (c000000000d30c10)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
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
In net/core/dev.c (ffffffe00075c62a)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffe00078d512)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/sched/sch_generic.c (ffffffe0007aa0f2)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
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
In net/core/dev.c (ffffffff818d3dde)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff8190ac6c)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/sched/sch_generic.c (ffffffff8192d4ef)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
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
In net/core/dev.c (ffffffff8188dc6e)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff818c4a0c)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/sched/sch_generic.c (ffffffff818e6fef)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
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
In net/core/dev.c (ffffffff81924dde)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff8195bc9c)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/sched/sch_generic.c (ffffffff8197e67f)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
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
In net/core/dev.c (ffffffff8194628e)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff8197e09d)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/sched/sch_generic.c (ffffffff819a038b)
Location: include/linux/netdevice.h:3160
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
</details>
</li>
</ul>

## Differences
