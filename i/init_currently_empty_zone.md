# Function: <code>init_currently_empty_zone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8181ce7e)
Location: mm/page_alloc.c:4747
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:ensure_zone_is_initialized
```
**Symbols:**

```
ffffffff8181ce7e-ffffffff8181cf0f: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff818973c7)
Location: mm/page_alloc.c:5288
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:ensure_zone_is_initialized
```
**Symbols:**

```
ffffffff818973c7-ffffffff81897440: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff818cbad5)
Location: mm/page_alloc.c:5328
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:ensure_zone_is_initialized
```
**Symbols:**

```
ffffffff818cbad5-ffffffff818cbb3c: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8190305b)
Location: mm/page_alloc.c:5627
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff8190305b-ffffffff819030c0: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8198cf6b)
Location: mm/page_alloc.c:5599
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff8198cf6b-ffffffff8198cfd0: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff819e983d)
Location: mm/page_alloc.c:5737
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff819e983d-ffffffff819e989d: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a25251)
Location: mm/page_alloc.c:5981
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81a25251-ffffffff81a252b9: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a956a0)
Location: mm/page_alloc.c:6167
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81a956a0-ffffffff81a95708: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81accf83)
Location: mm/page_alloc.c:6185
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81accf83-ffffffff81accfeb: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81bc5968)
Location: mm/page_alloc.c:6297
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81bc5968-ffffffff81bc59d0: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c3e918)
Location: mm/page_alloc.c:6544
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81c3e918-ffffffff81c3e980: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c30a48)
Location: mm/page_alloc.c:6765
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81c30a48-ffffffff81c30ab0: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81d4f2fb)
Location: mm/page_alloc.c:7007
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81d4f2fb-ffffffff81d4f3cc: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81f1f287)
Location: mm/page_alloc.c:7128
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81f1f287-ffffffff81f1f368: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff83ebe467)
Location: mm/page_alloc.c:7312
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_core
Direct callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff820c8430-ffffffff820c8539: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff8214c1e0)
Location: mm/mm_init.c:1389
Inline: False
Direct callers:
  - mm/mm_init.c:free_area_init_core
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff8214c1e0-ffffffff8214c304: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff8222ed60)
Location: mm/mm_init.c:1398
Inline: False
Direct callers:
  - mm/mm_init.c:free_area_init_core
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff8222ed60-ffffffff8222ee84: init_currently_empty_zone (STB_GLOBAL)
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
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010d9ff34)
Location: mm/page_alloc.c:6185
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffff800010d9ff34-ffff800010d9ffb4: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c15bde3c)
Location: mm/page_alloc.c:6185
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
c15bde3c-c15bdeb8: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c000000000eecb10)
Location: mm/page_alloc.c:6185
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
c000000000eecb10-c000000000eecb9c: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe0000472f6)
Location: mm/page_alloc.c:6185
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffe0000472f6-ffffffe000047360: init_currently_empty_zone (STB_GLOBAL)
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
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a6bdf3)
Location: mm/page_alloc.c:6185
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81a6bdf3-ffffffff81a6be5b: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a2833a)
Location: mm/page_alloc.c:6185
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81a2833a-ffffffff81a283a2: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ad8203)
Location: mm/page_alloc.c:6185
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81ad8203-ffffffff81ad826b: init_currently_empty_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void init_currently_empty_zone(struct zone *zone, long unsigned int zone_start_pfn, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ae46be)
Location: mm/page_alloc.c:6185
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81ae46be-ffffffff81ae4726: init_currently_empty_zone (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
