# Function: <code>net_dm_hw_metadata_clone</code>

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
In net/core/drop_monitor.c (ffffffff8197472f)
Location: net/core/drop_monitor.c:795
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct net_dm_hw_metadata *net_dm_hw_metadata_clone(const struct net_dm_hw_metadata *hw_metadata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a49820)
Location: net/core/drop_monitor.c:814
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
```
**Symbols:**

```
ffffffff81a49820-ffffffff81a498e9: net_dm_hw_metadata_clone (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In net/core/drop_monitor.c (ffff800010c1b894)
Location: net/core/drop_monitor.c:795
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
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
In net/core/drop_monitor.c (c0d326ec)
Location: net/core/drop_monitor.c:795
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
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
In net/core/drop_monitor.c (c000000000d0ab10)
Location: net/core/drop_monitor.c:795
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
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
In net/core/drop_monitor.c (ffffffe000794c32)
Location: net/core/drop_monitor.c:795
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
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
In net/core/drop_monitor.c (ffffffff819146ff)
Location: net/core/drop_monitor.c:795
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
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
In net/core/drop_monitor.c (ffffffff818ce4bf)
Location: net/core/drop_monitor.c:795
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
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
In net/core/drop_monitor.c (ffffffff8196572f)
Location: net/core/drop_monitor.c:795
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
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
In net/core/drop_monitor.c (ffffffff8198796f)
Location: net/core/drop_monitor.c:795
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
