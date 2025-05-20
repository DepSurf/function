# Function: <code>trace_event_get_offsets_devlink_health_report</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194b6f4)
Location: include/trace/events/devlink.h:81
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81981cf4)
Location: include/trace/events/devlink.h:81
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a51f60)
Location: include/trace/events/devlink.h:81
Inline: True
Direct callers:
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
```
**Symbols:**

```
ffffffff81a51f60-ffffffff81a520a8: trace_event_get_offsets_devlink_health_report.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a58630)
Location: include/trace/events/devlink.h:81
Inline: True
Direct callers:
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
```
**Symbols:**

```
ffffffff81a58630-ffffffff81a58778: trace_event_get_offsets_devlink_health_report.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a3b320)
Location: include/trace/events/devlink.h:81
Inline: True
Direct callers:
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
```
**Symbols:**

```
ffffffff81a3b320-ffffffff81a3b468: trace_event_get_offsets_devlink_health_report.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81af1680)
Location: include/trace/events/devlink.h:81
Inline: True
Direct callers:
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
```
**Symbols:**

```
ffffffff81af1680-ffffffff81af17c8: trace_event_get_offsets_devlink_health_report.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81c75180)
Location: include/trace/events/devlink.h:81
Inline: True
Direct callers:
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
```
**Symbols:**

```
ffffffff81c75180-ffffffff81c752cb: trace_event_get_offsets_devlink_health_report.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int trace_event_get_offsets_devlink_health_report(struct trace_event_data_offsets_devlink_health_report *__data_offsets, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2ac50)
Location: include/trace/events/devlink.h:81
Inline: False
Direct callers:
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
```
**Symbols:**

```
ffffffff81e2ac50-ffffffff81e2adbb: trace_event_get_offsets_devlink_health_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trace_event_get_offsets_devlink_health_report(struct trace_event_data_offsets_devlink_health_report *__data_offsets, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8202eb40)
Location: include/trace/events/devlink.h:81
Inline: False
Direct callers:
  - net/devlink/leftover.c:perf_trace_devlink_health_report
  - net/devlink/leftover.c:trace_event_raw_event_devlink_health_report
```
**Symbols:**

```
ffffffff8202eb40-ffffffff8202ece4: trace_event_get_offsets_devlink_health_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trace_event_get_offsets_devlink_health_report(struct trace_event_data_offsets_devlink_health_report *__data_offsets, const struct devlink *devlink, const char *reporter_name, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/core.c (ffffffff820fdeb0)
Location: include/trace/events/devlink.h:81
Inline: False
Direct callers:
  - net/devlink/core.c:perf_trace_devlink_health_report
  - net/devlink/core.c:trace_event_raw_event_devlink_health_report
```
**Symbols:**

```
ffffffff820fdeb0-ffffffff820fe01e: trace_event_get_offsets_devlink_health_report (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c295d0)
Location: include/trace/events/devlink.h:81
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d412c0)
Location: include/trace/events/devlink.h:81
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d1df30)
Location: include/trace/events/devlink.h:81
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079ef78)
Location: include/trace/events/devlink.h:81
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81921b64)
Location: include/trace/events/devlink.h:81
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818db914)
Location: include/trace/events/devlink.h:81
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81972cf4)
Location: include/trace/events/devlink.h:81
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819951e4)
Location: include/trace/events/devlink.h:81
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
