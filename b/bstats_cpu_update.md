# Function: <code>bstats_cpu_update</code>

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
In net/core/dev.c (ffffffff8171a527)
Location: include/net/sch_generic.h:521
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
In net/core/dev.c (ffffffff817829c9)
Location: include/net/sch_generic.h:541
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
In net/core/dev.c (ffffffff817b02ad)
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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ceba7)
Location: include/net/sch_generic.h:594
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818484b4)
Location: include/net/sch_generic.h:609
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/dev.c (ffffffff818921af)
Location: include/net/sch_generic.h:680
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff818cc14f)
Location: include/net/sch_generic.h:680
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In net/core/dev.c (ffffffff818b600f)
Location: include/net/sch_generic.h:779
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff818f6b8f)
Location: include/net/sch_generic.h:779
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
In net/core/dev.c (ffffffff81902154)
Location: include/net/sch_generic.h:848
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8195631b)
Location: include/net/sch_generic.h:848
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In net/core/dev.c (ffffffff81934394)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8198c7bb)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In net/core/dev.c (ffffffff81a090e9)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff81a64820)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In net/core/dev.c (ffffffff81a0a655)
Location: include/net/sch_generic.h:813
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff81a6c960)
Location: include/net/sch_generic.h:813
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In net/core/dev.c (ffffffff819f0428)
Location: include/net/sch_generic.h:866
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff81a5517f)
Location: include/net/sch_generic.h:866
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
In net/core/dev.c (ffffffff81aa184d)
Location: include/net/sch_generic.h:873
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81b0e3af)
Location: include/net/sch_generic.h:873
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In net/core/dev.c (ffff800010bd26e0)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffff800010c384f0)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In net/core/dev.c (c0ced72c)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (c0d4a08c)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In net/core/dev.c (c000000000cb0e00)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (c000000000d3145c)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In net/core/dev.c (ffffffe00075ce80)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffe0007a90f6)
Location: include/net/sch_generic.h:821
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d4394)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8192c62b)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In net/core/dev.c (ffffffff8188e224)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff818e612b)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In net/core/dev.c (ffffffff81925394)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8197d7bb)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
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
In net/core/dev.c (ffffffff81946845)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8199fd2b)
Location: include/net/sch_generic.h:821
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
</details>
</li>
</ul>

## Differences
