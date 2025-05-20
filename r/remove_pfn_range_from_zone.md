# Function: <code>remove_pfn_range_from_zone</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void remove_pfn_range_from_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ac8c00)
Location: mm/memory_hotplug.c:470
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81ac8c00-ffffffff81ac900d: remove_pfn_range_from_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void remove_pfn_range_from_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81bc15f0)
Location: mm/memory_hotplug.c:472
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81bc15f0-ffffffff81bc1725: remove_pfn_range_from_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void remove_pfn_range_from_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c3a5f0)
Location: mm/memory_hotplug.c:472
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memremap.c:pageunmap_range
```
**Symbols:**

```
ffffffff81c3a5f0-ffffffff81c3a728: remove_pfn_range_from_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void remove_pfn_range_from_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c2cbd0)
Location: mm/memory_hotplug.c:514
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81c2cbd0-ffffffff81c2cd08: remove_pfn_range_from_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void remove_pfn_range_from_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81d4b340)
Location: mm/memory_hotplug.c:461
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81d4b340-ffffffff81d4b625: remove_pfn_range_from_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void remove_pfn_range_from_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81f1ac00)
Location: mm/memory_hotplug.c:472
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81f1ac00-ffffffff81f1aefe: remove_pfn_range_from_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void remove_pfn_range_from_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff820c2ac0)
Location: mm/memory_hotplug.c:460
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff820c2ac0-ffffffff820c2dbe: remove_pfn_range_from_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void remove_pfn_range_from_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff82146860)
Location: mm/memory_hotplug.c:459
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff82146860-ffffffff82146b5f: remove_pfn_range_from_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void remove_pfn_range_from_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff82228ff0)
Location: mm/memory_hotplug.c:527
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff82228ff0-ffffffff822292ef: remove_pfn_range_from_zone (STB_GLOBAL)
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
void remove_pfn_range_from_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffff800010d9c7c0)
Location: mm/memory_hotplug.c:470
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffff800010d9c7c0-ffff800010d9cc24: remove_pfn_range_from_zone (STB_GLOBAL)
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
void remove_pfn_range_from_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042f610)
Location: mm/memory_hotplug.c:470
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
c00000000042f610-c00000000042fad0: remove_pfn_range_from_zone (STB_GLOBAL)
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
void remove_pfn_range_from_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a67a70)
Location: mm/memory_hotplug.c:470
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81a67a70-ffffffff81a67e7d: remove_pfn_range_from_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void remove_pfn_range_from_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a24530)
Location: mm/memory_hotplug.c:470
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81a24530-ffffffff81a2493d: remove_pfn_range_from_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void remove_pfn_range_from_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ad3e80)
Location: mm/memory_hotplug.c:470
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81ad3e80-ffffffff81ad428d: remove_pfn_range_from_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void remove_pfn_range_from_zone(struct zone *zone, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ae0360)
Location: mm/memory_hotplug.c:470
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81ae0360-ffffffff81ae0764: remove_pfn_range_from_zone (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
