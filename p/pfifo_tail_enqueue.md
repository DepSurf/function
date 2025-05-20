# Function: <code>pfifo_tail_enqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81749170)
Location: net/sched/sch_fifo.c:38
Inline: True
```
**Symbols:**

```
ffffffff81749170-ffffffff8174924c: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff817b6130)
Location: net/sched/sch_fifo.c:40
Inline: True
```
**Symbols:**

```
ffffffff817b6130-ffffffff817b621b: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff817e5af0)
Location: net/sched/sch_fifo.c:40
Inline: False
```
**Symbols:**

```
ffffffff817e5af0-ffffffff817e5c03: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81805620)
Location: net/sched/sch_fifo.c:40
Inline: False
```
**Symbols:**

```
ffffffff81805620-ffffffff81805733: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81884330)
Location: net/sched/sch_fifo.c:40
Inline: False
```
**Symbols:**

```
ffffffff81884330-ffffffff81884443: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff818d7ed0)
Location: net/sched/sch_fifo.c:40
Inline: False
```
**Symbols:**

```
ffffffff818d7ed0-ffffffff818d7fe3: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff819046c0)
Location: net/sched/sch_fifo.c:40
Inline: False
```
**Symbols:**

```
ffffffff819046c0-ffffffff819047d3: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81965930)
Location: net/sched/sch_fifo.c:36
Inline: False
```
**Symbols:**

```
ffffffff81965930-ffffffff81965a43: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff8199c3c0)
Location: net/sched/sch_fifo.c:36
Inline: False
```
**Symbols:**

```
ffffffff8199c3c0-ffffffff8199c4d3: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81a75540)
Location: net/sched/sch_fifo.c:37
Inline: False
```
**Symbols:**

```
ffffffff81a75540-ffffffff81a75658: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81a7e310)
Location: net/sched/sch_fifo.c:37
Inline: False
```
**Symbols:**

```
ffffffff81a7e310-ffffffff81a7e428: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81a67160)
Location: net/sched/sch_fifo.c:37
Inline: False
```
**Symbols:**

```
ffffffff81a67160-ffffffff81a67273: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81b20640)
Location: net/sched/sch_fifo.c:37
Inline: False
```
**Symbols:**

```
ffffffff81b20640-ffffffff81b20753: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81ca8950)
Location: net/sched/sch_fifo.c:37
Inline: False
```
**Symbols:**

```
ffffffff81ca8950-ffffffff81ca8a8b: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81e657c0)
Location: net/sched/sch_fifo.c:37
Inline: False
```
**Symbols:**

```
ffffffff81e657c0-ffffffff81e658fb: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81ec1700)
Location: net/sched/sch_fifo.c:37
Inline: False
```
**Symbols:**

```
ffffffff81ec1700-ffffffff81ec183b: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81f84a40)
Location: net/sched/sch_fifo.c:37
Inline: False
```
**Symbols:**

```
ffffffff81f84a40-ffffffff81f84b7b: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffff800010c49648)
Location: net/sched/sch_fifo.c:36
Inline: False
```
**Symbols:**

```
ffff800010c49648-ffff800010c49788: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (c0d5a3b8)
Location: net/sched/sch_fifo.c:36
Inline: False
```
**Symbols:**

```
c0d5a3b8-c0d5a4d4: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (c000000000d46e90)
Location: net/sched/sch_fifo.c:36
Inline: False
```
**Symbols:**

```
c000000000d46e90-c000000000d47018: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffe0007b6d12)
Location: net/sched/sch_fifo.c:36
Inline: False
```
**Symbols:**

```
ffffffe0007b6d12-ffffffe0007b6e0a: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff8193c230)
Location: net/sched/sch_fifo.c:36
Inline: False
```
**Symbols:**

```
ffffffff8193c230-ffffffff8193c343: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff818f5d30)
Location: net/sched/sch_fifo.c:36
Inline: False
```
**Symbols:**

```
ffffffff818f5d30-ffffffff818f5e43: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff8198d3c0)
Location: net/sched/sch_fifo.c:36
Inline: False
```
**Symbols:**

```
ffffffff8198d3c0-ffffffff8198d4d3: pfifo_tail_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pfifo_tail_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff819afc50)
Location: net/sched/sch_fifo.c:36
Inline: False
```
**Symbols:**

```
ffffffff819afc50-ffffffff819afd63: pfifo_tail_enqueue (STB_LOCAL)
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
