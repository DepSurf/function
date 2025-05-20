# Function: <code>adjust_zone_range_for_zone_movable</code>

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
In mm/page_alloc.c (ffffffff8181d40f)
Location: mm/page_alloc.c:4898
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (ffffffff818976d3)
Location: mm/page_alloc.c:5439
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (ffffffff818cb5f7)
Location: mm/page_alloc.c:5477
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff818cb5f7-ffffffff818cb656: adjust_zone_range_for_zone_movable.isra.66 (STB_LOCAL)
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
In mm/page_alloc.c (ffffffff81902be1)
Location: mm/page_alloc.c:5774
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff81902be1-ffffffff81902c43: adjust_zone_range_for_zone_movable.isra.68 (STB_LOCAL)
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
In mm/page_alloc.c (ffffffff8198cb29)
Location: mm/page_alloc.c:5746
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff8198cb29-ffffffff8198cb8b: adjust_zone_range_for_zone_movable.isra.69 (STB_LOCAL)
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
In mm/page_alloc.c (ffffffff819e9435)
Location: mm/page_alloc.c:5884
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff819e9435-ffffffff819e9490: adjust_zone_range_for_zone_movable.isra.75 (STB_LOCAL)
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
In mm/page_alloc.c (ffffffff828b8511)
Location: mm/page_alloc.c:6130
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff828b8511-ffffffff828b8578: adjust_zone_range_for_zone_movable.isra.80 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff828d562f)
Location: mm/page_alloc.c:6316
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff828d562f-ffffffff828d5696: adjust_zone_range_for_zone_movable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff828ddaa3)
Location: mm/page_alloc.c:6334
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff828ddaa3-ffffffff828ddb0a: adjust_zone_range_for_zone_movable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff82cfb3d7)
Location: mm/page_alloc.c:6395
Inline: True
Direct callers:
  - mm/page_alloc.c:calculate_node_totalpages
  - mm/page_alloc.c:zone_absent_pages_in_node
```
**Symbols:**

```
ffffffff82cfb3d7-ffffffff82cfb43e: adjust_zone_range_for_zone_movable.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff82fe804c)
Location: mm/page_alloc.c:6626
Inline: True
Direct callers:
  - mm/page_alloc.c:calculate_node_totalpages
  - mm/page_alloc.c:zone_absent_pages_in_node
```
**Symbols:**

```
ffffffff82fe804c-ffffffff82fe80b3: adjust_zone_range_for_zone_movable.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff831f2790)
Location: mm/page_alloc.c:6847
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff831f2790-ffffffff831f27f5: adjust_zone_range_for_zone_movable.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff832d7dbc)
Location: mm/page_alloc.c:7089
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff832d7dbc-ffffffff832d7f25: adjust_zone_range_for_zone_movable.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff8348cac3)
Location: mm/page_alloc.c:7210
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff8348cac3-ffffffff8348cc44: adjust_zone_range_for_zone_movable.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff83ebe020)
Location: mm/page_alloc.c:7394
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:zone_absent_pages_in_node
```
**Symbols:**

```
ffffffff83ebe020-ffffffff83ebe28b: adjust_zone_range_for_zone_movable.constprop.0 (STB_LOCAL)
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
In mm/mm_init.c (ffffffff836e0bc4)
Location: mm/mm_init.c:1106
Inline: True
Inline callers:
  - mm/mm_init.c:calculate_node_totalpages
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
In mm/mm_init.c (ffffffff839134c4)
Location: mm/mm_init.c:1117
Inline: True
Inline callers:
  - mm/mm_init.c:calculate_node_totalpages
```
</details>
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
In mm/page_alloc.c (ffff800011456844)
Location: mm/page_alloc.c:6334
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffff800011456844-ffff800011456900: adjust_zone_range_for_zone_movable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (c00000000137ff04)
Location: mm/page_alloc.c:6334
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
c00000000137ff04-c00000000137ffa0: adjust_zone_range_for_zone_movable.isra.0 (STB_LOCAL)
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
In mm/page_alloc.c (ffffffe0000154b0)
Location: mm/page_alloc.c:6334
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffe0000154b0-ffffffe000015544: adjust_zone_range_for_zone_movable.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff828c6957)
Location: mm/page_alloc.c:6334
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff828c6957-ffffffff828c69be: adjust_zone_range_for_zone_movable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff828bf07c)
Location: mm/page_alloc.c:6334
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff828bf07c-ffffffff828bf0e3: adjust_zone_range_for_zone_movable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff828d96d7)
Location: mm/page_alloc.c:6334
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff828d96d7-ffffffff828d973e: adjust_zone_range_for_zone_movable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff828deaf8)
Location: mm/page_alloc.c:6334
Inline: True
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff828deaf8-ffffffff828deb5f: adjust_zone_range_for_zone_movable.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
