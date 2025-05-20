# Function: <code>qdisc_bstats_update</code>

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
In net/core/dev.c (ffffffff8171cf2a)
Location: include/net/sch_generic.h:535
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff81740c12)
Location: include/net/sch_generic.h:535
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff817490b3)
Location: include/net/sch_generic.h:535
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
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
In net/core/dev.c (ffffffff8178591e)
Location: include/net/sch_generic.h:555
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff817ada48)
Location: include/net/sch_generic.h:555
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff817b6089)
Location: include/net/sch_generic.h:555
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
In net/core/dev.c (ffffffff817b2f0a)
Location: include/net/sch_generic.h:563
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff817dd084)
Location: include/net/sch_generic.h:563
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff817e5a26)
Location: include/net/sch_generic.h:563
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
In net/core/dev.c (ffffffff817d076c)
Location: include/net/sch_generic.h:608
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff817fc6be)
Location: include/net/sch_generic.h:608
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81805550)
Location: include/net/sch_generic.h:608
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
In net/core/dev.c (ffffffff8184a1f1)
Location: include/net/sch_generic.h:623
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8187a11e)
Location: include/net/sch_generic.h:623
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81884260)
Location: include/net/sch_generic.h:623
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
In net/core/dev.c (ffffffff8189458e)
Location: include/net/sch_generic.h:694
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_fifo.c (ffffffff818d7cd7)
Location: include/net/sch_generic.h:694
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
In net/core/dev.c (ffffffff818b4fe4)
Location: include/net/sch_generic.h:793
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_fifo.c (ffffffff819044c7)
Location: include/net/sch_generic.h:793
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
In net/core/dev.c (ffffffff8190168e)
Location: include/net/sch_generic.h:862
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8195639e)
Location: include/net/sch_generic.h:862
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81965857)
Location: include/net/sch_generic.h:862
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
In net/core/dev.c (ffffffff819339bc)
Location: include/net/sch_generic.h:835
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8198c83e)
Location: include/net/sch_generic.h:835
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff8199c2e7)
Location: include/net/sch_generic.h:835
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
In net/core/dev.c (ffffffff81a072ba)
Location: include/net/sch_generic.h:835
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81a64884)
Location: include/net/sch_generic.h:835
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81a75027)
Location: include/net/sch_generic.h:835
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
In net/core/dev.c (ffffffff81a0886a)
Location: include/net/sch_generic.h:827
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81a6c9c4)
Location: include/net/sch_generic.h:827
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81a7df27)
Location: include/net/sch_generic.h:827
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
In net/core/dev.c (ffffffff819ef01f)
Location: include/net/sch_generic.h:880
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81a55235)
Location: include/net/sch_generic.h:880
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81a66d77)
Location: include/net/sch_generic.h:880
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
In net/core/dev.c (ffffffff81aa03e5)
Location: include/net/sch_generic.h:887
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81b0e456)
Location: include/net/sch_generic.h:887
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81b20237)
Location: include/net/sch_generic.h:887
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
In net/core/dev.c (ffffffff81c1821e)
Location: include/net/sch_generic.h:853
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81c94830)
Location: include/net/sch_generic.h:853
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81ca8487)
Location: include/net/sch_generic.h:853
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
In net/core/dev.c (ffffffff81dc900c)
Location: include/net/sch_generic.h:832
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81e502f0)
Location: include/net/sch_generic.h:832
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81e652a7)
Location: include/net/sch_generic.h:832
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
In net/core/dev.c (ffffffff81e3756c)
Location: include/net/sch_generic.h:844
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81eaba93)
Location: include/net/sch_generic.h:844
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81ec11e7)
Location: include/net/sch_generic.h:844
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
In net/core/dev.c (ffffffff81ef5594)
Location: include/net/sch_generic.h:872
Inline: True
Inline callers:
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/sched/sch_generic.c (ffffffff81f6e533)
Location: include/net/sch_generic.h:872
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff81f844e7)
Location: include/net/sch_generic.h:872
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
In net/core/dev.c (ffff800010bd1dd4)
Location: include/net/sch_generic.h:835
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffff800010c383c0)
Location: include/net/sch_generic.h:835
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffff800010c4957c)
Location: include/net/sch_generic.h:835
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
In net/core/dev.c (c0cec5a0)
Location: include/net/sch_generic.h:835
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (c0d49fa8)
Location: include/net/sch_generic.h:835
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (c0d5a2d0)
Location: include/net/sch_generic.h:835
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
In net/core/dev.c (c000000000cb0198)
Location: include/net/sch_generic.h:835
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (c000000000d31314)
Location: include/net/sch_generic.h:835
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (c000000000d46d58)
Location: include/net/sch_generic.h:835
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
In net/core/dev.c (ffffffe00075bf2e)
Location: include/net/sch_generic.h:835
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffe0007a8faa)
Location: include/net/sch_generic.h:835
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffe0007b6b9e)
Location: include/net/sch_generic.h:835
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
In net/core/dev.c (ffffffff818d39bc)
Location: include/net/sch_generic.h:835
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8192c6ae)
Location: include/net/sch_generic.h:835
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff8193c157)
Location: include/net/sch_generic.h:835
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
In net/core/dev.c (ffffffff8188d84c)
Location: include/net/sch_generic.h:835
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff818e61ae)
Location: include/net/sch_generic.h:835
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff818f5c57)
Location: include/net/sch_generic.h:835
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
In net/core/dev.c (ffffffff819249bc)
Location: include/net/sch_generic.h:835
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8197d83e)
Location: include/net/sch_generic.h:835
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff8198d2e7)
Location: include/net/sch_generic.h:835
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
In net/core/dev.c (ffffffff81945e58)
Location: include/net/sch_generic.h:835
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/sched/sch_generic.c (ffffffff8199fdae)
Location: include/net/sch_generic.h:835
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/sch_fifo.c (ffffffff819afb77)
Location: include/net/sch_generic.h:835
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
</details>
</li>
</ul>

## Differences
