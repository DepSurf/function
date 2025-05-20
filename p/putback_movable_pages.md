# Function: <code>putback_movable_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff811f1310)
Location: mm/migrate.c:83
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/compaction.c:isolate_migratepages_range
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/migrate.c:SyS_move_pages
```
**Symbols:**

```
ffffffff811f1310-ffffffff811f13cf: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81211380)
Location: mm/migrate.c:160
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/migrate.c:SyS_move_pages
```
**Symbols:**

```
ffffffff81211380-ffffffff812114d2: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81223540)
Location: mm/migrate.c:160
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:SYSC_move_pages
```
**Symbols:**

```
ffffffff81223540-ffffffff81223692: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8122ef10)
Location: mm/migrate.c:162
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:SYSC_move_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8122ef10-ffffffff8122f041: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8124bbf0)
Location: mm/migrate.c:166
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/migrate.c:SYSC_move_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8124bbf0-ffffffff8124bd82: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8126f6c0)
Location: mm/migrate.c:167
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8126f6c0-ffffffff8126f862: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81283d50)
Location: mm/migrate.c:167
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81283d50-ffffffff81283ef2: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129ef10)
Location: mm/migrate.c:167
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory_hotplug.c:do_migrate_range
```
**Symbols:**

```
ffffffff8129ef10-ffffffff8129f0bf: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812af900)
Location: mm/migrate.c:168
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory_hotplug.c:do_migrate_range
```
**Symbols:**

```
ffffffff812af900-ffffffff812afaaf: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e5990)
Location: mm/migrate.c:169
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
```
**Symbols:**

```
ffffffff812e5990-ffffffff812e5b5e: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f0d50)
Location: mm/migrate.c:165
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory-failure.c:__soft_offline_page
```
**Symbols:**

```
ffffffff812f0d50-ffffffff812f0f1b: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f7050)
Location: mm/migrate.c:138
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory-failure.c:__soft_offline_page
```
**Symbols:**

```
ffffffff812f7050-ffffffff812f721b: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813416b0)
Location: mm/migrate.c:139
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory-failure.c:__soft_offline_page
```
**Symbols:**

```
ffffffff813416b0-ffffffff8134187b: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813b3170)
Location: mm/migrate.c:138
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory-failure.c:__soft_offline_page
```
**Symbols:**

```
ffffffff813b3170-ffffffff813b3426: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81433690)
Location: mm/migrate.c:147
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory-failure.c:soft_offline_in_use_page
```
**Symbols:**

```
ffffffff81433690-ffffffff8143393b: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81469220)
Location: mm/migrate.c:147
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:migrate_longterm_unpinnable_pages
  - mm/gup.c:migrate_longterm_unpinnable_pages
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory-failure.c:soft_offline_in_use_page
```
**Symbols:**

```
ffffffff81469220-ffffffff81469393: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81498140)
Location: mm/migrate.c:147
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:move_pages_and_store_status
  - mm/memory-failure.c:soft_offline_in_use_page
```
**Symbols:**

```
ffffffff81498140-ffffffff814982b0: putback_movable_pages (STB_GLOBAL)
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
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff8000103507b8)
Location: mm/migrate.c:168
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffff8000103507b8-ffff8000103509b4: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0551ecc)
Location: mm/migrate.c:168
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
c0551ecc-c0552084: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0000000004355e0)
Location: mm/migrate.c:168
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory_hotplug.c:do_migrate_range
```
**Symbols:**

```
c0000000004355e0-c0000000004358c4: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffe00023f2ea)
Location: mm/migrate.c:168
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffe00023f2ea-ffffffe00023f450: putback_movable_pages (STB_GLOBAL)
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
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a7ee0)
Location: mm/migrate.c:168
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory_hotplug.c:do_migrate_range
```
**Symbols:**

```
ffffffff812a7ee0-ffffffff812a808f: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812998a0)
Location: mm/migrate.c:168
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory_hotplug.c:do_migrate_range
```
**Symbols:**

```
ffffffff812998a0-ffffffff81299a4f: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a5cf0)
Location: mm/migrate.c:168
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory_hotplug.c:do_migrate_range
```
**Symbols:**

```
ffffffff812a5cf0-ffffffff812a5e9f: putback_movable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head *l);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b6040)
Location: mm/migrate.c:168
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/memory_hotplug.c:do_migrate_range
```
**Symbols:**

```
ffffffff812b6040-ffffffff812b61ea: putback_movable_pages (STB_GLOBAL)
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
