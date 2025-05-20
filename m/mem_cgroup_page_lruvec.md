# Function: <code>mem_cgroup_page_lruvec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct lruvec *mem_cgroup_page_lruvec(struct page *page, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811febf0)
Location: mm/memcontrol.c:1083
Inline: False
Direct callers:
  - mm/swap.c:__page_cache_release
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:add_page_to_unevictable_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/compaction.c:isolate_migratepages_block
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/memcontrol.c:lock_page_lru
  - mm/memcontrol.c:unlock_page_lru
```
**Symbols:**

```
ffffffff811febf0-ffffffff811fec4d: mem_cgroup_page_lruvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct lruvec *mem_cgroup_page_lruvec(struct page *page, struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812247f2)
Location: mm/memcontrol.c:932
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff81222b80-ffffffff81222bc7: mem_cgroup_page_lruvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct lruvec *mem_cgroup_page_lruvec(struct page *page, struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81236ddb)
Location: mm/memcontrol.c:971
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff81234f60-ffffffff81234fa7: mem_cgroup_page_lruvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct lruvec *mem_cgroup_page_lruvec(struct page *page, struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81242889)
Location: mm/memcontrol.c:941
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/swap.c:release_pages
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812409e0-ffffffff81240a30: mem_cgroup_page_lruvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct lruvec *mem_cgroup_page_lruvec(struct page *page, struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812626c9)
Location: mm/memcontrol.c:955
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/swap.c:release_pages
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff81260720-ffffffff81260770: mem_cgroup_page_lruvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct lruvec *mem_cgroup_page_lruvec(struct page *page, struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81286889)
Location: mm/memcontrol.c:926
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff812848f0-ffffffff81284940: mem_cgroup_page_lruvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct lruvec *mem_cgroup_page_lruvec(struct page *page, struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81299800)
Location: mm/memcontrol.c:1100
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff81299800-ffffffff81299850: mem_cgroup_page_lruvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct lruvec *mem_cgroup_page_lruvec(struct page *page, struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b4b60)
Location: mm/memcontrol.c:1236
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/huge_memory.c:__split_huge_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff812b4b60-ffffffff812b4bb0: mem_cgroup_page_lruvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct lruvec *mem_cgroup_page_lruvec(struct page *page, struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c6630)
Location: mm/memcontrol.c:1247
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/huge_memory.c:__split_huge_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff812c6630-ffffffff812c6680: mem_cgroup_page_lruvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct lruvec *mem_cgroup_page_lruvec(struct page *page, struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fc0a0)
Location: mm/memcontrol.c:1207
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/workingset.c:workingset_activation
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff812fc0a0-ffffffff812fc0e7: mem_cgroup_page_lruvec (STB_GLOBAL)
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
In mm/page-writeback.c (ffffffff8126686c)
Location: include/linux/memcontrol.h:663
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff8126a3a2)
Location: include/linux/memcontrol.h:663
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost_page
```
```
In mm/compaction.c (ffffffff8128cbdd)
Location: include/linux/memcontrol.h:663
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81291169)
Location: include/linux/memcontrol.h:663
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
```
```
In mm/memcontrol.c (ffffffff8130823e)
Location: include/linux/memcontrol.h:663
Inline: True
Inline callers:
  - mm/memcontrol.c:lock_page_lruvec_irqsave
  - mm/memcontrol.c:lock_page_lruvec_irq
  - mm/memcontrol.c:lock_page_lruvec
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
In mm/swap.c (ffffffff8126f4b1)
Location: include/linux/memcontrol.h:750
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost_page
```
```
In mm/compaction.c (ffffffff81291a39)
Location: include/linux/memcontrol.h:750
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81296779)
Location: include/linux/memcontrol.h:750
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
```
```
In mm/memcontrol.c (ffffffff8130e9d2)
Location: include/linux/memcontrol.h:750
Inline: True
Inline callers:
  - mm/memcontrol.c:lock_page_lruvec_irqsave
  - mm/memcontrol.c:lock_page_lruvec_irq
  - mm/memcontrol.c:lock_page_lruvec
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
In mm/swap.c (ffffffff812ac601)
Location: include/linux/memcontrol.h:762
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost_page
```
```
In mm/compaction.c (ffffffff812d1304)
Location: include/linux/memcontrol.h:762
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff812d6eda)
Location: include/linux/memcontrol.h:762
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
```
```
In mm/memcontrol.c (ffffffff813597e6)
Location: include/linux/memcontrol.h:762
Inline: True
Inline callers:
  - mm/memcontrol.c:lock_page_lruvec_irqsave
  - mm/memcontrol.c:lock_page_lruvec_irq
  - mm/memcontrol.c:lock_page_lruvec
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct lruvec *mem_cgroup_page_lruvec(struct page *page, struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010369388)
Location: mm/memcontrol.c:1247
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/huge_memory.c:__split_huge_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffff800010369388-ffff800010369408: mem_cgroup_page_lruvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct lruvec *mem_cgroup_page_lruvec(struct page *page, struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055ce44)
Location: mm/memcontrol.c:1247
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
c055a86c-c055a8c4: mem_cgroup_page_lruvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct lruvec *mem_cgroup_page_lruvec(struct page *page, struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0000000004579f0)
Location: mm/memcontrol.c:1247
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/huge_memory.c:__split_huge_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
c0000000004579f0-c000000000457a6c: mem_cgroup_page_lruvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct lruvec *mem_cgroup_page_lruvec(struct page *page, struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000248e1e)
Location: mm/memcontrol.c:1247
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffe000246e72-ffffffe000246ed8: mem_cgroup_page_lruvec (STB_GLOBAL)
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
struct lruvec *mem_cgroup_page_lruvec(struct page *page, struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bec10)
Location: mm/memcontrol.c:1247
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/huge_memory.c:__split_huge_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff812bec10-ffffffff812bec60: mem_cgroup_page_lruvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct lruvec *mem_cgroup_page_lruvec(struct page *page, struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812afd00)
Location: mm/memcontrol.c:1247
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/huge_memory.c:__split_huge_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff812afd00-ffffffff812afd50: mem_cgroup_page_lruvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct lruvec *mem_cgroup_page_lruvec(struct page *page, struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bca20)
Location: mm/memcontrol.c:1247
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/huge_memory.c:__split_huge_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff812bca20-ffffffff812bca70: mem_cgroup_page_lruvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct lruvec *mem_cgroup_page_lruvec(struct page *page, struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cd200)
Location: mm/memcontrol.c:1247
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/huge_memory.c:__split_huge_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff812cd200-ffffffff812cd250: mem_cgroup_page_lruvec (STB_GLOBAL)
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
<code>struct pglist_data *pgdat</code>
</li>
<li>
<b>Param removed. </b>
<code>struct zone *zone</code>
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
