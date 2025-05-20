# Function: <code>move_freepages_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81192a50)
Location: mm/page_alloc.c:1512
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff81192a50-ffffffff81192b55: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a8360)
Location: mm/page_alloc.c:1871
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__rmqueue
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff811a8360-ffffffff811a8469: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b8730)
Location: mm/page_alloc.c:1890
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__rmqueue
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff811b8730-ffffffff811b8838: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c04e0)
Location: mm/page_alloc.c:1908
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__rmqueue
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff811c04e0-ffffffff811c061c: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d4fc0)
Location: mm/page_alloc.c:1946
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff811d4fc0-ffffffff811d50fc: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f63f0)
Location: mm/page_alloc.c:2055
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff811f63f0-ffffffff811f654f: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812086d0)
Location: mm/page_alloc.c:2095
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff812086d0-ffffffff8120882c: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126eb30)
Location: mm/page_alloc.c:2274
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff8126eb30-ffffffff8126ec81: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127d970)
Location: mm/page_alloc.c:2265
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff8127d970-ffffffff8127dac1: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812afa90)
Location: mm/page_alloc.c:2337
Inline: False
Direct callers:
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:set_migratetype_isolate
```
**Symbols:**

```
ffffffff812afa90-ffffffff812afbe1: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bb730)
Location: mm/page_alloc.c:2415
Inline: False
Direct callers:
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:set_migratetype_isolate
```
**Symbols:**

```
ffffffff812bb730-ffffffff812bb88c: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c0780)
Location: mm/page_alloc.c:2467
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff812c0780-ffffffff812c08e3: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2540
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff81cbd4d1-ffffffff81cbd518: move_freepages_block.cold (STB_LOCAL)
ffffffff81303630-ffffffff8130383e: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2565
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff81e6f4cf-ffffffff81e6f516: move_freepages_block.cold (STB_LOCAL)
ffffffff8136b5a0-ffffffff8136b811: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2644
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff8206528a-ffffffff820652d1: move_freepages_block.cold (STB_LOCAL)
ffffffff813e78e0-ffffffff813e7b4f: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1690
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff820e4a69-ffffffff820e4ab2: move_freepages_block.cold (STB_LOCAL)
ffffffff8141c9c0-ffffffff8141cc2f: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1653
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff821c1704-ffffffff821c174d: move_freepages_block.cold (STB_LOCAL)
ffffffff814494c0-ffffffff8144972c: move_freepages_block (STB_GLOBAL)
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
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010315240)
Location: mm/page_alloc.c:2265
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffff800010315240-ffff8000103153f4: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c052faf8)
Location: mm/page_alloc.c:2265
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
c052faf8-c052fc84: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e7060)
Location: mm/page_alloc.c:2265
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
c0000000003e7060-c0000000003e7258: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021bce0)
Location: mm/page_alloc.c:2265
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffe00021bce0-ffffffe00021be16: move_freepages_block (STB_GLOBAL)
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
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81275fc0)
Location: mm/page_alloc.c:2265
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff81275fc0-ffffffff81276111: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81267f10)
Location: mm/page_alloc.c:2265
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff81267f10-ffffffff81268061: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81273d60)
Location: mm/page_alloc.c:2265
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff81273d60-ffffffff81273eb1: move_freepages_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int move_freepages_block(struct zone *zone, struct page *page, int migratetype, int *num_movable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81283860)
Location: mm/page_alloc.c:2265
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff81283860-ffffffff812839b1: move_freepages_block (STB_GLOBAL)
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
<b>Param added. </b>
<code>int *num_movable</code>
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
