# Function: <code>try_bulk_dequeue_skb_slow</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817ae510)
Location: net/sched/sch_generic.c:83
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
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
In net/sched/sch_generic.c (ffffffff817ddb9c)
Location: net/sched/sch_generic.c:83
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
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
In net/sched/sch_generic.c (ffffffff817fd1aa)
Location: net/sched/sch_generic.c:83
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
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
In net/sched/sch_generic.c (ffffffff8187abab)
Location: net/sched/sch_generic.c:85
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
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
In net/sched/sch_generic.c (ffffffff818ccd8a)
Location: net/sched/sch_generic.c:193
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
In net/sched/sch_generic.c (ffffffff818f80f1)
Location: net/sched/sch_generic.c:193
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
In net/sched/sch_generic.c (ffffffff81957838)
Location: net/sched/sch_generic.c:176
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
In net/sched/sch_generic.c (ffffffff8198dcd8)
Location: net/sched/sch_generic.c:176
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void try_bulk_dequeue_skb_slow(struct Qdisc *q, struct sk_buff *skb, int *packets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a65490)
Location: net/sched/sch_generic.c:176
Inline: False
Direct callers:
  - net/sched/sch_generic.c:dequeue_skb
```
**Symbols:**

```
ffffffff81a65490-ffffffff81a65591: try_bulk_dequeue_skb_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void try_bulk_dequeue_skb_slow(struct Qdisc *q, struct sk_buff *skb, int *packets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a6d5a0)
Location: net/sched/sch_generic.c:176
Inline: False
Direct callers:
  - net/sched/sch_generic.c:dequeue_skb
```
**Symbols:**

```
ffffffff81a6d5a0-ffffffff81a6d6a1: try_bulk_dequeue_skb_slow (STB_LOCAL)
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
In net/sched/sch_generic.c (ffffffff81a55f5e)
Location: net/sched/sch_generic.c:196
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
In net/sched/sch_generic.c (ffffffff81b0ed0b)
Location: net/sched/sch_generic.c:202
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
In net/sched/sch_generic.c (ffffffff81c95f0f)
Location: net/sched/sch_generic.c:202
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
In net/sched/sch_generic.c (ffffffff81e51aef)
Location: net/sched/sch_generic.c:202
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
In net/sched/sch_generic.c (ffffffff81ead334)
Location: net/sched/sch_generic.c:202
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
In net/sched/sch_generic.c (ffffffff81f6fdd4)
Location: net/sched/sch_generic.c:202
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
In net/sched/sch_generic.c (ffff800010c39428)
Location: net/sched/sch_generic.c:176
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
In net/sched/sch_generic.c (c0d4b744)
Location: net/sched/sch_generic.c:176
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
In net/sched/sch_generic.c (c000000000d32020)
Location: net/sched/sch_generic.c:176
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
In net/sched/sch_generic.c (ffffffe0007aa642)
Location: net/sched/sch_generic.c:176
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
In net/sched/sch_generic.c (ffffffff8192db48)
Location: net/sched/sch_generic.c:176
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
In net/sched/sch_generic.c (ffffffff818e7648)
Location: net/sched/sch_generic.c:176
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
In net/sched/sch_generic.c (ffffffff8197ecd8)
Location: net/sched/sch_generic.c:176
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
In net/sched/sch_generic.c (ffffffff819a1261)
Location: net/sched/sch_generic.c:176
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
