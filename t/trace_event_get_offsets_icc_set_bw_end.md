# Function: <code>trace_event_get_offsets_icc_set_bw_end</code>

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
In drivers/interconnect/core.c (ffffffff819dd3ec)
Location: drivers/interconnect/trace.h:54
Inline: True
Inline callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:trace_event_raw_event_icc_set_bw_end
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
In drivers/interconnect/core.c (ffffffff819dcc5c)
Location: drivers/interconnect/trace.h:54
Inline: True
Inline callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:trace_event_raw_event_icc_set_bw_end
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
In drivers/interconnect/core.c (ffffffff819c2eac)
Location: drivers/interconnect/trace.h:54
Inline: True
Inline callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:trace_event_raw_event_icc_set_bw_end
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
In drivers/interconnect/core.c (ffffffff81a7274c)
Location: drivers/interconnect/trace.h:54
Inline: True
Inline callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:trace_event_raw_event_icc_set_bw_end
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81be2910)
Location: drivers/interconnect/trace.h:54
Inline: True
Direct callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:trace_event_raw_event_icc_set_bw_end
```
**Symbols:**

```
ffffffff81be2910-ffffffff81be299f: trace_event_get_offsets_icc_set_bw_end.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81d8e520)
Location: drivers/interconnect/trace.h:54
Inline: True
Direct callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:trace_event_raw_event_icc_set_bw_end
```
**Symbols:**

```
ffffffff81d8e520-ffffffff81d8e5af: trace_event_get_offsets_icc_set_bw_end.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81dfce30)
Location: drivers/interconnect/trace.h:54
Inline: True
Direct callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:trace_event_raw_event_icc_set_bw_end
```
**Symbols:**

```
ffffffff81dfce30-ffffffff81dfcebf: trace_event_get_offsets_icc_set_bw_end.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81eb3bc0)
Location: drivers/interconnect/trace.h:54
Inline: True
Direct callers:
  - drivers/interconnect/core.c:perf_trace_icc_set_bw_end
  - drivers/interconnect/core.c:trace_event_raw_event_icc_set_bw_end
```
**Symbols:**

```
ffffffff81eb3bc0-ffffffff81eb3c4f: trace_event_get_offsets_icc_set_bw_end.isra.0 (STB_LOCAL)
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
