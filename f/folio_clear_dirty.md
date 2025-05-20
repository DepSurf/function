# Function: <code>folio_clear_dirty</code>

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
In mm/page-writeback.c (ffffffff81300389)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_cancel_dirty
```
```
In mm/vmscan.c (ffffffff8130deec)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff81319297)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/migrate.c (ffffffff813b1fb2)
Location: include/linux/page-flags.h:498
Inline: True
Inline callers:
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
In mm/page-writeback.c (ffffffff8136aca9)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_cancel_dirty
```
```
In mm/vmscan.c (ffffffff8137917c)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8138d330)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_writepage
```
```
In mm/madvise.c (ffffffff813f42dc)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff81431ae4)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6a79)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/page-writeback.c (ffffffff8139ce39)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_cancel_dirty
```
```
In mm/vmscan.c (ffffffff813ad746)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff813bfd76)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_writepage
```
```
In mm/madvise.c (ffffffff81427a38)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff81467706)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff81477e2f)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/ext4/inline.c (ffffffff815adbdc)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff815b5ebe)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/hugetlbfs/inode.c (ffffffff8162eb39)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In mm/page-writeback.c (ffffffff813c6b29)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_cancel_dirty
```
```
In mm/vmscan.c (ffffffff813d6b53)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff813ea69a)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/madvise.c (ffffffff8146124c)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff81496bbe)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff814a75a3)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff814c5166)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In fs/ext4/inline.c (ffffffff815e699c)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff815eec64)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/hugetlbfs/inode.c (ffffffff81667fec)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
