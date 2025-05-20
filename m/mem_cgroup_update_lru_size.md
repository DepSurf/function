# Function: <code>mem_cgroup_update_lru_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811fec50)
Location: mm/memcontrol.c:1124
Inline: False
Direct callers:
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:lru_add_page_tail
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:lock_page_lru
  - mm/memcontrol.c:unlock_page_lru
```
**Symbols:**

```
ffffffff811fec50-ffffffff811fec6a: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81222bd0)
Location: mm/memcontrol.c:974
Inline: True
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff81222bd0-ffffffff81222c9b: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81234fb0)
Location: mm/memcontrol.c:1014
Inline: True
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff81234fb0-ffffffff81235086: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81240a30)
Location: mm/memcontrol.c:984
Inline: True
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff81240a30-ffffffff81240acc: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81260770)
Location: mm/memcontrol.c:998
Inline: True
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff81260770-ffffffff8126080a: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81284940)
Location: mm/memcontrol.c:969
Inline: True
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff81284940-ffffffff812849d3: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81299850)
Location: mm/memcontrol.c:1143
Inline: True
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff81299850-ffffffff812998e3: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b4bb0)
Location: mm/memcontrol.c:1279
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff812b4bb0-ffffffff812b4c44: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c6680)
Location: mm/memcontrol.c:1290
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff812c6680-ffffffff812c6714: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fc0f0)
Location: mm/memcontrol.c:1250
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffff812fc0f0-ffffffff812fc184: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813082b0)
Location: mm/memcontrol.c:1406
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/compaction.c:isolate_migratepages_block
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
ffffffff813082b0-ffffffff81308344: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130ea40)
Location: mm/memcontrol.c:1228
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/compaction.c:isolate_migratepages_block
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
ffffffff8130ea40-ffffffff8130ead4: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1280
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/compaction.c:isolate_migratepages_block
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
ffffffff81cc2913-ffffffff81cc2936: mem_cgroup_update_lru_size.cold (STB_LOCAL)
ffffffff81359860-ffffffff8135995e: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1283
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__folio_activate
  - mm/swap.c:__folio_activate
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/compaction.c:isolate_migratepages_block
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
**Symbols:**

```
ffffffff81e74e97-ffffffff81e74eba: mem_cgroup_update_lru_size.cold (STB_LOCAL)
ffffffff813d1840-ffffffff813d1989: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1363
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_add_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/compaction.c:isolate_migratepages_block
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
**Symbols:**

```
ffffffff820681a4-ffffffff820681c7: mem_cgroup_update_lru_size.cold (STB_LOCAL)
ffffffff81456ce0-ffffffff81456e32: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1387
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_add_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/compaction.c:isolate_migratepages_block
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
```
**Symbols:**

```
ffffffff820e7a8e-ffffffff820e7ab1: mem_cgroup_update_lru_size.cold (STB_LOCAL)
ffffffff8148c540-ffffffff8148c694: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1438
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_add_fn
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/compaction.c:isolate_migratepages_block
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
```
**Symbols:**

```
ffffffff821c47b7-ffffffff821c47da: mem_cgroup_update_lru_size.cold (STB_LOCAL)
ffffffff814bbe90-ffffffff814bbfe4: mem_cgroup_update_lru_size (STB_GLOBAL)
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
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010369408)
Location: mm/memcontrol.c:1290
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffff800010369408-ffff8000103694d0: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055a8c4)
Location: mm/memcontrol.c:1290
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
c055a8c4-c055a9a4: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000457a70)
Location: mm/memcontrol.c:1290
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
c000000000457a70-c000000000457b78: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000246ed8)
Location: mm/memcontrol.c:1290
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffe000246ed8-ffffffe000246f90: mem_cgroup_update_lru_size (STB_GLOBAL)
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
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bec60)
Location: mm/memcontrol.c:1290
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff812bec60-ffffffff812becf4: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812afd50)
Location: mm/memcontrol.c:1290
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff812afd50-ffffffff812afde4: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bca70)
Location: mm/memcontrol.c:1290
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff812bca70-ffffffff812bcb04: mem_cgroup_update_lru_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mem_cgroup_update_lru_size(struct lruvec *lruvec, enum lru_list lru, int zid, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cd250)
Location: mm/memcontrol.c:1290
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff812cd250-ffffffff812cd2e4: mem_cgroup_update_lru_size (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int zid</code>
</li>
<li>
<b>Param reordered. </b>
<code>lruvec, lru, nr_pages</code> ➡️ <code>lruvec, lru, zid, nr_pages</code>
</li>
</ul>
</details>
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
