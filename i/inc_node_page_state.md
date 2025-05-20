# Function: <code>inc_node_page_state</code>

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
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c52f0)
Location: mm/vmstat.c:511
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/vmscan.c:shrink_page_list
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:SyS_move_pages
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:soft_offline_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff811c52f0-ffffffff811c5379: inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d6910)
Location: mm/vmstat.c:511
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/vmscan.c:shrink_page_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:SYSC_move_pages
  - mm/khugepaged.c:khugepaged
  - mm/memory-failure.c:soft_offline_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff811d6910-ffffffff811d6999: inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811df770)
Location: mm/vmstat.c:511
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/vmscan.c:shrink_page_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:SYSC_move_pages
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:soft_offline_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff811df770-ffffffff811df7f6: inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f53d0)
Location: mm/vmstat.c:586
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/vmscan.c:shrink_page_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:__offline_pages
  - mm/khugepaged.c:khugepaged
  - mm/memory-failure.c:soft_offline_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff811f53d0-ffffffff811f5456: inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812166b0)
Location: mm/vmstat.c:586
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/vmscan.c:shrink_page_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:__offline_pages
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:soft_offline_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff812166b0-ffffffff81216736: inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812295b0)
Location: mm/vmstat.c:586
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/vmscan.c:shrink_page_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:__offline_pages
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:soft_offline_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff812295b0-ffffffff81229636: inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81239270)
Location: mm/vmstat.c:587
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/vmscan.c:shrink_page_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:do_migrate_range
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81239270-ffffffff812392f6: inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81247580)
Location: mm/vmstat.c:587
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/vmscan.c:shrink_page_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:do_migrate_range
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81247580-ffffffff81247606: inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81275760)
Location: mm/vmstat.c:587
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81275760-ffffffff812757e8: inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8127f950)
Location: mm/vmstat.c:601
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
  - mm/memory-failure.c:isolate_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8127f950-ffffffff8127f9f2: inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81284fb0)
Location: mm/vmstat.c:613
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
  - mm/memory-failure.c:__soft_offline_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81284fb0-ffffffff8128504b: inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c2fe0)
Location: mm/vmstat.c:659
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
  - mm/memory-failure.c:__soft_offline_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff812c2fe0-ffffffff812c3096: inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81320240)
Location: mm/vmstat.c:688
Inline: False
Direct callers:
  - mm/memory-failure.c:__soft_offline_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81320240-ffffffff8132032a: inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81394760)
Location: mm/vmstat.c:675
Inline: False
Direct callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81394760-ffffffff81394861: inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c6af0)
Location: mm/vmstat.c:676
Inline: False
Direct callers:
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory-failure.c:soft_offline_in_use_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff813c6af0-ffffffff813c6bf1: inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f20e0)
Location: mm/vmstat.c:677
Inline: False
Direct callers:
  - mm/memory_hotplug.c:do_migrate_range
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff813f20e0-ffffffff813f21db: inc_node_page_state (STB_GLOBAL)
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
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102db240)
Location: mm/vmstat.c:587
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/vmscan.c:shrink_page_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memory-failure.c:soft_offline_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffff8000102db240-ffff8000102db388: inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c05021e8)
Location: mm/vmstat.c:656
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/compaction.c:isolate_migratepages_block
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
c05021e8-c0502218: inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c00000000039bec0)
Location: mm/vmstat.c:656
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/vmscan.c:shrink_page_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:do_migrate_range
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
c00000000039bec0-c00000000039bf24: inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f533a)
Location: mm/vmstat.c:656
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/vmscan.c:shrink_page_list
  - mm/compaction.c:isolate_migratepages_block
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffe0001f533a-ffffffe0001f537a: inc_node_page_state (STB_GLOBAL)
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
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123fbd0)
Location: mm/vmstat.c:587
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/vmscan.c:shrink_page_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:do_migrate_range
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8123fbd0-ffffffff8123fc56: inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81232bd0)
Location: mm/vmstat.c:587
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/vmscan.c:shrink_page_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:do_migrate_range
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81232bd0-ffffffff81232c56: inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123d970)
Location: mm/vmstat.c:587
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/vmscan.c:shrink_page_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:do_migrate_range
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8123d970-ffffffff8123d9f6: inc_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inc_node_page_state(struct page *page, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124d0a0)
Location: mm/vmstat.c:587
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/vmscan.c:shrink_page_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:do_migrate_range
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8124d0a0-ffffffff8124d126: inc_node_page_state (STB_GLOBAL)
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
