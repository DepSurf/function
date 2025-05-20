# Function: <code>__net_dm_cpu_data_fini</code>

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
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81974e60)
Location: net/core/drop_monitor.c:1588
Inline: True
```
**Symbols:**

```
ffffffff81974e60-ffffffff81974e6d: __net_dm_cpu_data_fini.part.0 (STB_LOCAL)
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
In net/core/drop_monitor.c (ffffffff81a49baf)
Location: net/core/drop_monitor.c:1618
Inline: True
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
In net/core/drop_monitor.c (ffffffff81a4f37f)
Location: net/core/drop_monitor.c:1668
Inline: True
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
In net/core/drop_monitor.c (ffffffff81a343d3)
Location: net/core/drop_monitor.c:1668
Inline: True
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
In net/core/drop_monitor.c (ffffffff81ae9740)
Location: net/core/drop_monitor.c:1673
Inline: True
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
In net/core/drop_monitor.c (ffffffff81c6bf7f)
Location: net/core/drop_monitor.c:1675
Inline: True
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
In net/core/drop_monitor.c (ffffffff81e242bc)
Location: net/core/drop_monitor.c:1664
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81e997fc)
Location: net/core/drop_monitor.c:1679
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81f5bf2c)
Location: net/core/drop_monitor.c:1681
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (ffff800010c1a958)
Location: net/core/drop_monitor.c:1588
Inline: True
```
**Symbols:**

```
ffff800010c1a958-ffff800010c1a974: __net_dm_cpu_data_fini.part.0 (STB_LOCAL)
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
In net/core/drop_monitor.c (c0d33254)
Location: net/core/drop_monitor.c:1588
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __net_dm_cpu_data_fini(struct per_cpu_dm_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (c000000000d0a9e0)
Location: net/core/drop_monitor.c:1588
Inline: False
Direct callers:
  - net/core/drop_monitor.c:exit_net_drop_monitor
  - net/core/drop_monitor.c:exit_net_drop_monitor
```
**Symbols:**

```
c000000000d0a9e0-c000000000d0aa04: __net_dm_cpu_data_fini (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (ffffffe00079540e)
Location: net/core/drop_monitor.c:1588
Inline: True
```
**Symbols:**

```
ffffffe00079540e-ffffffe00079542a: __net_dm_cpu_data_fini.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81914e30)
Location: net/core/drop_monitor.c:1588
Inline: True
```
**Symbols:**

```
ffffffff81914e30-ffffffff81914e3d: __net_dm_cpu_data_fini.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (ffffffff818cebf0)
Location: net/core/drop_monitor.c:1588
Inline: True
```
**Symbols:**

```
ffffffff818cebf0-ffffffff818cebfd: __net_dm_cpu_data_fini.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81965e60)
Location: net/core/drop_monitor.c:1588
Inline: True
```
**Symbols:**

```
ffffffff81965e60-ffffffff81965e6d: __net_dm_cpu_data_fini.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (ffffffff819880f0)
Location: net/core/drop_monitor.c:1588
Inline: True
```
**Symbols:**

```
ffffffff819880f0-ffffffff819880fd: __net_dm_cpu_data_fini.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
