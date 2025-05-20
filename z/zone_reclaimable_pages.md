# Function: <code>zone_reclaimable_pages</code>

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
In mm/vmscan.c (ffffffff811a03c5)
Location: mm/vmscan.c:195
Inline: True
Inline callers:
  - mm/vmscan.c:pfmemalloc_watermark_ok
  - mm/vmscan.c:zone_reclaimable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b7ee0)
Location: mm/vmscan.c:202
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/compaction.c:compaction_zonelist_suitable
```
**Symbols:**

```
ffffffff811b7ee0-ffffffff811b8072: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811c8540)
Location: mm/vmscan.c:202
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/compaction.c:compaction_zonelist_suitable
```
**Symbols:**

```
ffffffff811c8540-ffffffff811c86d0: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811d0f30)
Location: mm/vmscan.c:209
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/compaction.c:compaction_zonelist_suitable
```
**Symbols:**

```
ffffffff811d0f30-ffffffff811d10bb: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e6420)
Location: mm/vmscan.c:210
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/compaction.c:compaction_zonelist_suitable
```
**Symbols:**

```
ffffffff811e6420-ffffffff811e658a: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812079d0)
Location: mm/vmscan.c:255
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/compaction.c:compaction_zonelist_suitable
```
**Symbols:**

```
ffffffff812079d0-ffffffff81207b4a: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8121a550)
Location: mm/vmscan.c:324
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/compaction.c:compaction_zonelist_suitable
```
**Symbols:**

```
ffffffff8121a550-ffffffff8121a6ca: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81229dc0)
Location: mm/vmscan.c:336
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff81229dc0-ffffffff81229f20: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81237c40)
Location: mm/vmscan.c:333
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff81237c40-ffffffff81237da0: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81266c60)
Location: mm/vmscan.c:301
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
**Symbols:**

```
ffffffff81266c60-ffffffff81266dc1: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812716b0)
Location: mm/vmscan.c:294
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
**Symbols:**

```
ffffffff812716b0-ffffffff81271811: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812769b0)
Location: mm/vmscan.c:526
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
**Symbols:**

```
ffffffff812769b0-ffffffff81276b06: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:572
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
**Symbols:**

```
ffffffff81cba7ce-ffffffff81cba7e3: zone_reclaimable_pages.cold (STB_LOCAL)
ffffffff812b41c0-ffffffff812b441f: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:569
Inline: False
Direct callers:
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:reclaim_throttle
  - mm/compaction.c:compaction_zonelist_suitable
```
**Symbols:**

```
ffffffff81e6c0ac-ffffffff81e6c0c1: zone_reclaimable_pages.cold (STB_LOCAL)
ffffffff81310180-ffffffff813103d0: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:583
Inline: False
Direct callers:
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:reclaim_throttle
  - mm/compaction.c:compaction_zonelist_suitable
```
**Symbols:**

```
ffffffff82062b88-ffffffff82062b9c: zone_reclaimable_pages.cold (STB_LOCAL)
ffffffff813837a0-ffffffff81383a17: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:635
Inline: False
Direct callers:
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:reclaim_throttle
  - mm/compaction.c:compaction_zonelist_suitable
```
**Symbols:**

```
ffffffff820e2300-ffffffff820e2314: zone_reclaimable_pages.cold (STB_LOCAL)
ffffffff813b51b0-ffffffff813b5427: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:341
Inline: False
Direct callers:
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:reclaim_throttle
  - mm/compaction.c:compaction_zonelist_suitable
```
**Symbols:**

```
ffffffff821bece5-ffffffff821becf9: zone_reclaimable_pages.cold (STB_LOCAL)
ffffffff813de1a0-ffffffff813de417: zone_reclaimable_pages (STB_GLOBAL)
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
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102c8938)
Location: mm/vmscan.c:333
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffff8000102c8938-ffff8000102c8ad0: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f2bf4)
Location: mm/vmscan.c:333
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
c04f2bf4-c04f2d64: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000384a70)
Location: mm/vmscan.c:333
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
c000000000384a70-c000000000384cb0: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e7ee2)
Location: mm/vmscan.c:333
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffe0001e7ee2-ffffffe0001e806e: zone_reclaimable_pages (STB_GLOBAL)
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
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81230290)
Location: mm/vmscan.c:333
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff81230290-ffffffff812303f0: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81223350)
Location: mm/vmscan.c:333
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff81223350-ffffffff812234b0: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122e030)
Location: mm/vmscan.c:333
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff8122e030-ffffffff8122e190: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int zone_reclaimable_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123d430)
Location: mm/vmscan.c:333
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff8123d430-ffffffff8123d590: zone_reclaimable_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
