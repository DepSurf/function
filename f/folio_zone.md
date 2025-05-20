# Function: <code>folio_zone</code>

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
In mm/page-writeback.c (ffffffff812ff0a6)
Location: include/linux/mm.h:1491
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/mlock.c (ffffffff8134c0fb)
Location: include/linux/mm.h:1491
Inline: True
Inline callers:
  - mm/mlock.c:mlock_folio
```
```
In mm/migrate.c (ffffffff813b16a5)
Location: include/linux/mm.h:1491
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
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
In mm/page-writeback.c (ffffffff8136972e)
Location: include/linux/mm.h:1604
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff8136f84a)
Location: include/linux/mm.h:1604
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/mlock.c (ffffffff813c4c4c)
Location: include/linux/mm.h:1604
Inline: True
Inline callers:
  - mm/mlock.c:mlock_folio
```
```
In mm/migrate.c (ffffffff81432a15)
Location: include/linux/mm.h:1604
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
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
In mm/page-writeback.c (ffffffff8139b8cb)
Location: include/linux/mm.h:1817
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff813a196a)
Location: include/linux/mm.h:1817
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/mlock.c (ffffffff813f9329)
Location: include/linux/mm.h:1817
Inline: True
Inline callers:
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_folio
```
```
In mm/migrate.c (ffffffff814673b4)
Location: include/linux/mm.h:1817
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff814782c0)
Location: include/linux/mm.h:1817
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
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
In mm/page-writeback.c (ffffffff813c42f4)
Location: include/linux/mm.h:1872
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff813cb5ee)
Location: include/linux/mm.h:1872
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/mlock.c (ffffffff81424ed6)
Location: include/linux/mm.h:1872
Inline: True
Inline callers:
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_folio
```
```
In mm/hugetlb.c (ffffffff8391a945)
Location: include/linux/mm.h:1872
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_folio_init_tail_vmemmap
  - mm/hugetlb.c:hugetlb_folio_init_tail_vmemmap
```
```
In mm/migrate.c (ffffffff81496681)
Location: include/linux/mm.h:1872
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff814a7a00)
Location: include/linux/mm.h:1872
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
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
