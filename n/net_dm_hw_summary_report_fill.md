# Function: <code>net_dm_hw_summary_report_fill</code>

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
In net/core/drop_monitor.c (ffffffff8197584c)
Location: net/core/drop_monitor.c:370
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_work
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
In net/core/drop_monitor.c (ffffffff81a4a66a)
Location: net/core/drop_monitor.c:374
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_work
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
In net/core/drop_monitor.c (ffffffff81a502aa)
Location: net/core/drop_monitor.c:376
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int net_dm_hw_summary_report_fill(struct sk_buff *msg, const struct net_dm_hw_entries *hw_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:376
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
**Symbols:**

```
ffffffff81a34fd0-ffffffff81a35228: net_dm_hw_summary_report_fill (STB_LOCAL)
ffffffff81c24134-ffffffff81c2414c: net_dm_hw_summary_report_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int net_dm_hw_summary_report_fill(struct sk_buff *msg, const struct net_dm_hw_entries *hw_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:380
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
**Symbols:**

```
ffffffff81aeaba0-ffffffff81aeadf8: net_dm_hw_summary_report_fill (STB_LOCAL)
ffffffff81d381a8-ffffffff81d381c0: net_dm_hw_summary_report_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int net_dm_hw_summary_report_fill(struct sk_buff *msg, const struct net_dm_hw_entries *hw_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:387
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
**Symbols:**

```
ffffffff81c6d3c0-ffffffff81c6d629: net_dm_hw_summary_report_fill (STB_LOCAL)
ffffffff81f04b91-ffffffff81f04ba9: net_dm_hw_summary_report_fill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int net_dm_hw_summary_report_fill(struct sk_buff *msg, const struct net_dm_hw_entries *hw_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81e24fd0)
Location: net/core/drop_monitor.c:374
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
**Symbols:**

```
ffffffff81e24fd0-ffffffff81e25251: net_dm_hw_summary_report_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int net_dm_hw_summary_report_fill(struct sk_buff *msg, const struct net_dm_hw_entries *hw_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81e9a510)
Location: net/core/drop_monitor.c:376
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
**Symbols:**

```
ffffffff81e9a510-ffffffff81e9a791: net_dm_hw_summary_report_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int net_dm_hw_summary_report_fill(struct sk_buff *msg, const struct net_dm_hw_entries *hw_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81f5cc40)
Location: net/core/drop_monitor.c:376
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
**Symbols:**

```
ffffffff81f5cc40-ffffffff81f5cec1: net_dm_hw_summary_report_fill (STB_LOCAL)
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
In net/core/drop_monitor.c (ffff800010c1bc38)
Location: net/core/drop_monitor.c:370
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_work
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
In net/core/drop_monitor.c (c0d33a9c)
Location: net/core/drop_monitor.c:370
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_work
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
In net/core/drop_monitor.c (c000000000d0c830)
Location: net/core/drop_monitor.c:370
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_work
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
In net/core/drop_monitor.c (ffffffe000795e54)
Location: net/core/drop_monitor.c:370
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_work
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
In net/core/drop_monitor.c (ffffffff8191581c)
Location: net/core/drop_monitor.c:370
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_work
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
In net/core/drop_monitor.c (ffffffff818cf5cc)
Location: net/core/drop_monitor.c:370
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_work
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
In net/core/drop_monitor.c (ffffffff8196684c)
Location: net/core/drop_monitor.c:370
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_work
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
In net/core/drop_monitor.c (ffffffff81988adc)
Location: net/core/drop_monitor.c:370
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
