# Function: <code>bfifo_enqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff817490f0)
Location: net/sched/sch_fifo.c:22
Inline: False
```
**Symbols:**

```
ffffffff817490f0-ffffffff81749163: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff817b60c0)
Location: net/sched/sch_fifo.c:22
Inline: True
```
**Symbols:**

```
ffffffff817b60c0-ffffffff817b6121: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff817e5c10)
Location: net/sched/sch_fifo.c:22
Inline: True
```
**Symbols:**

```
ffffffff817e5c10-ffffffff817e5c87: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81805740)
Location: net/sched/sch_fifo.c:22
Inline: True
```
**Symbols:**

```
ffffffff81805740-ffffffff818057b7: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81884450)
Location: net/sched/sch_fifo.c:22
Inline: True
```
**Symbols:**

```
ffffffff81884450-ffffffff818844c7: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff818d7ff0)
Location: net/sched/sch_fifo.c:22
Inline: True
```
**Symbols:**

```
ffffffff818d7ff0-ffffffff818d8067: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff819047e0)
Location: net/sched/sch_fifo.c:22
Inline: True
```
**Symbols:**

```
ffffffff819047e0-ffffffff81904857: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81965ad0)
Location: net/sched/sch_fifo.c:18
Inline: True
```
**Symbols:**

```
ffffffff81965ad0-ffffffff81965b47: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff8199c560)
Location: net/sched/sch_fifo.c:18
Inline: True
```
**Symbols:**

```
ffffffff8199c560-ffffffff8199c5d7: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81a750e0)
Location: net/sched/sch_fifo.c:19
Inline: False
```
**Symbols:**

```
ffffffff81a750e0-ffffffff81a75157: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81a7dfe0)
Location: net/sched/sch_fifo.c:19
Inline: False
```
**Symbols:**

```
ffffffff81a7dfe0-ffffffff81a7e057: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81a66e30)
Location: net/sched/sch_fifo.c:19
Inline: False
```
**Symbols:**

```
ffffffff81a66e30-ffffffff81a66ea7: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81b202f0)
Location: net/sched/sch_fifo.c:19
Inline: False
```
**Symbols:**

```
ffffffff81b202f0-ffffffff81b20367: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81ca8560)
Location: net/sched/sch_fifo.c:19
Inline: False
```
**Symbols:**

```
ffffffff81ca8560-ffffffff81ca85ef: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81e653a0)
Location: net/sched/sch_fifo.c:19
Inline: False
```
**Symbols:**

```
ffffffff81e653a0-ffffffff81e6542f: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81ec12e0)
Location: net/sched/sch_fifo.c:19
Inline: False
```
**Symbols:**

```
ffffffff81ec12e0-ffffffff81ec136f: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff81f845e0)
Location: net/sched/sch_fifo.c:19
Inline: False
```
**Symbols:**

```
ffffffff81f845e0-ffffffff81f8466f: bfifo_enqueue (STB_LOCAL)
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
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffff800010c49788)
Location: net/sched/sch_fifo.c:18
Inline: True
```
**Symbols:**

```
ffff800010c49788-ffff800010c49844: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (c0d5a4d4)
Location: net/sched/sch_fifo.c:18
Inline: True
```
**Symbols:**

```
c0d5a4d4-c0d5a568: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (c000000000d470d0)
Location: net/sched/sch_fifo.c:18
Inline: True
```
**Symbols:**

```
c000000000d470d0-c000000000d47190: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffe0007b6e0a)
Location: net/sched/sch_fifo.c:18
Inline: True
```
**Symbols:**

```
ffffffe0007b6e0a-ffffffe0007b6ea0: bfifo_enqueue (STB_LOCAL)
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
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff8193c3d0)
Location: net/sched/sch_fifo.c:18
Inline: True
```
**Symbols:**

```
ffffffff8193c3d0-ffffffff8193c447: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff818f5ed0)
Location: net/sched/sch_fifo.c:18
Inline: True
```
**Symbols:**

```
ffffffff818f5ed0-ffffffff818f5f47: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff8198d560)
Location: net/sched/sch_fifo.c:18
Inline: True
```
**Symbols:**

```
ffffffff8198d560-ffffffff8198d5d7: bfifo_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int bfifo_enqueue(struct sk_buff *skb, struct Qdisc *sch, struct sk_buff **to_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_fifo.c (ffffffff819afdf0)
Location: net/sched/sch_fifo.c:18
Inline: True
```
**Symbols:**

```
ffffffff819afdf0-ffffffff819afe67: bfifo_enqueue (STB_LOCAL)
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
