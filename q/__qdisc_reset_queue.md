# Function: <code>__qdisc_reset_queue</code>

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
In net/sched/sch_generic.c (ffffffff81740df1)
Location: include/net/sch_generic.h:685
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_reset
```
```
In net/sched/sch_fifo.c (ffffffff81748fb1)
Location: include/net/sch_generic.h:685
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_generic.c (ffffffff817adbbf)
Location: include/net/sch_generic.h:704
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_reset
```
```
In net/sched/sch_fifo.c (ffffffff817b6001)
Location: include/net/sch_generic.h:704
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_generic.c (ffffffff817dd211)
Location: include/net/sch_generic.h:740
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_reset
```
```
In net/sched/sch_fifo.c (ffffffff817e5a78)
Location: include/net/sch_generic.h:740
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_generic.c (ffffffff817fc861)
Location: include/net/sch_generic.h:785
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_reset
```
```
In net/sched/sch_fifo.c (ffffffff818055a8)
Location: include/net/sch_generic.h:785
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_generic.c (ffffffff8187a2d1)
Location: include/net/sch_generic.h:810
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_reset
```
```
In net/sched/sch_fifo.c (ffffffff818842b8)
Location: include/net/sch_generic.h:810
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_fifo.c (ffffffff818d7e30)
Location: include/net/sch_generic.h:912
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_fifo.c (ffffffff81904620)
Location: include/net/sch_generic.h:1021
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_fifo.c (ffffffff81965890)
Location: include/net/sch_generic.h:1156
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_fifo.c (ffffffff8199c320)
Location: include/net/sch_generic.h:1129
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_fifo.c (ffffffff81a75160)
Location: include/net/sch_generic.h:1129
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_fifo.c (ffffffff81a7e068)
Location: include/net/sch_generic.h:1115
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_fifo.c (ffffffff81a66eb8)
Location: include/net/sch_generic.h:1168
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_fifo.c (ffffffff81b2037a)
Location: include/net/sch_generic.h:1175
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_fifo.c (ffffffff81ca85fa)
Location: include/net/sch_generic.h:1140
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_fifo.c (ffffffff81e6544a)
Location: include/net/sch_generic.h:1112
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_fifo.c (ffffffff81ec138a)
Location: include/net/sch_generic.h:1124
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_fifo.c (ffffffff81f8468a)
Location: include/net/sch_generic.h:1183
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_fifo.c (ffff800010c495c0)
Location: include/net/sch_generic.h:1129
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_fifo.c (c0d5a324)
Location: include/net/sch_generic.h:1129
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_fifo.c (c000000000d46dc8)
Location: include/net/sch_generic.h:1129
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_fifo.c (ffffffe0007b6c8e)
Location: include/net/sch_generic.h:1129
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_fifo.c (ffffffff8193c190)
Location: include/net/sch_generic.h:1129
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_fifo.c (ffffffff818f5c90)
Location: include/net/sch_generic.h:1129
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_fifo.c (ffffffff8198d320)
Location: include/net/sch_generic.h:1129
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
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
In net/sched/sch_fifo.c (ffffffff819afbb0)
Location: include/net/sch_generic.h:1129
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
</details>
</li>
</ul>

## Differences
