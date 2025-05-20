# Function: <code>qdisc_is_percpu_stats</code>

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
In net/sched/sch_generic.c (0)
Location: include/net/sch_generic.h:509
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:509
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
In net/sched/sch_generic.c (0)
Location: include/net/sch_generic.h:513
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:513
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
In net/sched/sch_generic.c (0)
Location: include/net/sch_generic.h:521
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:521
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
In net/sched/sch_generic.c (0)
Location: include/net/sch_generic.h:566
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:566
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
In net/sched/sch_generic.c (0)
Location: include/net/sch_generic.h:581
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/sch_generic.h:581
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
In net/sched/sch_generic.c (ffffffff818cd375)
Location: include/net/sch_generic.h:652
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff818ce117)
Location: include/net/sch_generic.h:652
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff818cfdcf)
Location: include/net/sch_generic.h:652
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
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
In net/sched/sch_generic.c (ffffffff818f89d5)
Location: include/net/sch_generic.h:751
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_mq.c (ffffffff818f92b0)
Location: include/net/sch_generic.h:751
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff818fb041)
Location: include/net/sch_generic.h:751
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
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
In net/sched/sch_generic.c (ffffffff819581a5)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_mq.c (ffffffff81958fa1)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff8195a953)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
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
In net/sched/sch_generic.c (ffffffff8198e655)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_mq.c (ffffffff8198f443)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81990e03)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
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
In net/sched/sch_generic.c (ffffffff81a64a65)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:try_bulk_dequeue_skb_slow
```
```
In net/sched/sch_mq.c (ffffffff81a66d93)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81a68e13)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
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
In net/sched/sch_generic.c (ffffffff81a6cbb2)
Location: include/net/sch_generic.h:147
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:try_bulk_dequeue_skb_slow
```
```
In net/sched/sch_mq.c (ffffffff81a6ed43)
Location: include/net/sch_generic.h:147
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81a71548)
Location: include/net/sch_generic.h:147
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
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
In net/sched/sch_generic.c (ffffffff81a55712)
Location: include/net/sch_generic.h:148
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_mq.c (ffffffff81a575df)
Location: include/net/sch_generic.h:148
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81a59f08)
Location: include/net/sch_generic.h:148
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
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
In net/sched/sch_generic.c (ffffffff81b0e292)
Location: include/net/sch_generic.h:158
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_mq.c (ffffffff81b1051f)
Location: include/net/sch_generic.h:158
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81b12fd8)
Location: include/net/sch_generic.h:158
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
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
In net/sched/sch_generic.c (ffffffff81c95cf2)
Location: include/net/sch_generic.h:169
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_mq.c (ffffffff81c977e1)
Location: include/net/sch_generic.h:169
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
```
```
In net/sched/sch_api.c (ffffffff81c99c32)
Location: include/net/sch_generic.h:169
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
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
In net/sched/sch_generic.c (ffffffff81e518b2)
Location: include/net/sch_generic.h:169
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_mq.c (ffffffff81e5383d)
Location: include/net/sch_generic.h:169
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
```
```
In net/sched/sch_api.c (ffffffff81e55f62)
Location: include/net/sch_generic.h:169
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
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
In net/sched/sch_generic.c (ffffffff81ead102)
Location: include/net/sch_generic.h:176
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_mq.c (ffffffff81eaf0bd)
Location: include/net/sch_generic.h:176
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
```
```
In net/sched/sch_api.c (ffffffff81eb22ed)
Location: include/net/sch_generic.h:176
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
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
In net/sched/sch_generic.c (ffffffff81f6fba2)
Location: include/net/sch_generic.h:177
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_mq.c (ffffffff81f71b5a)
Location: include/net/sch_generic.h:177
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
```
```
In net/sched/sch_api.c (ffffffff81f74d9d)
Location: include/net/sch_generic.h:177
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
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
In net/sched/sch_generic.c (ffff800010c39f00)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_mq.c (ffff800010c3b32c)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffff800010c3d338)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
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
In net/sched/sch_generic.c (c0d4c1dc)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_mq.c (c0d4d07c)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (c0d4ee04)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
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
In net/sched/sch_generic.c (c000000000d32f20)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_mq.c (c000000000d3435c)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (c000000000d36b80)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
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
In net/sched/sch_generic.c (ffffffe0007ab166)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_mq.c (ffffffe0007abb24)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffe0007ad7de)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
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
In net/sched/sch_generic.c (ffffffff8192e4c5)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_mq.c (ffffffff8192f2b3)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81930c73)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
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
In net/sched/sch_generic.c (ffffffff818e7fc5)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_mq.c (ffffffff818e8db3)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff818ea773)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
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
In net/sched/sch_generic.c (ffffffff8197f655)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_mq.c (ffffffff81980443)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81981e03)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
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
In net/sched/sch_generic.c (ffffffff819a1bb5)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_mq.c (ffffffff819a29a3)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff819a4343)
Location: include/net/sch_generic.h:144
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:tc_fill_qdisc
```
</details>
</li>
</ul>

## Differences
