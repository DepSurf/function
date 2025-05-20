# Function: <code>memmap_init_zone_device</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone *zone, long unsigned int start_pfn, long unsigned int size, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a20da0)
Location: mm/page_alloc.c:5719
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff81a20da0-ffffffff81a20ed1: memmap_init_zone_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone *zone, long unsigned int start_pfn, long unsigned int size, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a912f0)
Location: mm/page_alloc.c:5906
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff81a912f0-ffffffff81a91491: memmap_init_zone_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone *zone, long unsigned int start_pfn, long unsigned int size, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ac8630)
Location: mm/page_alloc.c:5924
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81ac8630-ffffffff81ac87be: memmap_init_zone_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81bc1030)
Location: mm/page_alloc.c:6007
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81bc1030-ffffffff81bc11be: memmap_init_zone_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c3a0c0)
Location: mm/page_alloc.c:6175
Inline: False
Direct callers:
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff81c3a0c0-ffffffff81c3a210: memmap_init_zone_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c2c680)
Location: mm/page_alloc.c:6377
Inline: False
Direct callers:
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff81c2c680-ffffffff81c2c7d0: memmap_init_zone_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81d4ad90)
Location: mm/page_alloc.c:6561
Inline: False
Direct callers:
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff81d4ad90-ffffffff81d4aee0: memmap_init_zone_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81f1a6c0)
Location: mm/page_alloc.c:6707
Inline: False
Direct callers:
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff81f1a6c0-ffffffff81f1a895: memmap_init_zone_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff820c2550)
Location: mm/page_alloc.c:6880
Inline: False
Direct callers:
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff820c2550-ffffffff820c2717: memmap_init_zone_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff82146190)
Location: mm/mm_init.c:1053
Inline: False
Direct callers:
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff82146190-ffffffff8214642b: memmap_init_zone_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff822288b0)
Location: mm/mm_init.c:1064
Inline: False
Direct callers:
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff822288b0-ffffffff82228b37: memmap_init_zone_device (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone *zone, long unsigned int start_pfn, long unsigned int size, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003ee810)
Location: mm/page_alloc.c:5924
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
c0000000003ee810-c0000000003eea38: memmap_init_zone_device (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone *zone, long unsigned int start_pfn, long unsigned int size, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a674a0)
Location: mm/page_alloc.c:5924
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81a674a0-ffffffff81a6762e: memmap_init_zone_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone *zone, long unsigned int start_pfn, long unsigned int size, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a23f60)
Location: mm/page_alloc.c:5924
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81a23f60-ffffffff81a240ee: memmap_init_zone_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone *zone, long unsigned int start_pfn, long unsigned int size, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ad38b0)
Location: mm/page_alloc.c:5924
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81ad38b0-ffffffff81ad3a3e: memmap_init_zone_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void memmap_init_zone_device(struct zone *zone, long unsigned int start_pfn, long unsigned int size, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81adfdb0)
Location: mm/page_alloc.c:5924
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81adfdb0-ffffffff81adff31: memmap_init_zone_device (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Param added. </b>
<code>long unsigned int nr_pages</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int size</code>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
