# Function: <code>migrate_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff811f22c0)
Location: mm/migrate.c:1122
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/compaction.c:compact_zone
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_mbind
  - mm/migrate.c:SyS_move_pages
  - mm/migrate.c:migrate_misplaced_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff811f22c0-ffffffff811f2a98: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81211b60)
Location: mm/migrate.c:1302
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/compaction.c:compact_zone
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SyS_move_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81211b60-ffffffff81212730: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81223d40)
Location: mm/migrate.c:1311
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/compaction.c:compact_zone
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81223d40-ffffffff81224911: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8122f660)
Location: mm/migrate.c:1299
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/compaction.c:compact_zone
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8122f660-ffffffff81230032: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8124d190)
Location: mm/migrate.c:1378
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/compaction.c:compact_zone
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8124d190-ffffffff8124dcc9: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81270c70)
Location: mm/migrate.c:1370
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/compaction.c:compact_zone
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:migrate_misplaced_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81270c70-ffffffff81271772: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81285280)
Location: mm/migrate.c:1403
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/compaction.c:compact_zone
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:migrate_misplaced_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81285280-ffffffff81285d9d: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129f8f0)
Location: mm/migrate.c:1398
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_misplaced_page
```
**Symbols:**

```
ffffffff8129f8f0-ffffffff812a0486: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b0c90)
Location: mm/migrate.c:1399
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_misplaced_page
```
**Symbols:**

```
ffffffff812b0c90-ffffffff812b1826: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e6de0)
Location: mm/migrate.c:1416
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:migrate_misplaced_page
```
**Symbols:**

```
ffffffff812e6de0-ffffffff812e7055: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f2130)
Location: mm/migrate.c:1423
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:migrate_misplaced_page
  - mm/memory-failure.c:__soft_offline_page
```
**Symbols:**

```
ffffffff812f2130-ffffffff812f25c8: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f8480)
Location: mm/migrate.c:1403
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:migrate_misplaced_page
  - mm/memory-failure.c:__soft_offline_page
```
**Symbols:**

```
ffffffff812f8480-ffffffff812f896a: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason, unsigned int *ret_succeeded);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81342b30)
Location: mm/migrate.c:1442
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/compaction.c:compact_zone
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:migrate_misplaced_page
  - mm/memory-failure.c:__soft_offline_page
```
**Symbols:**

```
ffffffff81342b30-ffffffff8134300e: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason, unsigned int *ret_succeeded);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813b5050)
Location: mm/migrate.c:1358
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/compaction.c:compact_zone
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:migrate_misplaced_page
  - mm/memory-failure.c:__soft_offline_page
```
**Symbols:**

```
ffffffff813b5050-ffffffff813b579f: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason, unsigned int *ret_succeeded);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81435100)
Location: mm/migrate.c:1427
Inline: False
Direct callers:
  - mm/vmscan.c:demote_folio_list
  - mm/compaction.c:compact_zone
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:migrate_misplaced_page
  - mm/memory-failure.c:soft_offline_in_use_page
```
**Symbols:**

```
ffffffff81435100-ffffffff81435872: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_folio_t *get_new_folio, free_folio_t *put_new_folio, long unsigned int private, enum migrate_mode mode, int reason, unsigned int *ret_succeeded);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8146b080)
Location: mm/migrate.c:1883
Inline: False
Direct callers:
  - mm/vmscan.c:demote_folio_list
  - mm/compaction.c:compact_zone
  - mm/gup.c:migrate_longterm_unpinnable_pages
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:migrate_misplaced_page
  - mm/memory-failure.c:soft_offline_in_use_page
```
**Symbols:**

```
ffffffff8146b080-ffffffff8146b58b: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_folio_t *get_new_folio, free_folio_t *put_new_folio, long unsigned int private, enum migrate_mode mode, int reason, unsigned int *ret_succeeded);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8149a060)
Location: mm/migrate.c:1906
Inline: False
Direct callers:
  - mm/vmscan.c:demote_folio_list
  - mm/compaction.c:compact_zone
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:move_pages_and_store_status
  - mm/memory-failure.c:soft_offline_in_use_page
```
**Symbols:**

```
ffffffff8149a060-ffffffff8149a52b: migrate_pages (STB_GLOBAL)
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
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff800010351170)
Location: mm/migrate.c:1399
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_mbind
  - mm/migrate.c:migrate_misplaced_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffff800010351170-ffff800010351e2c: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0552794)
Location: mm/migrate.c:1399
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
c0552794-c05530f4: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0000000004373e0)
Location: mm/migrate.c:1399
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_misplaced_page
```
**Symbols:**

```
c0000000004373e0-c0000000004386a0: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffe00023fa82)
Location: mm/migrate.c:1399
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffe00023fa82-ffffffe000240298: migrate_pages (STB_GLOBAL)
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
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a9270)
Location: mm/migrate.c:1399
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_misplaced_page
```
**Symbols:**

```
ffffffff812a9270-ffffffff812a9e06: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129abd0)
Location: mm/migrate.c:1399
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_misplaced_page
```
**Symbols:**

```
ffffffff8129abd0-ffffffff8129b766: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a7080)
Location: mm/migrate.c:1399
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_misplaced_page
```
**Symbols:**

```
ffffffff812a7080-ffffffff812a7c16: migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int migrate_pages(struct list_head *from, new_page_t *get_new_page, free_page_t *put_new_page, long unsigned int private, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b7390)
Location: mm/migrate.c:1399
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory_hotplug.c:do_migrate_range
  - mm/migrate.c:migrate_misplaced_page
```
**Symbols:**

```
ffffffff812b7390-ffffffff812b7f1d: migrate_pages (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int *ret_succeeded</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>new_folio_t *get_new_folio</code>
</li>
<li>
<b>Param added. </b>
<code>free_folio_t *put_new_folio</code>
</li>
<li>
<b>Param removed. </b>
<code>new_page_t *get_new_page</code>
</li>
<li>
<b>Param removed. </b>
<code>free_page_t *put_new_page</code>
</li>
</ul>
</details>
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
