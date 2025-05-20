# Function: <code>folio_test_private</code>

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
In mm/page-writeback.c (ffffffff813004f2)
Location: include/linux/page-flags.h:530
Inline: True
```
```
In mm/swap.c (ffffffff813027ac)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8130e30b)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
```
```
In mm/migrate.c (ffffffff813b2a4f)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
```
```
In fs/buffer.c (ffffffff8144384b)
Location: include/linux/page-flags.h:530
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff81488570)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_migrate_page
  - fs/iomap/buffered-io.c:iomap_migrate_page
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In drivers/md/md-bitmap.c (ffffffff81b68ccd)
Location: include/linux/page-flags.h:530
Inline: True
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
In mm/page-writeback.c (ffffffff8136ae32)
Location: include/linux/page-flags.h:509
Inline: True
```
```
In mm/swap.c (ffffffff8136e345)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8137dfdc)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
```
```
In mm/migrate.c (ffffffff814345f3)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff81441bec)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/buffer.c (ffffffff814d209b)
Location: include/linux/page-flags.h:509
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8151c3e6)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In drivers/md/md-bitmap.c (ffffffff81d047ed)
Location: include/linux/page-flags.h:509
Inline: True
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
In mm/page-writeback.c (ffffffff8139cfc2)
Location: include/linux/page-flags.h:502
Inline: True
```
```
In mm/swap.c (ffffffff813a0565)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff813afa19)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
```
```
In mm/migrate.c (ffffffff81468852)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff81477593)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/buffer.c (ffffffff81509aab)
Location: include/linux/page-flags.h:502
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff815545f3)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In drivers/md/md-bitmap.c (ffffffff81d6d8ad)
Location: include/linux/page-flags.h:502
Inline: True
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
In mm/page-writeback.c (ffffffff813c6cb2)
Location: include/linux/page-flags.h:504
Inline: True
```
```
In mm/swap.c (ffffffff813ca1e2)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff813dad53)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
```
```
In mm/migrate.c (ffffffff81497f06)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In fs/buffer.c (ffffffff8153e8db)
Location: include/linux/page-flags.h:504
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8158af67)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:ifs_free
```
```
In drivers/md/md-bitmap.c (ffffffff81e24ced)
Location: include/linux/page-flags.h:504
Inline: True
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
