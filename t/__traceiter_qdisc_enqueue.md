# Function: <code>__traceiter_qdisc_enqueue</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_qdisc_enqueue(void *__data, struct Qdisc *qdisc, const struct netdev_queue *txq, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81ade710)
Location: include/trace/events/qdisc.h:49
Inline: False
```
**Symbols:**

```
ffffffff81ade710-ffffffff81ade75f: __traceiter_qdisc_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_qdisc_enqueue(void *__data, struct Qdisc *qdisc, const struct netdev_queue *txq, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81c5ff90)
Location: include/trace/events/qdisc.h:49
Inline: False
```
**Symbols:**

```
ffffffff81c5ff90-ffffffff81c5ffeb: __traceiter_qdisc_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_qdisc_enqueue(void *__data, struct Qdisc *qdisc, const struct netdev_queue *txq, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e16a70)
Location: include/trace/events/qdisc.h:49
Inline: False
```
**Symbols:**

```
ffffffff81e16a70-ffffffff81e16acb: __traceiter_qdisc_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_qdisc_enqueue(void *__data, struct Qdisc *qdisc, const struct netdev_queue *txq, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e8a640)
Location: include/trace/events/qdisc.h:49
Inline: False
```
**Symbols:**

```
ffffffff81e8a640-ffffffff81e8a69b: __traceiter_qdisc_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_qdisc_enqueue(void *__data, struct Qdisc *qdisc, const struct netdev_queue *txq, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81f4c650)
Location: include/trace/events/qdisc.h:49
Inline: False
```
**Symbols:**

```
ffffffff81f4c650-ffffffff81f4c6ab: __traceiter_qdisc_enqueue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
