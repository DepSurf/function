# Function: <code>folio_test_referenced</code>

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
In mm/swap.c (ffffffff81305a85)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
```
```
In mm/migrate.c (ffffffff813b08af)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
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
In mm/swap.c (ffffffff8137097a)
Location: include/linux/page-flags.h:474
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_mark_accessed
```
```
In mm/vmscan.c (ffffffff81381170)
Location: include/linux/page-flags.h:474
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:isolate_folio
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/migrate.c (ffffffff81431423)
Location: include/linux/page-flags.h:474
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
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
In mm/swap.c (ffffffff813a2b63)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_mark_accessed
```
```
In mm/vmscan.c (ffffffff813b2522)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/migrate.c (ffffffff81466da3)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
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
In mm/swap.c (ffffffff813cc7e3)
Location: include/linux/page-flags.h:470
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_mark_accessed
```
```
In mm/vmscan.c (ffffffff813dbacc)
Location: include/linux/page-flags.h:470
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/migrate.c (ffffffff81496003)
Location: include/linux/page-flags.h:470
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff814a1502)
Location: include/linux/page-flags.h:470
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff814afaa0)
Location: include/linux/page-flags.h:470
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
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
