# Function: <code>compact_zone_order</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum migrate_mode mode, int *contended, int alloc_flags, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811b7d10)
Location: mm/compaction.c:1486
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff811b7d10-ffffffff811b7daa: compact_zone_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811d1830)
Location: mm/compaction.c:1625
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff811d1830-ffffffff811d18c5: compact_zone_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811e1840)
Location: mm/compaction.c:1640
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff811e1840-ffffffff811e18e7: compact_zone_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811eb5c0)
Location: mm/compaction.c:1676
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff811eb5c0-ffffffff811eb683: compact_zone_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81201940)
Location: mm/compaction.c:1700
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff81201940-ffffffff81201a03: compact_zone_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81222d40)
Location: mm/compaction.c:1700
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff81222d40-ffffffff81222df2: compact_zone_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81235d90)
Location: mm/compaction.c:1701
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff81235d90-ffffffff81235e42: compact_zone_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int classzone_idx, struct page **capture);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81247220)
Location: mm/compaction.c:2277
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff81247220-ffffffff81247331: compact_zone_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int classzone_idx, struct page **capture);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81255700)
Location: mm/compaction.c:2288
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff81255700-ffffffff812557f8: compact_zone_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int highest_zoneidx, struct page **capture);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81283ec0)
Location: mm/compaction.c:2294
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff81283ec0-ffffffff81283f9c: compact_zone_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int highest_zoneidx, struct page **capture);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128df20)
Location: mm/compaction.c:2448
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff8128df20-ffffffff8128dffc: compact_zone_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int highest_zoneidx, struct page **capture);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81293560)
Location: mm/compaction.c:2488
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff81293560-ffffffff8129365b: compact_zone_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int highest_zoneidx, struct page **capture);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812d39c0)
Location: mm/compaction.c:2480
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff812d39c0-ffffffff812d3abb: compact_zone_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int highest_zoneidx, struct page **capture);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81332850)
Location: mm/compaction.c:2500
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff81332850-ffffffff81332963: compact_zone_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int highest_zoneidx, struct page **capture);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813a9540)
Location: mm/compaction.c:2499
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff813a9540-ffffffff813a9653: compact_zone_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int highest_zoneidx, struct page **capture);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813dc810)
Location: mm/compaction.c:2589
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff813dc810-ffffffff813dc923: compact_zone_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int highest_zoneidx, struct page **capture);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81406760)
Location: mm/compaction.c:2657
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff81406760-ffffffff81406873: compact_zone_order (STB_LOCAL)
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
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int classzone_idx, struct page **capture);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffff8000102ecbb8)
Location: mm/compaction.c:2288
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffff8000102ecbb8-ffff8000102eccbc: compact_zone_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0511508)
Location: mm/compaction.c:2288
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int classzone_idx, struct page **capture);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0000000003b06a0)
Location: mm/compaction.c:2288
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
c0000000003b06a0-c0000000003b07ec: compact_zone_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int classzone_idx, struct page **capture);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffe0002013d2)
Location: mm/compaction.c:2288
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffe0002013d2-ffffffe000201494: compact_zone_order (STB_LOCAL)
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
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int classzone_idx, struct page **capture);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124dd50)
Location: mm/compaction.c:2288
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff8124dd50-ffffffff8124de48: compact_zone_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int classzone_idx, struct page **capture);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81240cf0)
Location: mm/compaction.c:2288
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff81240cf0-ffffffff81240de8: compact_zone_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int classzone_idx, struct page **capture);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124baf0)
Location: mm/compaction.c:2288
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff8124baf0-ffffffff8124bbe8: compact_zone_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum compact_result compact_zone_order(struct zone *zone, int order, gfp_t gfp_mask, enum compact_priority prio, unsigned int alloc_flags, int classzone_idx, struct page **capture);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8125b400)
Location: mm/compaction.c:2288
Inline: False
Direct callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
ffffffff8125b400-ffffffff8125b4f8: compact_zone_order (STB_LOCAL)
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
<b>Param added. </b>
<code>enum compact_priority prio</code>
</li>
<li>
<b>Param removed. </b>
<code>enum migrate_mode mode</code>
</li>
<li>
<b>Param removed. </b>
<code>int *contended</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone, order, gfp_mask, mode, contended, alloc_flags, classzone_idx</code> ➡️ <code>zone, order, gfp_mask, prio, alloc_flags, classzone_idx</code>
</li>
<li>
<b>Param type changed. </b>
<code>int alloc_flags</code> ➡️ <code>unsigned int alloc_flags</code>
</li>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>enum compact_result</code>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct page **capture</code>
</li>
</ul>
</details>
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
