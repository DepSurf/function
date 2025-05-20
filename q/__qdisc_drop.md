# Function: <code>__qdisc_drop</code>

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
In net/core/dev.c (ffffffff81785a5e)
Location: include/net/sch_generic.h:638
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff817ad8e5)
Location: include/net/sch_generic.h:638
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffffffff817b2925)
Location: include/net/sch_generic.h:638
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff817b610a)
Location: include/net/sch_generic.h:638
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
In net/core/dev.c (ffffffff817b2fff)
Location: include/net/sch_generic.h:672
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff817dcf35)
Location: include/net/sch_generic.h:672
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffffffff817e20d5)
Location: include/net/sch_generic.h:672
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff817e5b87)
Location: include/net/sch_generic.h:672
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/core/dev.c (ffffffff817d08e2)
Location: include/net/sch_generic.h:717
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff817fc575)
Location: include/net/sch_generic.h:717
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffffffff81801625)
Location: include/net/sch_generic.h:717
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff818056b7)
Location: include/net/sch_generic.h:717
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/core/dev.c (ffffffff8184a33d)
Location: include/net/sch_generic.h:732
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff81879f35)
Location: include/net/sch_generic.h:732
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffffffff8187f365)
Location: include/net/sch_generic.h:732
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff818843c7)
Location: include/net/sch_generic.h:732
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/core/dev.c (ffffffff8189466f)
Location: include/net/sch_generic.h:830
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff818cc2dc)
Location: include/net/sch_generic.h:830
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_enqueue
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffffffff818d2145)
Location: include/net/sch_generic.h:830
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff818d7f67)
Location: include/net/sch_generic.h:830
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/core/dev.c (ffffffff818b507d)
Location: include/net/sch_generic.h:939
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff818f790d)
Location: include/net/sch_generic.h:939
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_enqueue
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffffffff818fd535)
Location: include/net/sch_generic.h:939
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff81904757)
Location: include/net/sch_generic.h:939
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/core/dev.c (ffffffff81901a5e)
Location: include/net/sch_generic.h:1043
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff81956115)
Location: include/net/sch_generic.h:1043
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffffffff8195cf75)
Location: include/net/sch_generic.h:1043
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff819659cd)
Location: include/net/sch_generic.h:1043
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/core/dev.c (ffffffff81933cc6)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8198c5b5)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffffffff81993475)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff8199c45d)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/core/dev.c (ffffffff81a07392)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81a64195)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffffffff81a6b665)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff81a755e0)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
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
In net/core/dev.c (ffffffff81a08942)
Location: include/net/sch_generic.h:1008
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81a6c2f5)
Location: include/net/sch_generic.h:1008
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffffffff81a73dd5)
Location: include/net/sch_generic.h:1008
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/cls_api.c (ffffffff81a74bde)
Location: include/net/sch_generic.h:1008
Inline: True
```
```
In net/sched/sch_fifo.c (ffffffff81a7e3b0)
Location: include/net/sch_generic.h:1008
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
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
In net/core/dev.c (ffffffff819ef11c)
Location: include/net/sch_generic.h:1061
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81a54a85)
Location: include/net/sch_generic.h:1061
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffffffff81a5c975)
Location: include/net/sch_generic.h:1061
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/cls_api.c (ffffffff81a5d787)
Location: include/net/sch_generic.h:1061
Inline: True
```
```
In net/sched/sch_fifo.c (ffffffff81a671fd)
Location: include/net/sch_generic.h:1061
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
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
In net/core/dev.c (ffffffff81aa0569)
Location: include/net/sch_generic.h:1068
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81b0d775)
Location: include/net/sch_generic.h:1068
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffffffff81b15b25)
Location: include/net/sch_generic.h:1068
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/cls_api.c (ffffffff81b16a67)
Location: include/net/sch_generic.h:1068
Inline: True
```
```
In net/sched/sch_fifo.c (ffffffff81b206dd)
Location: include/net/sch_generic.h:1068
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
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
In net/core/dev.c (ffffffff81c18351)
Location: include/net/sch_generic.h:1033
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81c94615)
Location: include/net/sch_generic.h:1033
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffffffff81c9cf45)
Location: include/net/sch_generic.h:1033
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/cls_api.c (ffffffff81c9e1a7)
Location: include/net/sch_generic.h:1033
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_handle
  - net/sched/cls_api.c:tcf_qevent_handle
```
```
In net/sched/sch_fifo.c (ffffffff81ca8a03)
Location: include/net/sch_generic.h:1033
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
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
In net/core/dev.c (ffffffff81dc9360)
Location: include/net/sch_generic.h:1005
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81e50075)
Location: include/net/sch_generic.h:1005
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffffffff81e593c5)
Location: include/net/sch_generic.h:1005
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/cls_api.c (ffffffff81e5a8c7)
Location: include/net/sch_generic.h:1005
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_handle
  - net/sched/cls_api.c:tcf_qevent_handle
```
```
In net/sched/sch_fifo.c (ffffffff81e65873)
Location: include/net/sch_generic.h:1005
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
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
In net/core/dev.c (ffffffff81e378c0)
Location: include/net/sch_generic.h:1017
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81eab7f5)
Location: include/net/sch_generic.h:1017
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffffffff81eb4df5)
Location: include/net/sch_generic.h:1017
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/cls_api.c (ffffffff81eb6567)
Location: include/net/sch_generic.h:1017
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_handle
  - net/sched/cls_api.c:tcf_qevent_handle
```
```
In net/sched/sch_fifo.c (ffffffff81ec17b3)
Location: include/net/sch_generic.h:1017
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
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
In net/core/dev.c (ffffffff81ef58e6)
Location: include/net/sch_generic.h:1076
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81f6e295)
Location: include/net/sch_generic.h:1076
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffffffff81f77ab5)
Location: include/net/sch_generic.h:1076
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/cls_api.c (ffffffff81f79277)
Location: include/net/sch_generic.h:1076
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_qevent_handle
  - net/sched/cls_api.c:tcf_qevent_handle
```
```
In net/sched/sch_fifo.c (ffffffff81f84af3)
Location: include/net/sch_generic.h:1076
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
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
In net/core/dev.c (ffff800010bd1ecc)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffff800010c374e4)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffff800010c3f95c)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffff800010c49708)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/core/dev.c (c0cecb4c)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (c0d49d78)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (c0d512fc)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (c0d5a468)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/core/dev.c (c000000000cb0420)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (c000000000d2fa48)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (c000000000d39ef8)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (c000000000d46f7c)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/core/dev.c (ffffffe00075c490)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffe0007a8d98)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffffffe0007af454)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffe0007b6da0)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/core/dev.c (ffffffff818d3cc6)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8192c425)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffffffff819332e5)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff8193c2cd)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/core/dev.c (ffffffff8188db56)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff818e5f25)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffffffff818ecde5)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff818f5dcd)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/core/dev.c (ffffffff81924cc6)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8197d5b5)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffffffff81984475)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff8198d45d)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/core/dev.c (ffffffff8194617f)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8199fb25)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_generic.c:noop_enqueue
```
```
In net/sched/sch_blackhole.c (ffffffff819a69b5)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff819afced)
Location: include/net/sch_generic.h:1016
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
</details>
</li>
</ul>

## Differences
