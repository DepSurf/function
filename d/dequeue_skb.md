# Function: <code>dequeue_skb</code>

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
In net/sched/sch_generic.c (ffffffff8174162a)
Location: net/sched/sch_generic.c:82
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
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
In net/sched/sch_generic.c (ffffffff817ae3ea)
Location: net/sched/sch_generic.c:111
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
In net/sched/sch_generic.c (ffffffff817dda7a)
Location: net/sched/sch_generic.c:111
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
In net/sched/sch_generic.c (ffffffff817fd08f)
Location: net/sched/sch_generic.c:111
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
In net/sched/sch_generic.c (ffffffff8187aa22)
Location: net/sched/sch_generic.c:113
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
In net/sched/sch_generic.c (ffffffff818ccbc8)
Location: net/sched/sch_generic.c:219
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
In net/sched/sch_generic.c (ffffffff818f7f38)
Location: net/sched/sch_generic.c:219
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
In net/sched/sch_generic.c (ffffffff8195766a)
Location: net/sched/sch_generic.c:202
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
In net/sched/sch_generic.c (ffffffff8198db0a)
Location: net/sched/sch_generic.c:202
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
struct sk_buff *dequeue_skb(struct Qdisc *q, bool *validate, int *packets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a655a0)
Location: net/sched/sch_generic.c:202
Inline: False
Direct callers:
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff81a655a0-ffffffff81a659a1: dequeue_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *dequeue_skb(struct Qdisc *q, bool *validate, int *packets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a6d6b0)
Location: net/sched/sch_generic.c:202
Inline: False
Direct callers:
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff81a6d6b0-ffffffff81a6dacd: dequeue_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *dequeue_skb(struct Qdisc *q, bool *validate, int *packets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a55e20)
Location: net/sched/sch_generic.c:222
Inline: False
Direct callers:
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff81a55e20-ffffffff81a56308: dequeue_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *dequeue_skb(struct Qdisc *q, bool *validate, int *packets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81b0ebd0)
Location: net/sched/sch_generic.c:228
Inline: False
Direct callers:
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff81b0ebd0-ffffffff81b0f0c1: dequeue_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *dequeue_skb(struct Qdisc *q, bool *validate, int *packets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81c95db0)
Location: net/sched/sch_generic.c:228
Inline: False
Direct callers:
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff81c95db0-ffffffff81c962cc: dequeue_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *dequeue_skb(struct Qdisc *q, bool *validate, int *packets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81e51990)
Location: net/sched/sch_generic.c:228
Inline: False
Direct callers:
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff81e51990-ffffffff81e51eac: dequeue_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *dequeue_skb(struct Qdisc *q, bool *validate, int *packets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81ead1d0)
Location: net/sched/sch_generic.c:228
Inline: False
Direct callers:
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff81ead1d0-ffffffff81ead720: dequeue_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *dequeue_skb(struct Qdisc *q, bool *validate, int *packets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81f6fc70)
Location: net/sched/sch_generic.c:228
Inline: False
Direct callers:
  - net/sched/sch_generic.c:__qdisc_run
```
**Symbols:**

```
ffffffff81f6fc70-ffffffff81f701ba: dequeue_skb (STB_LOCAL)
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
In net/sched/sch_generic.c (ffff800010c391f8)
Location: net/sched/sch_generic.c:202
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
In net/sched/sch_generic.c (c0d4b548)
Location: net/sched/sch_generic.c:202
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
In net/sched/sch_generic.c (c000000000d31dd0)
Location: net/sched/sch_generic.c:202
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
Location: net/sched/sch_generic.c:202
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
In net/sched/sch_generic.c (ffffffff8192d97a)
Location: net/sched/sch_generic.c:202
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
In net/sched/sch_generic.c (ffffffff818e747a)
Location: net/sched/sch_generic.c:202
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
In net/sched/sch_generic.c (ffffffff8197eb0a)
Location: net/sched/sch_generic.c:202
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
In net/sched/sch_generic.c (ffffffff819a107a)
Location: net/sched/sch_generic.c:202
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
