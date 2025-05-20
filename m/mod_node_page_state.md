# Function: <code>mod_node_page_state</code>

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
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c6700)
Location: mm/vmstat.c:499
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
**Symbols:**

```
ffffffff811c6700-ffffffff811c6776: mod_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d6890)
Location: mm/vmstat.c:499
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
**Symbols:**

```
ffffffff811d6890-ffffffff811d6906: mod_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811df6f0)
Location: mm/vmstat.c:499
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
**Symbols:**

```
ffffffff811df6f0-ffffffff811df761: mod_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f5350)
Location: mm/vmstat.c:574
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/mempolicy.c:migrate_page_add
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff811f5350-ffffffff811f53c1: mod_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81216630)
Location: mm/vmstat.c:574
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/mempolicy.c:migrate_page_add
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:__d_free_external_name
```
**Symbols:**

```
ffffffff81216630-ffffffff812166a1: mod_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81229530)
Location: mm/vmstat.c:574
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/mempolicy.c:migrate_page_add
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff81229530-ffffffff812295a1: mod_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812391f0)
Location: mm/vmstat.c:575
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/gup.c:__gup_longterm_locked
  - mm/mempolicy.c:migrate_page_add
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff812391f0-ffffffff81239261: mod_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81247500)
Location: mm/vmstat.c:575
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/slab_common.c:kmalloc_order
  - mm/gup.c:__gup_longterm_locked
  - mm/mempolicy.c:migrate_page_add
  - mm/slub.c:kfree
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff81247500-ffffffff81247571: mod_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812754a0)
Location: mm/vmstat.c:575
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/slab_common.c:kmalloc_order
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:put_compound_head
  - mm/gup.c:unpin_user_page
  - mm/gup.c:__unpin_devmap_managed_user_page
  - mm/mempolicy.c:migrate_page_add
  - mm/slub.c:kfree
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:putback_movable_pages
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
**Symbols:**

```
ffffffff812754a0-ffffffff81275514: mod_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8127ff90)
Location: mm/vmstat.c:589
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:put_compound_head
  - mm/mempolicy.c:migrate_page_add
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:putback_movable_pages
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
**Symbols:**

```
ffffffff8127ff90-ffffffff81280027: mod_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81284f20)
Location: mm/vmstat.c:601
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:put_compound_head
  - mm/mempolicy.c:migrate_page_add
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:putback_movable_pages
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
**Symbols:**

```
ffffffff81284f20-ffffffff81284fae: mod_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c3540)
Location: mm/vmstat.c:647
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:put_compound_head
  - mm/mempolicy.c:migrate_page_add
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:putback_movable_pages
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
**Symbols:**

```
ffffffff812c3540-ffffffff812c35e4: mod_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813208a0)
Location: mm/vmstat.c:676
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_account_redirty
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/mempolicy.c:migrate_page_add
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:putback_movable_pages
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
**Symbols:**

```
ffffffff813208a0-ffffffff81320982: mod_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81394650)
Location: mm/vmstat.c:663
Inline: False
Direct callers:
  - kernel/sched/fair.c:should_numa_migrate_memory
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_account_redirty
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/mempolicy.c:migrate_page_add
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:putback_movable_pages
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
**Symbols:**

```
ffffffff81394650-ffffffff81394749: mod_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c7160)
Location: mm/vmstat.c:664
Inline: False
Direct callers:
  - kernel/sched/fair.c:should_numa_migrate_memory
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_account_redirty
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/mempolicy.c:migrate_folio_add
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:putback_movable_pages
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_folio
```
**Symbols:**

```
ffffffff813c7160-ffffffff813c7259: mod_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f1fd0)
Location: mm/vmstat.c:665
Inline: False
Direct callers:
  - kernel/sched/fair.c:should_numa_migrate_memory
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_redirty_for_writepage
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:demote_folio_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/mempolicy.c:migrate_folio_add
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:putback_movable_pages
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_folio
  - mm/memory-failure.c:soft_offline_in_use_page
```
**Symbols:**

```
ffffffff813f1fd0-ffffffff813f20c3: mod_node_page_state (STB_GLOBAL)
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
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102dafc0)
Location: mm/vmstat.c:575
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/slab_common.c:kmalloc_order
  - mm/gup.c:__gup_longterm_locked
  - mm/mempolicy.c:migrate_page_add
  - mm/slub.c:kfree
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffff8000102dafc0-ffff8000102db100: mod_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c05019e4)
Location: mm/vmstat.c:645
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/slab_common.c:kmalloc_order
  - mm/gup.c:__gup_longterm_locked
  - mm/slub.c:kfree
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
c05019e4-c0501a0c: mod_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c000000000399760)
Location: mm/vmstat.c:645
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/slab_common.c:kmalloc_order
  - mm/gup.c:__gup_longterm_locked
  - mm/mempolicy.c:migrate_page_add
  - mm/slub.c:kfree
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
c000000000399760-c0000000003997b0: mod_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f3bfc)
Location: mm/vmstat.c:645
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/slab_common.c:kmalloc_order
  - mm/gup.c:__gup_longterm_locked
  - mm/slub.c:kfree
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffe0001f3bfc-ffffffe0001f3c44: mod_node_page_state (STB_GLOBAL)
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
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123fb50)
Location: mm/vmstat.c:575
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/slab_common.c:kmalloc_order
  - mm/gup.c:__gup_longterm_locked
  - mm/mempolicy.c:migrate_page_add
  - mm/slub.c:kfree
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff8123fb50-ffffffff8123fbc1: mod_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81232b50)
Location: mm/vmstat.c:575
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/slab_common.c:kmalloc_order
  - mm/gup.c:__gup_longterm_locked
  - mm/mempolicy.c:migrate_page_add
  - mm/slub.c:kfree
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff81232b50-ffffffff81232bc1: mod_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123d8f0)
Location: mm/vmstat.c:575
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/slab_common.c:kmalloc_order
  - mm/gup.c:__gup_longterm_locked
  - mm/mempolicy.c:migrate_page_add
  - mm/slub.c:kfree
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff8123d8f0-ffffffff8123d961: mod_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mod_node_page_state(struct pglist_data *pgdat, enum node_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124d020)
Location: mm/vmstat.c:575
Inline: False
Direct callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/slab_common.c:kmalloc_order
  - mm/gup.c:__gup_longterm_locked
  - mm/mempolicy.c:migrate_page_add
  - mm/slub.c:kfree
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff8124d020-ffffffff8124d091: mod_node_page_state (STB_GLOBAL)
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
