# Function: <code>folio_maybe_dma_pinned</code>

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
In mm/vmscan.c (ffffffff8130e93b)
Location: include/linux/mm.h:1558
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (ffffffff813402cf)
Location: include/linux/mm.h:1558
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff8135e7a2)
Location: include/linux/mm.h:1558
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81391b5d)
Location: include/linux/mm.h:1558
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff813a092d)
Location: include/linux/mm.h:1558
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff813b7a6a)
Location: include/linux/mm.h:1558
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c1c34)
Location: include/linux/mm.h:1558
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8149a8fc)
Location: include/linux/mm.h:1558
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
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
In mm/vmscan.c (ffffffff8138089f)
Location: include/linux/mm.h:1676
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/memory.c (ffffffff813b825f)
Location: include/linux/mm.h:1676
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff813d99c4)
Location: include/linux/mm.h:1676
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8140ebae)
Location: include/linux/mm.h:1676
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8142009c)
Location: include/linux/mm.h:1676
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff814396e8)
Location: include/linux/mm.h:1676
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81443dd1)
Location: include/linux/mm.h:1676
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8152ee1c)
Location: include/linux/mm.h:1676
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
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
In mm/vmscan.c (ffffffff813b1946)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/memory.c (ffffffff813ed04e)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff8140de9a)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81441f68)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff81454caa)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8146fb53)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8147931d)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8156712c)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In fs/ext4/inode.c (ffffffff815b04e0)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
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
In mm/vmscan.c (ffffffff813daeb5)
Location: include/linux/mm.h:1939
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/memory.c (ffffffff8141857d)
Location: include/linux/mm.h:1939
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff8143a54f)
Location: include/linux/mm.h:1939
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8147c2ab)
Location: include/linux/mm.h:1939
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8148ff77)
Location: include/linux/mm.h:1939
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8149e227)
Location: include/linux/mm.h:1939
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a8886)
Location: include/linux/mm.h:1939
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/userfaultfd.c (ffffffff814cff04)
Location: include/linux/mm.h:1939
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159ccbf)
Location: include/linux/mm.h:1939
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In fs/ext4/inode.c (ffffffff815e92d0)
Location: include/linux/mm.h:1939
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
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
