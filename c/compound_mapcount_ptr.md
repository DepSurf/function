# Function: <code>compound_mapcount_ptr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:502
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/mm.h:502
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm.h:502
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:502
Inline: True
```
```
In mm/rmap.c (ffffffff811e8082)
Location: include/linux/mm.h:502
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/mm.h:502
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/mm.h:502
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/mm.h:502
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:489
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/mm.h:489
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm.h:489
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:489
Inline: True
```
```
In mm/rmap.c (ffffffff811f9402)
Location: include/linux/mm.h:489
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/mm.h:489
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/mm.h:489
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/mm.h:489
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:545
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/mm.h:545
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/mm.h:545
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm.h:545
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:545
Inline: True
```
```
In mm/rmap.c (ffffffff81203f19)
Location: include/linux/mm.h:545
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/mm.h:545
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/mm.h:545
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/mm.h:545
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:562
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/mm.h:562
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/mm.h:562
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm.h:562
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:562
Inline: True
```
```
In mm/rmap.c (ffffffff8121cc89)
Location: include/linux/mm.h:562
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:562
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/mm.h:562
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/mm.h:562
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/mm.h:562
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:604
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/mm.h:604
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/mm.h:604
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm.h:604
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:604
Inline: True
```
```
In mm/rmap.c (ffffffff812403fb)
Location: include/linux/mm.h:604
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:604
Inline: True
```
```
In mm/hugetlb.c (ffffffff81255562)
Location: include/linux/mm.h:604
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff8126d56d)
Location: include/linux/mm.h:604
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8127756d)
Location: include/linux/mm.h:604
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:632
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/mm.h:632
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/mm.h:632
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm.h:632
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:632
Inline: True
```
```
In mm/rmap.c (ffffffff81254afb)
Location: include/linux/mm.h:632
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:632
Inline: True
```
```
In mm/hugetlb.c (ffffffff8126993d)
Location: include/linux/mm.h:632
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff81281c5d)
Location: include/linux/mm.h:632
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81288d6a)
Location: include/linux/mm.h:632
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (0)
Location: include/linux/mm.h:698
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/mm.h:698
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm.h:698
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:698
Inline: True
```
```
In mm/rmap.c (ffffffff81266db7)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:698
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:698
Inline: True
```
```
In mm/hugetlb.c (ffffffff81284a77)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff8129dd5d)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a39d5)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/rmap.c (ffffffff812756d7)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/hugetlb.c (ffffffff81294617)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812ad60d)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b4ed5)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/rmap.c (ffffffff812a6ac7)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/hugetlb.c (ffffffff812c7a09)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812e29b9)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ea397)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (0)
Location: include/linux/mm_types.h:227
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/mm_types.h:227
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm_types.h:227
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm_types.h:227
Inline: True
```
```
In mm/rmap.c (ffffffff812b1f67)
Location: include/linux/mm_types.h:227
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm_types.h:227
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/mm_types.h:227
Inline: True
```
```
In mm/hugetlb.c (ffffffff812d3579)
Location: include/linux/mm_types.h:227
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812edde4)
Location: include/linux/mm_types.h:227
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812f556e)
Location: include/linux/mm_types.h:227
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (0)
Location: include/linux/mm_types.h:227
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/mm_types.h:227
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm_types.h:227
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm_types.h:227
Inline: True
```
```
In mm/rmap.c (ffffffff812b7637)
Location: include/linux/mm_types.h:227
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm_types.h:227
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/mm_types.h:227
Inline: True
```
```
In mm/hugetlb.c (ffffffff812da39c)
Location: include/linux/mm_types.h:227
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812f3f93)
Location: include/linux/mm_types.h:227
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812fbbc5)
Location: include/linux/mm_types.h:227
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (0)
Location: include/linux/mm_types.h:242
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/mm_types.h:242
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm_types.h:242
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm_types.h:242
Inline: True
```
```
In mm/rmap.c (ffffffff812f9d47)
Location: include/linux/mm_types.h:242
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm_types.h:242
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/mm_types.h:242
Inline: True
```
```
In mm/hugetlb.c (ffffffff81321291)
Location: include/linux/mm_types.h:242
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff8133e9c4)
Location: include/linux/mm_types.h:242
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff813459be)
Location: include/linux/mm_types.h:242
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (0)
Location: include/linux/mm_types.h:304
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm_types.h:304
Inline: True
```
```
In mm/rmap.c (ffffffff8135ffe5)
Location: include/linux/mm_types.h:304
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_anon_rmap
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm_types.h:304
Inline: True
```
```
In mm/hugetlb.c (ffffffff8138e2c4)
Location: include/linux/mm_types.h:304
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff813b1aaf)
Location: include/linux/mm_types.h:304
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff813bbaff)
Location: include/linux/mm_types.h:304
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/filemap.c (0)
Location: include/linux/mm_types.h:436
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm_types.h:436
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm_types.h:436
Inline: True
```
```
In mm/rmap.c (ffffffff813daf42)
Location: include/linux/mm_types.h:436
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_anon_rmap
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm_types.h:436
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/mm_types.h:436
Inline: True
```
```
In mm/hugetlb.c (ffffffff8140ceba)
Location: include/linux/mm_types.h:436
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (0)
Location: include/linux/mm_types.h:436
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/mm_types.h:436
Inline: True
```
```
In mm/migrate.c (ffffffff81432555)
Location: include/linux/mm_types.h:436
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (0)
Location: include/linux/mm_types.h:436
Inline: True
```
```
In mm/huge_memory.c (ffffffff81441200)
Location: include/linux/mm_types.h:436
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (0)
Location: include/linux/mm_types.h:436
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/mm_types.h:436
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm_types.h:436
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/mm_types.h:436
Inline: True
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/mmu.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/rmap.c (ffff80001030b67c)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/hugetlb.c (ffff80001033308c)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffff80001034f120)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffff800010355fa0)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/rmap.c (c052602c)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c00000000038769c)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/util.c (c000000000398000)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/debug.c (c0000000003b5180)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/rmap.c (c0000000003db884)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_alloc.c (c0000000003e51bc)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (c00000000040ee30)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/migrate.c (c000000000431374)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (c000000000442820)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/rmap.c (ffffffe000214fde)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/hugetlb.c (ffffffe00022f5aa)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffe00023e1fe)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/rmap.c (ffffffff8126dd27)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128cbf7)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812a5bed)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ad4b5)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/rmap.c (ffffffff8125fd57)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/hugetlb.c (ffffffff8127ea19)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812976bb)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8129e46c)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/rmap.c (ffffffff8126bac7)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128aa07)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812a39fd)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ab2c5)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/util.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/rmap.c (ffffffff8127b457)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/mm_types.h:224
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129a7fc)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812b420d)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812bb615)
Location: include/linux/mm_types.h:224
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
</ul>

## Differences
