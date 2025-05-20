# Function: <code>folio_test_workingset</code>

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
In mm/filemap.c (ffffffff812f419f)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:migration_entry_wait_on_locked
```
```
In mm/workingset.c (ffffffff8133625d)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/migrate.c (ffffffff813b08db)
Location: include/linux/page-flags.h:504
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
In mm/filemap.c (ffffffff8135c7ab)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - mm/filemap.c:filemap_read_folio
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
```
```
In mm/readahead.c (ffffffff8136c582)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/swap.c (ffffffff81370a21)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
```
```
In mm/vmscan.c (ffffffff8138126e)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
```
```
In mm/workingset.c (ffffffff813ad508)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/migrate.c (ffffffff8143144f)
Location: include/linux/page-flags.h:483
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
In mm/filemap.c (ffffffff8138e7db)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/filemap.c:filemap_read_folio
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
```
```
In mm/readahead.c (ffffffff8139e2c7)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/swap.c (ffffffff813a2b6f)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
```
```
In mm/vmscan.c (ffffffff813b2622)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
```
```
In mm/workingset.c (ffffffff813e1915)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/migrate.c (ffffffff81466dcf)
Location: include/linux/page-flags.h:477
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
In mm/filemap.c (ffffffff813b7e9b)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/filemap.c:filemap_read_folio
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
```
```
In mm/readahead.c (ffffffff813c7f67)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/swap.c (ffffffff813cc7ef)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
```
```
In mm/vmscan.c (ffffffff813dbbb0)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
```
```
In mm/workingset.c (ffffffff8140c052)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/slub.c (ffffffff8145922f)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
```
```
In mm/page_io.c (ffffffff81464802)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio
```
```
In mm/migrate.c (ffffffff81496030)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
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
