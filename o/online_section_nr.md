# Function: <code>online_section_nr</code>

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
Location: include/linux/mmzone.h:1198
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/vmstat.c (ffffffff811df0d7)
Location: include/linux/mmzone.h:1198
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff811e8bf9)
Location: include/linux/mmzone.h:1198
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/page_isolation.c (ffffffff81247014)
Location: include/linux/mmzone.h:1198
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
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/vmstat.c (ffffffff811f4d47)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff811fefe5)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/page_isolation.c (ffffffff81267185)
Location: include/linux/mmzone.h:1211
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
Location: include/linux/mmzone.h:1218
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/vmstat.c (ffffffff81215ff1)
Location: include/linux/mmzone.h:1218
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff812203e1)
Location: include/linux/mmzone.h:1218
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/page_isolation.c (ffffffff8128ba5c)
Location: include/linux/mmzone.h:1218
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
Location: include/linux/mmzone.h:1218
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
Location: include/linux/mmzone.h:1226
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/vmstat.c (ffffffff81228ef1)
Location: include/linux/mmzone.h:1226
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff81233361)
Location: include/linux/mmzone.h:1226
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/page_isolation.c (ffffffff812a09bc)
Location: include/linux/mmzone.h:1226
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
Location: include/linux/mmzone.h:1226
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
In kernel/power/snapshot.c (ffffffff81100d53)
Location: include/linux/mmzone.h:1299
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/vmstat.c (ffffffff81238bcd)
Location: include/linux/mmzone.h:1299
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff81245b64)
Location: include/linux/mmzone.h:1299
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff8126e9d1)
Location: include/linux/mmzone.h:1299
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/page_isolation.c (ffffffff812bbc4d)
Location: include/linux/mmzone.h:1299
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
Location: include/linux/mmzone.h:1299
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
In kernel/power/snapshot.c (ffffffff8110d1b3)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/vmstat.c (ffffffff81246ebd)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff81254026)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff8127d811)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff812915c6)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff81ac8d47)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/memory-failure.c (ffffffff812cbdcc)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812cdb2d)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In fs/proc/page.c (ffffffff81381cc1)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/base/memory.c (ffffffff8171cadc)
Location: include/linux/mmzone.h:1306
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
In kernel/power/snapshot.c (ffffffff811183cb)
Location: include/linux/mmzone.h:1283
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/vmstat.c (ffffffff81274727)
Location: include/linux/mmzone.h:1283
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff81280bde)
Location: include/linux/mmzone.h:1283
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff812ae144)
Location: include/linux/mmzone.h:1283
Inline: True
Inline callers:
  - mm/page_alloc.c:pfn_range_valid_contig
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/shuffle.c (ffffffff81bc5a9f)
Location: include/linux/mmzone.h:1283
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812e0ab2)
Location: include/linux/mmzone.h:1283
Inline: True
Inline callers:
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/memory-failure.c (ffffffff81302851)
Location: include/linux/mmzone.h:1283
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff81303dc4)
Location: include/linux/mmzone.h:1283
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/page_idle.c (ffffffff813091eb)
Location: include/linux/mmzone.h:1283
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff813cc2b1)
Location: include/linux/mmzone.h:1283
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
In kernel/power/snapshot.c (ffffffff81bdf862)
Location: include/linux/mmzone.h:1321
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/vmstat.c (ffffffff8127ef7a)
Location: include/linux/mmzone.h:1321
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8128aeee)
Location: include/linux/mmzone.h:1321
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff812b9bc4)
Location: include/linux/mmzone.h:1321
Inline: True
Inline callers:
  - mm/page_alloc.c:pfn_range_valid_contig
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/shuffle.c (ffffffff81c3ea85)
Location: include/linux/mmzone.h:1321
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812eb973)
Location: include/linux/mmzone.h:1321
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/memory-failure.c (ffffffff8130ebb1)
Location: include/linux/mmzone.h:1321
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff8130fc94)
Location: include/linux/mmzone.h:1321
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/page_idle.c (ffffffff8131504f)
Location: include/linux/mmzone.h:1321
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff813ddeee)
Location: include/linux/mmzone.h:1321
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813dba50)
Location: include/linux/mmzone.h:1940
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff814059b0)
Location: include/linux/mmzone.h:1951
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages
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
In mm/vmstat.c (ffff8000102da25c)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffff8000102e99dc)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffff8000103150b8)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffff80001032e790)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_gigantic_page
```
```
In mm/memory_hotplug.c (ffff800010d9c8b0)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/memory-failure.c (ffff80001036f36c)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffff800010371f90)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In fs/proc/page.c (ffff80001044faa4)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/base/memory.c (ffff8000109107e4)
Location: include/linux/mmzone.h:1306
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
In mm/vmstat.c (c00000000039aabc)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (c0000000003ae840)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (c0000000003e6e68)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (c0000000004077c0)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (c00000000042f7c0)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/memory-failure.c (c000000000460f44)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (c000000000463874)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In fs/proc/page.c (c000000000567e2c)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/base/memory.c (c0000000009b1668)
Location: include/linux/mmzone.h:1306
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
In kernel/power/snapshot.c (ffffffff811053d3)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/vmstat.c (ffffffff8123f50d)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8124c676)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff81275e61)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff81289ba6)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff81a67bb7)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/memory-failure.c (ffffffff812c43ac)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812c610d)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In fs/proc/page.c (ffffffff8137a2a1)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/base/memory.c (ffffffff816e2e0c)
Location: include/linux/mmzone.h:1306
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
In kernel/power/snapshot.c (ffffffff810f6673)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/vmstat.c (ffffffff8123250d)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8123f616)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff81267db1)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff8127b9d6)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff81a24677)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/memory-failure.c (ffffffff812b53ec)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812b714d)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In fs/proc/page.c (ffffffff8136ad71)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/base/memory.c (ffffffff816bd44c)
Location: include/linux/mmzone.h:1306
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
In kernel/power/snapshot.c (ffffffff81103683)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/vmstat.c (ffffffff8123d2ad)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8124a416)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff81273c01)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff812879b6)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff81ad3fc7)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/memory-failure.c (ffffffff812c21bc)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812c3f1d)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In fs/proc/page.c (ffffffff81377d71)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/base/memory.c (ffffffff8170ff9c)
Location: include/linux/mmzone.h:1306
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
In kernel/power/snapshot.c (ffffffff8110ea73)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/vmstat.c (ffffffff8124c9dd)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff81259c76)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff81283701)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff81297f53)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff81ae04a9)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/memory-failure.c (ffffffff812d2c4c)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812d49bd)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In fs/proc/page.c (ffffffff8138b81b)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/base/memory.c (ffffffff8172b0fc)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
</ul>

## Differences
