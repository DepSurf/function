# Function: <code>trace_event_get_offsets_devlink_hwmsg</code>

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
In net/core/devlink.c (ffffffff8194980b)
Location: include/trace/events/devlink.h:17
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
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
In net/core/devlink.c (ffffffff8197eccb)
Location: include/trace/events/devlink.h:17
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
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
In net/core/devlink.c (ffffffff81a526e0)
Location: include/trace/events/devlink.h:17
Inline: True
Direct callers:
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
```
**Symbols:**

```
ffffffff81a526e0-ffffffff81a527cc: trace_event_get_offsets_devlink_hwmsg.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a58c20)
Location: include/trace/events/devlink.h:17
Inline: True
Direct callers:
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
```
**Symbols:**

```
ffffffff81a58c20-ffffffff81a58d0c: trace_event_get_offsets_devlink_hwmsg.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a3b910)
Location: include/trace/events/devlink.h:17
Inline: True
Direct callers:
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
```
**Symbols:**

```
ffffffff81a3b910-ffffffff81a3b9fc: trace_event_get_offsets_devlink_hwmsg.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81af1c70)
Location: include/trace/events/devlink.h:17
Inline: True
Direct callers:
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
```
**Symbols:**

```
ffffffff81af1c70-ffffffff81af1d5c: trace_event_get_offsets_devlink_hwmsg.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81c75b30)
Location: include/trace/events/devlink.h:17
Inline: True
Direct callers:
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
```
**Symbols:**

```
ffffffff81c75b30-ffffffff81c75c27: trace_event_get_offsets_devlink_hwmsg.constprop.0 (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81e2e260)
Location: include/trace/events/devlink.h:17
Inline: True
Direct callers:
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
```
**Symbols:**

```
ffffffff81e2e260-ffffffff81e2e357: trace_event_get_offsets_devlink_hwmsg.constprop.0 (STB_LOCAL)
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
In net/devlink/leftover.c (ffffffff820329d0)
Location: include/trace/events/devlink.h:17
Inline: True
Direct callers:
  - net/devlink/leftover.c:perf_trace_devlink_hwmsg
  - net/devlink/leftover.c:trace_event_raw_event_devlink_hwmsg
```
**Symbols:**

```
ffffffff820329d0-ffffffff82032aff: trace_event_get_offsets_devlink_hwmsg.isra.0 (STB_LOCAL)
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
In net/devlink/core.c (ffffffff821001f0)
Location: include/trace/events/devlink.h:17
Inline: True
Direct callers:
  - net/devlink/core.c:perf_trace_devlink_hwmsg
  - net/devlink/core.c:trace_event_raw_event_devlink_hwmsg
```
**Symbols:**

```
ffffffff821001f0-ffffffff821002f5: trace_event_get_offsets_devlink_hwmsg.isra.0 (STB_LOCAL)
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
In net/core/devlink.c (ffff800010c27184)
Location: include/trace/events/devlink.h:17
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
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
In net/core/devlink.c (c0d3db2c)
Location: include/trace/events/devlink.h:17
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
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
In net/core/devlink.c (c000000000d1b844)
Location: include/trace/events/devlink.h:17
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
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
In net/core/devlink.c (ffffffe00079ddb8)
Location: include/trace/events/devlink.h:17
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
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
In net/core/devlink.c (ffffffff8191eb3b)
Location: include/trace/events/devlink.h:17
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
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
In net/core/devlink.c (ffffffff818d88eb)
Location: include/trace/events/devlink.h:17
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
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
In net/core/devlink.c (ffffffff8196fccb)
Location: include/trace/events/devlink.h:17
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
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
In net/core/devlink.c (ffffffff819921bb)
Location: include/trace/events/devlink.h:17
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
```
</details>
</li>
</ul>

## Differences
