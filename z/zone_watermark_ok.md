# Function: <code>zone_watermark_ok</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81192dd0)
Location: mm/page_alloc.c:2421
Inline: True
Inline callers:
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:compact_zone
  - mm/compaction.c:__compact_pgdat
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff81192dd0-ffffffff81192df4: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811aac10)
Location: mm/page_alloc.c:2781
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:__compact_pgdat
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff811aa2d0-ffffffff811aa2f3: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811ba0b3)
Location: mm/page_alloc.c:2832
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff811ba800-ffffffff811ba823: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c1eee)
Location: mm/page_alloc.c:3015
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
```
**Symbols:**

```
ffffffff811c2840-ffffffff811c2863: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d646f)
Location: mm/page_alloc.c:3083
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
```
**Symbols:**

```
ffffffff811d7650-ffffffff811d7673: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f786d)
Location: mm/page_alloc.c:3187
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
```
**Symbols:**

```
ffffffff811f89a0-ffffffff811f89c3: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81209d24)
Location: mm/page_alloc.c:3300
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
```
**Symbols:**

```
ffffffff8120af20-ffffffff8120af43: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81270ef9)
Location: mm/page_alloc.c:3465
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
```
**Symbols:**

```
ffffffff812711b0-ffffffff812711d3: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127fd3c)
Location: mm/page_alloc.c:3456
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
```
**Symbols:**

```
ffffffff8127fff0-ffffffff81280013: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b23d0)
Location: mm/page_alloc.c:3566
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/page_reporting.c:page_reporting_process_zone
```
**Symbols:**

```
ffffffff812b2850-ffffffff812b2873: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bdd48)
Location: mm/page_alloc.c:3690
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/page_reporting.c:page_reporting_process_zone
```
**Symbols:**

```
ffffffff812be3c0-ffffffff812be3e3: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c2fb5)
Location: mm/page_alloc.c:3740
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff812c3450-ffffffff812c3471: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81306c7e)
Location: mm/page_alloc.c:3911
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/migrate.c:migrate_misplaced_page
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff813071c0-ffffffff813071e1: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8136ee37)
Location: mm/page_alloc.c:3947
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/migrate.c:numamigrate_isolate_page
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff8136f4c0-ffffffff8136f4f3: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813eb38a)
Location: mm/page_alloc.c:4032
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - kernel/sched/fair.c:should_numa_migrate_memory
  - mm/compaction.c:__compaction_suitable
  - mm/migrate.c:numamigrate_isolate_page
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff813eba50-ffffffff813eba83: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8142030b)
Location: mm/page_alloc.c:2964
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - kernel/sched/fair.c:should_numa_migrate_memory
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/migrate.c:numamigrate_isolate_page
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff81420a60-ffffffff81420a93: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144d03f)
Location: mm/page_alloc.c:3035
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
Direct callers:
  - kernel/sched/fair.c:should_numa_migrate_memory
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:should_abort_scan
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/migrate.c:migrate_misplaced_folio
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff8144d820-ffffffff8144d853: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010317a5c)
Location: mm/page_alloc.c:3456
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
```
**Symbols:**

```
ffff800010317e20-ffff800010317e88: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0532350)
Location: mm/page_alloc.c:3456
Inline: True
Inline callers:
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
```
**Symbols:**

```
c05323c0-c05323f8: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e9fa0)
Location: mm/page_alloc.c:3456
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
```
**Symbols:**

```
c0000000003ea3d0-c0000000003ea3f4: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021dca0)
Location: mm/page_alloc.c:3456
Inline: True
Inline callers:
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
```
**Symbols:**

```
ffffffe00021dcf6-ffffffe00021dd4c: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127838c)
Location: mm/page_alloc.c:3456
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
```
**Symbols:**

```
ffffffff81278640-ffffffff81278663: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126a27c)
Location: mm/page_alloc.c:3456
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
```
**Symbols:**

```
ffffffff8126a530-ffffffff8126a553: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127612c)
Location: mm/page_alloc.c:3456
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
```
**Symbols:**

```
ffffffff812763e0-ffffffff81276403: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81285d0c)
Location: mm/page_alloc.c:3456
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
```
**Symbols:**

```
ffffffff81285fa0-ffffffff81285fc3: zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int alloc_flags</code> ➡️ <code>unsigned int alloc_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int highest_zoneidx</code>
</li>
<li>
<b>Param removed. </b>
<code>int classzone_idx</code>
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
