# Function: <code>shrink_node</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811bb4e0)
Location: mm/vmscan.c:2509
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff811bb4e0-ffffffff811bb7f8: shrink_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811cbbb0)
Location: mm/vmscan.c:2521
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff811cbbb0-ffffffff811cbec8: shrink_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811d4750)
Location: mm/vmscan.c:2561
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff811d4750-ffffffff811d4a42: shrink_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e9ca0)
Location: mm/vmscan.c:2585
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff811e9ca0-ffffffff811e9f92: shrink_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8120b260)
Location: mm/vmscan.c:2521
Inline: False
Direct callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff8120b260-ffffffff8120b703: shrink_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8121df70)
Location: mm/vmscan.c:2691
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff8121df70-ffffffff8121e3db: shrink_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122d5e0)
Location: mm/vmscan.c:2659
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff8122d5e0-ffffffff8122da69: shrink_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123b800)
Location: mm/vmscan.c:2756
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff8123b800-ffffffff8123bbfc: shrink_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81268a70)
Location: mm/vmscan.c:2677
Inline: False
Direct callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_zones
```
**Symbols:**

```
ffffffff81268a70-ffffffff81268f9c: shrink_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81273530)
Location: mm/vmscan.c:2676
Inline: False
Direct callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_zones
```
**Symbols:**

```
ffffffff81273530-ffffffff81273a6e: shrink_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81278850)
Location: mm/vmscan.c:2874
Inline: False
Direct callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81278850-ffffffff81278d83: shrink_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:3029
Inline: False
Direct callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff812b65b0-ffffffff812b6b60: shrink_node (STB_LOCAL)
ffffffff81cba7fa-ffffffff81cba863: shrink_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:3135
Inline: False
Direct callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff81311a50-ffffffff81311ff0: shrink_node (STB_LOCAL)
ffffffff81e6c0d8-ffffffff81e6c141: shrink_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:6159
Inline: False
Direct callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff813850a0-ffffffff813853d3: shrink_node (STB_LOCAL)
ffffffff82062bb7-ffffffff82062bd5: shrink_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:6517
Inline: False
Direct callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff813b81a0-ffffffff813b86bd: shrink_node (STB_LOCAL)
ffffffff820e236b-ffffffff820e2389: shrink_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:5881
Inline: False
Direct callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff813e1330-ffffffff813e16b4: shrink_node (STB_LOCAL)
ffffffff821bed15-ffffffff821bed33: shrink_node.cold (STB_LOCAL)
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
bool shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102cc8d0)
Location: mm/vmscan.c:2756
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffff8000102cc8d0-ffff8000102ccd64: shrink_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f6654)
Location: mm/vmscan.c:2756
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
c04f6654-c04f6b68: shrink_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000389fa0)
Location: mm/vmscan.c:2756
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
c000000000389fa0-c00000000038a598: shrink_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001eb30e)
Location: mm/vmscan.c:2756
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffe0001eb30e-ffffffe0001eb69c: shrink_node (STB_LOCAL)
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
bool shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81233e50)
Location: mm/vmscan.c:2756
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81233e50-ffffffff8123424c: shrink_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81226ec0)
Location: mm/vmscan.c:2756
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81226ec0-ffffffff812272bc: shrink_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81231bf0)
Location: mm/vmscan.c:2756
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81231bf0-ffffffff81231fec: shrink_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool shrink_node(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81241050)
Location: mm/vmscan.c:2756
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81241050-ffffffff8124144c: shrink_node (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
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
