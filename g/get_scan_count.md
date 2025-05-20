# Function: <code>get_scan_count</code>

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
In mm/vmscan.c (ffffffff811a42b3)
Location: mm/vmscan.c:1961
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_lruvec
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811badb9)
Location: mm/vmscan.c:2088
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811cb449)
Location: mm/vmscan.c:2100
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811d4059)
Location: mm/vmscan.c:2160
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e95a9)
Location: mm/vmscan.c:2184
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8120ab5d)
Location: mm/vmscan.c:2114
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8121d85d)
Location: mm/vmscan.c:2282
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void get_scan_count(struct lruvec *lruvec, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *nr, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122a600)
Location: mm/vmscan.c:2250
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff8122a600-ffffffff8122a9f7: get_scan_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void get_scan_count(struct lruvec *lruvec, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *nr, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81238440)
Location: mm/vmscan.c:2304
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff81238440-ffffffff812388cd: get_scan_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void get_scan_count(struct lruvec *lruvec, struct scan_control *sc, long unsigned int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81264150)
Location: mm/vmscan.c:2239
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_lruvec
```
**Symbols:**

```
ffffffff81264150-ffffffff8126448d: get_scan_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void get_scan_count(struct lruvec *lruvec, struct scan_control *sc, long unsigned int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8126eb30)
Location: mm/vmscan.c:2246
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_lruvec
```
**Symbols:**

```
ffffffff8126eb30-ffffffff8126eeea: get_scan_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void get_scan_count(struct lruvec *lruvec, struct scan_control *sc, long unsigned int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81273c60)
Location: mm/vmscan.c:2436
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_lruvec
```
**Symbols:**

```
ffffffff81273c60-ffffffff81274009: get_scan_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void get_scan_count(struct lruvec *lruvec, struct scan_control *sc, long unsigned int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:2574
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_lruvec
```
**Symbols:**

```
ffffffff812b1780-ffffffff812b1d16: get_scan_count (STB_LOCAL)
ffffffff81cba670-ffffffff81cba6b5: get_scan_count.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void get_scan_count(struct lruvec *lruvec, struct scan_control *sc, long unsigned int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:2680
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_lruvec
```
**Symbols:**

```
ffffffff8130c680-ffffffff8130cc48: get_scan_count (STB_LOCAL)
ffffffff81e6bfa7-ffffffff81e6bfe4: get_scan_count.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void get_scan_count(struct lruvec *lruvec, struct scan_control *sc, long unsigned int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:2941
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_lruvec
```
**Symbols:**

```
ffffffff81381a70-ffffffff8138201c: get_scan_count (STB_LOCAL)
ffffffff82062b01-ffffffff82062b3e: get_scan_count.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void get_scan_count(struct lruvec *lruvec, struct scan_control *sc, long unsigned int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:3025
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_lruvec
```
**Symbols:**

```
ffffffff813b3340-ffffffff813b3921: get_scan_count (STB_LOCAL)
ffffffff820e227a-ffffffff820e22aa: get_scan_count.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void get_scan_count(struct lruvec *lruvec, struct scan_control *sc, long unsigned int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:2325
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_lruvec
```
**Symbols:**

```
ffffffff813dc930-ffffffff813dcf12: get_scan_count (STB_LOCAL)
ffffffff821bec49-ffffffff821bec79: get_scan_count.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void get_scan_count(struct lruvec *lruvec, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *nr, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102c91e0)
Location: mm/vmscan.c:2304
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffff8000102c91e0-ffff8000102c965c: get_scan_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void get_scan_count(struct lruvec *lruvec, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *nr, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f3134)
Location: mm/vmscan.c:2304
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
c04f3134-c04f3644: get_scan_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void get_scan_count(struct lruvec *lruvec, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *nr, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c0000000003855e0)
Location: mm/vmscan.c:2304
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
c0000000003855e0-c000000000385b7c: get_scan_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void get_scan_count(struct lruvec *lruvec, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *nr, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e86ac)
Location: mm/vmscan.c:2304
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffe0001e86ac-ffffffe0001e8a8e: get_scan_count (STB_LOCAL)
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
void get_scan_count(struct lruvec *lruvec, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *nr, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81230a90)
Location: mm/vmscan.c:2304
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff81230a90-ffffffff81230f1d: get_scan_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void get_scan_count(struct lruvec *lruvec, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *nr, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81223b50)
Location: mm/vmscan.c:2304
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff81223b50-ffffffff81223fd7: get_scan_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void get_scan_count(struct lruvec *lruvec, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *nr, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122e830)
Location: mm/vmscan.c:2304
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff8122e830-ffffffff8122ecbd: get_scan_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void get_scan_count(struct lruvec *lruvec, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *nr, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123dc40)
Location: mm/vmscan.c:2304
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff8123dc40-ffffffff8123e0c1: get_scan_count (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct mem_cgroup *memcg</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *lru_pages</code>
</li>
<li>
<b>Param reordered. </b>
<code>lruvec, memcg, sc, nr, lru_pages</code> ➡️ <code>lruvec, sc, nr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
