# Function: <code>qdisc_pkt_len</code>

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
In net/core/dev.c (0)
Location: include/net/sch_generic.h:475
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/net/sch_generic.h:475
Inline: True
```
```
In net/sched/sch_fifo.c (ffffffff8174905d)
Location: include/net/sch_generic.h:475
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_queue_drop
  - net/sched/sch_fifo.c:qdisc_queue_drop_head
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
In net/core/dev.c (0)
Location: include/net/sch_generic.h:478
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/net/sch_generic.h:478
Inline: True
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/sch_generic.h:478
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
Location: include/net/sch_generic.h:486
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/net/sch_generic.h:486
Inline: True
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/sch_generic.h:486
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
Location: include/net/sch_generic.h:531
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/net/sch_generic.h:531
Inline: True
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/sch_generic.h:531
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
Location: include/net/sch_generic.h:546
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/net/sch_generic.h:546
Inline: True
```
```
In net/sched/sch_fifo.c (0)
Location: include/net/sch_generic.h:546
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
In net/core/dev.c (ffffffff8189413a)
Location: include/net/sch_generic.h:617
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff818cc13d)
Location: include/net/sch_generic.h:617
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_enqueue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_fifo.c (ffffffff818d7f0c)
Location: include/net/sch_generic.h:617
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffffffff818b4b21)
Location: include/net/sch_generic.h:716
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff818f6b7d)
Location: include/net/sch_generic.h:716
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_enqueue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_fifo.c (ffffffff819046fc)
Location: include/net/sch_generic.h:716
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffffffff81901465)
Location: include/net/sch_generic.h:790
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff81956335)
Location: include/net/sch_generic.h:790
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_fifo.c (ffffffff81965972)
Location: include/net/sch_generic.h:790
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffffffff81933795)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8198c7d5)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_fifo.c (ffffffff8199c402)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffffffff81a084fe)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81a6480e)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:try_bulk_dequeue_skb_slow
  - net/sched/sch_generic.c:try_bulk_dequeue_skb_slow
```
```
In net/sched/sch_fifo.c (ffffffff81a75585)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffffffff81a09ad0)
Location: include/net/sch_generic.h:755
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81a6c94a)
Location: include/net/sch_generic.h:755
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:try_bulk_dequeue_skb_slow
  - net/sched/sch_generic.c:try_bulk_dequeue_skb_slow
```
```
In net/sched/sch_fifo.c (ffffffff81a7e355)
Location: include/net/sch_generic.h:755
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffffffff819f0448)
Location: include/net/sch_generic.h:808
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81a55169)
Location: include/net/sch_generic.h:808
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_fifo.c (ffffffff81a671a2)
Location: include/net/sch_generic.h:808
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffffffff81aa186d)
Location: include/net/sch_generic.h:815
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81b0e399)
Location: include/net/sch_generic.h:815
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_fifo.c (ffffffff81b20682)
Location: include/net/sch_generic.h:815
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffffffff81c198dc)
Location: include/net/sch_generic.h:795
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81c94908)
Location: include/net/sch_generic.h:795
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_fifo.c (ffffffff81ca8992)
Location: include/net/sch_generic.h:795
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffffffff81dca918)
Location: include/net/sch_generic.h:774
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81e503c8)
Location: include/net/sch_generic.h:774
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_fifo.c (ffffffff81e65802)
Location: include/net/sch_generic.h:774
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffffffff81e3b49d)
Location: include/net/sch_generic.h:786
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81eabba0)
Location: include/net/sch_generic.h:786
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_fifo.c (ffffffff81ec1742)
Location: include/net/sch_generic.h:786
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffffffff81eedf82)
Location: include/net/sch_generic.h:814
Inline: True
Inline callers:
  - net/core/dev.c:tc_run
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81f6e640)
Location: include/net/sch_generic.h:814
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_fifo.c (ffffffff81f84a82)
Location: include/net/sch_generic.h:814
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffff800010bd1884)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffff800010c383ac)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_fifo.c (ffff800010c496a0)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (c0ced73c)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (c0d49f94)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_fifo.c (c0d5a418)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (c000000000cafc5c)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (c000000000d31300)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_fifo.c (c000000000d46ee8)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffffffe00075bf2e)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffe0007a8fa4)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_fifo.c (ffffffe0007b6d54)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffffffff818d3795)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8192c645)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_fifo.c (ffffffff8193c272)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffffffff8188d625)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff818e6145)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_fifo.c (ffffffff818f5d72)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffffffff81924795)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8197d7d5)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_fifo.c (ffffffff8198d402)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffffffff81945c25)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8199fd45)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_fifo.c (ffffffff819afc92)
Location: include/net/sch_generic.h:763
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
</details>
</li>
</ul>

## Differences
