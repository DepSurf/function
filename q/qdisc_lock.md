# Function: <code>qdisc_lock</code>

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
In net/core/dev.c (ffffffff8171ce41)
Location: include/net/sch_generic.h:280
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff81741612)
Location: include/net/sch_generic.h:280
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:280
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81745123)
Location: include/net/sch_generic.h:280
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_modify_qdisc
```
```
In net/sched/cls_api.c (0)
Location: include/net/sch_generic.h:280
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
In net/core/dev.c (ffffffff81785678)
Location: include/net/sch_generic.h:259
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff817ae3d2)
Location: include/net/sch_generic.h:259
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:259
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:259
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/sch_generic.h:259
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
In net/core/dev.c (ffffffff817b2c7d)
Location: include/net/sch_generic.h:267
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff817dda62)
Location: include/net/sch_generic.h:267
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:267
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:267
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/sch_generic.h:267
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
In net/core/dev.c (ffffffff817d0483)
Location: include/net/sch_generic.h:296
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (0)
Location: include/net/sch_generic.h:296
Inline: True
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:296
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:296
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/sch_generic.h:296
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
In net/core/dev.c (ffffffff81849e5e)
Location: include/net/sch_generic.h:303
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (0)
Location: include/net/sch_generic.h:303
Inline: True
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:303
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:303
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
In net/core/dev.c (ffffffff81891cde)
Location: include/net/sch_generic.h:371
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff818ccfbf)
Location: include/net/sch_generic.h:371
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:371
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:371
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
In net/core/dev.c (ffffffff818b2638)
Location: include/net/sch_generic.h:436
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff818f834e)
Location: include/net/sch_generic.h:436
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:436
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:436
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
In net/core/dev.c (ffffffff818fec3d)
Location: include/net/sch_generic.h:511
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff81957afa)
Location: include/net/sch_generic.h:511
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:511
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:511
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
In net/core/dev.c (ffffffff81930f7d)
Location: include/net/sch_generic.h:495
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8198df9a)
Location: include/net/sch_generic.h:495
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:495
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:495
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
In net/core/dev.c (ffffffff81a061ee)
Location: include/net/sch_generic.h:500
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81a65bd6)
Location: include/net/sch_generic.h:500
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:try_bulk_dequeue_skb_slow
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:500
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:500
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
In net/core/dev.c (ffffffff81a06e2f)
Location: include/net/sch_generic.h:492
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81a6dcf6)
Location: include/net/sch_generic.h:492
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:try_bulk_dequeue_skb_slow
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:492
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:492
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
In net/core/dev.c (ffffffff819ee537)
Location: include/net/sch_generic.h:539
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81a5655f)
Location: include/net/sch_generic.h:539
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:539
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:539
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
In net/core/dev.c (ffffffff81a9f7d7)
Location: include/net/sch_generic.h:544
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81b0f2fa)
Location: include/net/sch_generic.h:544
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:544
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:544
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
In net/core/dev.c (ffffffff81c17e85)
Location: include/net/sch_generic.h:532
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81c964d8)
Location: include/net/sch_generic.h:532
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:532
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:532
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
In net/core/dev.c (ffffffff81dc8dad)
Location: include/net/sch_generic.h:527
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81e520c8)
Location: include/net/sch_generic.h:527
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:527
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:527
Inline: True
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
In net/core/dev.c (ffffffff81e3731b)
Location: include/net/sch_generic.h:536
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81ead938)
Location: include/net/sch_generic.h:536
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:536
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:536
Inline: True
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
In net/core/dev.c (ffffffff81ef533b)
Location: include/net/sch_generic.h:537
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81f703d8)
Location: include/net/sch_generic.h:537
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:537
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:537
Inline: True
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
In net/core/dev.c (ffff800010bce6e8)
Location: include/net/sch_generic.h:495
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffff800010c39630)
Location: include/net/sch_generic.h:495
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:495
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:495
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
In net/core/dev.c (c0ce7f3c)
Location: include/net/sch_generic.h:495
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (c0d4bb44)
Location: include/net/sch_generic.h:495
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:495
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:495
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
In net/core/dev.c (c000000000cac3b0)
Location: include/net/sch_generic.h:495
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (c000000000d323f0)
Location: include/net/sch_generic.h:495
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:495
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:495
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
In net/core/dev.c (ffffffe000758aa8)
Location: include/net/sch_generic.h:495
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffe0007aaba6)
Location: include/net/sch_generic.h:495
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:495
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:495
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
In net/core/dev.c (ffffffff818d0f7d)
Location: include/net/sch_generic.h:495
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8192de0a)
Location: include/net/sch_generic.h:495
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:495
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:495
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
In net/core/dev.c (ffffffff8188ae35)
Location: include/net/sch_generic.h:495
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff818e790a)
Location: include/net/sch_generic.h:495
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:495
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:495
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
In net/core/dev.c (ffffffff81921f7d)
Location: include/net/sch_generic.h:495
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8197ef9a)
Location: include/net/sch_generic.h:495
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:495
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:495
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
In net/core/dev.c (ffffffff81943c95)
Location: include/net/sch_generic.h:495
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff819a1523)
Location: include/net/sch_generic.h:495
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_mq.c (0)
Location: include/net/sch_generic.h:495
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:495
Inline: True
```
</details>
</li>
</ul>

## Differences
