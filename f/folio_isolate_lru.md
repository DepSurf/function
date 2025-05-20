# Function: <code>folio_isolate_lru</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int folio_isolate_lru(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81313810)
Location: mm/vmscan.c:2193
Inline: False
Direct callers:
  - mm/folio-compat.c:isolate_lru_page
  - mm/gup.c:check_and_migrate_movable_pages
```
**Symbols:**

```
ffffffff81313810-ffffffff813139d0: folio_isolate_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int folio_isolate_lru(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81386b30)
Location: mm/vmscan.c:2337
Inline: False
Direct callers:
  - mm/folio-compat.c:isolate_lru_page
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81386b30-ffffffff81386cf7: folio_isolate_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool folio_isolate_lru(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813b6fc0)
Location: mm/vmscan.c:2421
Inline: False
Direct callers:
  - mm/folio-compat.c:isolate_lru_page
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:migrate_folio_add
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff813b6fc0-ffffffff813b7182: folio_isolate_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool folio_isolate_lru(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813dfe60)
Location: mm/vmscan.c:1721
Inline: False
Direct callers:
  - mm/folio-compat.c:isolate_lru_page
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:migrate_folio_add
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:add_page_for_migration
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:delete_from_lru_cache
```
**Symbols:**

```
ffffffff813dfe60-ffffffff813e0020: folio_isolate_lru (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
