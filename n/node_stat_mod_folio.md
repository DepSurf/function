# Function: <code>node_stat_mod_folio</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813007ca)
Location: include/linux/vmstat.h:472
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_account_redirty
```
```
In mm/vmscan.c (ffffffff8130eaf5)
Location: include/linux/vmstat.h:472
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/gup.c (ffffffff81337ca8)
Location: include/linux/vmstat.h:472
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8136b108)
Location: include/linux/vmstat.h:466
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_account_redirty
```
```
In mm/vmscan.c (ffffffff81380aac)
Location: include/linux/vmstat.h:466
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/gup.c (ffffffff813ae97e)
Location: include/linux/vmstat.h:466
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8139d267)
Location: include/linux/vmstat.h:472
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_account_redirty
```
```
In mm/vmscan.c (ffffffff813b1f82)
Location: include/linux/vmstat.h:472
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/compaction.c (ffffffff813db108)
Location: include/linux/vmstat.h:472
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813e327e)
Location: include/linux/vmstat.h:472
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/mempolicy.c (ffffffff81449551)
Location: include/linux/vmstat.h:472
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
```
```
In mm/migrate.c (ffffffff814692b7)
Location: include/linux/vmstat.h:472
Inline: True
Inline callers:
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff8147b2a7)
Location: include/linux/vmstat.h:472
Inline: True
Inline callers:
  - mm/khugepaged.c:release_pte_folio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813c6f1d)
Location: include/linux/vmstat.h:472
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_redirty_for_writepage
```
```
In mm/vmscan.c (ffffffff813db514)
Location: include/linux/vmstat.h:472
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/compaction.c (ffffffff81405291)
Location: include/linux/vmstat.h:472
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8140db09)
Location: include/linux/vmstat.h:472
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/mempolicy.c (ffffffff81482fa8)
Location: include/linux/vmstat.h:472
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
```
```
In mm/migrate.c (ffffffff8149ad99)
Location: include/linux/vmstat.h:472
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff814ad096)
Location: include/linux/vmstat.h:472
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_folio
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
