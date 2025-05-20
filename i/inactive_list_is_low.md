# Function: <code>inactive_list_is_low</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a44f2)
Location: mm/vmscan.c:1925
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_lruvec
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool inactive_list_is_low(struct lruvec *lruvec, bool file, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b8740)
Location: mm/vmscan.c:2010
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff811b8740-ffffffff811b885a: inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool inactive_list_is_low(struct lruvec *lruvec, bool file, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811c8e10)
Location: mm/vmscan.c:2044
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff811c8e10-ffffffff811c8e90: inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool inactive_list_is_low(struct lruvec *lruvec, bool file, struct mem_cgroup *memcg, struct scan_control *sc, bool actual_reclaim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811d1780)
Location: mm/vmscan.c:2079
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff811d1780-ffffffff811d19a3: inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool inactive_list_is_low(struct lruvec *lruvec, bool file, struct mem_cgroup *memcg, struct scan_control *sc, bool actual_reclaim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e6c20)
Location: mm/vmscan.c:2103
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff811e6c20-ffffffff811e6e37: inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool inactive_list_is_low(struct lruvec *lruvec, bool file, struct mem_cgroup *memcg, struct scan_control *sc, bool actual_reclaim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81207fd0)
Location: mm/vmscan.c:2033
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff81207fd0-ffffffff812081e3: inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool inactive_list_is_low(struct lruvec *lruvec, bool file, struct mem_cgroup *memcg, struct scan_control *sc, bool actual_reclaim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8121ab50)
Location: mm/vmscan.c:2201
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff8121ab50-ffffffff8121ad70: inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool inactive_list_is_low(struct lruvec *lruvec, bool file, struct scan_control *sc, bool trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122a3f0)
Location: mm/vmscan.c:2176
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff8122a3f0-ffffffff8122a5f9: inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool inactive_list_is_low(struct lruvec *lruvec, bool file, struct scan_control *sc, bool trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81238230)
Location: mm/vmscan.c:2230
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff81238230-ffffffff81238439: inactive_list_is_low (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffff8000102c8fb0)
Location: mm/vmscan.c:2230
Inline: True
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffff8000102c8fb0-ffff8000102c91dc: inactive_list_is_low.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool inactive_list_is_low(struct lruvec *lruvec, bool file, struct scan_control *sc, bool trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f2eb8)
Location: mm/vmscan.c:2230
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
c04f2eb8-c04f3134: inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (c000000000385310)
Location: mm/vmscan.c:2230
Inline: True
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
c000000000385310-c0000000003855d4: inactive_list_is_low.isra.0 (STB_LOCAL)
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
In mm/vmscan.c (ffffffe0001e84c0)
Location: mm/vmscan.c:2230
Inline: True
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffe0001e84c0-ffffffe0001e86ac: inactive_list_is_low.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool inactive_list_is_low(struct lruvec *lruvec, bool file, struct scan_control *sc, bool trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81230880)
Location: mm/vmscan.c:2230
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff81230880-ffffffff81230a89: inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool inactive_list_is_low(struct lruvec *lruvec, bool file, struct scan_control *sc, bool trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81223940)
Location: mm/vmscan.c:2230
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff81223940-ffffffff81223b49: inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool inactive_list_is_low(struct lruvec *lruvec, bool file, struct scan_control *sc, bool trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122e620)
Location: mm/vmscan.c:2230
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff8122e620-ffffffff8122e829: inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool inactive_list_is_low(struct lruvec *lruvec, bool file, struct scan_control *sc, bool trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123da10)
Location: mm/vmscan.c:2230
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff8123da10-ffffffff8123dc32: inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mem_cgroup *memcg</code>
</li>
<li>
<b>Param added. </b>
<code>bool actual_reclaim</code>
</li>
<li>
<b>Param reordered. </b>
<code>lruvec, file, sc</code> ➡️ <code>lruvec, file, memcg, sc, actual_reclaim</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool trace</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mem_cgroup *memcg</code>
</li>
<li>
<b>Param removed. </b>
<code>bool actual_reclaim</code>
</li>
<li>
<b>Param reordered. </b>
<code>lruvec, file, memcg, sc, actual_reclaim</code> ➡️ <code>lruvec, file, sc, trace</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
