# Function: <code>walk_zones_in_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void walk_zones_in_node(struct seq_file *m, pg_data_t *pgdat, void (*print)(struct seq_file *, pg_data_t *, struct zone *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811ac560)
Location: mm/vmstat.c:903
Inline: False
Direct callers:
  - mm/vmstat.c:frag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:unusable_show
```
**Symbols:**

```
ffffffff811ac560-ffffffff811ac5ec: walk_zones_in_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void walk_zones_in_node(struct seq_file *m, pg_data_t *pgdat, void (*print)(struct seq_file *, pg_data_t *, struct zone *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c53f0)
Location: mm/vmstat.c:1123
Inline: False
Direct callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:unusable_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
```
**Symbols:**

```
ffffffff811c53f0-ffffffff811c5479: walk_zones_in_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void walk_zones_in_node(struct seq_file *m, pg_data_t *pgdat, void (*print)(struct seq_file *, pg_data_t *, struct zone *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d5500)
Location: mm/vmstat.c:1123
Inline: False
Direct callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:unusable_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
```
**Symbols:**

```
ffffffff811d5500-ffffffff811d5589: walk_zones_in_node (STB_LOCAL)
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
In mm/vmstat.c (ffffffff811df370)
Location: mm/vmstat.c:1132
Inline: True
Direct callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
```
**Symbols:**

```
ffffffff811df370-ffffffff811df3f5: walk_zones_in_node.constprop.16 (STB_LOCAL)
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
In mm/vmstat.c (ffffffff811f4fe0)
Location: mm/vmstat.c:1326
Inline: True
Direct callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
```
**Symbols:**

```
ffffffff811f4fe0-ffffffff811f5068: walk_zones_in_node.constprop.16 (STB_LOCAL)
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
In mm/vmstat.c (ffffffff812162b0)
Location: mm/vmstat.c:1327
Inline: True
Direct callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
```
**Symbols:**

```
ffffffff812162b0-ffffffff81216337: walk_zones_in_node.constprop.18 (STB_LOCAL)
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
In mm/vmstat.c (ffffffff812291b0)
Location: mm/vmstat.c:1331
Inline: True
Direct callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
```
**Symbols:**

```
ffffffff812291b0-ffffffff8122923a: walk_zones_in_node.constprop.18 (STB_LOCAL)
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
In mm/vmstat.c (ffffffff81238e70)
Location: mm/vmstat.c:1327
Inline: True
Direct callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
```
**Symbols:**

```
ffffffff81238e70-ffffffff81238ef9: walk_zones_in_node.constprop.0 (STB_LOCAL)
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
In mm/vmstat.c (ffffffff81247180)
Location: mm/vmstat.c:1329
Inline: True
Direct callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
```
**Symbols:**

```
ffffffff81247180-ffffffff81247209: walk_zones_in_node.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812750f5)
Location: mm/vmstat.c:1341
Inline: True
Inline callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8127f8e0)
Location: mm/vmstat.c:1388
Inline: True
Inline callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
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
In mm/vmstat.c (ffffffff81284900)
Location: mm/vmstat.c:1411
Inline: True
Inline callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
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
In mm/vmstat.c (ffffffff812c2e10)
Location: mm/vmstat.c:1419
Inline: True
Inline callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
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
In mm/vmstat.c (ffffffff813200d0)
Location: mm/vmstat.c:1442
Inline: True
Inline callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
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
In mm/vmstat.c (ffffffff81393dd0)
Location: mm/vmstat.c:1437
Inline: True
Inline callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
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
In mm/vmstat.c (ffffffff813c68d0)
Location: mm/vmstat.c:1447
Inline: True
Inline callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
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
In mm/vmstat.c (ffffffff813f13f0)
Location: mm/vmstat.c:1451
Inline: True
Inline callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
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
In mm/vmstat.c (ffff8000102da6f8)
Location: mm/vmstat.c:1329
Inline: True
Direct callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
```
**Symbols:**

```
ffff8000102da6f8-ffff8000102da7ec: walk_zones_in_node.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (c050137c)
Location: mm/vmstat.c:1329
Inline: True
Direct callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
```
**Symbols:**

```
c050137c-c05013f8: walk_zones_in_node.constprop.0 (STB_LOCAL)
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
In mm/vmstat.c (c00000000039af50)
Location: mm/vmstat.c:1329
Inline: True
Direct callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
```
**Symbols:**

```
c00000000039af50-c00000000039b040: walk_zones_in_node.constprop.0 (STB_LOCAL)
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
In mm/vmstat.c (ffffffe0001f49f2)
Location: mm/vmstat.c:1329
Inline: True
Direct callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
```
**Symbols:**

```
ffffffe0001f49f2-ffffffe0001f4a74: walk_zones_in_node.constprop.0 (STB_LOCAL)
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
In mm/vmstat.c (ffffffff8123f7d0)
Location: mm/vmstat.c:1329
Inline: True
Direct callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
```
**Symbols:**

```
ffffffff8123f7d0-ffffffff8123f859: walk_zones_in_node.constprop.0 (STB_LOCAL)
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
In mm/vmstat.c (ffffffff812327d0)
Location: mm/vmstat.c:1329
Inline: True
Direct callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
```
**Symbols:**

```
ffffffff812327d0-ffffffff81232859: walk_zones_in_node.constprop.0 (STB_LOCAL)
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
In mm/vmstat.c (ffffffff8123d570)
Location: mm/vmstat.c:1329
Inline: True
Direct callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
```
**Symbols:**

```
ffffffff8123d570-ffffffff8123d5f9: walk_zones_in_node.constprop.0 (STB_LOCAL)
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
In mm/vmstat.c (ffffffff8124cca0)
Location: mm/vmstat.c:1329
Inline: True
Direct callers:
  - mm/vmstat.c:extfrag_show
  - mm/vmstat.c:zoneinfo_show
  - mm/vmstat.c:frag_show
```
**Symbols:**

```
ffffffff8124cca0-ffffffff8124cd29: walk_zones_in_node.constprop.0 (STB_LOCAL)
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
</ul>
