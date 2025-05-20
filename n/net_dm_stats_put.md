# Function: <code>net_dm_stats_put</code>

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
In net/core/drop_monitor.c (ffffffff819763f3)
Location: net/core/drop_monitor.c:1358
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int net_dm_stats_put(struct sk_buff *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a4b160)
Location: net/core/drop_monitor.c:1388
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
**Symbols:**

```
ffffffff81a4b160-ffffffff81a4b279: net_dm_stats_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int net_dm_stats_put(struct sk_buff *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a4f860)
Location: net/core/drop_monitor.c:1438
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
**Symbols:**

```
ffffffff81a4f860-ffffffff81a4f979: net_dm_stats_put (STB_LOCAL)
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
In net/core/drop_monitor.c (ffffffff81a35d15)
Location: net/core/drop_monitor.c:1438
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
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
In net/core/drop_monitor.c (ffffffff81aeb8e5)
Location: net/core/drop_monitor.c:1440
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
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
In net/core/drop_monitor.c (ffffffff81c6e225)
Location: net/core/drop_monitor.c:1455
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
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
In net/core/drop_monitor.c (ffffffff81e25ea6)
Location: net/core/drop_monitor.c:1443
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
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
In net/core/drop_monitor.c (ffffffff81e9b446)
Location: net/core/drop_monitor.c:1458
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
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
In net/core/drop_monitor.c (ffffffff81f5dbb6)
Location: net/core/drop_monitor.c:1458
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
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
In net/core/drop_monitor.c (ffff800010c1c8d8)
Location: net/core/drop_monitor.c:1358
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
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
In net/core/drop_monitor.c (c0d34788)
Location: net/core/drop_monitor.c:1358
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
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
In net/core/drop_monitor.c (c000000000d0d850)
Location: net/core/drop_monitor.c:1358
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
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
In net/core/drop_monitor.c (ffffffe0007967c8)
Location: net/core/drop_monitor.c:1358
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
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
In net/core/drop_monitor.c (ffffffff819163c3)
Location: net/core/drop_monitor.c:1358
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
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
In net/core/drop_monitor.c (ffffffff818d0173)
Location: net/core/drop_monitor.c:1358
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
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
In net/core/drop_monitor.c (ffffffff819673f3)
Location: net/core/drop_monitor.c:1358
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
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
In net/core/drop_monitor.c (ffffffff81989683)
Location: net/core/drop_monitor.c:1358
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
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
