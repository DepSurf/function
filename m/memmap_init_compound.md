# Function: <code>memmap_init_compound</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void memmap_init_compound(struct page *head, long unsigned int head_pfn, long unsigned int zone_idx, int nid, struct dev_pagemap *pgmap, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81f1a4ee)
Location: mm/page_alloc.c:6678
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init_zone_device
```
**Symbols:**

```
ffffffff81f1a4ee-ffffffff81f1a603: memmap_init_compound (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void memmap_init_compound(struct page *head, long unsigned int head_pfn, long unsigned int zone_idx, int nid, struct dev_pagemap *pgmap, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff820c2320)
Location: mm/page_alloc.c:6853
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init_zone_device
```
**Symbols:**

```
ffffffff820c2320-ffffffff820c2475: memmap_init_compound (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mm_init.c (ffffffff82145e40)
Location: mm/mm_init.c:1026
Inline: True
Direct callers:
  - mm/mm_init.c:memmap_init_zone_device
```
**Symbols:**

```
ffffffff82145e40-ffffffff82145fa5: memmap_init_compound.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mm_init.c (ffffffff82228560)
Location: mm/mm_init.c:1037
Inline: True
Direct callers:
  - mm/mm_init.c:memmap_init_zone_device
```
**Symbols:**

```
ffffffff82228560-ffffffff822286c2: memmap_init_compound.constprop.0 (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
