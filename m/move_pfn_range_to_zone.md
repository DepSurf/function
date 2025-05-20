# Function: <code>move_pfn_range_to_zone</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void move_pfn_range_to_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff818ff460)
Location: mm/memory_hotplug.c:823
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff818ff460-ffffffff818ff599: move_pfn_range_to_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void move_pfn_range_to_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81989560)
Location: mm/memory_hotplug.c:807
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - mm/memory_hotplug.c:online_pages
  - mm/hmm.c:hmm_devmem_pages_create
```
**Symbols:**

```
ffffffff81989560-ffffffff81989699: move_pfn_range_to_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void move_pfn_range_to_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff819e5e30)
Location: mm/memory_hotplug.c:783
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - mm/memory_hotplug.c:online_pages
  - mm/hmm.c:hmm_devmem_pages_create
```
**Symbols:**

```
ffffffff819e5e30-ffffffff819e5f7a: move_pfn_range_to_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void move_pfn_range_to_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a211c0)
Location: mm/memory_hotplug.c:742
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81a211c0-ffffffff81a21313: move_pfn_range_to_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void move_pfn_range_to_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a91870)
Location: mm/memory_hotplug.c:721
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff81a91870-ffffffff81a919c1: move_pfn_range_to_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void move_pfn_range_to_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ac9010)
Location: mm/memory_hotplug.c:704
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81ac9010-ffffffff81ac9163: move_pfn_range_to_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void move_pfn_range_to_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81bc1730)
Location: mm/memory_hotplug.c:698
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81bc1730-ffffffff81bc1883: move_pfn_range_to_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void move_pfn_range_to_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c3a730)
Location: mm/memory_hotplug.c:692
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff81c3a730-ffffffff81c3a89b: move_pfn_range_to_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void move_pfn_range_to_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c2cd10)
Location: mm/memory_hotplug.c:749
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:mhp_init_memmap_on_memory
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff81c2cd10-ffffffff81c2cec0: move_pfn_range_to_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void move_pfn_range_to_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81d4b630)
Location: mm/memory_hotplug.c:692
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:mhp_init_memmap_on_memory
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff81d4b630-ffffffff81d4b78c: move_pfn_range_to_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void move_pfn_range_to_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81f1af00)
Location: mm/memory_hotplug.c:691
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:mhp_init_memmap_on_memory
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff81f1af00-ffffffff81f1b079: move_pfn_range_to_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void move_pfn_range_to_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff820c2dd0)
Location: mm/memory_hotplug.c:687
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:mhp_init_memmap_on_memory
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff820c2dd0-ffffffff820c2fc3: move_pfn_range_to_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void move_pfn_range_to_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff82146b70)
Location: mm/memory_hotplug.c:681
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:mhp_init_memmap_on_memory
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff82146b70-ffffffff82146d72: move_pfn_range_to_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void move_pfn_range_to_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff82229300)
Location: mm/memory_hotplug.c:750
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:mhp_init_memmap_on_memory
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff82229300-ffffffff82229502: move_pfn_range_to_zone (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void move_pfn_range_to_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffff800010d9cc28)
Location: mm/memory_hotplug.c:704
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffff800010d9cc28-ffff800010d9ce30: move_pfn_range_to_zone (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void move_pfn_range_to_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042fad0)
Location: mm/memory_hotplug.c:704
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
c00000000042fad0-c00000000042fcdc: move_pfn_range_to_zone (STB_GLOBAL)
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
void move_pfn_range_to_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a67e80)
Location: mm/memory_hotplug.c:704
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81a67e80-ffffffff81a67fd3: move_pfn_range_to_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void move_pfn_range_to_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a24940)
Location: mm/memory_hotplug.c:704
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81a24940-ffffffff81a24a93: move_pfn_range_to_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void move_pfn_range_to_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ad4290)
Location: mm/memory_hotplug.c:704
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81ad4290-ffffffff81ad43e3: move_pfn_range_to_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void move_pfn_range_to_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ae0770)
Location: mm/memory_hotplug.c:704
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81ae0770-ffffffff81ae08c9: move_pfn_range_to_zone (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vmem_altmap *altmap</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int migratetype</code>
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
