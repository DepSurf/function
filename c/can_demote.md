# Function: <code>can_demote</code>

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
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool can_demote(int nid, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff812b429a)
Location: mm/vmscan.c:525
Inline: True
Inline callers:
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812b0430-ffffffff812b048e: can_demote (STB_LOCAL)
ffffffff81cba612-ffffffff81cba62d: can_demote.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool can_demote(int nid, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff813124b3)
Location: mm/vmscan.c:527
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:zone_reclaimable_pages
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff8130bc60-ffffffff8130bcb6: can_demote (STB_LOCAL)
ffffffff81e6bf43-ffffffff81e6bf5e: can_demote.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool can_demote(int nid, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff81385b12)
Location: mm/vmscan.c:541
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:zone_reclaimable_pages
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:get_swappiness
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:shrink_folio_list
```
**Symbols:**

```
ffffffff81377280-ffffffff813772d6: can_demote (STB_LOCAL)
ffffffff820628af-ffffffff820628ca: can_demote.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool can_demote(int nid, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff813b8d8b)
Location: mm/vmscan.c:593
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:zone_reclaimable_pages
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:get_swappiness
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:shrink_folio_list
```
**Symbols:**

```
ffffffff813a92e0-ffffffff813a9336: can_demote (STB_LOCAL)
ffffffff820e2070-ffffffff820e208b: can_demote.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool can_demote(int nid, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff813e1d8b)
Location: mm/vmscan.c:299
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:zone_reclaimable_pages
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:get_swappiness
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:shrink_folio_list
```
**Symbols:**

```
ffffffff813d2ce0-ffffffff813d2d36: can_demote (STB_LOCAL)
ffffffff821bea5b-ffffffff821bea76: can_demote.cold (STB_LOCAL)
```
</details>
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
