# Function: <code>qdisc_qlen_sum</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_mq.c (ffffffff818ce11f)
Location: include/net/sch_generic.h:351
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff818cfcdf)
Location: include/net/sch_generic.h:351
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
In net/sched/sch_mq.c (ffffffff818f9227)
Location: include/net/sch_generic.h:419
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff818faf5c)
Location: include/net/sch_generic.h:419
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
In net/sched/sch_mq.c (ffffffff81958f9a)
Location: include/net/sch_generic.h:491
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff8195a94c)
Location: include/net/sch_generic.h:491
Inline: True
Inline callers:
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
In net/sched/sch_mq.c (ffffffff8198f43c)
Location: include/net/sch_generic.h:475
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81990dfc)
Location: include/net/sch_generic.h:475
Inline: True
Inline callers:
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
In net/sched/sch_mq.c (ffffffff81a66d8c)
Location: include/net/sch_generic.h:480
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81a68e0c)
Location: include/net/sch_generic.h:480
Inline: True
Inline callers:
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
In net/sched/sch_mq.c (ffffffff81a6ed3c)
Location: include/net/sch_generic.h:472
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81a71541)
Location: include/net/sch_generic.h:472
Inline: True
Inline callers:
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
In net/sched/sch_mq.c (ffffffff81a575d8)
Location: include/net/sch_generic.h:519
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81a59f01)
Location: include/net/sch_generic.h:519
Inline: True
Inline callers:
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
In net/sched/sch_mq.c (ffffffff81b10518)
Location: include/net/sch_generic.h:524
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81b12fd1)
Location: include/net/sch_generic.h:524
Inline: True
Inline callers:
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
In net/sched/sch_mq.c (ffffffff81c977d6)
Location: include/net/sch_generic.h:512
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
```
```
In net/sched/sch_api.c (ffffffff81c99c2b)
Location: include/net/sch_generic.h:512
Inline: True
Inline callers:
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
In net/sched/sch_mq.c (ffffffff81e53836)
Location: include/net/sch_generic.h:507
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
```
```
In net/sched/sch_api.c (ffffffff81e55f5b)
Location: include/net/sch_generic.h:507
Inline: True
Inline callers:
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
In net/sched/sch_mq.c (ffffffff81eaf0b6)
Location: include/net/sch_generic.h:516
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
```
```
In net/sched/sch_api.c (ffffffff81eb22e6)
Location: include/net/sch_generic.h:516
Inline: True
Inline callers:
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
In net/sched/sch_mq.c (ffffffff81f71b53)
Location: include/net/sch_generic.h:517
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
```
```
In net/sched/sch_api.c (ffffffff81f74d96)
Location: include/net/sch_generic.h:517
Inline: True
Inline callers:
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
In net/sched/sch_mq.c (ffff800010c3b324)
Location: include/net/sch_generic.h:475
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffff800010c3d330)
Location: include/net/sch_generic.h:475
Inline: True
Inline callers:
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
In net/sched/sch_mq.c (c0d4d074)
Location: include/net/sch_generic.h:475
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (c0d4edfc)
Location: include/net/sch_generic.h:475
Inline: True
Inline callers:
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
In net/sched/sch_mq.c (c000000000d34350)
Location: include/net/sch_generic.h:475
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (c000000000d36b78)
Location: include/net/sch_generic.h:475
Inline: True
Inline callers:
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
In net/sched/sch_mq.c (ffffffe0007abb24)
Location: include/net/sch_generic.h:475
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffe0007ad7de)
Location: include/net/sch_generic.h:475
Inline: True
Inline callers:
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
In net/sched/sch_mq.c (ffffffff8192f2ac)
Location: include/net/sch_generic.h:475
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81930c6c)
Location: include/net/sch_generic.h:475
Inline: True
Inline callers:
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
In net/sched/sch_mq.c (ffffffff818e8dac)
Location: include/net/sch_generic.h:475
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff818ea76c)
Location: include/net/sch_generic.h:475
Inline: True
Inline callers:
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
In net/sched/sch_mq.c (ffffffff8198043c)
Location: include/net/sch_generic.h:475
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81981dfc)
Location: include/net/sch_generic.h:475
Inline: True
Inline callers:
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
In net/sched/sch_mq.c (ffffffff819a299c)
Location: include/net/sch_generic.h:475
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff819a433c)
Location: include/net/sch_generic.h:475
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
</details>
</li>
</ul>

## Differences
