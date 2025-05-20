# Function: <code>qdisc_dequeue_skb_bad_txq</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818ccbf5)
Location: net/sched/sch_generic.c:87
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
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
In net/sched/sch_generic.c (ffffffff818f7f65)
Location: net/sched/sch_generic.c:87
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
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
In net/sched/sch_generic.c (ffffffff8195769c)
Location: net/sched/sch_generic.c:86
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
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
In net/sched/sch_generic.c (ffffffff8198db3c)
Location: net/sched/sch_generic.c:86
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
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
In net/sched/sch_generic.c (ffffffff81a655f5)
Location: net/sched/sch_generic.c:86
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
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
In net/sched/sch_generic.c (ffffffff81a6d70e)
Location: net/sched/sch_generic.c:86
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
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
In net/sched/sch_generic.c (ffffffff81a55e7d)
Location: net/sched/sch_generic.c:106
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
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
In net/sched/sch_generic.c (ffffffff81b0ec2d)
Location: net/sched/sch_generic.c:108
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
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
In net/sched/sch_generic.c (ffffffff81c95e0d)
Location: net/sched/sch_generic.c:108
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
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
In net/sched/sch_generic.c (ffffffff81e519ed)
Location: net/sched/sch_generic.c:108
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
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
In net/sched/sch_generic.c (ffffffff81ead232)
Location: net/sched/sch_generic.c:108
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
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
In net/sched/sch_generic.c (ffffffff81f6fcd2)
Location: net/sched/sch_generic.c:108
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
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
In net/sched/sch_generic.c (ffff800010c3921c)
Location: net/sched/sch_generic.c:86
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
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
In net/sched/sch_generic.c (c0d4b574)
Location: net/sched/sch_generic.c:86
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
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
In net/sched/sch_generic.c (c000000000d31dfc)
Location: net/sched/sch_generic.c:86
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
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
In net/sched/sch_generic.c (ffffffe0007aa656)
Location: net/sched/sch_generic.c:86
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
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
In net/sched/sch_generic.c (ffffffff8192d9ac)
Location: net/sched/sch_generic.c:86
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
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
In net/sched/sch_generic.c (ffffffff818e74ac)
Location: net/sched/sch_generic.c:86
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
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
In net/sched/sch_generic.c (ffffffff8197eb3c)
Location: net/sched/sch_generic.c:86
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
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
In net/sched/sch_generic.c (ffffffff819a10ac)
Location: net/sched/sch_generic.c:86
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
</details>
</li>
</ul>

## Differences
