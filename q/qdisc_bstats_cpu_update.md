# Function: <code>qdisc_bstats_cpu_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171a51b)
Location: include/net/sch_generic.h:529
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817829b8)
Location: include/net/sch_generic.h:549
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b029c)
Location: include/net/sch_generic.h:557
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ceb97)
Location: include/net/sch_generic.h:602
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818cc143)
Location: include/net/sch_generic.h:688
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818f6b83)
Location: include/net/sch_generic.h:787
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In net/core/dev.c (ffffffff8190195b)
Location: include/net/sch_generic.h:856
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8195630f)
Location: include/net/sch_generic.h:856
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8198c7af)
Location: include/net/sch_generic.h:829
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a64814)
Location: include/net/sch_generic.h:829
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a6c954)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a55173)
Location: include/net/sch_generic.h:874
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In net/core/dev.c (ffffffff81aa04e1)
Location: include/net/sch_generic.h:881
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81b0e3a3)
Location: include/net/sch_generic.h:881
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In net/core/dev.c (ffffffff81c182da)
Location: include/net/sch_generic.h:847
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81c94912)
Location: include/net/sch_generic.h:847
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In net/core/dev.c (ffffffff81dc9190)
Location: include/net/sch_generic.h:826
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81e503d2)
Location: include/net/sch_generic.h:826
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In net/core/dev.c (ffffffff81e376f0)
Location: include/net/sch_generic.h:838
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81eabbaa)
Location: include/net/sch_generic.h:838
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In net/core/dev.c (ffffffff81ef5718)
Location: include/net/sch_generic.h:866
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81f6e64a)
Location: include/net/sch_generic.h:866
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffff800010c384cc)
Location: include/net/sch_generic.h:829
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c0d4a080)
Location: include/net/sch_generic.h:829
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c000000000d31438)
Location: include/net/sch_generic.h:829
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffe0007a90f2)
Location: include/net/sch_generic.h:829
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8192c61f)
Location: include/net/sch_generic.h:829
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818e611f)
Location: include/net/sch_generic.h:829
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8197d7af)
Location: include/net/sch_generic.h:829
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8199fd1f)
Location: include/net/sch_generic.h:829
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
</details>
</li>
</ul>

## Differences
