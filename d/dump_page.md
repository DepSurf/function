# Function: <code>dump_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff811ba1a0)
Location: mm/debug.c:103
Inline: False
Direct callers:
  - mm/memory.c:print_bad_pte
  - mm/balloon_compaction.c:balloon_page_putback
  - mm/balloon_compaction.c:balloon_page_migrate
```
**Symbols:**

```
ffffffff811ba1a0-ffffffff811ba1b2: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff811d4600)
Location: mm/debug.c:66
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/memory.c:print_bad_pte
```
**Symbols:**

```
ffffffff811d4600-ffffffff811d4610: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff811e4690)
Location: mm/debug.c:75
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/memory.c:print_bad_pte
```
**Symbols:**

```
ffffffff811e4690-ffffffff811e46a0: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff811eeaf0)
Location: mm/debug.c:75
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/memory.c:print_bad_pte
```
**Symbols:**

```
ffffffff811eeaf0-ffffffff811eeb00: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff81204f60)
Location: mm/debug.c:76
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
```
**Symbols:**

```
ffffffff81204f60-ffffffff81204f70: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff81225cb0)
Location: mm/debug.c:90
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
```
**Symbols:**

```
ffffffff81225cb0-ffffffff81225cc0: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff81239370)
Location: mm/debug.c:106
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page_alloc.c:has_unmovable_pages
  - mm/memory.c:print_bad_pte
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff81239370-ffffffff81239380: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff8124a3d0)
Location: mm/debug.c:106
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:has_unmovable_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
**Symbols:**

```
ffffffff8124a3d0-ffffffff8124a3e0: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff81258850)
Location: mm/debug.c:111
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:has_unmovable_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
**Symbols:**

```
ffffffff81258850-ffffffff81258860: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff81287330)
Location: mm/debug.c:187
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_isolation.c:set_migratetype_isolate
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81287330-ffffffff81287340: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff81291400)
Location: mm/debug.c:190
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_isolation.c:set_migratetype_isolate
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81291400-ffffffff81291410: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff81296950)
Location: mm/debug.c:190
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_isolation.c:start_isolate_page_range
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81296950-ffffffff81296960: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/debug.c (0)
Location: mm/debug.c:176
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:bad_page
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/memory-failure.c:get_any_page
  - mm/page_isolation.c:start_isolate_page_range
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81cbc0c5-ffffffff81cbc0ed: dump_page.cold (STB_LOCAL)
ffffffff812d71b0-ffffffff812d71dc: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/debug.c (ffffffff81e6dc51)
Location: mm/debug.c:126
Inline: True
Direct callers:
  - mm/filemap.c:filemap_unaccount_folio
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/page_alloc.c:bad_page
  - mm/page_poison.c:__kernel_unpoison_pages
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81e6dc3d-ffffffff81e6dc65: dump_page.cold (STB_LOCAL)
ffffffff81336b10-ffffffff81336b48: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff813ae040)
Location: mm/debug.c:127
Inline: True
Direct callers:
  - mm/filemap.c:filemap_unaccount_folio
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/page_alloc.c:bad_page
  - mm/page_poison.c:__kernel_unpoison_pages
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff813ae040-ffffffff813ae090: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff813e2390)
Location: mm/debug.c:134
Inline: True
Direct callers:
  - mm/filemap.c:filemap_unaccount_folio
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/page_alloc.c:bad_page
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/page_poison.c:__kernel_unpoison_pages
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff813e2390-ffffffff813e23e0: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff8140cb90)
Location: mm/debug.c:134
Inline: True
Direct callers:
  - mm/filemap.c:filemap_unaccount_folio
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/page_alloc.c:bad_page
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/page_poison.c:__kernel_unpoison_pages
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff8140cb90-ffffffff8140cbe0: dump_page (STB_GLOBAL)
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
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffff8000102f0ab0)
Location: mm/debug.c:111
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:has_unmovable_pages
```
**Symbols:**

```
ffff8000102f0ab0-ffff8000102f0ae4: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (c0513f38)
Location: mm/debug.c:111
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:has_unmovable_pages
```
**Symbols:**

```
c0513f38-c0513f54: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (c0000000003b5530)
Location: mm/debug.c:111
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:has_unmovable_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
**Symbols:**

```
c0000000003b5530-c0000000003b5544: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffe000204202)
Location: mm/debug.c:111
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:has_unmovable_pages
```
**Symbols:**

```
ffffffe000204202-ffffffe000204234: dump_page (STB_GLOBAL)
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
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff81250ea0)
Location: mm/debug.c:111
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:has_unmovable_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
**Symbols:**

```
ffffffff81250ea0-ffffffff81250eb0: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff81243de0)
Location: mm/debug.c:111
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:has_unmovable_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
**Symbols:**

```
ffffffff81243de0-ffffffff81243df0: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff8124ec40)
Location: mm/debug.c:111
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:has_unmovable_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
**Symbols:**

```
ffffffff8124ec40-ffffffff8124ec50: dump_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dump_page(struct page *page, const char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff8125e5c0)
Location: mm/debug.c:111
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:has_unmovable_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
**Symbols:**

```
ffffffff8125e5c0-ffffffff8125e5d0: dump_page (STB_GLOBAL)
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
