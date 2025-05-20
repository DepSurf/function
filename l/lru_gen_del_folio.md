# Function: <code>lru_gen_del_folio</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
bool lru_gen_del_folio(struct lruvec *lruvec, struct folio *folio, bool reclaiming);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff8136d2b0)
Location: include/linux/mm_inline.h:266
Inline: True
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8137bf3e)
Location: include/linux/mm_inline.h:266
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
Direct callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:isolate_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:folio_isolate_lru
```
```
In mm/compaction.c (ffffffff813a54a0)
Location: include/linux/mm_inline.h:266
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff813c1fa0)
Location: include/linux/mm_inline.h:266
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
**Symbols:**

```
ffffffff8136d2b0-ffffffff8136d638: lru_gen_del_folio.constprop.0 (STB_LOCAL)
ffffffff81379830-ffffffff81379bcb: lru_gen_del_folio (STB_LOCAL)
ffffffff813a54a0-ffffffff813a5828: lru_gen_del_folio.constprop.0 (STB_LOCAL)
ffffffff813c1fa0-ffffffff813c2328: lru_gen_del_folio.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
bool lru_gen_del_folio(struct lruvec *lruvec, struct folio *folio, bool reclaiming);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff8139f4f0)
Location: include/linux/mm_inline.h:266
Inline: True
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff813ab2b5)
Location: include/linux/mm_inline.h:266
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_change_state
Direct callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:folio_isolate_lru
```
```
In mm/compaction.c (ffffffff813d8af0)
Location: include/linux/mm_inline.h:266
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff813f68f0)
Location: include/linux/mm_inline.h:266
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
```
**Symbols:**

```
ffffffff8139f4f0-ffffffff8139f878: lru_gen_del_folio.constprop.0 (STB_LOCAL)
ffffffff813aa970-ffffffff813aad0b: lru_gen_del_folio (STB_LOCAL)
ffffffff813d8af0-ffffffff813d8e78: lru_gen_del_folio.constprop.0 (STB_LOCAL)
ffffffff813f68f0-ffffffff813f6c78: lru_gen_del_folio.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
bool lru_gen_del_folio(struct lruvec *lruvec, struct folio *folio, bool reclaiming);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (ffffffff813c9150)
Location: include/linux/mm_inline.h:272
Inline: True
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff813d4b56)
Location: include/linux/mm_inline.h:272
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_change_state
Direct callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:folio_isolate_lru
```
```
In mm/compaction.c (ffffffff81402870)
Location: include/linux/mm_inline.h:272
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81422ad0)
Location: include/linux/mm_inline.h:272
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
```
**Symbols:**

```
ffffffff813c9150-ffffffff813c94d5: lru_gen_del_folio.constprop.0 (STB_LOCAL)
ffffffff813d4210-ffffffff813d45a8: lru_gen_del_folio (STB_LOCAL)
ffffffff81402870-ffffffff81402bf5: lru_gen_del_folio.constprop.0 (STB_LOCAL)
ffffffff81422ad0-ffffffff81422e55: lru_gen_del_folio.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
