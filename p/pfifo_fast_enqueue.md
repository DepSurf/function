# Function: <code>pfifo_fast_enqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817412e0)
Location: net/sched/sch_generic.c:472
Inline: True
```
**Symbols:**

```
ffffffff817412e0-ffffffff81741374: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817ae0c0)
Location: net/sched/sch_generic.c:487
Inline: True
```
**Symbols:**

```
ffffffff817ae0c0-ffffffff817ae155: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817dd740)
Location: net/sched/sch_generic.c:486
Inline: True
```
**Symbols:**

```
ffffffff817dd740-ffffffff817dd7e3: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817fcd80)
Location: net/sched/sch_generic.c:486
Inline: True
```
**Symbols:**

```
ffffffff817fcd80-ffffffff817fce1e: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8187a4e0)
Location: net/sched/sch_generic.c:493
Inline: True
```
**Symbols:**

```
ffffffff8187a4e0-ffffffff8187a57e: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818cc1f0)
Location: net/sched/sch_generic.c:622
Inline: False
```
**Symbols:**

```
ffffffff818cc1f0-ffffffff818cc306: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818f7820)
Location: net/sched/sch_generic.c:634
Inline: False
```
**Symbols:**

```
ffffffff818f7820-ffffffff818f7937: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81956f40)
Location: net/sched/sch_generic.c:621
Inline: True
```
**Symbols:**

```
ffffffff81956f40-ffffffff8195708f: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8198d3e0)
Location: net/sched/sch_generic.c:621
Inline: True
```
**Symbols:**

```
ffffffff8198d3e0-ffffffff8198d52f: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a650d0)
Location: net/sched/sch_generic.c:617
Inline: True
```
**Symbols:**

```
ffffffff81a650d0-ffffffff81a6521d: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a6d200)
Location: net/sched/sch_generic.c:617
Inline: True
```
**Symbols:**

```
ffffffff81a6d200-ffffffff81a6d34d: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a55a80)
Location: net/sched/sch_generic.c:642
Inline: True
```
**Symbols:**

```
ffffffff81a55a80-ffffffff81a55bcd: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81b0e800)
Location: net/sched/sch_generic.c:670
Inline: True
```
**Symbols:**

```
ffffffff81b0e800-ffffffff81b0e94d: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81c94db0)
Location: net/sched/sch_generic.c:724
Inline: True
```
**Symbols:**

```
ffffffff81c94db0-ffffffff81c94ef6: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81e50860)
Location: net/sched/sch_generic.c:721
Inline: True
```
**Symbols:**

```
ffffffff81e50860-ffffffff81e509a6: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81eac040)
Location: net/sched/sch_generic.c:721
Inline: True
```
**Symbols:**

```
ffffffff81eac040-ffffffff81eac1b3: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81f6ead0)
Location: net/sched/sch_generic.c:723
Inline: True
```
**Symbols:**

```
ffffffff81f6ead0-ffffffff81f6ec43: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffff800010c386b8)
Location: net/sched/sch_generic.c:621
Inline: True
```
**Symbols:**

```
ffff800010c386b8-ffff800010c388d8: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c0d4a880)
Location: net/sched/sch_generic.c:621
Inline: True
```
**Symbols:**

```
c0d4a880-c0d4aa18: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c000000000d31500)
Location: net/sched/sch_generic.c:621
Inline: True
```
**Symbols:**

```
c000000000d31500-c000000000d317a8: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffe0007a9d64)
Location: net/sched/sch_generic.c:621
Inline: True
```
**Symbols:**

```
ffffffe0007a9d64-ffffffe0007a9f36: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8192d250)
Location: net/sched/sch_generic.c:621
Inline: True
```
**Symbols:**

```
ffffffff8192d250-ffffffff8192d39f: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818e6d50)
Location: net/sched/sch_generic.c:621
Inline: True
```
**Symbols:**

```
ffffffff818e6d50-ffffffff818e6e9f: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8197e3e0)
Location: net/sched/sch_generic.c:621
Inline: True
```
**Symbols:**

```
ffffffff8197e3e0-ffffffff8197e52f: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pfifo_fast_enqueue(struct sk_buff *skb, struct Qdisc *qdisc, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff819a05a0)
Location: net/sched/sch_generic.c:621
Inline: True
```
**Symbols:**

```
ffffffff819a05a0-ffffffff819a06ea: pfifo_fast_enqueue (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sk_buff **to_free</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
