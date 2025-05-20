# Function: <code>__qdisc_enqueue_tail</code>

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
In net/sched/sch_generic.c (ffffffff81741336)
Location: include/net/sch_generic.h:583
Inline: True
```
```
In net/sched/sch_fifo.c (ffffffff81749103)
Location: include/net/sch_generic.h:583
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:bfifo_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
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
In net/sched/sch_generic.c (ffffffff817ae132)
Location: include/net/sch_generic.h:603
Inline: True
```
```
In net/sched/sch_fifo.c (ffffffff817b60d7)
Location: include/net/sch_generic.h:603
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
In net/sched/sch_generic.c (ffffffff817dd79b)
Location: include/net/sch_generic.h:618
Inline: True
```
```
In net/sched/sch_fifo.c (ffffffff817e5b00)
Location: include/net/sch_generic.h:618
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff817fcdd6)
Location: include/net/sch_generic.h:663
Inline: True
```
```
In net/sched/sch_fifo.c (ffffffff81805630)
Location: include/net/sch_generic.h:663
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_generic.c (ffffffff8187a536)
Location: include/net/sch_generic.h:678
Inline: True
```
```
In net/sched/sch_fifo.c (ffffffff81884340)
Location: include/net/sch_generic.h:678
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff818d7ee0)
Location: include/net/sch_generic.h:776
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_fifo.c (ffffffff819046d0)
Location: include/net/sch_generic.h:875
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81965946)
Location: include/net/sch_generic.h:979
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_fifo.c (ffffffff8199c3d6)
Location: include/net/sch_generic.h:952
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_fifo.c (ffffffff81a75559)
Location: include/net/sch_generic.h:952
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
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
In net/sched/sch_fifo.c (ffffffff81a7e329)
Location: include/net/sch_generic.h:944
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
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
In net/sched/sch_fifo.c (ffffffff81a67176)
Location: include/net/sch_generic.h:997
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81b20656)
Location: include/net/sch_generic.h:1004
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81ca8966)
Location: include/net/sch_generic.h:969
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81e657d6)
Location: include/net/sch_generic.h:941
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81ec1716)
Location: include/net/sch_generic.h:953
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_enqueue
  - net/sched/sch_fifo.c:bfifo_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81f84a56)
Location: include/net/sch_generic.h:981
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffff800010c4967c)
Location: include/net/sch_generic.h:952
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_fifo.c (c0d5a3e4)
Location: include/net/sch_generic.h:952
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_fifo.c (c000000000d46eb8)
Location: include/net/sch_generic.h:952
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_fifo.c (ffffffe0007b6d3a)
Location: include/net/sch_generic.h:952
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_fifo.c (ffffffff8193c246)
Location: include/net/sch_generic.h:952
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_fifo.c (ffffffff818f5d46)
Location: include/net/sch_generic.h:952
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_fifo.c (ffffffff8198d3d6)
Location: include/net/sch_generic.h:952
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
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
In net/sched/sch_fifo.c (ffffffff819afc66)
Location: include/net/sch_generic.h:952
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
</details>
</li>
</ul>

## Differences
