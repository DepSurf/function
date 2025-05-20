# Function: <code>pfifo_enqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff817493b0)
Location: net/sched/sch_fifo.c:30
Inline: False
```
**Symbols:**

```
ffffffff817493b0-ffffffff81749420: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff817b6330)
Location: net/sched/sch_fifo.c:31
Inline: True
```
**Symbols:**

```
ffffffff817b6330-ffffffff817b638e: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff817e5da0)
Location: net/sched/sch_fifo.c:31
Inline: True
```
**Symbols:**

```
ffffffff817e5da0-ffffffff817e5e14: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff818058d0)
Location: net/sched/sch_fifo.c:31
Inline: True
```
**Symbols:**

```
ffffffff818058d0-ffffffff81805944: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff818845f0)
Location: net/sched/sch_fifo.c:31
Inline: True
```
**Symbols:**

```
ffffffff818845f0-ffffffff81884664: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff818d8170)
Location: net/sched/sch_fifo.c:31
Inline: True
```
**Symbols:**

```
ffffffff818d8170-ffffffff818d81e4: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81904840)
Location: net/sched/sch_fifo.c:31
Inline: True
```
**Symbols:**

```
ffffffff81904960-ffffffff819049d4: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81965a50)
Location: net/sched/sch_fifo.c:27
Inline: True
```
**Symbols:**

```
ffffffff81965a50-ffffffff81965ac4: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff8199c4e0)
Location: net/sched/sch_fifo.c:27
Inline: True
```
**Symbols:**

```
ffffffff8199c4e0-ffffffff8199c554: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81a75060)
Location: net/sched/sch_fifo.c:28
Inline: False
```
**Symbols:**

```
ffffffff81a75060-ffffffff81a750d4: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81a7df60)
Location: net/sched/sch_fifo.c:28
Inline: False
```
**Symbols:**

```
ffffffff81a7df60-ffffffff81a7dfd4: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81a66db0)
Location: net/sched/sch_fifo.c:28
Inline: False
```
**Symbols:**

```
ffffffff81a66db0-ffffffff81a66e24: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81b20270)
Location: net/sched/sch_fifo.c:28
Inline: False
```
**Symbols:**

```
ffffffff81b20270-ffffffff81b202e4: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81ca84d0)
Location: net/sched/sch_fifo.c:28
Inline: False
```
**Symbols:**

```
ffffffff81ca84d0-ffffffff81ca8558: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81e65300)
Location: net/sched/sch_fifo.c:28
Inline: False
```
**Symbols:**

```
ffffffff81e65300-ffffffff81e65388: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81ec1240)
Location: net/sched/sch_fifo.c:28
Inline: False
```
**Symbols:**

```
ffffffff81ec1240-ffffffff81ec12c8: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81f84540)
Location: net/sched/sch_fifo.c:28
Inline: False
```
**Symbols:**

```
ffffffff81f84540-ffffffff81f845c8: pfifo_enqueue (STB_LOCAL)
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
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffff800010c49818)
Location: net/sched/sch_fifo.c:27
Inline: True
```
**Symbols:**

```
ffff800010c499a8-ffff800010c49a5c: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (c0d5a548)
Location: net/sched/sch_fifo.c:27
Inline: True
```
**Symbols:**

```
c0d5a694-c0d5a720: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (c000000000d47020)
Location: net/sched/sch_fifo.c:27
Inline: True
```
**Symbols:**

```
c000000000d47020-c000000000d470d0: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffe0007b6e7a)
Location: net/sched/sch_fifo.c:27
Inline: True
```
**Symbols:**

```
ffffffe0007b6fc8-ffffffe0007b7058: pfifo_enqueue (STB_LOCAL)
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
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff8193c350)
Location: net/sched/sch_fifo.c:27
Inline: True
```
**Symbols:**

```
ffffffff8193c350-ffffffff8193c3c4: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff818f5e50)
Location: net/sched/sch_fifo.c:27
Inline: True
```
**Symbols:**

```
ffffffff818f5e50-ffffffff818f5ec4: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff8198d4e0)
Location: net/sched/sch_fifo.c:27
Inline: True
```
**Symbols:**

```
ffffffff8198d4e0-ffffffff8198d554: pfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff819afd70)
Location: net/sched/sch_fifo.c:27
Inline: True
```
**Symbols:**

```
ffffffff819afd70-ffffffff819afde4: pfifo_enqueue (STB_LOCAL)
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
