# Function: <code>folio_pfn</code>

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
In kernel/events/uprobes.c (ffffffff812e5dc8)
Location: include/linux/mm.h:1523
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81e6b424)
Location: include/linux/mm.h:1523
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
  - mm/filemap.c:trace_event_raw_event_mm_filemap_op_page_cache
```
```
In mm/swap.c (ffffffff81302905)
Location: include/linux/mm.h:1523
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_activate
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8130a004)
Location: include/linux/mm.h:1523
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_write_folio
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_write_folio
```
```
In mm/rmap.c (ffffffff8135f062)
Location: include/linux/mm.h:1523
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/ksm.c (ffffffff813a36bf)
Location: include/linux/mm.h:1523
Inline: True
Inline callers:
  - mm/ksm.c:folio_migrate_ksm
```
```
In mm/migrate.c (ffffffff813b1920)
Location: include/linux/mm.h:1523
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/page_idle.c (ffffffff813e632d)
Location: include/linux/mm.h:1523
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
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
In kernel/events/uprobes.c (ffffffff8134fa53)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff813599be)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
  - mm/filemap.c:trace_event_raw_event_mm_filemap_op_page_cache
```
```
In mm/swap.c (ffffffff8136cf42)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_activate
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81374171)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_write_folio
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_write_folio
```
```
In mm/rmap.c (ffffffff813d9f23)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/hugetlb.c (ffffffff83ec3e8d)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_hugetlb_folio
  - mm/hugetlb.c:__update_and_free_page
```
```
In mm/ksm.c (ffffffff8142342f)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/ksm.c:folio_migrate_ksm
```
```
In mm/migrate.c (ffffffff81432380)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/page_idle.c (ffffffff8146de1d)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
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
In kernel/events/uprobes.c (ffffffff81380c22)
Location: include/linux/mm.h:1849
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8138b30b)
Location: include/linux/mm.h:1849
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
  - mm/filemap.c:trace_event_raw_event_mm_filemap_op_page_cache
```
```
In mm/swap.c (ffffffff8139f1c2)
Location: include/linux/mm.h:1849
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_activate
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff813a6e11)
Location: include/linux/mm.h:1849
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_write_folio
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_write_folio
```
```
In mm/rmap.c (ffffffff8140e633)
Location: include/linux/mm.h:1849
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/hugetlb.c (ffffffff836e8f3a)
Location: include/linux/mm.h:1849
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_hugetlb_folio
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
```
```
In mm/ksm.c (ffffffff8145868e)
Location: include/linux/mm.h:1849
Inline: True
Inline callers:
  - mm/ksm.c:folio_migrate_ksm
```
```
In mm/migrate.c (ffffffff81467ae0)
Location: include/linux/mm.h:1849
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memory-failure.c (ffffffff81498d7f)
Location: include/linux/mm.h:1849
Inline: True
Inline callers:
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
```
In mm/page_idle.c (ffffffff814a291d)
Location: include/linux/mm.h:1849
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
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
In kernel/events/uprobes.c (ffffffff813aa002)
Location: include/linux/mm.h:1904
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff813b4e38)
Location: include/linux/mm.h:1904
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
  - mm/filemap.c:trace_event_raw_event_mm_filemap_op_page_cache
```
```
In mm/swap.c (ffffffff813c8e22)
Location: include/linux/mm.h:1904
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_activate
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff813d0971)
Location: include/linux/mm.h:1904
Inline: True
Inline callers:
  - mm/vmscan.c:perf_trace_mm_vmscan_write_folio
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_write_folio
```
```
In mm/mlock.c (ffffffff81425260)
Location: include/linux/mm.h:1904
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/rmap.c (ffffffff8143ae24)
Location: include/linux/mm.h:1904
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/hugetlb.c (ffffffff8391a9c1)
Location: include/linux/mm.h:1904
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_folio_init_tail_vmemmap
  - mm/hugetlb.c:__alloc_fresh_hugetlb_folio
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
```
```
In mm/ksm.c (ffffffff81492dee)
Location: include/linux/mm.h:1904
Inline: True
Inline callers:
  - mm/ksm.c:folio_migrate_ksm
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff814977c8)
Location: include/linux/mm.h:1904
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memory-failure.c (ffffffff814c844f)
Location: include/linux/mm.h:1904
Inline: True
Inline callers:
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
```
In mm/page_idle.c (ffffffff814d37e8)
Location: include/linux/mm.h:1904
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c0dc)
Location: include/linux/mm.h:1904
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_get_pages
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
