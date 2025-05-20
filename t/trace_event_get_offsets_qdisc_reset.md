# Function: <code>trace_event_get_offsets_qdisc_reset</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a48974)
Location: include/trace/events/qdisc.h:49
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a4dc7a)
Location: include/trace/events/qdisc.h:49
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
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
In net/core/net-traces.c (ffffffff81a32c8a)
Location: include/trace/events/qdisc.h:49
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
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
In net/core/net-traces.c (ffffffff81ae88ba)
Location: include/trace/events/qdisc.h:77
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
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
In net/core/net-traces.c (ffffffff81c64d39)
Location: include/trace/events/qdisc.h:77
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
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
In net/core/net-traces.c (ffffffff81e1b6c9)
Location: include/trace/events/qdisc.h:77
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trace_event_get_offsets_qdisc_reset(struct trace_event_data_offsets_qdisc_reset *__data_offsets, struct Qdisc *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e8f740)
Location: include/trace/events/qdisc.h:77
Inline: False
Direct callers:
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
```
**Symbols:**

```
ffffffff81e8f740-ffffffff81e8f7fa: trace_event_get_offsets_qdisc_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trace_event_get_offsets_qdisc_reset(struct trace_event_data_offsets_qdisc_reset *__data_offsets, struct Qdisc *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81f51750)
Location: include/trace/events/qdisc.h:77
Inline: False
Direct callers:
  - net/core/net-traces.c:perf_trace_qdisc_reset
  - net/core/net-traces.c:trace_event_raw_event_qdisc_reset
```
**Symbols:**

```
ffffffff81f51750-ffffffff81f51824: trace_event_get_offsets_qdisc_reset (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
