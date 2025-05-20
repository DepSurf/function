# Function: <code>__zone_watermark_ok</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, int alloc_flags, long int free_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811917c0)
Location: mm/page_alloc.c:2353
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff811917c0-ffffffff811918db: __zone_watermark_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a9330)
Location: mm/page_alloc.c:2713
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
```
**Symbols:**

```
ffffffff811a9330-ffffffff811a947e: __zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b98b0)
Location: mm/page_alloc.c:2764
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
```
**Symbols:**

```
ffffffff811b98b0-ffffffff811b99fe: __zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c1910)
Location: mm/page_alloc.c:2947
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
```
**Symbols:**

```
ffffffff811c1910-ffffffff811c1a36: __zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d5e20)
Location: mm/page_alloc.c:3004
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
```
**Symbols:**

```
ffffffff811d5e20-ffffffff811d5f6e: __zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f7250)
Location: mm/page_alloc.c:3108
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
  - mm/compaction.c:__compaction_suitable
```
**Symbols:**

```
ffffffff811f7250-ffffffff811f739e: __zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81209670)
Location: mm/page_alloc.c:3221
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
  - mm/compaction.c:__compaction_suitable
```
**Symbols:**

```
ffffffff81209670-ffffffff812097be: __zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81270980)
Location: mm/page_alloc.c:3386
Inline: False
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
```
**Symbols:**

```
ffffffff81270980-ffffffff81270ace: __zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127f7c0)
Location: mm/page_alloc.c:3377
Inline: False
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
```
**Symbols:**

```
ffffffff8127f7c0-ffffffff8127f90e: __zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b1eec)
Location: mm/page_alloc.c:3488
Inline: True
Inline callers:
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
```
**Symbols:**

```
ffffffff812b2070-ffffffff812b2190: __zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bd8b7)
Location: mm/page_alloc.c:3626
Inline: True
Inline callers:
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
```
**Symbols:**

```
ffffffff812bda30-ffffffff812bdb60: __zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c4631)
Location: mm/page_alloc.c:3676
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
```
**Symbols:**

```
ffffffff812c29e0-ffffffff812c2b1f: __zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff81308527)
Location: mm/page_alloc.c:3847
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
```
**Symbols:**

```
ffffffff81cbd8bb-ffffffff81cbd8eb: __zone_watermark_ok.cold (STB_LOCAL)
ffffffff813065a0-ffffffff81306776: __zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff813708ba)
Location: mm/page_alloc.c:3883
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
```
**Symbols:**

```
ffffffff81e6f7dd-ffffffff81e6f80d: __zone_watermark_ok.cold (STB_LOCAL)
ffffffff8136e790-ffffffff8136e990: __zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff813ecd3a)
Location: mm/page_alloc.c:3968
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
```
**Symbols:**

```
ffffffff82065587-ffffffff820655b7: __zone_watermark_ok.cold (STB_LOCAL)
ffffffff813eac90-ffffffff813eae90: __zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff81421c8c)
Location: mm/page_alloc.c:2886
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
```
**Symbols:**

```
ffffffff820e4d87-ffffffff820e4daf: __zone_watermark_ok.cold (STB_LOCAL)
ffffffff8141fbf0-ffffffff8141fdf8: __zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int highest_zoneidx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff8144eabc)
Location: mm/page_alloc.c:2957
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
```
**Symbols:**

```
ffffffff821c1a56-ffffffff821c1a7e: __zone_watermark_ok.cold (STB_LOCAL)
ffffffff8144c810-ffffffff8144ca18: __zone_watermark_ok (STB_GLOBAL)
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
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff8000103174d0)
Location: mm/page_alloc.c:3377
Inline: False
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
```
**Symbols:**

```
ffff8000103174d0-ffff80001031765c: __zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0531ba4)
Location: mm/page_alloc.c:3377
Inline: False
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
```
**Symbols:**

```
c0531ba4-c0531cdc: __zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e98e0)
Location: mm/page_alloc.c:3377
Inline: False
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
```
**Symbols:**

```
c0000000003e98e0-c0000000003e9a58: __zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021d692)
Location: mm/page_alloc.c:3377
Inline: False
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
```
**Symbols:**

```
ffffffe00021d692-ffffffe00021d7c0: __zone_watermark_ok (STB_GLOBAL)
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
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81277e10)
Location: mm/page_alloc.c:3377
Inline: False
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
```
**Symbols:**

```
ffffffff81277e10-ffffffff81277f5e: __zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81269d00)
Location: mm/page_alloc.c:3377
Inline: False
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
```
**Symbols:**

```
ffffffff81269d00-ffffffff81269e4e: __zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81275bb0)
Location: mm/page_alloc.c:3377
Inline: False
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
```
**Symbols:**

```
ffffffff81275bb0-ffffffff81275cfe: __zone_watermark_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __zone_watermark_ok(struct zone *z, unsigned int order, long unsigned int mark, int classzone_idx, unsigned int alloc_flags, long int free_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81285790)
Location: mm/page_alloc.c:3377
Inline: False
Direct callers:
  - mm/compaction.c:__compaction_suitable
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
```
**Symbols:**

```
ffffffff81285790-ffffffff812858de: __zone_watermark_ok (STB_GLOBAL)
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
