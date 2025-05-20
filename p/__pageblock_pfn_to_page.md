# Function: <code>__pageblock_pfn_to_page</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a8100)
Location: mm/page_alloc.c:1334
Inline: False
Direct callers:
  - mm/page_alloc.c:set_zone_contiguous
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff811a8100-ffffffff811a81e9: __pageblock_pfn_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b84d0)
Location: mm/page_alloc.c:1350
Inline: False
Direct callers:
  - mm/page_alloc.c:set_zone_contiguous
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff811b84d0-ffffffff811b85b6: __pageblock_pfn_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c0320)
Location: mm/page_alloc.c:1357
Inline: False
Direct callers:
  - mm/page_alloc.c:set_zone_contiguous
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff811c0320-ffffffff811c0411: __pageblock_pfn_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d4e00)
Location: mm/page_alloc.c:1373
Inline: False
Direct callers:
  - mm/page_alloc.c:set_zone_contiguous
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff811d4e00-ffffffff811d4ef9: __pageblock_pfn_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f6220)
Location: mm/page_alloc.c:1354
Inline: False
Direct callers:
  - mm/page_alloc.c:set_zone_contiguous
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff811f6220-ffffffff811f6318: __pageblock_pfn_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812084f0)
Location: mm/page_alloc.c:1405
Inline: False
Direct callers:
  - mm/page_alloc.c:set_zone_contiguous
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff812084f0-ffffffff812085f3: __pageblock_pfn_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126e8e0)
Location: mm/page_alloc.c:1515
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
  - mm/page_alloc.c:set_zone_contiguous
```
**Symbols:**

```
ffffffff8126e8e0-ffffffff8126ea5d: __pageblock_pfn_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127d720)
Location: mm/page_alloc.c:1502
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
  - mm/page_alloc.c:set_zone_contiguous
```
**Symbols:**

```
ffffffff8127d720-ffffffff8127d89d: __pageblock_pfn_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812af800)
Location: mm/page_alloc.c:1561
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
  - mm/page_alloc.c:set_zone_contiguous
```
**Symbols:**

```
ffffffff812af800-ffffffff812af9b8: __pageblock_pfn_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bb470)
Location: mm/page_alloc.c:1644
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
  - mm/page_alloc.c:set_zone_contiguous
```
**Symbols:**

```
ffffffff812bb470-ffffffff812bb628: __pageblock_pfn_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c05f0)
Location: mm/page_alloc.c:1679
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
  - mm/page_alloc.c:set_zone_contiguous
```
**Symbols:**

```
ffffffff812c05f0-ffffffff812c0677: __pageblock_pfn_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81303420)
Location: mm/page_alloc.c:1763
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
  - mm/page_alloc.c:set_zone_contiguous
```
**Symbols:**

```
ffffffff81303420-ffffffff813034f8: __pageblock_pfn_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8136b1a0)
Location: mm/page_alloc.c:1746
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
  - mm/page_alloc.c:set_zone_contiguous
```
**Symbols:**

```
ffffffff8136b1a0-ffffffff8136b3b9: __pageblock_pfn_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e74b0)
Location: mm/page_alloc.c:1831
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
  - mm/page_alloc.c:set_zone_contiguous
```
**Symbols:**

```
ffffffff813e74b0-ffffffff813e76b7: __pageblock_pfn_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8141c730)
Location: mm/page_alloc.c:1381
Inline: False
Direct callers:
  - mm/mm_init.c:set_zone_contiguous
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff8141c730-ffffffff8141c87d: __pageblock_pfn_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff814491d0)
Location: mm/page_alloc.c:1344
Inline: False
Direct callers:
  - mm/mm_init.c:set_zone_contiguous
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff814491d0-ffffffff81449377: __pageblock_pfn_to_page (STB_GLOBAL)
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
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010315068)
Location: mm/page_alloc.c:1502
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
  - mm/page_alloc.c:set_zone_contiguous
```
**Symbols:**

```
ffff800010315068-ffff80001031515c: __pageblock_pfn_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c052f97c)
Location: mm/page_alloc.c:1502
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
  - mm/page_alloc.c:set_zone_contiguous
```
**Symbols:**

```
c052f97c-c052fa30: __pageblock_pfn_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e6d80)
Location: mm/page_alloc.c:1502
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
  - mm/page_alloc.c:set_zone_contiguous
```
**Symbols:**

```
c0000000003e6d80-c0000000003e6ed8: __pageblock_pfn_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021bb10)
Location: mm/page_alloc.c:1502
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
  - mm/page_alloc.c:set_zone_contiguous
```
**Symbols:**

```
ffffffe00021bb10-ffffffe00021bc1e: __pageblock_pfn_to_page (STB_GLOBAL)
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
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81275d70)
Location: mm/page_alloc.c:1502
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
  - mm/page_alloc.c:set_zone_contiguous
```
**Symbols:**

```
ffffffff81275d70-ffffffff81275eed: __pageblock_pfn_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81267cc0)
Location: mm/page_alloc.c:1502
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
  - mm/page_alloc.c:set_zone_contiguous
```
**Symbols:**

```
ffffffff81267cc0-ffffffff81267e3d: __pageblock_pfn_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81273b10)
Location: mm/page_alloc.c:1502
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
  - mm/page_alloc.c:set_zone_contiguous
```
**Symbols:**

```
ffffffff81273b10-ffffffff81273c8d: __pageblock_pfn_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *__pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81283610)
Location: mm/page_alloc.c:1502
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:isolate_freepages_range
  - mm/page_alloc.c:set_zone_contiguous
```
**Symbols:**

```
ffffffff81283610-ffffffff8128378d: __pageblock_pfn_to_page (STB_GLOBAL)
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
