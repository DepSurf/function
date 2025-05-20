# Function: <code>shrink_active_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a3e80)
Location: mm/vmscan.c:1761
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff811a3e80-ffffffff811a426d: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811ba9b0)
Location: mm/vmscan.c:1884
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff811ba9b0-ffffffff811bad43: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811cb040)
Location: mm/vmscan.c:1918
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff811cb040-ffffffff811cb3d3: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811d3bd0)
Location: mm/vmscan.c:1951
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff811d3bd0-ffffffff811d3fd5: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e9120)
Location: mm/vmscan.c:1975
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff811e9120-ffffffff811e9522: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8120a640)
Location: mm/vmscan.c:1905
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff8120a640-ffffffff8120aaeb: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8121d330)
Location: mm/vmscan.c:2072
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff8121d330-ffffffff8121d7eb: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122cdc0)
Location: mm/vmscan.c:2045
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff8122cdc0-ffffffff8122d26a: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123afe0)
Location: mm/vmscan.c:2043
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff8123afe0-ffffffff8123b48a: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81268110)
Location: mm/vmscan.c:2012
Inline: False
Direct callers:
  - mm/vmscan.c:age_active_anon
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_lruvec
```
**Symbols:**

```
ffffffff81268110-ffffffff812685d2: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81272b90)
Location: mm/vmscan.c:2020
Inline: False
Direct callers:
  - mm/vmscan.c:age_active_anon
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_lruvec
```
**Symbols:**

```
ffffffff81272b90-ffffffff81273058: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81277e80)
Location: mm/vmscan.c:2210
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_lruvec
```
**Symbols:**

```
ffffffff81277e80-ffffffff81278345: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b5b10)
Location: mm/vmscan.c:2343
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_lruvec
```
**Symbols:**

```
ffffffff812b5b10-ffffffff812b5fde: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8130ed90)
Location: mm/vmscan.c:2448
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_lruvec
```
**Symbols:**

```
ffffffff8130ed90-ffffffff8130f347: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8137dcd0)
Location: mm/vmscan.c:2604
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_lruvec
```
**Symbols:**

```
ffffffff8137dcd0-ffffffff8137e104: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813af710)
Location: mm/vmscan.c:2688
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_lruvec
```
**Symbols:**

```
ffffffff813af710-ffffffff813afb41: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813d8e30)
Location: mm/vmscan.c:1988
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_lruvec
```
**Symbols:**

```
ffffffff813d8e30-ffffffff813d9267: shrink_active_list (STB_LOCAL)
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
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102cc038)
Location: mm/vmscan.c:2043
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffff8000102cc038-ffff8000102cc584: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f5e0c)
Location: mm/vmscan.c:2043
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
c04f5e0c-c04f6300: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000389440)
Location: mm/vmscan.c:2043
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
c000000000389440-c000000000389b8c: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001eab9a)
Location: mm/vmscan.c:2043
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffe0001eab9a-ffffffe0001eb044: shrink_active_list (STB_LOCAL)
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
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81233630)
Location: mm/vmscan.c:2043
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff81233630-ffffffff81233ada: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812266b0)
Location: mm/vmscan.c:2043
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff812266b0-ffffffff81226b4e: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812313d0)
Location: mm/vmscan.c:2043
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff812313d0-ffffffff8123187a: shrink_active_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void shrink_active_list(long unsigned int nr_to_scan, struct lruvec *lruvec, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81240810)
Location: mm/vmscan.c:2043
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
**Symbols:**

```
ffffffff81240810-ffffffff81240cbd: shrink_active_list (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
