# Function: <code>isolate_lru_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff811a26e0)
Location: mm/vmscan.c:1356
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_active_list
```
**Symbols:**

```
ffffffff811a26e0-ffffffff811a2889: isolate_lru_pages.isra.49 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff811b8a90)
Location: mm/vmscan.c:1414
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff811b8a90-ffffffff811b8e4a: isolate_lru_pages.isra.47 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff811c90c0)
Location: mm/vmscan.c:1448
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff811c90c0-ffffffff811c948c: isolate_lru_pages.isra.47 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff811d1bb0)
Location: mm/vmscan.c:1492
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff811d1bb0-ffffffff811d1f64: isolate_lru_pages.isra.56 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff811e7050)
Location: mm/vmscan.c:1509
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff811e7050-ffffffff811e7406: isolate_lru_pages.isra.59 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff812085a0)
Location: mm/vmscan.c:1486
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff812085a0-ffffffff8120896b: isolate_lru_pages.isra.53 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff8121b230)
Location: mm/vmscan.c:1653
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff8121b230-ffffffff8121b60c: isolate_lru_pages.isra.56 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int isolate_lru_pages(long unsigned int nr_to_scan, struct lruvec *lruvec, struct list_head *dst, long unsigned int *nr_scanned, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122aeb0)
Location: mm/vmscan.c:1684
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff8122aeb0-ffffffff8122b2b7: isolate_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int isolate_lru_pages(long unsigned int nr_to_scan, struct lruvec *lruvec, struct list_head *dst, long unsigned int *nr_scanned, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81238d80)
Location: mm/vmscan.c:1683
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff81238d80-ffffffff8123918d: isolate_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int isolate_lru_pages(long unsigned int nr_to_scan, struct lruvec *lruvec, struct list_head *dst, long unsigned int *nr_scanned, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812678c0)
Location: mm/vmscan.c:1652
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff812678c0-ffffffff81267cb8: isolate_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int isolate_lru_pages(long unsigned int nr_to_scan, struct lruvec *lruvec, struct list_head *dst, long unsigned int *nr_scanned, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812722f0)
Location: mm/vmscan.c:1638
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff812722f0-ffffffff81272759: isolate_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int isolate_lru_pages(long unsigned int nr_to_scan, struct lruvec *lruvec, struct list_head *dst, long unsigned int *nr_scanned, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81277610)
Location: mm/vmscan.c:1837
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff81277610-ffffffff81277a42: isolate_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int isolate_lru_pages(long unsigned int nr_to_scan, struct lruvec *lruvec, struct list_head *dst, long unsigned int *nr_scanned, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b4fa0)
Location: mm/vmscan.c:1970
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff812b4fa0-ffffffff812b5645: isolate_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int isolate_lru_pages(long unsigned int nr_to_scan, struct lruvec *lruvec, struct list_head *dst, long unsigned int *nr_scanned, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8130d480)
Location: mm/vmscan.c:2077
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff8130d480-ffffffff8130dcec: isolate_lru_pages (STB_LOCAL)
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
long unsigned int isolate_lru_pages(long unsigned int nr_to_scan, struct lruvec *lruvec, struct list_head *dst, long unsigned int *nr_scanned, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102c9c50)
Location: mm/vmscan.c:1683
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffff8000102c9c50-ffff8000102c9fe0: isolate_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int isolate_lru_pages(long unsigned int nr_to_scan, struct lruvec *lruvec, struct list_head *dst, long unsigned int *nr_scanned, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f3b34)
Location: mm/vmscan.c:1683
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
c04f3b34-c04f3ee8: isolate_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int isolate_lru_pages(long unsigned int nr_to_scan, struct lruvec *lruvec, struct list_head *dst, long unsigned int *nr_scanned, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000386400)
Location: mm/vmscan.c:1683
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
c000000000386400-c000000000386860: isolate_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int isolate_lru_pages(long unsigned int nr_to_scan, struct lruvec *lruvec, struct list_head *dst, long unsigned int *nr_scanned, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e8ef6)
Location: mm/vmscan.c:1683
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffe0001e8ef6-ffffffe0001e91be: isolate_lru_pages (STB_LOCAL)
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
long unsigned int isolate_lru_pages(long unsigned int nr_to_scan, struct lruvec *lruvec, struct list_head *dst, long unsigned int *nr_scanned, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812313d0)
Location: mm/vmscan.c:1683
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff812313d0-ffffffff812317dd: isolate_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int isolate_lru_pages(long unsigned int nr_to_scan, struct lruvec *lruvec, struct list_head *dst, long unsigned int *nr_scanned, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81224490)
Location: mm/vmscan.c:1683
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff81224490-ffffffff8122489d: isolate_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int isolate_lru_pages(long unsigned int nr_to_scan, struct lruvec *lruvec, struct list_head *dst, long unsigned int *nr_scanned, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122f170)
Location: mm/vmscan.c:1683
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff8122f170-ffffffff8122f57d: isolate_lru_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int isolate_lru_pages(long unsigned int nr_to_scan, struct lruvec *lruvec, struct list_head *dst, long unsigned int *nr_scanned, struct scan_control *sc, enum lru_list lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123e580)
Location: mm/vmscan.c:1683
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
**Symbols:**

```
ffffffff8123e580-ffffffff8123e9a6: isolate_lru_pages (STB_LOCAL)
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
