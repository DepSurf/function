# Function: <code>set_pfnblock_flags_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81195380)
Location: mm/page_alloc.c:6463
Inline: False
Direct callers:
  - mm/page_alloc.c:set_pageblock_migratetype
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:update_pageblock_skip
```
**Symbols:**

```
ffffffff81195380-ffffffff811953fe: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a7fb0)
Location: mm/page_alloc.c:415
Inline: False
Direct callers:
  - mm/page_alloc.c:set_pageblock_migratetype
  - mm/compaction.c:update_pageblock_skip
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffffffff811a7fb0-ffffffff811a8033: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b8380)
Location: mm/page_alloc.c:420
Inline: False
Direct callers:
  - mm/page_alloc.c:set_pageblock_migratetype
  - mm/compaction.c:update_pageblock_skip
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffffffff811b8380-ffffffff811b8403: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c01e0)
Location: mm/page_alloc.c:436
Inline: False
Direct callers:
  - mm/page_alloc.c:set_pageblock_migratetype
  - mm/compaction.c:update_pageblock_skip
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffffffff811c01e0-ffffffff811c025b: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d4cb0)
Location: mm/page_alloc.c:451
Inline: False
Direct callers:
  - mm/page_alloc.c:set_pageblock_migratetype
  - mm/compaction.c:update_pageblock_skip
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffffffff811d4cb0-ffffffff811d4d34: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f60d0)
Location: mm/page_alloc.c:412
Inline: False
Direct callers:
  - mm/page_alloc.c:set_pageblock_migratetype
  - mm/compaction.c:update_pageblock_skip
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffffffff811f60d0-ffffffff811f615c: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812083a0)
Location: mm/page_alloc.c:456
Inline: False
Direct callers:
  - mm/page_alloc.c:set_pageblock_migratetype
  - mm/compaction.c:update_pageblock_skip
  - mm/compaction.c:__reset_isolation_suitable
```
**Symbols:**

```
ffffffff812083a0-ffffffff81208428: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126e790)
Location: mm/page_alloc.c:518
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:set_pageblock_migratetype
```
**Symbols:**

```
ffffffff8126e790-ffffffff8126e814: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127d5d0)
Location: mm/page_alloc.c:505
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:set_pageblock_migratetype
```
**Symbols:**

```
ffffffff8127d5d0-ffffffff8127d654: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812af5b0)
Location: mm/page_alloc.c:504
Inline: False
Direct callers:
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:steal_suitable_fallback
```
**Symbols:**

```
ffffffff812af5b0-ffffffff812af639: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bb200)
Location: mm/page_alloc.c:506
Inline: False
Direct callers:
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:steal_suitable_fallback
```
**Symbols:**

```
ffffffff812bb200-ffffffff812bb27f: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c0350)
Location: mm/page_alloc.c:528
Inline: False
Direct callers:
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:steal_suitable_fallback
```
**Symbols:**

```
ffffffff812c0350-ffffffff812c03cf: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813030e0)
Location: mm/page_alloc.c:531
Inline: False
Direct callers:
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:steal_suitable_fallback
```
**Symbols:**

```
ffffffff813030e0-ffffffff8130315f: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8136aa70)
Location: mm/page_alloc.c:521
Inline: False
Direct callers:
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:steal_suitable_fallback
```
**Symbols:**

```
ffffffff8136aa70-ffffffff8136ab1d: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e6da0)
Location: mm/page_alloc.c:582
Inline: False
Direct callers:
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:__init_zone_device_page
  - mm/page_alloc.c:memmap_init_range
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:steal_suitable_fallback
```
**Symbols:**

```
ffffffff813e6da0-ffffffff813e6e4a: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8141bf00)
Location: mm/page_alloc.c:423
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:steal_suitable_fallback
```
**Symbols:**

```
ffffffff8141bf00-ffffffff8141bfaa: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81448a70)
Location: mm/page_alloc.c:405
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:steal_suitable_fallback
```
**Symbols:**

```
ffffffff81448a70-ffffffff81448b1a: set_pfnblock_flags_mask (STB_GLOBAL)
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
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010314ea0)
Location: mm/page_alloc.c:505
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:set_pageblock_migratetype
```
**Symbols:**

```
ffff800010314ea0-ffff800010314f6c: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c052f7e0)
Location: mm/page_alloc.c:505
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:set_pageblock_migratetype
```
**Symbols:**

```
c052f7e0-c052f884: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e6ba0)
Location: mm/page_alloc.c:505
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:set_pageblock_migratetype
```
**Symbols:**

```
c0000000003e6ba0-c0000000003e6c94: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021b9a2)
Location: mm/page_alloc.c:505
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:set_pageblock_migratetype
```
**Symbols:**

```
ffffffe00021b9a2-ffffffe00021ba46: set_pfnblock_flags_mask (STB_GLOBAL)
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
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81275c20)
Location: mm/page_alloc.c:505
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:set_pageblock_migratetype
```
**Symbols:**

```
ffffffff81275c20-ffffffff81275ca4: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81267b70)
Location: mm/page_alloc.c:505
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:set_pageblock_migratetype
```
**Symbols:**

```
ffffffff81267b70-ffffffff81267bf4: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812739c0)
Location: mm/page_alloc.c:505
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:set_pageblock_migratetype
```
**Symbols:**

```
ffffffff812739c0-ffffffff81273a44: set_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_pfnblock_flags_mask(struct page *page, long unsigned int flags, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812834c0)
Location: mm/page_alloc.c:505
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:set_pageblock_migratetype
```
**Symbols:**

```
ffffffff812834c0-ffffffff81283544: set_pfnblock_flags_mask (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int end_bitidx</code>
</li>
<li>
<b>Param reordered. </b>
<code>page, flags, pfn, end_bitidx, mask</code> ➡️ <code>page, flags, pfn, mask</code>
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
