# Function: <code>qdisc_qstats_backlog_dec</code>

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
In net/sched/sch_generic.c (ffffffff81740c0f)
Location: include/net/sch_generic.h:541
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81749051)
Location: include/net/sch_generic.h:541
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_queue_drop
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/sched/sch_generic.c (ffffffff817ada3f)
Location: include/net/sch_generic.h:561
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_fifo.c (ffffffff817b6080)
Location: include/net/sch_generic.h:561
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
In net/sched/sch_generic.c (ffffffff817dd07b)
Location: include/net/sch_generic.h:569
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_fifo.c (ffffffff817e5b7e)
Location: include/net/sch_generic.h:569
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff817fc6bb)
Location: include/net/sch_generic.h:614
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_fifo.c (ffffffff818056ae)
Location: include/net/sch_generic.h:614
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff8187a11b)
Location: include/net/sch_generic.h:629
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_fifo.c (ffffffff818843be)
Location: include/net/sch_generic.h:629
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff818ccf66)
Location: include/net/sch_generic.h:700
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_fifo.c (ffffffff818d7f5e)
Location: include/net/sch_generic.h:700
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff818f82a4)
Location: include/net/sch_generic.h:799
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_fifo.c (ffffffff8190474e)
Location: include/net/sch_generic.h:799
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff81956398)
Location: include/net/sch_generic.h:868
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_fifo.c (ffffffff819659c4)
Location: include/net/sch_generic.h:868
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff8198c838)
Location: include/net/sch_generic.h:841
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_fifo.c (ffffffff8199c454)
Location: include/net/sch_generic.h:841
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff81a6487d)
Location: include/net/sch_generic.h:841
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_fifo.c (ffffffff81a755d7)
Location: include/net/sch_generic.h:841
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff81a6c9bd)
Location: include/net/sch_generic.h:833
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_fifo.c (ffffffff81a7e3a7)
Location: include/net/sch_generic.h:833
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff81a5522e)
Location: include/net/sch_generic.h:886
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_fifo.c (ffffffff81a671f4)
Location: include/net/sch_generic.h:886
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff81b0e44f)
Location: include/net/sch_generic.h:893
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_fifo.c (ffffffff81b206d4)
Location: include/net/sch_generic.h:893
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff81c94829)
Location: include/net/sch_generic.h:859
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_fifo.c (ffffffff81ca89fa)
Location: include/net/sch_generic.h:859
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff81e502e9)
Location: include/net/sch_generic.h:838
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_fifo.c (ffffffff81e6586a)
Location: include/net/sch_generic.h:838
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff81eaba8c)
Location: include/net/sch_generic.h:850
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_fifo.c (ffffffff81ec17aa)
Location: include/net/sch_generic.h:850
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff81f6e52c)
Location: include/net/sch_generic.h:878
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:dequeue_skb
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_fifo.c (ffffffff81f84aea)
Location: include/net/sch_generic.h:878
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffff800010c383ac)
Location: include/net/sch_generic.h:841
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_fifo.c (ffff800010c496f8)
Location: include/net/sch_generic.h:841
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (c0d49f94)
Location: include/net/sch_generic.h:841
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_fifo.c (c0d5a458)
Location: include/net/sch_generic.h:841
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (c000000000d31300)
Location: include/net/sch_generic.h:841
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_fifo.c (c000000000d46f70)
Location: include/net/sch_generic.h:841
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffe0007a8fa4)
Location: include/net/sch_generic.h:841
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_fifo.c (ffffffe0007b6d94)
Location: include/net/sch_generic.h:841
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff8192c6a8)
Location: include/net/sch_generic.h:841
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_fifo.c (ffffffff8193c2c4)
Location: include/net/sch_generic.h:841
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff818e61a8)
Location: include/net/sch_generic.h:841
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_fifo.c (ffffffff818f5dc4)
Location: include/net/sch_generic.h:841
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff8197d838)
Location: include/net/sch_generic.h:841
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_fifo.c (ffffffff8198d454)
Location: include/net/sch_generic.h:841
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff8199fda8)
Location: include/net/sch_generic.h:841
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/sch_fifo.c (ffffffff819afce4)
Location: include/net/sch_generic.h:841
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
</details>
</li>
</ul>

## Differences
