# Function: <code>mod_zone_page_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811ad530)
Location: mm/vmstat.c:359
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:free_area_init_node
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/compaction.c:acct_isolated
  - mm/compaction.c:acct_isolated
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:mlock_vma_page
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
**Symbols:**

```
ffffffff811ad530-ffffffff811ad598: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c65d0)
Location: mm/vmstat.c:442
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
```
**Symbols:**

```
ffffffff811c65d0-ffffffff811c6641: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d6760)
Location: mm/vmstat.c:442
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
```
**Symbols:**

```
ffffffff811d6760-ffffffff811d67d1: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811df5d0)
Location: mm/vmstat.c:442
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
**Symbols:**

```
ffffffff811df5d0-ffffffff811df63c: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f5230)
Location: mm/vmstat.c:517
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
**Symbols:**

```
ffffffff811f5230-ffffffff811f529c: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81216510)
Location: mm/vmstat.c:517
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
**Symbols:**

```
ffffffff81216510-ffffffff8121657c: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81229410)
Location: mm/vmstat.c:517
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
**Symbols:**

```
ffffffff81229410-ffffffff8122947c: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812390d0)
Location: mm/vmstat.c:518
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
**Symbols:**

```
ffffffff812390d0-ffffffff8123913c: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812473e0)
Location: mm/vmstat.c:518
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
**Symbols:**

```
ffffffff812473e0-ffffffff8124744c: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81274ea0)
Location: mm/vmstat.c:518
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
**Symbols:**

```
ffffffff81274ea0-ffffffff81274f12: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8127f700)
Location: mm/vmstat.c:527
Inline: False
Direct callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
**Symbols:**

```
ffffffff8127f700-ffffffff8127f784: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81284870)
Location: mm/vmstat.c:533
Inline: False
Direct callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
**Symbols:**

```
ffffffff81284870-ffffffff812848ee: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c30a0)
Location: mm/vmstat.c:579
Inline: False
Direct callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
**Symbols:**

```
ffffffff812c30a0-ffffffff812c3155: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81320330)
Location: mm/vmstat.c:608
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
  - mm/swap.c:__page_cache_release
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
```
**Symbols:**

```
ffffffff81320330-ffffffff81320418: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81394100)
Location: mm/vmstat.c:595
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
```
**Symbols:**

```
ffffffff81394100-ffffffff813941e8: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c6c10)
Location: mm/vmstat.c:596
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
```
**Symbols:**

```
ffffffff813c6c10-ffffffff813c6cf8: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f1600)
Location: mm/vmstat.c:596
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
```
**Symbols:**

```
ffffffff813f1600-ffffffff813f16ef: mod_zone_page_state (STB_GLOBAL)
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
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102db100)
Location: mm/vmstat.c:518
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
**Symbols:**

```
ffff8000102db100-ffff8000102db23c: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c0501908)
Location: mm/vmstat.c:602
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
**Symbols:**

```
c0501908-c0501930: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c000000000399660)
Location: mm/vmstat.c:602
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
**Symbols:**

```
c000000000399660-c0000000003996b0: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f3b02)
Location: mm/vmstat.c:602
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
**Symbols:**

```
ffffffe0001f3b02-ffffffe0001f3b4a: mod_zone_page_state (STB_GLOBAL)
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
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123fa30)
Location: mm/vmstat.c:518
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
**Symbols:**

```
ffffffff8123fa30-ffffffff8123fa9c: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81232a30)
Location: mm/vmstat.c:518
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
**Symbols:**

```
ffffffff81232a30-ffffffff81232a9c: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123d7d0)
Location: mm/vmstat.c:518
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
**Symbols:**

```
ffffffff8123d7d0-ffffffff8123d83c: mod_zone_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mod_zone_page_state(struct zone *zone, enum zone_stat_item item, long int delta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124cf00)
Location: mm/vmstat.c:518
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
**Symbols:**

```
ffffffff8124cf00-ffffffff8124cf6c: mod_zone_page_state (STB_GLOBAL)
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
