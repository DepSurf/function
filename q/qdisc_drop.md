# Function: <code>qdisc_drop</code>

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
In net/sched/sch_generic.c (ffffffff81741360)
Location: include/net/sch_generic.h:720
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81745a3d)
Location: include/net/sch_generic.h:720
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
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
In net/sched/sch_generic.c (ffffffff817ae0e0)
Location: include/net/sch_generic.h:746
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff817b2925)
Location: include/net/sch_generic.h:746
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff817b610a)
Location: include/net/sch_generic.h:746
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
In net/sched/sch_generic.c (ffffffff817dd7c3)
Location: include/net/sch_generic.h:786
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff817e20d5)
Location: include/net/sch_generic.h:786
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff817e5c70)
Location: include/net/sch_generic.h:786
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
In net/sched/sch_generic.c (ffffffff817fcdfe)
Location: include/net/sch_generic.h:834
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81801625)
Location: include/net/sch_generic.h:834
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff818057a0)
Location: include/net/sch_generic.h:834
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
In net/sched/sch_generic.c (ffffffff8187a55e)
Location: include/net/sch_generic.h:859
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff8187f365)
Location: include/net/sch_generic.h:859
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff818844b0)
Location: include/net/sch_generic.h:859
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
In net/sched/sch_blackhole.c (ffffffff818d2145)
Location: include/net/sch_generic.h:969
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff818d8050)
Location: include/net/sch_generic.h:969
Inline: True
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
In net/sched/sch_blackhole.c (ffffffff818fd535)
Location: include/net/sch_generic.h:1078
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff81904840)
Location: include/net/sch_generic.h:1078
Inline: True
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
In net/sched/sch_generic.c (ffffffff81957079)
Location: include/net/sch_generic.h:1208
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff8195cf75)
Location: include/net/sch_generic.h:1208
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff81965aad)
Location: include/net/sch_generic.h:1208
Inline: True
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
In net/sched/sch_generic.c (ffffffff8198d519)
Location: include/net/sch_generic.h:1181
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81993475)
Location: include/net/sch_generic.h:1181
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff8199c53d)
Location: include/net/sch_generic.h:1181
Inline: True
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
In net/sched/sch_generic.c (ffffffff81a65207)
Location: include/net/sch_generic.h:1181
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81a6b665)
Location: include/net/sch_generic.h:1181
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff81a750bd)
Location: include/net/sch_generic.h:1181
Inline: True
Inline callers:
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
In net/sched/sch_generic.c (ffffffff81a6d337)
Location: include/net/sch_generic.h:1167
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81a73dd5)
Location: include/net/sch_generic.h:1167
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff81a7dfbd)
Location: include/net/sch_generic.h:1167
Inline: True
Inline callers:
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
In net/sched/sch_generic.c (ffffffff81a55bb7)
Location: include/net/sch_generic.h:1220
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81a5c975)
Location: include/net/sch_generic.h:1220
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff81a66e0d)
Location: include/net/sch_generic.h:1220
Inline: True
Inline callers:
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
In net/sched/sch_generic.c (ffffffff81b0e937)
Location: include/net/sch_generic.h:1227
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81b15b25)
Location: include/net/sch_generic.h:1227
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff81b202cd)
Location: include/net/sch_generic.h:1227
Inline: True
Inline callers:
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
In net/sched/sch_generic.c (ffffffff81c94eed)
Location: include/net/sch_generic.h:1192
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81c9cf45)
Location: include/net/sch_generic.h:1192
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff81ca8537)
Location: include/net/sch_generic.h:1192
Inline: True
Inline callers:
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
In net/sched/sch_generic.c (ffffffff81e5099d)
Location: include/net/sch_generic.h:1163
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81e593c5)
Location: include/net/sch_generic.h:1163
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff81e65367)
Location: include/net/sch_generic.h:1163
Inline: True
Inline callers:
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
In net/sched/sch_generic.c (ffffffff81eac18f)
Location: include/net/sch_generic.h:1175
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81eb4df5)
Location: include/net/sch_generic.h:1175
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff81ec12a7)
Location: include/net/sch_generic.h:1175
Inline: True
Inline callers:
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
In net/sched/sch_generic.c (ffffffff81f6ec1f)
Location: include/net/sch_generic.h:1234
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81f77ab5)
Location: include/net/sch_generic.h:1234
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff81f845a7)
Location: include/net/sch_generic.h:1234
Inline: True
Inline callers:
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
In net/sched/sch_generic.c (ffff800010c38824)
Location: include/net/sch_generic.h:1181
Inline: True
```
```
In net/sched/sch_blackhole.c (ffff800010c3f95c)
Location: include/net/sch_generic.h:1181
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffff800010c49818)
Location: include/net/sch_generic.h:1181
Inline: True
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
In net/sched/sch_generic.c (c0d4aa00)
Location: include/net/sch_generic.h:1181
Inline: True
```
```
In net/sched/sch_blackhole.c (c0d512fc)
Location: include/net/sch_generic.h:1181
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (c0d5a548)
Location: include/net/sch_generic.h:1181
Inline: True
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
In net/sched/sch_generic.c (c000000000d31740)
Location: include/net/sch_generic.h:1181
Inline: True
```
```
In net/sched/sch_blackhole.c (c000000000d39ef8)
Location: include/net/sch_generic.h:1181
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (c000000000d470b0)
Location: include/net/sch_generic.h:1181
Inline: True
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
In net/sched/sch_generic.c (ffffffe0007a9f28)
Location: include/net/sch_generic.h:1181
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffe0007af454)
Location: include/net/sch_generic.h:1181
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffe0007b6e7a)
Location: include/net/sch_generic.h:1181
Inline: True
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
In net/sched/sch_generic.c (ffffffff8192d389)
Location: include/net/sch_generic.h:1181
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff819332e5)
Location: include/net/sch_generic.h:1181
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff8193c3ad)
Location: include/net/sch_generic.h:1181
Inline: True
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
In net/sched/sch_generic.c (ffffffff818e6e89)
Location: include/net/sch_generic.h:1181
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff818ecde5)
Location: include/net/sch_generic.h:1181
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff818f5ead)
Location: include/net/sch_generic.h:1181
Inline: True
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
In net/sched/sch_generic.c (ffffffff8197e519)
Location: include/net/sch_generic.h:1181
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff81984475)
Location: include/net/sch_generic.h:1181
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff8198d53d)
Location: include/net/sch_generic.h:1181
Inline: True
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
In net/sched/sch_generic.c (ffffffff819a06dc)
Location: include/net/sch_generic.h:1181
Inline: True
```
```
In net/sched/sch_blackhole.c (ffffffff819a69b5)
Location: include/net/sch_generic.h:1181
Inline: True
Inline callers:
  - net/sched/sch_blackhole.c:blackhole_enqueue
```
```
In net/sched/sch_fifo.c (ffffffff819afdcd)
Location: include/net/sch_generic.h:1181
Inline: True
```
</details>
</li>
</ul>

## Differences
