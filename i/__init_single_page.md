# Function: <code>__init_single_page</code>

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
In mm/page_alloc.c (ffffffff8181d1ca)
Location: mm/page_alloc.c:880
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
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
In mm/page_alloc.c (ffffffff8189728e)
Location: mm/page_alloc.c:1148
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
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
In mm/page_alloc.c (ffffffff818cb9e8)
Location: mm/page_alloc.c:1164
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
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
In mm/page_alloc.c (ffffffff81903011)
Location: mm/page_alloc.c:1169
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
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
In mm/page_alloc.c (ffffffff8198cb8b)
Location: mm/page_alloc.c:1183
Inline: True
Direct callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
```
**Symbols:**

```
ffffffff8198cb8b-ffffffff8198cc02: __init_single_page.constprop.100 (STB_LOCAL)
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
In mm/page_alloc.c (ffffffff819e9752)
Location: mm/page_alloc.c:1171
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
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
In mm/page_alloc.c (ffffffff81a24e51)
Location: mm/page_alloc.c:1216
Inline: True
Direct callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
```
**Symbols:**

```
ffffffff81a24e51-ffffffff81a24ea0: __init_single_page.isra.69 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a91409)
Location: mm/page_alloc.c:1340
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ac873e)
Location: mm/page_alloc.c:1327
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
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
In mm/page_alloc.c (ffffffff82cfb49c)
Location: mm/page_alloc.c:1382
Inline: True
Inline callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
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
In mm/page_alloc.c (ffffffff81c3e362)
Location: mm/page_alloc.c:1446
Inline: True
Direct callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
```
**Symbols:**

```
ffffffff81c3e362-ffffffff81c3e3c3: __init_single_page.constprop.0 (STB_LOCAL)
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
In mm/page_alloc.c (ffffffff81c3066f)
Location: mm/page_alloc.c:1481
Inline: True
Direct callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_range
```
**Symbols:**

```
ffffffff81c3066f-ffffffff81c306d0: __init_single_page.constprop.0 (STB_LOCAL)
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
In mm/page_alloc.c (ffffffff81d4eea1)
Location: mm/page_alloc.c:1561
Inline: True
Direct callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_range
```
**Symbols:**

```
ffffffff81d4eea1-ffffffff81d4eef9: __init_single_page.constprop.0 (STB_LOCAL)
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
In mm/page_alloc.c (ffffffff81f1ed81)
Location: mm/page_alloc.c:1544
Inline: True
Direct callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:__init_zone_device_page
  - mm/page_alloc.c:memmap_init_range
  - mm/page_alloc.c:memmap_init_range
  - mm/page_alloc.c:memmap_init_range
```
**Symbols:**

```
ffffffff81f1ed81-ffffffff81f1edd7: __init_single_page.constprop.0 (STB_LOCAL)
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
In mm/page_alloc.c (ffffffff83ebe7f0)
Location: mm/page_alloc.c:1620
Inline: True
Inline callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:__init_zone_device_page
  - mm/page_alloc.c:memmap_init_range
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
In mm/mm_init.c (ffffffff8214bf86)
Location: mm/mm_init.c:554
Inline: True
Inline callers:
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:init_unavailable_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __init_single_page(struct page *page, long unsigned int pfn, long unsigned int zone, int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff8222eb1c)
Location: mm/mm_init.c:564
Inline: True
Inline callers:
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:init_unavailable_range
Direct callers:
  - mm/hugetlb.c:hugetlb_folio_init_tail_vmemmap
```
**Symbols:**

```
ffffffff8222e8d0-ffffffff8222e935: __init_single_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010d9fe28)
Location: mm/page_alloc.c:1327
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c15bdd2c)
Location: mm/page_alloc.c:1327
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003ee9c4)
Location: mm/page_alloc.c:1327
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe000047108)
Location: mm/page_alloc.c:1327
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a675ae)
Location: mm/page_alloc.c:1327
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a2406e)
Location: mm/page_alloc.c:1327
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ad39be)
Location: mm/page_alloc.c:1327
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81adfeb8)
Location: mm/page_alloc.c:1327
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
