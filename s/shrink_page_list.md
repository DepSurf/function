# Function: <code>shrink_page_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int shrink_page_list(struct list_head *page_list, struct zone *zone, struct scan_control *sc, enum ttu_flags ttu_flags, long unsigned int *ret_nr_dirty, long unsigned int *ret_nr_unqueued_dirty, long unsigned int *ret_nr_congested, long unsigned int *ret_nr_writeback, long unsigned int *ret_nr_immediate, bool force_reclaim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a2d30)
Location: mm/vmscan.c:880
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff811a2d30-ffffffff811a34c4: shrink_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int shrink_page_list(struct list_head *page_list, struct pglist_data *pgdat, struct scan_control *sc, enum ttu_flags ttu_flags, long unsigned int *ret_nr_dirty, long unsigned int *ret_nr_unqueued_dirty, long unsigned int *ret_nr_congested, long unsigned int *ret_nr_writeback, long unsigned int *ret_nr_immediate, bool force_reclaim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b94a0)
Location: mm/vmscan.c:900
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
**Symbols:**

```
ffffffff811b94a0-ffffffff811b9e3b: shrink_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int shrink_page_list(struct list_head *page_list, struct pglist_data *pgdat, struct scan_control *sc, enum ttu_flags ttu_flags, long unsigned int *ret_nr_dirty, long unsigned int *ret_nr_unqueued_dirty, long unsigned int *ret_nr_congested, long unsigned int *ret_nr_writeback, long unsigned int *ret_nr_immediate, bool force_reclaim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811c9ad0)
Location: mm/vmscan.c:935
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
**Symbols:**

```
ffffffff811c9ad0-ffffffff811ca4ce: shrink_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int shrink_page_list(struct list_head *page_list, struct pglist_data *pgdat, struct scan_control *sc, enum ttu_flags ttu_flags, struct reclaim_stat *stat, bool force_reclaim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811d24f0)
Location: mm/vmscan.c:948
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
**Symbols:**

```
ffffffff811d24f0-ffffffff811d3052: shrink_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int shrink_page_list(struct list_head *page_list, struct pglist_data *pgdat, struct scan_control *sc, enum ttu_flags ttu_flags, struct reclaim_stat *stat, bool force_reclaim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e79f0)
Location: mm/vmscan.c:960
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
**Symbols:**

```
ffffffff811e79f0-ffffffff811e85ac: shrink_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int shrink_page_list(struct list_head *page_list, struct pglist_data *pgdat, struct scan_control *sc, enum ttu_flags ttu_flags, struct reclaim_stat *stat, bool force_reclaim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81208e50)
Location: mm/vmscan.c:927
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
**Symbols:**

```
ffffffff81208e50-ffffffff81209a6d: shrink_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int shrink_page_list(struct list_head *page_list, struct pglist_data *pgdat, struct scan_control *sc, enum ttu_flags ttu_flags, struct reclaim_stat *stat, bool force_reclaim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8121bb30)
Location: mm/vmscan.c:1100
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
**Symbols:**

```
ffffffff8121bb30-ffffffff8121c74d: shrink_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int shrink_page_list(struct list_head *page_list, struct pglist_data *pgdat, struct scan_control *sc, enum ttu_flags ttu_flags, struct reclaim_stat *stat, bool force_reclaim);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122b7e0)
Location: mm/vmscan.c:1119
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
**Symbols:**

```
ffffffff8122b7e0-ffffffff8122c390: shrink_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int shrink_page_list(struct list_head *page_list, struct pglist_data *pgdat, struct scan_control *sc, enum ttu_flags ttu_flags, struct reclaim_stat *stat, bool ignore_references);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812396b0)
Location: mm/vmscan.c:1119
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
**Symbols:**

```
ffffffff812396b0-ffffffff8123a25c: shrink_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int shrink_page_list(struct list_head *page_list, struct pglist_data *pgdat, struct scan_control *sc, enum ttu_flags ttu_flags, struct reclaim_stat *stat, bool ignore_references);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81265e60)
Location: mm/vmscan.c:1076
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
**Symbols:**

```
ffffffff81265e60-ffffffff81266970: shrink_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int shrink_page_list(struct list_head *page_list, struct pglist_data *pgdat, struct scan_control *sc, struct reclaim_stat *stat, bool ignore_references);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81270800)
Location: mm/vmscan.c:1070
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
**Symbols:**

```
ffffffff81270800-ffffffff812713b3: shrink_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int shrink_page_list(struct list_head *page_list, struct pglist_data *pgdat, struct scan_control *sc, struct reclaim_stat *stat, bool ignore_references);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81275240)
Location: mm/vmscan.c:1270
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
**Symbols:**

```
ffffffff81275240-ffffffff81275f05: shrink_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int shrink_page_list(struct list_head *page_list, struct pglist_data *pgdat, struct scan_control *sc, struct reclaim_stat *stat, bool ignore_references);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:1364
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
**Symbols:**

```
ffffffff812b2d10-ffffffff812b3c00: shrink_page_list (STB_LOCAL)
ffffffff81cba6b5-ffffffff81cba7ce: shrink_page_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int shrink_page_list(struct list_head *page_list, struct pglist_data *pgdat, struct scan_control *sc, struct reclaim_stat *stat, bool ignore_references);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:1528
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_page_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
**Symbols:**

```
ffffffff8130e000-ffffffff8130ec59: shrink_page_list (STB_LOCAL)
ffffffff81e6bfe4-ffffffff81e6c0ac: shrink_page_list.cold (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
long unsigned int shrink_page_list(struct list_head *page_list, struct pglist_data *pgdat, struct scan_control *sc, enum ttu_flags ttu_flags, struct reclaim_stat *stat, bool ignore_references);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102ca5c8)
Location: mm/vmscan.c:1119
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
**Symbols:**

```
ffff8000102ca5c8-ffff8000102cb18c: shrink_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int shrink_page_list(struct list_head *page_list, struct pglist_data *pgdat, struct scan_control *sc, enum ttu_flags ttu_flags, struct reclaim_stat *stat, bool ignore_references);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f43f8)
Location: mm/vmscan.c:1119
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
**Symbols:**

```
c04f43f8-c04f5234: shrink_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int shrink_page_list(struct list_head *page_list, struct pglist_data *pgdat, struct scan_control *sc, enum ttu_flags ttu_flags, struct reclaim_stat *stat, bool ignore_references);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c0000000003870b0)
Location: mm/vmscan.c:1119
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
**Symbols:**

```
c0000000003870b0-c00000000038810c: shrink_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int shrink_page_list(struct list_head *page_list, struct pglist_data *pgdat, struct scan_control *sc, enum ttu_flags ttu_flags, struct reclaim_stat *stat, bool ignore_references);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e966c)
Location: mm/vmscan.c:1119
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
**Symbols:**

```
ffffffe0001e966c-ffffffe0001ea0c2: shrink_page_list (STB_LOCAL)
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
long unsigned int shrink_page_list(struct list_head *page_list, struct pglist_data *pgdat, struct scan_control *sc, enum ttu_flags ttu_flags, struct reclaim_stat *stat, bool ignore_references);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81231d00)
Location: mm/vmscan.c:1119
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
**Symbols:**

```
ffffffff81231d00-ffffffff812328ac: shrink_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int shrink_page_list(struct list_head *page_list, struct pglist_data *pgdat, struct scan_control *sc, enum ttu_flags ttu_flags, struct reclaim_stat *stat, bool ignore_references);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81224dc0)
Location: mm/vmscan.c:1119
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
**Symbols:**

```
ffffffff81224dc0-ffffffff81225944: shrink_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int shrink_page_list(struct list_head *page_list, struct pglist_data *pgdat, struct scan_control *sc, enum ttu_flags ttu_flags, struct reclaim_stat *stat, bool ignore_references);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122faa0)
Location: mm/vmscan.c:1119
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
**Symbols:**

```
ffffffff8122faa0-ffffffff8123064c: shrink_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int shrink_page_list(struct list_head *page_list, struct pglist_data *pgdat, struct scan_control *sc, enum ttu_flags ttu_flags, struct reclaim_stat *stat, bool ignore_references);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123eef0)
Location: mm/vmscan.c:1119
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
**Symbols:**

```
ffffffff8123eef0-ffffffff8123fa97: shrink_page_list (STB_LOCAL)
```
</details>
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
<b>Param added. </b>
<code>struct pglist_data *pgdat</code>
</li>
<li>
<b>Param removed. </b>
<code>struct zone *zone</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct reclaim_stat *stat</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *ret_nr_dirty</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *ret_nr_unqueued_dirty</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *ret_nr_congested</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *ret_nr_writeback</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *ret_nr_immediate</code>
</li>
<li>
<b>Param reordered. </b>
<code>page_list, pgdat, sc, ttu_flags, ret_nr_dirty, ret_nr_unqueued_dirty, ret_nr_congested, ret_nr_writeback, ret_nr_immediate, force_reclaim</code> ➡️ <code>page_list, pgdat, sc, ttu_flags, stat, force_reclaim</code>
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool ignore_references</code>
</li>
<li>
<b>Param removed. </b>
<code>bool force_reclaim</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>enum ttu_flags ttu_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>page_list, pgdat, sc, ttu_flags, stat, ignore_references</code> ➡️ <code>page_list, pgdat, sc, stat, ignore_references</code>
</li>
</ul>
</details>
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
