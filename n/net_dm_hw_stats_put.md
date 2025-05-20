# Function: <code>net_dm_hw_stats_put</code>

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
In net/core/drop_monitor.c (ffffffff819764b2)
Location: net/core/drop_monitor.c:1402
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
int net_dm_hw_stats_put(struct sk_buff *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a4a120)
Location: net/core/drop_monitor.c:1432
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
**Symbols:**

```
ffffffff81a4a120-ffffffff81a4a239: net_dm_hw_stats_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int net_dm_hw_stats_put(struct sk_buff *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a50d90)
Location: net/core/drop_monitor.c:1482
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
**Symbols:**

```
ffffffff81a50d90-ffffffff81a50ea9: net_dm_hw_stats_put (STB_LOCAL)
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
In net/core/drop_monitor.c (ffffffff81a35dcf)
Location: net/core/drop_monitor.c:1482
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
In net/core/drop_monitor.c (ffffffff81aeb9b1)
Location: net/core/drop_monitor.c:1484
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
In net/core/drop_monitor.c (ffffffff81c6e2e4)
Location: net/core/drop_monitor.c:1499
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
In net/core/drop_monitor.c (ffffffff81e25f6a)
Location: net/core/drop_monitor.c:1487
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
In net/core/drop_monitor.c (ffffffff81e9b50a)
Location: net/core/drop_monitor.c:1502
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
In net/core/drop_monitor.c (ffffffff81f5dc7a)
Location: net/core/drop_monitor.c:1502
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
In net/core/drop_monitor.c (ffff800010c1c980)
Location: net/core/drop_monitor.c:1402
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
In net/core/drop_monitor.c (c0d34890)
Location: net/core/drop_monitor.c:1402
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
In net/core/drop_monitor.c (c000000000d0d968)
Location: net/core/drop_monitor.c:1402
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
In net/core/drop_monitor.c (ffffffe00079686c)
Location: net/core/drop_monitor.c:1402
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
In net/core/drop_monitor.c (ffffffff81916482)
Location: net/core/drop_monitor.c:1402
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
In net/core/drop_monitor.c (ffffffff818d0232)
Location: net/core/drop_monitor.c:1402
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
In net/core/drop_monitor.c (ffffffff819674b2)
Location: net/core/drop_monitor.c:1402
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
In net/core/drop_monitor.c (ffffffff81989742)
Location: net/core/drop_monitor.c:1402
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
