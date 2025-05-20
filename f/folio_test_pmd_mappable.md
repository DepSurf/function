# Function: <code>folio_test_pmd_mappable</code>

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
In mm/filemap.c (ffffffff812f2613)
Location: include/linux/huge_mm.h:271
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/vmscan.c (ffffffff8130e511)
Location: include/linux/huge_mm.h:271
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff813190f3)
Location: include/linux/huge_mm.h:271
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/memory.c (ffffffff81341623)
Location: include/linux/huge_mm.h:271
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
In mm/filemap.c (ffffffff8135abd3)
Location: include/linux/huge_mm.h:256
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/vmscan.c (ffffffff813804db)
Location: include/linux/huge_mm.h:256
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff8138cfd1)
Location: include/linux/huge_mm.h:256
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/memory.c (ffffffff813b9557)
Location: include/linux/huge_mm.h:256
Inline: True
```
```
In mm/migrate.c (ffffffff81435329)
Location: include/linux/huge_mm.h:256
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
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
In mm/filemap.c (ffffffff8138f8d3)
Location: include/linux/huge_mm.h:218
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/vmscan.c (ffffffff813b1cd8)
Location: include/linux/huge_mm.h:218
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff813bfb4a)
Location: include/linux/huge_mm.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/memory.c (ffffffff813ee189)
Location: include/linux/huge_mm.h:218
Inline: True
```
```
In mm/rmap.c (ffffffff8140c9c4)
Location: include/linux/huge_mm.h:218
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
```
```
In mm/migrate.c (ffffffff8146a6a8)
Location: include/linux/huge_mm.h:218
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:folio_migrate_mapping
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
In mm/filemap.c (ffffffff813b92fd)
Location: include/linux/huge_mm.h:339
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/vmscan.c (ffffffff813db24d)
Location: include/linux/huge_mm.h:339
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff813ea9f1)
Location: include/linux/huge_mm.h:339
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/memory.c (ffffffff814197d9)
Location: include/linux/huge_mm.h:339
Inline: True
```
```
In mm/rmap.c (ffffffff81438f58)
Location: include/linux/huge_mm.h:339
Inline: True
Inline callers:
  - mm/rmap.c:folio_add_new_anon_rmap
```
```
In mm/page_io.c (ffffffff8146420d)
Location: include/linux/huge_mm.h:339
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:swap_writepage_fs
```
```
In mm/migrate.c (ffffffff81499696)
Location: include/linux/huge_mm.h:339
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff814a7051)
Location: include/linux/huge_mm.h:339
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffffffff814bc9d0)
Location: include/linux/huge_mm.h:339
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
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
