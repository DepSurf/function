# Function: <code>linear_hugepage_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811dc3c0)
Location: mm/hugetlb.c:623
Inline: False
Direct callers:
  - mm/memory.c:print_bad_pte
  - mm/memory.c:do_wp_page
  - mm/mincore.c:__mincore_unmapped_range
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/memcontrol.c:get_mctgt_type
```
**Symbols:**

```
ffffffff811dc3c0-ffffffff811dc403: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811f7c80)
Location: mm/hugetlb.c:625
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:print_bad_pte
  - mm/mincore.c:__mincore_unmapped_range
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:get_mctgt_type
```
**Symbols:**

```
ffffffff811f7c80-ffffffff811f7cc0: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81208630)
Location: mm/hugetlb.c:625
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
  - mm/memory.c:print_bad_pte
  - mm/mincore.c:__mincore_unmapped_range
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/memcontrol.c:get_mctgt_type
  - fs/dax.c:dax_iomap_pmd_fault
```
**Symbols:**

```
ffffffff81208630-ffffffff81208670: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81213c20)
Location: mm/hugetlb.c:627
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
  - mm/mincore.c:__mincore_unmapped_range
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/memcontrol.c:get_mctgt_type
  - mm/userfaultfd.c:mcopy_atomic
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff81213c20-ffffffff81213c60: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8122e7b0)
Location: mm/hugetlb.c:628
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
  - mm/mincore.c:__mincore_unmapped_range
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/memcontrol.c:get_mctgt_type
  - mm/userfaultfd.c:mcopy_atomic
  - fs/dax.c:dax_iomap_fault
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8122e7b0-ffffffff8122e7f0: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81251640)
Location: mm/hugetlb.c:627
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
  - mm/mincore.c:__mincore_unmapped_range
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/memcontrol.c:get_mctgt_type
  - mm/userfaultfd.c:mcopy_atomic
  - fs/dax.c:dax_insert_mapping_entry
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81251640-ffffffff81251680: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81265a40)
Location: mm/hugetlb.c:627
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
  - mm/mincore.c:__mincore_unmapped_range
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/memcontrol.c:get_mctgt_type
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/dax.c:dax_insert_entry
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81265a40-ffffffff81265a80: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81280ab0)
Location: mm/hugetlb.c:629
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
  - mm/mincore.c:__mincore_unmapped_range
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/memcontrol.c:get_mctgt_type
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/dax.c:dax_insert_entry
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81280ab0-ffffffff81280af0: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812904c0)
Location: mm/hugetlb.c:630
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
  - mm/mincore.c:__mincore_unmapped_range
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/memcontrol.c:get_mctgt_type
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/dax.c:dax_insert_entry
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812904c0-ffffffff81290500: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c3120)
Location: mm/hugetlb.c:769
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
  - mm/memory.c:__handle_mm_fault
  - mm/mincore.c:__mincore_unmapped_range
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/memcontrol.c:get_mctgt_type
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_zeropage_pte
  - mm/userfaultfd.c:mcopy_atomic_pte
  - fs/dax.c:dax_insert_entry
```
**Symbols:**

```
ffffffff812c3120-ffffffff812c3160: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812cee70)
Location: mm/hugetlb.c:799
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
  - mm/memory.c:__handle_mm_fault
  - mm/mincore.c:__mincore_unmapped_range
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/memcontrol.c:get_mctgt_type
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
  - fs/dax.c:dax_insert_entry
```
**Symbols:**

```
ffffffff812cee70-ffffffff812ceeb0: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d5a90)
Location: mm/hugetlb.c:806
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
  - mm/memory.c:__handle_mm_fault
  - mm/mincore.c:__mincore_unmapped_range
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/memcontrol.c:get_mctgt_type
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
  - fs/dax.c:dax_insert_entry
```
**Symbols:**

```
ffffffff812d5a90-ffffffff812d5ad0: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:808
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
  - mm/memory.c:__handle_mm_fault
  - mm/mincore.c:__mincore_unmapped_range
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/memcontrol.c:get_mctgt_type
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - fs/dax.c:dax_insert_entry
```
**Symbols:**

```
ffffffff81cbf396-ffffffff81cbf3e3: linear_hugepage_index.cold (STB_LOCAL)
ffffffff8131cf80-ffffffff8131cfef: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:825
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/memory.c:__handle_mm_fault
  - mm/mincore.c:__mincore_unmapped_range
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/memcontrol.c:get_mctgt_type
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - fs/dax.c:dax_insert_entry
  - fs/proc/task_mmu.c:smaps_pte_hole
  - fs/proc/task_mmu.c:smaps_pte_hole
```
**Symbols:**

```
ffffffff81e71731-ffffffff81e7177e: linear_hugepage_index.cold (STB_LOCAL)
ffffffff81389930-ffffffff813899ab: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:969
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
  - mm/mincore.c:__mincore_unmapped_range
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/memcontrol.c:get_mctgt_type
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - fs/dax.c:dax_insert_entry
  - fs/proc/task_mmu.c:smaps_pte_hole
  - fs/proc/task_mmu.c:smaps_pte_hole
```
**Symbols:**

```
ffffffff82066158-ffffffff820661a5: linear_hugepage_index.cold (STB_LOCAL)
ffffffff814073a0-ffffffff81407415: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:963
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
  - mm/mincore.c:__mincore_unmapped_range
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/madvise.c:shmem_swapin_range
  - mm/madvise.c:shmem_swapin_range
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/memcontrol.c:get_mctgt_type
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_pte_zeropage
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - fs/dax.c:dax_insert_entry
  - fs/proc/task_mmu.c:smaps_pte_hole
  - fs/proc/task_mmu.c:smaps_pte_hole
```
**Symbols:**

```
ffffffff820e5905-ffffffff820e5952: linear_hugepage_index.cold (STB_LOCAL)
ffffffff8143abd0-ffffffff8143ac4e: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff80001032d5b8)
Location: mm/hugetlb.c:630
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
  - mm/mincore.c:__mincore_unmapped_range
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/memcontrol.c:get_mctgt_type
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffff80001032d5b8-ffff80001032d614: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000405100)
Location: mm/hugetlb.c:630
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
  - mm/mincore.c:__mincore_unmapped_range
  - mm/rmap.c:__page_set_anon_rmap
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/memcontrol.c:get_mctgt_type
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
c000000000405100-c000000000405140: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022bbd8)
Location: mm/hugetlb.c:630
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
  - mm/mincore.c:__mincore_unmapped_range
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:remove_migration_pte
  - mm/memcontrol.c:get_mctgt_type
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffe00022bbd8-ffffffe00022bc26: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81288aa0)
Location: mm/hugetlb.c:630
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
  - mm/mincore.c:__mincore_unmapped_range
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/memcontrol.c:get_mctgt_type
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/dax.c:dax_insert_entry
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81288aa0-ffffffff81288ae0: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127a8f0)
Location: mm/hugetlb.c:630
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
  - mm/mincore.c:__mincore_unmapped_range
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/memcontrol.c:get_mctgt_type
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/dax.c:dax_insert_entry
  - fs/proc/task_mmu.c:smaps_pte_range
  - drivers/dax/device.c:dev_dax_huge_fault
  - drivers/dax/device.c:dev_dax_huge_fault
  - drivers/dax/device.c:dev_dax_huge_fault
```
**Symbols:**

```
ffffffff8127a8f0-ffffffff8127a930: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812868b0)
Location: mm/hugetlb.c:630
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
  - mm/mincore.c:__mincore_unmapped_range
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/memcontrol.c:get_mctgt_type
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/dax.c:dax_insert_entry
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812868b0-ffffffff812868f0: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812966a0)
Location: mm/hugetlb.c:630
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
  - mm/mincore.c:__mincore_unmapped_range
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/memcontrol.c:get_mctgt_type
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/dax.c:dax_insert_entry
```
**Symbols:**

```
ffffffff812966a0-ffffffff812966e0: linear_hugepage_index (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
