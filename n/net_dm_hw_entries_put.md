# Function: <code>net_dm_hw_entries_put</code>

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
In net/core/drop_monitor.c (ffffffff8197589a)
Location: net/core/drop_monitor.c:342
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int net_dm_hw_entries_put(struct sk_buff *msg, const struct net_dm_hw_entries *hw_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a4a290)
Location: net/core/drop_monitor.c:346
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
**Symbols:**

```
ffffffff81a4a290-ffffffff81a4a448: net_dm_hw_entries_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int net_dm_hw_entries_put(struct sk_buff *msg, const struct net_dm_hw_entries *hw_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:348
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_work
```
**Symbols:**

```
ffffffff81a4fed0-ffffffff81a50090: net_dm_hw_entries_put (STB_LOCAL)
ffffffff81c31e6b-ffffffff81c31e83: net_dm_hw_entries_put.cold (STB_LOCAL)
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
In net/core/drop_monitor.c (ffffffff81a35046)
Location: net/core/drop_monitor.c:348
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
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
In net/core/drop_monitor.c (ffffffff81aeac16)
Location: net/core/drop_monitor.c:352
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
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
In net/core/drop_monitor.c (ffffffff81c6d436)
Location: net/core/drop_monitor.c:359
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
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
In net/core/drop_monitor.c (ffffffff81e25046)
Location: net/core/drop_monitor.c:346
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
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
In net/core/drop_monitor.c (ffffffff81e9a586)
Location: net/core/drop_monitor.c:348
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
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
In net/core/drop_monitor.c (ffffffff81f5ccb6)
Location: net/core/drop_monitor.c:348
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_summary_report_fill
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
In net/core/drop_monitor.c (ffff800010c1bc88)
Location: net/core/drop_monitor.c:342
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
In net/core/drop_monitor.c (c0d33ae8)
Location: net/core/drop_monitor.c:342
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
In net/core/drop_monitor.c (c000000000d0c888)
Location: net/core/drop_monitor.c:342
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
In net/core/drop_monitor.c (ffffffe000795e8c)
Location: net/core/drop_monitor.c:342
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
In net/core/drop_monitor.c (ffffffff8191586a)
Location: net/core/drop_monitor.c:342
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
In net/core/drop_monitor.c (ffffffff818cf61a)
Location: net/core/drop_monitor.c:342
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
In net/core/drop_monitor.c (ffffffff8196689a)
Location: net/core/drop_monitor.c:342
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
In net/core/drop_monitor.c (ffffffff81988b2a)
Location: net/core/drop_monitor.c:342
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
