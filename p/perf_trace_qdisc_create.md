# Function: <code>perf_trace_qdisc_create</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_trace_qdisc_create(void *__data, const struct Qdisc_ops *ops, struct net_device *dev, u32 parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a457e0)
Location: include/trace/events/qdisc.h:99
Inline: False
```
**Symbols:**

```
ffffffff81a457e0-ffffffff81a4598d: perf_trace_qdisc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void perf_trace_qdisc_create(void *__data, const struct Qdisc_ops *ops, struct net_device *dev, u32 parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/qdisc.h:99
Inline: False
```
**Symbols:**

```
ffffffff81a49c90-ffffffff81a49fb7: perf_trace_qdisc_create (STB_LOCAL)
ffffffff81c31c5b-ffffffff81c31c73: perf_trace_qdisc_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void perf_trace_qdisc_create(void *__data, const struct Qdisc_ops *ops, struct net_device *dev, u32 parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/qdisc.h:99
Inline: False
```
**Symbols:**

```
ffffffff81a2ebe0-ffffffff81a2ef1f: perf_trace_qdisc_create (STB_LOCAL)
ffffffff81c23f24-ffffffff81c23f3c: perf_trace_qdisc_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void perf_trace_qdisc_create(void *__data, const struct Qdisc_ops *ops, struct net_device *dev, u32 parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/qdisc.h:127
Inline: False
```
**Symbols:**

```
ffffffff81ae41c0-ffffffff81ae44ff: perf_trace_qdisc_create (STB_LOCAL)
ffffffff81d37f38-ffffffff81d37f50: perf_trace_qdisc_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void perf_trace_qdisc_create(void *__data, const struct Qdisc_ops *ops, struct net_device *dev, u32 parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/qdisc.h:127
Inline: False
```
**Symbols:**

```
ffffffff81c665c0-ffffffff81c6690a: perf_trace_qdisc_create (STB_LOCAL)
ffffffff81f04891-ffffffff81f048a9: perf_trace_qdisc_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_trace_qdisc_create(void *__data, const struct Qdisc_ops *ops, struct net_device *dev, u32 parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e1d620)
Location: include/trace/events/qdisc.h:127
Inline: False
```
**Symbols:**

```
ffffffff81e1d620-ffffffff81e1d988: perf_trace_qdisc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_trace_qdisc_create(void *__data, const struct Qdisc_ops *ops, struct net_device *dev, u32 parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e94070)
Location: include/trace/events/qdisc.h:127
Inline: False
```
**Symbols:**

```
ffffffff81e94070-ffffffff81e9440e: perf_trace_qdisc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_trace_qdisc_create(void *__data, const struct Qdisc_ops *ops, struct net_device *dev, u32 parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81f56530)
Location: include/trace/events/qdisc.h:127
Inline: False
```
**Symbols:**

```
ffffffff81f56530-ffffffff81f568da: perf_trace_qdisc_create (STB_LOCAL)
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
