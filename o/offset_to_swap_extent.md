# Function: <code>offset_to_swap_extent</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff81278500)
Location: mm/swapfile.c:205
Inline: True
Direct callers:
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
ffffffff81278500-ffffffff81278538: offset_to_swap_extent.isra.0 (STB_LOCAL)
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
In mm/swapfile.c (ffffffff81287ff0)
Location: mm/swapfile.c:205
Inline: True
Direct callers:
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
ffffffff81287ff0-ffffffff81288028: offset_to_swap_extent.isra.0 (STB_LOCAL)
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
In mm/swapfile.c (ffffffff812ba6e2)
Location: mm/swapfile.c:204
Inline: True
Inline callers:
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct swap_extent *offset_to_swap_extent(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c6090)
Location: mm/swapfile.c:204
Inline: True
Direct callers:
  - mm/swapfile.c:map_swap_page
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_page_sector
```
**Symbols:**

```
ffffffff812c6090-ffffffff812c60ca: offset_to_swap_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct swap_extent *offset_to_swap_extent(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cca70)
Location: mm/swapfile.c:203
Inline: True
Direct callers:
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_page_sector
```
**Symbols:**

```
ffffffff812cca70-ffffffff812ccaaa: offset_to_swap_extent (STB_LOCAL)
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
In mm/swapfile.c (ffffffff81315f5a)
Location: mm/swapfile.c:203
Inline: True
Inline callers:
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_page_sector
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
In mm/swapfile.c (ffffffff813820de)
Location: mm/swapfile.c:205
Inline: True
Inline callers:
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_page_sector
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
In mm/swapfile.c (ffffffff814008ce)
Location: mm/swapfile.c:209
Inline: True
Inline callers:
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_page_sector
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
In mm/swapfile.c (ffffffff8143376e)
Location: mm/swapfile.c:210
Inline: True
Inline callers:
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_page_sector
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
In mm/swapfile.c (ffffffff8146cb5e)
Location: mm/swapfile.c:212
Inline: True
Inline callers:
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_folio_sector
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
In mm/swapfile.c (ffff800010322f10)
Location: mm/swapfile.c:205
Inline: True
Direct callers:
  - mm/swapfile.c:map_swap_page
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
ffff800010322f10-ffff800010322f74: offset_to_swap_extent.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct swap_extent *offset_to_swap_extent(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053b6e0)
Location: mm/swapfile.c:205
Inline: True
Direct callers:
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
c053b6e0-c053b730: offset_to_swap_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct swap_extent *offset_to_swap_extent(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003f92b0)
Location: mm/swapfile.c:205
Inline: True
Direct callers:
  - mm/swapfile.c:map_swap_page
  - mm/swapfile.c:map_swap_page
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
c0000000003f92b0-c0000000003f9308: offset_to_swap_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct swap_extent *offset_to_swap_extent(struct swap_info_struct *sis, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe000223a5a)
Location: mm/swapfile.c:205
Inline: True
Direct callers:
  - mm/swapfile.c:map_swap_page
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
ffffffe000223a5a-ffffffe000223a9e: offset_to_swap_extent (STB_LOCAL)
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
In mm/swapfile.c (ffffffff812805d0)
Location: mm/swapfile.c:205
Inline: True
Direct callers:
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
ffffffff812805d0-ffffffff81280608: offset_to_swap_extent.isra.0 (STB_LOCAL)
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
In mm/swapfile.c (ffffffff81272440)
Location: mm/swapfile.c:205
Inline: True
Direct callers:
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
ffffffff81272440-ffffffff81272478: offset_to_swap_extent.isra.0 (STB_LOCAL)
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
In mm/swapfile.c (ffffffff8127e3e0)
Location: mm/swapfile.c:205
Inline: True
Direct callers:
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
ffffffff8127e3e0-ffffffff8127e418: offset_to_swap_extent.isra.0 (STB_LOCAL)
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
In mm/swapfile.c (ffffffff8128e710)
Location: mm/swapfile.c:205
Inline: True
Direct callers:
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:swap_do_scheduled_discard
```
**Symbols:**

```
ffffffff8128e710-ffffffff8128e748: offset_to_swap_extent.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
