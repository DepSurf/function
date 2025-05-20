# Function: <code>dev_xmit_complete</code>

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
In net/core/dev.c (ffffffff8171caa0)
Location: include/linux/netdevice.h:117
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8174145b)
Location: include/linux/netdevice.h:117
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/packet/af_packet.c (ffffffff81803895)
Location: include/linux/netdevice.h:117
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
In net/core/dev.c (ffffffff81785ace)
Location: include/linux/netdevice.h:118
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/sched/sch_generic.c (ffffffff817ae267)
Location: include/linux/netdevice.h:118
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/packet/af_packet.c (ffffffff81874ad5)
Location: include/linux/netdevice.h:118
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
In net/core/dev.c (ffffffff817b3095)
Location: include/linux/netdevice.h:119
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/sched/sch_generic.c (ffffffff817dd8f7)
Location: include/linux/netdevice.h:119
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/packet/af_packet.c (ffffffff818a8ff5)
Location: include/linux/netdevice.h:119
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
In net/core/dev.c (ffffffff817d0b45)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/sched/sch_generic.c (ffffffff817fcf25)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/packet/af_packet.c (ffffffff818cf9bb)
Location: include/linux/netdevice.h:120
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
In net/core/dev.c (ffffffff8184a4be)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/sched/sch_generic.c (ffffffff8187a8b7)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/packet/af_packet.c (ffffffff81954934)
Location: include/linux/netdevice.h:120
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
In net/core/dev.c (ffffffff81894862)
Location: include/linux/netdevice.h:122
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/sched/sch_generic.c (ffffffff818cc8b6)
Location: include/linux/netdevice.h:122
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81958375)
Location: include/linux/netdevice.h:122
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
In net/core/dev.c (ffffffff818b526f)
Location: include/linux/netdevice.h:122
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/sched/sch_generic.c (ffffffff818f7c02)
Location: include/linux/netdevice.h:122
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff8198cbc5)
Location: include/linux/netdevice.h:122
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
In net/core/dev.c (ffffffff81901c5c)
Location: include/linux/netdevice.h:118
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81937e0a)
Location: include/linux/netdevice.h:118
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81957381)
Location: include/linux/netdevice.h:118
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff819f81b4)
Location: include/linux/netdevice.h:118
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
In net/core/dev.c (ffffffff81933e9c)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff8196acca)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8198d821)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2ee04)
Location: include/linux/netdevice.h:120
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
In net/core/dev.c (ffffffff81a088b0)
Location: include/linux/netdevice.h:123
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81a3e803)
Location: include/linux/netdevice.h:123
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81a65a41)
Location: include/linux/netdevice.h:123
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81b21d14)
Location: include/linux/netdevice.h:123
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
In net/core/dev.c (ffffffff81a09e70)
Location: include/linux/netdevice.h:126
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81a415a3)
Location: include/linux/netdevice.h:126
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff81a6db61)
Location: include/linux/netdevice.h:126
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81b306e4)
Location: include/linux/netdevice.h:126
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
```
In net/packet/af_packet.c (ffffffff81b951a2)
Location: include/linux/netdevice.h:126
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In net/core/dev.c (ffffffff819f0800)
Location: include/linux/netdevice.h:126
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81a26213)
Location: include/linux/netdevice.h:126
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/selftests.c (ffffffff81a36706)
Location: include/linux/netdevice.h:126
Inline: True
Inline callers:
  - net/core/selftests.c:__net_test_loopback
```
```
In net/sched/sch_generic.c (ffffffff81a563cc)
Location: include/linux/netdevice.h:126
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e014)
Location: include/linux/netdevice.h:126
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
```
In net/packet/af_packet.c (ffffffff81b841d9)
Location: include/linux/netdevice.h:126
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
In net/core/dev.c (ffffffff81aa1fed)
Location: include/linux/netdevice.h:127
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81adaf83)
Location: include/linux/netdevice.h:127
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/selftests.c (ffffffff81aec3e6)
Location: include/linux/netdevice.h:127
Inline: True
Inline callers:
  - net/core/selftests.c:__net_test_loopback
```
```
In net/sched/sch_generic.c (ffffffff81b0f18b)
Location: include/linux/netdevice.h:127
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81be2b04)
Location: include/linux/netdevice.h:127
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
```
In net/packet/af_packet.c (ffffffff81c502c9)
Location: include/linux/netdevice.h:127
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
In net/core/dev.c (ffffffff81c1a345)
Location: include/linux/netdevice.h:131
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81c5c440)
Location: include/linux/netdevice.h:131
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/selftests.c (ffffffff81c6ed91)
Location: include/linux/netdevice.h:131
Inline: True
Inline callers:
  - net/core/selftests.c:__net_test_loopback
```
```
In net/sched/sch_generic.c (ffffffff81c96387)
Location: include/linux/netdevice.h:131
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81d79c69)
Location: include/linux/netdevice.h:131
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
```
In net/packet/af_packet.c (ffffffff81df17ed)
Location: include/linux/netdevice.h:131
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
In net/core/dev.c (ffffffff81dcb3e5)
Location: include/linux/netdevice.h:132
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81e12af4)
Location: include/linux/netdevice.h:132
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/selftests.c (ffffffff81e26ae1)
Location: include/linux/netdevice.h:132
Inline: True
Inline callers:
  - net/core/selftests.c:__net_test_loopback
```
```
In net/sched/sch_generic.c (ffffffff81e51f77)
Location: include/linux/netdevice.h:132
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81f46a79)
Location: include/linux/netdevice.h:132
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
```
In net/packet/af_packet.c (ffffffff81fc579d)
Location: include/linux/netdevice.h:132
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
In net/core/dev.c (ffffffff81e3bf75)
Location: include/linux/netdevice.h:135
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81e86410)
Location: include/linux/netdevice.h:135
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/selftests.c (ffffffff81e9c081)
Location: include/linux/netdevice.h:135
Inline: True
Inline callers:
  - net/core/selftests.c:__net_test_loopback
```
```
In net/sched/sch_generic.c (ffffffff81ead7e7)
Location: include/linux/netdevice.h:135
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa63b9)
Location: include/linux/netdevice.h:135
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
```
In net/packet/af_packet.c (ffffffff82027779)
Location: include/linux/netdevice.h:135
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
In net/core/dev.c (ffffffff81efa4aa)
Location: include/linux/netdevice.h:139
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff81f48429)
Location: include/linux/netdevice.h:139
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/selftests.c (ffffffff81f5e810)
Location: include/linux/netdevice.h:139
Inline: True
Inline callers:
  - net/core/selftests.c:__net_test_loopback
```
```
In net/sched/sch_generic.c (ffffffff81f70287)
Location: include/linux/netdevice.h:139
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff820736a9)
Location: include/linux/netdevice.h:139
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
```
In net/packet/af_packet.c (ffffffff820f6fcc)
Location: include/linux/netdevice.h:139
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
In net/core/dev.c (ffff800010bd20d8)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffff800010c11324)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffff800010c38d18)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffff800010cee1ac)
Location: include/linux/netdevice.h:120
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
In net/core/dev.c (c0cecd58)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (c0d291c8)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (c0d4b15c)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (c0df5d28)
Location: include/linux/netdevice.h:120
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
In net/core/dev.c (c000000000cb0760)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (c000000000cfdb54)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (c000000000d31890)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (c000000000e12684)
Location: include/linux/netdevice.h:120
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
In net/core/dev.c (ffffffe00075c704)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffe00078d4f8)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffe0007aa2c0)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b1a4)
Location: include/linux/netdevice.h:120
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
In net/core/dev.c (ffffffff818d3e9c)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff8190ac9a)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8192d691)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff819ce494)
Location: include/linux/netdevice.h:120
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
In net/core/dev.c (ffffffff8188dd2c)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff818c4a3a)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff818e7191)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b284)
Location: include/linux/netdevice.h:120
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
In net/core/dev.c (ffffffff81924e9c)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff8195bcca)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff8197e821)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81a38f14)
Location: include/linux/netdevice.h:120
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
In net/core/dev.c (ffffffff81946341)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff8197e0c7)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/sched/sch_generic.c (ffffffff819a0d9b)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/xfrm/xfrm_device.c (ffffffff81a44939)
Location: include/linux/netdevice.h:120
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
</details>
</li>
</ul>

## Differences
