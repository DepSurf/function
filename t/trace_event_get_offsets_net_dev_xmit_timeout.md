# Function: <code>trace_event_get_offsets_net_dev_xmit_timeout</code>

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
In net/core/net-traces.c (ffffffff8193eeb9)
Location: include/trace/events/net.h:98
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:trace_event_raw_event_net_dev_xmit_timeout
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
In net/core/net-traces.c (ffffffff81971d49)
Location: include/trace/events/net.h:98
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:trace_event_raw_event_net_dev_xmit_timeout
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a45f19)
Location: include/trace/events/net.h:98
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:trace_event_raw_event_net_dev_xmit_timeout
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
In net/core/net-traces.c (ffffffff81a4ac00)
Location: include/trace/events/net.h:98
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:trace_event_raw_event_net_dev_xmit_timeout
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
In net/core/net-traces.c (ffffffff81a2fb50)
Location: include/trace/events/net.h:98
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:trace_event_raw_event_net_dev_xmit_timeout
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
In net/core/net-traces.c (ffffffff81ae5130)
Location: include/trace/events/net.h:98
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:trace_event_raw_event_net_dev_xmit_timeout
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
In net/core/net-traces.c (0)
Location: include/trace/events/net.h:98
Inline: True
Direct callers:
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:trace_event_raw_event_net_dev_xmit_timeout
```
**Symbols:**

```
ffffffff81c66910-ffffffff81c669ae: trace_event_get_offsets_net_dev_xmit_timeout.constprop.0 (STB_LOCAL)
ffffffff81f048a9-ffffffff81f048c1: trace_event_get_offsets_net_dev_xmit_timeout.constprop.0.cold (STB_LOCAL)
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
In net/core/net-traces.c (ffffffff81e1d9a0)
Location: include/trace/events/net.h:98
Inline: True
Direct callers:
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:trace_event_raw_event_net_dev_xmit_timeout
```
**Symbols:**

```
ffffffff81e1d9a0-ffffffff81e1da4e: trace_event_get_offsets_net_dev_xmit_timeout.constprop.0 (STB_LOCAL)
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
In net/core/net-traces.c (ffffffff81e94c80)
Location: include/trace/events/net.h:99
Inline: True
Direct callers:
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:trace_event_raw_event_net_dev_xmit_timeout
```
**Symbols:**

```
ffffffff81e94c80-ffffffff81e94d3c: trace_event_get_offsets_net_dev_xmit_timeout.isra.0 (STB_LOCAL)
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
In net/core/net-traces.c (ffffffff81f571b0)
Location: include/trace/events/net.h:99
Inline: True
Direct callers:
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:trace_event_raw_event_net_dev_xmit_timeout
```
**Symbols:**

```
ffffffff81f571b0-ffffffff81f57278: trace_event_get_offsets_net_dev_xmit_timeout.isra.0 (STB_LOCAL)
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
In net/core/net-traces.c (ffff800010c196c0)
Location: include/trace/events/net.h:98
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:trace_event_raw_event_net_dev_xmit_timeout
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
In net/core/net-traces.c (c0d2fc9c)
Location: include/trace/events/net.h:98
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:trace_event_raw_event_net_dev_xmit_timeout
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
In net/core/net-traces.c (c000000000d074d8)
Location: include/trace/events/net.h:98
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:trace_event_raw_event_net_dev_xmit_timeout
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
In net/core/net-traces.c (ffffffe000792a1a)
Location: include/trace/events/net.h:98
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:trace_event_raw_event_net_dev_xmit_timeout
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
In net/core/net-traces.c (ffffffff81911d19)
Location: include/trace/events/net.h:98
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:trace_event_raw_event_net_dev_xmit_timeout
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
In net/core/net-traces.c (ffffffff818cbad9)
Location: include/trace/events/net.h:98
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:trace_event_raw_event_net_dev_xmit_timeout
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
In net/core/net-traces.c (ffffffff81962d49)
Location: include/trace/events/net.h:98
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:trace_event_raw_event_net_dev_xmit_timeout
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
In net/core/net-traces.c (ffffffff81984fb9)
Location: include/trace/events/net.h:98
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:trace_event_raw_event_net_dev_xmit_timeout
```
</details>
</li>
</ul>

## Differences
