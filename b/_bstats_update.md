# Function: <code>_bstats_update</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817829e6)
Location: include/net/sch_generic.h:518
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff817ada67)
Location: include/net/sch_generic.h:518
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff817b60a9)
Location: include/net/sch_generic.h:518
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffffffff817b02ca)
Location: include/net/sch_generic.h:526
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff817dd0a3)
Location: include/net/sch_generic.h:526
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff817e5a46)
Location: include/net/sch_generic.h:526
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffffffff817cebb7)
Location: include/net/sch_generic.h:571
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff817fc6e1)
Location: include/net/sch_generic.h:571
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81805576)
Location: include/net/sch_generic.h:571
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffffffff818484d1)
Location: include/net/sch_generic.h:586
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8187a141)
Location: include/net/sch_generic.h:586
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81884286)
Location: include/net/sch_generic.h:586
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffffffff818921cc)
Location: include/net/sch_generic.h:657
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff818cc167)
Location: include/net/sch_generic.h:657
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff818d7cef)
Location: include/net/sch_generic.h:657
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffff818b602d)
Location: include/net/sch_generic.h:756
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff818f6ba7)
Location: include/net/sch_generic.h:756
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff819044df)
Location: include/net/sch_generic.h:756
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffff81902172)
Location: include/net/sch_generic.h:825
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff81956335)
Location: include/net/sch_generic.h:825
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff8196586f)
Location: include/net/sch_generic.h:825
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffff819343b2)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8198c7d5)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff8199c2ff)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffff81a09109)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81a6483a)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/act_api.c (ffffffff81a72280)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
```
```
In net/sched/sch_fifo.c (ffffffff81a7503f)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffff81a0a673)
Location: include/net/sch_generic.h:790
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81a6c97a)
Location: include/net/sch_generic.h:790
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/act_api.c (ffffffff81a7ae4f)
Location: include/net/sch_generic.h:790
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
```
```
In net/sched/sch_fifo.c (ffffffff81a7df3f)
Location: include/net/sch_generic.h:790
Inline: True
Inline callers:
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
Location: include/net/sch_generic.h:843
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81a55199)
Location: include/net/sch_generic.h:843
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/act_api.c (ffffffff81a63ba5)
Location: include/net/sch_generic.h:843
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
```
```
In net/sched/sch_fifo.c (ffffffff81a66d8f)
Location: include/net/sch_generic.h:843
Inline: True
Inline callers:
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
Location: include/net/sch_generic.h:850
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81b0e3c9)
Location: include/net/sch_generic.h:850
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/act_api.c (ffffffff81b1cf25)
Location: include/net/sch_generic.h:850
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
```
```
In net/sched/sch_fifo.c (ffffffff81b2024f)
Location: include/net/sch_generic.h:850
Inline: True
Inline callers:
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
In net/core/gen_stats.c (ffffffff81c029ec)
Location: include/net/sch_generic.h:830
Inline: True
```
```
In net/core/dev.c (ffffffff81c198dc)
Location: include/net/sch_generic.h:830
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81c9484a)
Location: include/net/sch_generic.h:830
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/act_api.c (ffffffff81ca42a5)
Location: include/net/sch_generic.h:830
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
```
```
In net/sched/sch_fifo.c (ffffffff81ca849f)
Location: include/net/sch_generic.h:830
Inline: True
Inline callers:
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
In net/core/gen_stats.c (ffffffff81db1eac)
Location: include/net/sch_generic.h:809
Inline: True
```
```
In net/core/dev.c (ffffffff81dca918)
Location: include/net/sch_generic.h:809
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81e5030a)
Location: include/net/sch_generic.h:809
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/act_api.c (ffffffff81e60c15)
Location: include/net/sch_generic.h:809
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
```
```
In net/sched/sch_fifo.c (ffffffff81e652bf)
Location: include/net/sch_generic.h:809
Inline: True
Inline callers:
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
In net/core/gen_stats.c (ffffffff81e2247c)
Location: include/net/sch_generic.h:821
Inline: True
```
```
In net/core/dev.c (ffffffff81e3b49d)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81eabab0)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/act_api.c (ffffffff81ebcc65)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
```
```
In net/sched/sch_fifo.c (ffffffff81ec11ff)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
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
In net/core/gen_stats.c (ffffffff81ee03bc)
Location: include/net/sch_generic.h:849
Inline: True
```
```
In net/core/dev.c (ffffffff81eedf82)
Location: include/net/sch_generic.h:849
Inline: True
Inline callers:
  - net/core/dev.c:tc_run
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81f6e550)
Location: include/net/sch_generic.h:849
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/act_api.c (ffffffff81f7fe65)
Location: include/net/sch_generic.h:849
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
```
```
In net/sched/sch_fifo.c (ffffffff81f844ff)
Location: include/net/sch_generic.h:849
Inline: True
Inline callers:
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
In net/core/dev.c (ffff800010bd26e4)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffff800010c383d8)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffff800010c49598)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
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
In net/core/dev.c (c0ced750)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (c0d49fcc)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (c0d5a2f4)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
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
In net/core/dev.c (c000000000cb0e04)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (c000000000d31334)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (c000000000d46d78)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffe00075cea8)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffe0007a8fc8)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffe0007b6bb8)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffff818d43b2)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8192c645)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff8193c16f)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffff8188e242)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff818e6145)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff818f5c6f)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffff819253b2)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8197d7d5)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff8198d2ff)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffff81946863)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8199fd45)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff819afb8f)
Location: include/net/sch_generic.h:798
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
</details>
</li>
</ul>

## Differences
