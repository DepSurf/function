# Function: <code>page_order</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/internal.h:102
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:102
Inline: True
```
```
In mm/page_alloc.c (ffffffff811929d7)
Location: mm/internal.h:238
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In mm/memory_hotplug.c (0)
Location: mm/internal.h:238
Inline: True
```
```
In mm/page_isolation.c (ffffffff81203b85)
Location: mm/internal.h:238
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/internal.h:110
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:110
Inline: True
```
```
In mm/page_alloc.c (ffffffff811acbed)
Location: mm/internal.h:210
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/compaction.c (0)
Location: mm/internal.h:210
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: mm/internal.h:210
Inline: True
```
```
In mm/page_isolation.c (ffffffff81228ff8)
Location: mm/internal.h:210
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/internal.h:110
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:110
Inline: True
```
```
In mm/page_alloc.c (ffffffff811bd1ac)
Location: mm/internal.h:213
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/compaction.c (0)
Location: mm/internal.h:213
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: mm/internal.h:213
Inline: True
```
```
In mm/page_isolation.c (ffffffff8123b58d)
Location: mm/internal.h:213
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/internal.h:110
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:110
Inline: True
```
```
In mm/page_alloc.c (ffffffff811c5406)
Location: mm/internal.h:227
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/compaction.c (0)
Location: mm/internal.h:227
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: mm/internal.h:227
Inline: True
```
```
In mm/page_isolation.c (ffffffff812471a8)
Location: mm/internal.h:227
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/internal.h:111
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:111
Inline: True
```
```
In mm/page_alloc.c (ffffffff811da1d4)
Location: mm/internal.h:228
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/compaction.c (0)
Location: mm/internal.h:228
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: mm/internal.h:228
Inline: True
```
```
In mm/page_isolation.c (ffffffff812672eb)
Location: mm/internal.h:228
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/internal.h:111
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:111
Inline: True
```
```
In mm/page_alloc.c (ffffffff811fabf2)
Location: mm/internal.h:228
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/compaction.c (ffffffff81220bb5)
Location: mm/internal.h:228
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff8126c588)
Location: mm/internal.h:228
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (ffffffff8128bbf0)
Location: mm/internal.h:228
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/internal.h:111
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:111
Inline: True
```
```
In mm/page_alloc.c (ffffffff8120d432)
Location: mm/internal.h:228
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/compaction.c (ffffffff81233c09)
Location: mm/internal.h:228
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff81280def)
Location: mm/internal.h:228
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (ffffffff812a0b50)
Location: mm/internal.h:228
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/internal.h:112
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:112
Inline: True
```
```
In mm/compaction.c (ffffffff81244873)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/page_alloc.c (ffffffff81273892)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (0)
Location: mm/internal.h:236
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8129d250)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (ffffffff812bbde4)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/internal.h:112
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:112
Inline: True
```
```
In mm/compaction.c (ffffffff81252d33)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/page_alloc.c (ffffffff81282702)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (0)
Location: mm/internal.h:236
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812aca20)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (ffffffff812cdcc4)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/internal.h:113
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:113
Inline: True
```
```
In mm/compaction.c (ffffffff812819d3)
Location: mm/internal.h:276
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/page_alloc.c (ffffffff812b4868)
Location: mm/internal.h:276
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
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
In mm/shuffle.c (ffffffff81bc5b17)
Location: mm/internal.h:276
Inline: True
```
```
In mm/page_isolation.c (ffffffff81303fbc)
Location: mm/internal.h:276
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/page_reporting.c (ffffffff8130cf00)
Location: mm/internal.h:276
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/internal.h:113
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:113
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
In kernel/events/core.c (0)
Location: kernel/events/internal.h:113
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:113
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
In kernel/events/core.c (0)
Location: kernel/events/internal.h:113
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:113
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
In kernel/events/core.c (0)
Location: kernel/events/internal.h:113
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:113
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
In kernel/events/core.c (0)
Location: kernel/events/internal.h:113
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:113
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
In kernel/events/core.c (0)
Location: kernel/events/internal.h:113
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:113
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
In kernel/events/core.c (0)
Location: kernel/events/internal.h:113
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:113
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/internal.h:112
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:112
Inline: True
```
```
In mm/compaction.c (ffff8000102ea488)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/page_alloc.c (ffff80001031ac90)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/shuffle.c (0)
Location: mm/internal.h:236
Inline: True
```
```
In mm/page_isolation.c (ffff800010372180)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c6b88)
Location: kernel/events/internal.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/events/ring_buffer.c (c04d2cd0)
Location: kernel/events/internal.h:105
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:rb_free_work
  - kernel/events/ring_buffer.c:perf_output_skip
  - kernel/events/ring_buffer.c:perf_output_copy
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/compaction.c (c050da7c)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/page_alloc.c (c0535098)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (c15be000)
Location: mm/internal.h:236
Inline: True
```
```
In mm/page_isolation.c (c055ee8c)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/internal.h:112
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:112
Inline: True
```
```
In mm/compaction.c (c0000000003acecc)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/page_alloc.c (c0000000003ee478)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (c000000000eecda0)
Location: mm/internal.h:236
Inline: True
```
```
In mm/memory_hotplug.c (c00000000042eed0)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (c0000000004639c8)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/internal.h:112
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:112
Inline: True
```
```
In mm/compaction.c (ffffffe0001fea8c)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/page_alloc.c (ffffffe0002201b6)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffffffe0000474ce)
Location: mm/internal.h:236
Inline: True
```
```
In mm/page_isolation.c (ffffffe00024b3fe)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/internal.h:112
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:112
Inline: True
```
```
In mm/compaction.c (ffffffff8124b383)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/page_alloc.c (ffffffff8127ad52)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (0)
Location: mm/internal.h:236
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812a5000)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (ffffffff812c62a4)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/internal.h:112
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:112
Inline: True
```
```
In mm/compaction.c (ffffffff8123e323)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/page_alloc.c (ffffffff8126cc32)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (0)
Location: mm/internal.h:236
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81296ad0)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (ffffffff812b72e4)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/internal.h:112
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:112
Inline: True
```
```
In mm/compaction.c (ffffffff81249123)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/page_alloc.c (ffffffff81278af2)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (0)
Location: mm/internal.h:236
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812a2e10)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (ffffffff812c40b4)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/internal.h:112
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: kernel/events/internal.h:112
Inline: True
```
```
In mm/compaction.c (ffffffff81258983)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/page_alloc.c (ffffffff812886e2)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (0)
Location: mm/internal.h:236
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812b309b)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
```
```
In mm/page_isolation.c (ffffffff812d4b54)
Location: mm/internal.h:236
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
```
</details>
</li>
</ul>

## Differences
