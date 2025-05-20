# Function: <code>split_folio_to_list</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8130e6de)
Location: include/linux/huge_mm.h:458
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/truncate.c (ffffffff81372227)
Location: include/linux/huge_mm.h:441
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_partial_folio
```
```
In mm/vmscan.c (ffffffff813808e4)
Location: include/linux/huge_mm.h:441
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff8138c274)
Location: include/linux/huge_mm.h:441
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/madvise.c (ffffffff813f44cc)
Location: include/linux/huge_mm.h:441
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff8143529a)
Location: include/linux/huge_mm.h:441
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff81443173)
Location: include/linux/huge_mm.h:441
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
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
In mm/truncate.c (ffffffff813a43c8)
Location: include/linux/huge_mm.h:394
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_partial_folio
```
```
In mm/vmscan.c (ffffffff813b1dd0)
Location: include/linux/huge_mm.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff813be832)
Location: include/linux/huge_mm.h:394
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/madvise.c (ffffffff81427b5e)
Location: include/linux/huge_mm.h:394
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff8146a80b)
Location: include/linux/huge_mm.h:394
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
```
```
In mm/huge_memory.c (ffffffff8147810f)
Location: include/linux/huge_mm.h:394
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
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
In mm/truncate.c (ffffffff813cdf16)
Location: include/linux/huge_mm.h:522
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_partial_folio
```
```
In mm/vmscan.c (ffffffff813db33c)
Location: include/linux/huge_mm.h:522
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff813e94f8)
Location: include/linux/huge_mm.h:522
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/madvise.c (ffffffff81461373)
Location: include/linux/huge_mm.h:522
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff814997eb)
Location: include/linux/huge_mm.h:522
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
```
```
In mm/huge_memory.c (ffffffff814a7856)
Location: include/linux/huge_mm.h:522
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/userfaultfd.c (ffffffff814d2c8d)
Location: include/linux/huge_mm.h:522
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
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
