# Function: <code>perf_trace_qdisc_destroy</code>

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
void perf_trace_qdisc_destroy(void *__data, struct Qdisc *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a45d40)
Location: include/trace/events/qdisc.h:74
Inline: False
```
**Symbols:**

```
ffffffff81a45d40-ffffffff81a45ee8: perf_trace_qdisc_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void perf_trace_qdisc_destroy(void *__data, struct Qdisc *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/qdisc.h:74
Inline: False
```
**Symbols:**

```
ffffffff81a4a5d0-ffffffff81a4a83a: perf_trace_qdisc_destroy (STB_LOCAL)
ffffffff81c31ca3-ffffffff81c31cbb: perf_trace_qdisc_destroy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void perf_trace_qdisc_destroy(void *__data, struct Qdisc *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/qdisc.h:74
Inline: False
```
**Symbols:**

```
ffffffff81a2f530-ffffffff81a2f796: perf_trace_qdisc_destroy (STB_LOCAL)
ffffffff81c23f6c-ffffffff81c23f84: perf_trace_qdisc_destroy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void perf_trace_qdisc_destroy(void *__data, struct Qdisc *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/qdisc.h:102
Inline: False
```
**Symbols:**

```
ffffffff81ae4b10-ffffffff81ae4d76: perf_trace_qdisc_destroy (STB_LOCAL)
ffffffff81d37f80-ffffffff81d37f98: perf_trace_qdisc_destroy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void perf_trace_qdisc_destroy(void *__data, struct Qdisc *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/qdisc.h:102
Inline: False
```
**Symbols:**

```
ffffffff81c64f90-ffffffff81c6521c: perf_trace_qdisc_destroy (STB_LOCAL)
ffffffff81f0477d-ffffffff81f04795: perf_trace_qdisc_destroy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_trace_qdisc_destroy(void *__data, struct Qdisc *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e1b950)
Location: include/trace/events/qdisc.h:102
Inline: False
```
**Symbols:**

```
ffffffff81e1b950-ffffffff81e1bbf1: perf_trace_qdisc_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_trace_qdisc_destroy(void *__data, struct Qdisc *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e8fb40)
Location: include/trace/events/qdisc.h:102
Inline: False
```
**Symbols:**

```
ffffffff81e8fb40-ffffffff81e8fd82: perf_trace_qdisc_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_trace_qdisc_destroy(void *__data, struct Qdisc *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81f51c70)
Location: include/trace/events/qdisc.h:102
Inline: False
```
**Symbols:**

```
ffffffff81f51c70-ffffffff81f51f95: perf_trace_qdisc_destroy (STB_LOCAL)
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
