# Function: <code>buddy_order</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128bae8)
Location: mm/internal.h:280
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/page_alloc.c (ffffffff812c01f7)
Location: mm/internal.h:280
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/shuffle.c (ffffffff81c3eafd)
Location: mm/internal.h:280
Inline: True
```
```
In mm/page_isolation.c (ffffffff8130fe87)
Location: mm/internal.h:280
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/page_reporting.c (ffffffff81318e59)
Location: mm/internal.h:280
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812908df)
Location: mm/internal.h:285
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/page_alloc.c (ffffffff812c596d)
Location: mm/internal.h:285
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/shuffle.c (ffffffff81c30bcc)
Location: mm/internal.h:285
Inline: True
```
```
In mm/page_isolation.c (ffffffff81315f6f)
Location: mm/internal.h:285
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/page_reporting.c (ffffffff8131f046)
Location: mm/internal.h:285
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812d0ac8)
Location: mm/internal.h:293
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/page_alloc.c (ffffffff8130a08e)
Location: mm/internal.h:293
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/shuffle.c (ffffffff81d4f4f3)
Location: mm/internal.h:293
Inline: True
```
```
In mm/page_isolation.c (ffffffff8136205b)
Location: mm/internal.h:293
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/page_reporting.c (ffffffff8136c416)
Location: mm/internal.h:293
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8132f18e)
Location: mm/internal.h:237
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/page_alloc.c (ffffffff8137290c)
Location: mm/internal.h:237
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/shuffle.c (ffffffff81f1f451)
Location: mm/internal.h:237
Inline: True
```
```
In mm/page_isolation.c (ffffffff813deae0)
Location: mm/internal.h:237
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/page_reporting.c (ffffffff813ea714)
Location: mm/internal.h:237
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813a5ffd)
Location: mm/internal.h:239
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/page_alloc.c (ffffffff813f007c)
Location: mm/internal.h:239
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/shuffle.c (ffffffff820c866d)
Location: mm/internal.h:239
Inline: True
```
```
In mm/page_isolation.c (ffffffff814657a0)
Location: mm/internal.h:239
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/page_reporting.c (ffffffff814728a4)
Location: mm/internal.h:239
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813d95ca)
Location: mm/internal.h:253
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/page_alloc.c (ffffffff81423bf9)
Location: mm/internal.h:253
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/shuffle.c (ffffffff8214c8ed)
Location: mm/internal.h:253
Inline: True
```
```
In mm/page_isolation.c (ffffffff8149b22b)
Location: mm/internal.h:253
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/page_reporting.c (ffffffff814a7014)
Location: mm/internal.h:253
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff814031ab)
Location: mm/internal.h:270
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/page_alloc.c (ffffffff81450b36)
Location: mm/internal.h:270
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/shuffle.c (ffffffff8222f3fd)
Location: mm/internal.h:270
Inline: True
```
```
In mm/page_isolation.c (ffffffff814ca90b)
Location: mm/internal.h:270
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/page_reporting.c (ffffffff814d8014)
Location: mm/internal.h:270
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
