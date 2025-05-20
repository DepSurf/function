# Function: <code>trace_event_raw_event_qdisc_destroy</code>

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
void trace_event_raw_event_qdisc_destroy(void *__data, struct Qdisc *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a48790)
Location: include/trace/events/qdisc.h:74
Inline: False
```
**Symbols:**

```
ffffffff81a48790-ffffffff81a48912: trace_event_raw_event_qdisc_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_qdisc_destroy(void *__data, struct Qdisc *q);
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
ffffffff81a4de70-ffffffff81a4e0a8: trace_event_raw_event_qdisc_destroy (STB_LOCAL)
ffffffff81c31e0b-ffffffff81c31e23: trace_event_raw_event_qdisc_destroy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_qdisc_destroy(void *__data, struct Qdisc *q);
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
ffffffff81a32e80-ffffffff81a330b7: trace_event_raw_event_qdisc_destroy (STB_LOCAL)
ffffffff81c240d4-ffffffff81c240ec: trace_event_raw_event_qdisc_destroy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_qdisc_destroy(void *__data, struct Qdisc *q);
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
ffffffff81ae8630-ffffffff81ae8867: trace_event_raw_event_qdisc_destroy (STB_LOCAL)
ffffffff81d380f2-ffffffff81d3810a: trace_event_raw_event_qdisc_destroy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_qdisc_destroy(void *__data, struct Qdisc *q);
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
ffffffff81c6b630-ffffffff81c6b84c: trace_event_raw_event_qdisc_destroy (STB_LOCAL)
ffffffff81f04b23-ffffffff81f04b3b: trace_event_raw_event_qdisc_destroy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_event_raw_event_qdisc_destroy(void *__data, struct Qdisc *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e233d0)
Location: include/trace/events/qdisc.h:102
Inline: False
```
**Symbols:**

```
ffffffff81e233d0-ffffffff81e23604: trace_event_raw_event_qdisc_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_event_raw_event_qdisc_destroy(void *__data, struct Qdisc *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e8ffb0)
Location: include/trace/events/qdisc.h:102
Inline: False
```
**Symbols:**

```
ffffffff81e8ffb0-ffffffff81e901ac: trace_event_raw_event_qdisc_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_event_raw_event_qdisc_destroy(void *__data, struct Qdisc *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81f522a0)
Location: include/trace/events/qdisc.h:102
Inline: False
```
**Symbols:**

```
ffffffff81f522a0-ffffffff81f5257e: trace_event_raw_event_qdisc_destroy (STB_LOCAL)
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
