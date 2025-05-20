# Function: <code>set_all_monitor_traces</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81975327)
Location: net/core/drop_monitor.c:1120
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
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
In net/core/drop_monitor.c (ffffffff81a4a05a)
Location: net/core/drop_monitor.c:1150
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
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
In net/core/drop_monitor.c (ffffffff81a4fdba)
Location: net/core/drop_monitor.c:1200
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
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
In net/core/drop_monitor.c (ffffffff81a34d38)
Location: net/core/drop_monitor.c:1200
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81a33cc0-ffffffff81a33cf0: set_all_monitor_traces.part.0 (STB_LOCAL)
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
In net/core/drop_monitor.c (ffffffff81aea949)
Location: net/core/drop_monitor.c:1202
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81ae96b0-ffffffff81ae96e0: set_all_monitor_traces.part.0 (STB_LOCAL)
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
In net/core/drop_monitor.c (ffffffff81c6d14e)
Location: net/core/drop_monitor.c:1217
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81c6bee0-ffffffff81c6bf16: set_all_monitor_traces.part.0 (STB_LOCAL)
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
In net/core/drop_monitor.c (ffffffff81e24d3e)
Location: net/core/drop_monitor.c:1205
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81e23980-ffffffff81e239b6: set_all_monitor_traces.part.0 (STB_LOCAL)
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
In net/core/drop_monitor.c (ffffffff81e9a27e)
Location: net/core/drop_monitor.c:1220
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81e98ec0-ffffffff81e98ef6: set_all_monitor_traces.part.0 (STB_LOCAL)
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
In net/core/drop_monitor.c (ffffffff81f5c9ae)
Location: net/core/drop_monitor.c:1220
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81f5b580-ffffffff81f5b5b6: set_all_monitor_traces.part.0 (STB_LOCAL)
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
In net/core/drop_monitor.c (ffff800010c1b114)
Location: net/core/drop_monitor.c:1120
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
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
In net/core/drop_monitor.c (c0d334a4)
Location: net/core/drop_monitor.c:1120
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
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
In net/core/drop_monitor.c (c000000000d0bc08)
Location: net/core/drop_monitor.c:1120
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
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
In net/core/drop_monitor.c (ffffffe00079584a)
Location: net/core/drop_monitor.c:1120
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
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
In net/core/drop_monitor.c (ffffffff819152f7)
Location: net/core/drop_monitor.c:1120
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
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
In net/core/drop_monitor.c (ffffffff818cf0a7)
Location: net/core/drop_monitor.c:1120
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
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
In net/core/drop_monitor.c (ffffffff81966327)
Location: net/core/drop_monitor.c:1120
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
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
In net/core/drop_monitor.c (ffffffff819885b7)
Location: net/core/drop_monitor.c:1120
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
</details>
</li>
</ul>

## Differences
