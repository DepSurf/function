# Function: <code>online_section</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c03ad)
Location: include/linux/mmzone.h:1193
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/vmstat.c (ffffffff811df0f2)
Location: include/linux/mmzone.h:1193
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff811e8c14)
Location: include/linux/mmzone.h:1193
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/page_isolation.c (ffffffff8124702f)
Location: include/linux/mmzone.h:1193
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d4e95)
Location: include/linux/mmzone.h:1206
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/vmstat.c (ffffffff811f4d6a)
Location: include/linux/mmzone.h:1206
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff811ff008)
Location: include/linux/mmzone.h:1206
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/page_isolation.c (ffffffff812671c6)
Location: include/linux/mmzone.h:1206
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f62b5)
Location: include/linux/mmzone.h:1213
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/vmstat.c (ffffffff8121600d)
Location: include/linux/mmzone.h:1213
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff812203fd)
Location: include/linux/mmzone.h:1213
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/page_isolation.c (ffffffff8128ba75)
Location: include/linux/mmzone.h:1213
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In drivers/base/memory.c (ffffffff8169d680)
Location: include/linux/mmzone.h:1213
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_action
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81208590)
Location: include/linux/mmzone.h:1221
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/vmstat.c (ffffffff81228f0d)
Location: include/linux/mmzone.h:1221
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8123337d)
Location: include/linux/mmzone.h:1221
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/page_isolation.c (ffffffff812a09d5)
Location: include/linux/mmzone.h:1221
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In drivers/base/memory.c (ffffffff816bde1e)
Location: include/linux/mmzone.h:1221
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_action
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81100d77)
Location: include/linux/mmzone.h:1294
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/vmstat.c (ffffffff81238be9)
Location: include/linux/mmzone.h:1294
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff81245b94)
Location: include/linux/mmzone.h:1294
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff8126e9e6)
Location: include/linux/mmzone.h:1294
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/page_isolation.c (ffffffff812bbc66)
Location: include/linux/mmzone.h:1294
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In drivers/base/memory.c (ffffffff816f8cc9)
Location: include/linux/mmzone.h:1294
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_action
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff8110d1d7)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/vmstat.c (ffffffff81246ed9)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff81254057)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff8127d826)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff812915e2)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff81ac8d5c)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/memory-failure.c (ffffffff812cbdf0)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812cdb46)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In fs/proc/page.c (ffffffff81381cdd)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/base/memory.c (ffffffff8171caf8)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811183d0)
Location: include/linux/mmzone.h:1278
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/vmstat.c (ffffffff81274743)
Location: include/linux/mmzone.h:1278
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff81280bfa)
Location: include/linux/mmzone.h:1278
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff812ae168)
Location: include/linux/mmzone.h:1278
Inline: True
Inline callers:
  - mm/page_alloc.c:pfn_range_valid_contig
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/shuffle.c (ffffffff81bc5abb)
Location: include/linux/mmzone.h:1278
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812e0ac7)
Location: include/linux/mmzone.h:1278
Inline: True
Inline callers:
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/memory-failure.c (ffffffff8130286e)
Location: include/linux/mmzone.h:1278
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff81303de1)
Location: include/linux/mmzone.h:1278
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/page_idle.c (ffffffff8130920f)
Location: include/linux/mmzone.h:1278
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff813cc2cd)
Location: include/linux/mmzone.h:1278
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
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
In kernel/power/snapshot.c (ffffffff81bdf867)
Location: include/linux/mmzone.h:1316
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/vmstat.c (ffffffff8127ef9d)
Location: include/linux/mmzone.h:1316
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8128af11)
Location: include/linux/mmzone.h:1316
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff812b9bef)
Location: include/linux/mmzone.h:1316
Inline: True
Inline callers:
  - mm/page_alloc.c:pfn_range_valid_contig
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/shuffle.c (ffffffff81c3eaa8)
Location: include/linux/mmzone.h:1316
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812eb993)
Location: include/linux/mmzone.h:1316
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/memory-failure.c (ffffffff8130ebc6)
Location: include/linux/mmzone.h:1316
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff8130fcb8)
Location: include/linux/mmzone.h:1316
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/page_idle.c (ffffffff81315076)
Location: include/linux/mmzone.h:1316
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff813ddf11)
Location: include/linux/mmzone.h:1316
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812c63ce)
Location: include/linux/mmzone.h:1381
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8130aebe)
Location: include/linux/mmzone.h:1418
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81374577)
Location: include/linux/mmzone.h:1464
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813f16c7)
Location: include/linux/mmzone.h:1796
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
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
In mm/compaction.c (ffffffff813dba7f)
Location: include/linux/mmzone.h:1921
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages
```
```
In mm/memory_hotplug.c (ffffffff81425207)
Location: include/linux/mmzone.h:1921
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
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
In mm/compaction.c (ffffffff814059df)
Location: include/linux/mmzone.h:1932
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages
```
```
In mm/memory_hotplug.c (ffffffff81452447)
Location: include/linux/mmzone.h:1932
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102da270)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffff8000102e99f4)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffff8000103150d0)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffff80001032e7a4)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_gigantic_page
```
```
In mm/memory_hotplug.c (ffff800010d9c8b0)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/memory-failure.c (ffff80001036f384)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffff800010371f90)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In fs/proc/page.c (ffff80001044fab8)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/base/memory.c (ffff8000109107fc)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_block_action
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c00000000039aaec)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (c0000000003ae878)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (c0000000003e6e68)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (c0000000004077e0)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (c00000000042f7dc)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/memory-failure.c (c000000000460f78)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (c000000000463800)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In fs/proc/page.c (c000000000567e5c)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/base/memory.c (c0000000009b1668)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811053f7)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/vmstat.c (ffffffff8123f529)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8124c6a7)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff81275e76)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff81289bc2)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff81a67bcc)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/memory-failure.c (ffffffff812c43d0)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812c6126)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In fs/proc/page.c (ffffffff8137a2bd)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/base/memory.c (ffffffff816e2e28)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810f6697)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/vmstat.c (ffffffff81232529)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8123f647)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff81267dc6)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff8127b9f2)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff81a2468c)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/memory-failure.c (ffffffff812b5410)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812b7166)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In fs/proc/page.c (ffffffff8136ad8d)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/base/memory.c (ffffffff816bd468)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811036a7)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/vmstat.c (ffffffff8123d2c9)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8124a447)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff81273c16)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff812879d2)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff81ad3fdc)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/memory-failure.c (ffffffff812c21e0)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812c3f36)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In fs/proc/page.c (ffffffff81377d8d)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/base/memory.c (ffffffff8170ffb8)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff8110ea97)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/vmstat.c (ffffffff8124c9f9)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff81259ca7)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff81283716)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff81297f6f)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff81ae04be)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/memory-failure.c (ffffffff812d2c70)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812d49d6)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In fs/proc/page.c (ffffffff8138b837)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/base/memory.c (ffffffff8172b118)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
</ul>

## Differences
