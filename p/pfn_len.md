# Function: <code>pfn_len</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int pfn_len(struct dev_pagemap *pgmap, long unsigned int range_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memremap.c (0)
Location: mm/memremap.c:104
Inline: False
Direct callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff813e70d0-ffffffff813e7134: pfn_len (STB_LOCAL)
ffffffff81e75d93-ffffffff81e75dce: pfn_len.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int pfn_len(struct dev_pagemap *pgmap, long unsigned int range_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memremap.c (0)
Location: mm/memremap.c:104
Inline: False
Direct callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff8146ed20-ffffffff8146ed84: pfn_len (STB_LOCAL)
ffffffff820685e5-ffffffff82068620: pfn_len.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int pfn_len(struct dev_pagemap *pgmap, long unsigned int range_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memremap.c (0)
Location: mm/memremap.c:104
Inline: False
Direct callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff814a34e0-ffffffff814a3544: pfn_len (STB_LOCAL)
ffffffff820e7ebb-ffffffff820e7ef6: pfn_len.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int pfn_len(struct dev_pagemap *pgmap, long unsigned int range_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memremap.c (0)
Location: mm/memremap.c:105
Inline: False
Direct callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff814d4380-ffffffff814d43e4: pfn_len (STB_LOCAL)
ffffffff821c4bfa-ffffffff821c4c35: pfn_len.cold (STB_LOCAL)
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
