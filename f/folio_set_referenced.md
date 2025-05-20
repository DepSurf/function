# Function: <code>folio_set_referenced</code>

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
In mm/swap.c (ffffffff81305a94)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
```
```
In mm/vmscan.c (ffffffff8130e8bb)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/gup.c (ffffffff8133a7a0)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
```
```
In mm/migrate.c (ffffffff813b08b6)
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
In mm/swap.c (ffffffff81370989)
Location: include/linux/page-flags.h:474
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_mark_accessed
```
```
In mm/vmscan.c (ffffffff8138127a)
Location: include/linux/page-flags.h:474
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/gup.c (ffffffff813b2286)
Location: include/linux/page-flags.h:474
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
```
```
In mm/migrate.c (ffffffff8143142a)
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
In mm/swap.c (ffffffff813a2c53)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_mark_accessed
```
```
In mm/vmscan.c (ffffffff813b262e)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/gup.c (ffffffff813e7031)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
```
```
In mm/migrate.c (ffffffff81466daa)
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
In mm/swap.c (ffffffff813cc8d5)
Location: include/linux/page-flags.h:470
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_mark_accessed
```
```
In mm/vmscan.c (ffffffff813dbbbc)
Location: include/linux/page-flags.h:470
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff813eab5c)
Location: include/linux/page-flags.h:470
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In mm/gup.c (ffffffff81411cb1)
Location: include/linux/page-flags.h:470
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
```
```
In mm/migrate.c (ffffffff8149600a)
Location: include/linux/page-flags.h:470
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff814a1533)
Location: include/linux/page-flags.h:470
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
