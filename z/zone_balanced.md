# Function: <code>zone_balanced</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool zone_balanced(struct zone *zone, int order, long unsigned int balance_gap, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a0bb0)
Location: mm/vmscan.c:2959
Inline: True
Direct callers:
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff811a0bb0-ffffffff811a0bfe: zone_balanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool zone_balanced(struct zone *zone, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b6fd0)
Location: mm/vmscan.c:3079
Inline: True
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:prepare_kswapd_sleep
```
**Symbols:**

```
ffffffff811b6fd0-ffffffff811b7010: zone_balanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool zone_balanced(struct zone *zone, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811c75d0)
Location: mm/vmscan.c:3090
Inline: True
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:prepare_kswapd_sleep
```
**Symbols:**

```
ffffffff811c75d0-ffffffff811c7610: zone_balanced (STB_LOCAL)
```
</details>
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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int balance_gap</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone, order, balance_gap, classzone_idx</code> ➡️ <code>zone, order, classzone_idx</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
