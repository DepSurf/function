# Function: <code>linear_page_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bbf1b)
Location: include/linux/pagemap.h:419
Inline: True
Inline callers:
  - mm/memory.c:print_bad_pte
  - mm/memory.c:do_wp_page
```
```
In mm/mincore.c (ffffffff811c261a)
Location: include/linux/pagemap.h:419
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff811ca511)
Location: include/linux/pagemap.h:419
Inline: True
```
```
In mm/ksm.c (ffffffff811e6e1e)
Location: include/linux/pagemap.h:419
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/memcontrol.c (ffffffff811fa8d0)
Location: include/linux/pagemap.h:419
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811c3cd5)
Location: include/linux/pagemap.h:405
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/memory.c (ffffffff811db09f)
Location: include/linux/pagemap.h:405
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff811de19a)
Location: include/linux/pagemap.h:405
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff811e6a11)
Location: include/linux/pagemap.h:405
Inline: True
```
```
In mm/ksm.c (ffffffff81205eb2)
Location: include/linux/pagemap.h:405
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/khugepaged.c (ffffffff8121bd32)
Location: include/linux/pagemap.h:405
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff8121e7ea)
Location: include/linux/pagemap.h:405
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812a532e)
Location: include/linux/pagemap.h:405
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
In mm/shmem.c (ffffffff811d3d05)
Location: include/linux/pagemap.h:424
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/memory.c (ffffffff811ea6da)
Location: include/linux/pagemap.h:424
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff811edfaa)
Location: include/linux/pagemap.h:424
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff811f7db1)
Location: include/linux/pagemap.h:424
Inline: True
```
```
In mm/ksm.c (ffffffff81217ec4)
Location: include/linux/pagemap.h:424
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/khugepaged.c (ffffffff8122d4e1)
Location: include/linux/pagemap.h:424
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81230e1a)
Location: include/linux/pagemap.h:424
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/dax.c (ffffffff8129ca71)
Location: include/linux/pagemap.h:424
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff812bac81)
Location: include/linux/pagemap.h:424
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
In mm/shmem.c (ffffffff811dcb97)
Location: include/linux/pagemap.h:440
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/memory.c (ffffffff811f5687)
Location: include/linux/pagemap.h:440
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff811f8fba)
Location: include/linux/pagemap.h:440
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff81203341)
Location: include/linux/pagemap.h:440
Inline: True
```
```
In mm/ksm.c (ffffffff81223a98)
Location: include/linux/pagemap.h:440
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff8122dee8)
Location: include/linux/pagemap.h:440
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff81239e1d)
Location: include/linux/pagemap.h:440
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8123c67a)
Location: include/linux/pagemap.h:440
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff8124b74e)
Location: include/linux/pagemap.h:440
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff812aaefe)
Location: include/linux/pagemap.h:440
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
```
In fs/proc/task_mmu.c (ffffffff812c7f01)
Location: include/linux/pagemap.h:440
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
In mm/shmem.c (ffffffff811eea8a)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/memory.c (ffffffff8120e58a)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff812112fa)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff8121be81)
Location: include/linux/pagemap.h:453
Inline: True
```
```
In mm/ksm.c (ffffffff8123f0d8)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff81249c12)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff81258852)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8125c301)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff8126ba70)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff812ce739)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
```
In fs/proc/task_mmu.c (ffffffff812ec0a8)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/shmem.c (ffffffff8120f5cb)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/memory.c (ffffffff8122fd31)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff81231e41)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff8123dcae)
Location: include/linux/pagemap.h:453
Inline: True
```
```
In mm/ksm.c (ffffffff81262895)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff8126d45c)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff8127cf50)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8127fca8)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff81290576)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff812f7d25)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_mapping_entry
```
```
In fs/proc/task_mmu.c (ffffffff813197dd)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/shmem.c (ffffffff812224f8)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/memory.c (ffffffff81241a21)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff81245611)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff8125229e)
Location: include/linux/pagemap.h:453
Inline: True
```
```
In mm/ksm.c (ffffffff81277115)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff81281b4c)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff81291ace)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81294614)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff812a5ae6)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff8130d101)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
```
```
In fs/proc/task_mmu.c (ffffffff813303fe)
Location: include/linux/pagemap.h:453
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/shmem.c (ffffffff81231af8)
Location: include/linux/pagemap.h:437
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/memory.c (ffffffff8125438e)
Location: include/linux/pagemap.h:437
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff812576c0)
Location: include/linux/pagemap.h:437
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff8126443e)
Location: include/linux/pagemap.h:437
Inline: True
```
```
In mm/ksm.c (ffffffff81292bee)
Location: include/linux/pagemap.h:437
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff8129dc5c)
Location: include/linux/pagemap.h:437
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812ac892)
Location: include/linux/pagemap.h:437
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812b084a)
Location: include/linux/pagemap.h:437
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff812c11d4)
Location: include/linux/pagemap.h:437
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff81334496)
Location: include/linux/pagemap.h:437
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
```
```
In fs/proc/task_mmu.c (ffffffff8135822e)
Location: include/linux/pagemap.h:437
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/shmem.c (ffffffff8123fbb8)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/memory.c (ffffffff812628ee)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff81265c10)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff81272cae)
Location: include/linux/pagemap.h:447
Inline: True
```
```
In mm/ksm.c (ffffffff812a296e)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812ad50c)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812be230)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812c22aa)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff812d3124)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff81348061)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
```
```
In fs/proc/task_mmu.c (ffffffff8137045e)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int linear_page_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8126e422)
Location: include/linux/pagemap.h:488
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/memory.c (ffffffff812946ad)
Location: include/linux/pagemap.h:488
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
Direct callers:
  - mm/memory.c:print_bad_pte
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff81295f40)
Location: include/linux/pagemap.h:488
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff812a6b68)
Location: include/linux/pagemap.h:488
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
```
```
In mm/ksm.c (ffffffff812d70ee)
Location: include/linux/pagemap.h:488
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812e286c)
Location: include/linux/pagemap.h:488
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812f3bc5)
Location: include/linux/pagemap.h:488
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812f9200)
Location: include/linux/pagemap.h:488
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff8130894d)
Location: include/linux/pagemap.h:488
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_zeropage_pte
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/dax.c (ffffffff8138d675)
Location: include/linux/pagemap.h:488
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
```
```
In fs/proc/task_mmu.c (ffffffff813b8329)
Location: include/linux/pagemap.h:488
Inline: True
```
**Symbols:**

```
ffffffff8128b9c0-ffffffff8128b9e3: linear_page_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int linear_page_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81278e22)
Location: include/linux/pagemap.h:551
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/memory.c (ffffffff8129ef2d)
Location: include/linux/pagemap.h:551
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
Direct callers:
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff812a1104)
Location: include/linux/pagemap.h:551
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff812b2008)
Location: include/linux/pagemap.h:551
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
```
```
In mm/madvise.c (ffffffff812c0f97)
Location: include/linux/pagemap.h:551
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/ksm.c (ffffffff812e29d9)
Location: include/linux/pagemap.h:551
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812edc9c)
Location: include/linux/pagemap.h:551
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812ff352)
Location: include/linux/pagemap.h:551
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8130506b)
Location: include/linux/pagemap.h:551
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff8131472b)
Location: include/linux/pagemap.h:551
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/dax.c (ffffffff8139ee05)
Location: include/linux/pagemap.h:551
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
```
```
In fs/proc/task_mmu.c (ffffffff813c9a89)
Location: include/linux/pagemap.h:551
Inline: True
```
**Symbols:**

```
ffffffff81296970-ffffffff81296993: linear_page_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int linear_page_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127ddd2)
Location: include/linux/pagemap.h:567
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/memory.c (ffffffff812a3f7a)
Location: include/linux/pagemap.h:567
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
Direct callers:
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff812a6904)
Location: include/linux/pagemap.h:567
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff812b76d8)
Location: include/linux/pagemap.h:567
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
```
```
In mm/madvise.c (ffffffff812c7daa)
Location: include/linux/pagemap.h:567
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/ksm.c (ffffffff812ea169)
Location: include/linux/pagemap.h:567
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812f3e2c)
Location: include/linux/pagemap.h:567
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff81305fcf)
Location: include/linux/pagemap.h:567
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8130a506)
Location: include/linux/pagemap.h:567
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff8131b275)
Location: include/linux/pagemap.h:567
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/dax.c (ffffffff813a5f15)
Location: include/linux/pagemap.h:567
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
```
```
In fs/proc/task_mmu.c (ffffffff813d0b76)
Location: include/linux/pagemap.h:567
Inline: True
```
**Symbols:**

```
ffffffff8129c510-ffffffff8129c533: linear_page_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int linear_page_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812bfe4f)
Location: include/linux/pagemap.h:566
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/memory.c (ffffffff812e529a)
Location: include/linux/pagemap.h:566
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
Direct callers:
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff812e7de4)
Location: include/linux/pagemap.h:566
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff812f9de8)
Location: include/linux/pagemap.h:566
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
```
```
In mm/madvise.c (ffffffff8130cb70)
Location: include/linux/pagemap.h:566
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/ksm.c (ffffffff8133208b)
Location: include/linux/pagemap.h:566
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff8133e87c)
Location: include/linux/pagemap.h:566
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff8134fe3d)
Location: include/linux/pagemap.h:566
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81355c66)
Location: include/linux/pagemap.h:566
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff813681b5)
Location: include/linux/pagemap.h:566
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/dax.c (ffffffff813f5985)
Location: include/linux/pagemap.h:566
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
```
```
In fs/proc/task_mmu.c (ffffffff8142140e)
Location: include/linux/pagemap.h:566
Inline: True
```
**Symbols:**

```
ffffffff812dd060-ffffffff812dd083: linear_page_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int linear_page_index(struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8131c729)
Location: include/linux/pagemap.h:848
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81347571)
Location: include/linux/pagemap.h:848
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
Direct callers:
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff81349047)
Location: include/linux/pagemap.h:848
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff813600b9)
Location: include/linux/pagemap.h:848
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
```
```
In mm/madvise.c (ffffffff813760a0)
Location: include/linux/pagemap.h:848
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/ksm.c (ffffffff813a30ef)
Location: include/linux/pagemap.h:848
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff813b1c03)
Location: include/linux/pagemap.h:848
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff813c8056)
Location: include/linux/pagemap.h:848
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff813ce910)
Location: include/linux/pagemap.h:848
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff813e59c9)
Location: include/linux/pagemap.h:848
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/dax.c (ffffffff81468b04)
Location: include/linux/pagemap.h:848
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
```
```
In fs/proc/task_mmu.c (ffffffff8149827f)
Location: include/linux/pagemap.h:848
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_hole
  - fs/proc/task_mmu.c:smaps_pte_hole
```
**Symbols:**

```
ffffffff8133cd50-ffffffff8133cd83: linear_page_index (STB_LOCAL)
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
In mm/shmem.c (ffffffff81390396)
Location: include/linux/pagemap.h:844
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff813bf96e)
Location: include/linux/pagemap.h:844
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff813c112d)
Location: include/linux/pagemap.h:844
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff813db024)
Location: include/linux/pagemap.h:844
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
```
```
In mm/madvise.c (ffffffff813f39f0)
Location: include/linux/pagemap.h:844
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/ksm.c (ffffffff81422d6b)
Location: include/linux/pagemap.h:844
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff814326ae)
Location: include/linux/pagemap.h:844
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff8144cb21)
Location: include/linux/pagemap.h:844
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8145338a)
Location: include/linux/pagemap.h:844
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff8146d4a0)
Location: include/linux/pagemap.h:844
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/dax.c (ffffffff814f95e0)
Location: include/linux/pagemap.h:844
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
```
```
In fs/proc/task_mmu.c (ffffffff8152c3cf)
Location: include/linux/pagemap.h:844
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_hole
  - fs/proc/task_mmu.c:smaps_pte_hole
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
In mm/shmem.c (ffffffff813c2cfc)
Location: include/linux/pagemap.h:865
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff813f4631)
Location: include/linux/pagemap.h:865
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff813f5e70)
Location: include/linux/pagemap.h:865
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff8140f76e)
Location: include/linux/pagemap.h:865
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
```
```
In mm/madvise.c (ffffffff814274b6)
Location: include/linux/pagemap.h:865
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
  - mm/madvise.c:shmem_swapin_range
```
```
In mm/ksm.c (ffffffff81457dd9)
Location: include/linux/pagemap.h:865
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff81467dac)
Location: include/linux/pagemap.h:865
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff814823cf)
Location: include/linux/pagemap.h:865
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81488f98)
Location: include/linux/pagemap.h:865
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff814a1ed3)
Location: include/linux/pagemap.h:865
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_pte_zeropage
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/dax.c (ffffffff81530a5a)
Location: include/linux/pagemap.h:865
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
```
```
In fs/proc/task_mmu.c (ffffffff8156478f)
Location: include/linux/pagemap.h:865
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_hole
  - fs/proc/task_mmu.c:smaps_pte_hole
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
In mm/shmem.c (ffffffff813ed9a1)
Location: include/linux/pagemap.h:957
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81420c38)
Location: include/linux/pagemap.h:957
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff81421b45)
Location: include/linux/pagemap.h:957
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff8143c0e1)
Location: include/linux/pagemap.h:957
Inline: True
Inline callers:
  - mm/rmap.c:hugetlb_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_anon_rmap_pmd
  - mm/rmap.c:folio_add_anon_rmap_ptes
```
```
In mm/madvise.c (ffffffff81460bae)
Location: include/linux/pagemap.h:957
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
  - mm/madvise.c:shmem_swapin_range
```
```
In mm/hugetlb.c (ffffffff8147b55d)
Location: include/linux/pagemap.h:957
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
```
```
In mm/ksm.c (ffffffff81492880)
Location: include/linux/pagemap.h:957
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff81497815)
Location: include/linux/pagemap.h:957
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff814a4a17)
Location: include/linux/pagemap.h:957
Inline: True
Inline callers:
  - mm/huge_memory.c:move_pages_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814b1775)
Location: include/linux/pagemap.h:957
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff814b8f08)
Location: include/linux/pagemap.h:957
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff814d208f)
Location: include/linux/pagemap.h:957
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/dax.c (ffffffff8156590c)
Location: include/linux/pagemap.h:957
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
```
```
In fs/proc/task_mmu.c (ffffffff8159ff3f)
Location: include/linux/pagemap.h:957
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_entry
  - fs/proc/task_mmu.c:smaps_pte_entry
```
</details>
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
In mm/shmem.c (ffff8000102d2f1c)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/memory.c (ffff8000102f9b8c)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffff8000102fcdf0)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffff800010308814)
Location: include/linux/pagemap.h:447
Inline: True
```
```
In mm/ksm.c (ffff8000103423b4)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffff80001034ef5c)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffff80001035fb54)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffff800010363d94)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffff800010378c94)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/dax.c (ffff800010408bf8)
Location: include/linux/pagemap.h:447
Inline: True
```
```
In fs/proc/task_mmu.c (ffff80001043a120)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/shmem.c (c04fae64)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/memory.c (c051bd4c)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (c051c4e4)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (c0525a28)
Location: include/linux/pagemap.h:447
Inline: True
```
```
In mm/ksm.c (c054811c)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (c05516b0)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (c05560b8)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (c0564068)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/proc/task_mmu.c (c0600c50)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/shmem.c (c0000000003918cc)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/memory.c (c0000000003c3aa0)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (c0000000003c7e14)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (c0000000003d7840)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/rmap.c:__page_set_anon_rmap
```
```
In mm/ksm.c (c00000000041fd9c)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (c00000000043142c)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (c00000000044a84c)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (c000000000450fc4)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (c00000000046b99c)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (c00000000051421c)
Location: include/linux/pagemap.h:447
Inline: True
```
```
In fs/proc/task_mmu.c (c00000000054e098)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/shmem.c (ffffffe0001ee174)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/memory.c (ffffffe000209872)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffe00020ba24)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffe00021302e)
Location: include/linux/pagemap.h:447
Inline: True
```
```
In mm/ksm.c (ffffffe0002365d4)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffe00023e240)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffe000241c56)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffe00025054c)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffe0002b304e)
Location: include/linux/pagemap.h:447
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffe0002d341c)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/shmem.c (ffffffff81238208)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/memory.c (ffffffff8125af3e)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff8125e260)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff8126b2fe)
Location: include/linux/pagemap.h:447
Inline: True
```
```
In mm/ksm.c (ffffffff8129af4e)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812a5aec)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812b6810)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812ba88a)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff812cb704)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff81340641)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
```
```
In fs/proc/task_mmu.c (ffffffff81368a3e)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/shmem.c (ffffffff8122b246)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/memory.c (ffffffff8124d27e)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff812506f0)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff8125d3de)
Location: include/linux/pagemap.h:447
Inline: True
```
```
In mm/ksm.c (ffffffff8128cb0e)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812975bc)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812a79e0)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812aba48)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff812bc575)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff813312a1)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
```
```
In fs/proc/task_mmu.c (ffffffff81359cf0)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In drivers/dax/device.c (ffffffff816f1bcd)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - drivers/dax/device.c:dev_dax_huge_fault
  - drivers/dax/device.c:dev_dax_huge_fault
  - drivers/dax/device.c:dev_dax_huge_fault
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
In mm/shmem.c (ffffffff81235fa8)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/memory.c (ffffffff81258cde)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff8125c000)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff8126909e)
Location: include/linux/pagemap.h:447
Inline: True
```
```
In mm/ksm.c (ffffffff81298d5e)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812a38fc)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812b4620)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812b869a)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff812c9514)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff8133e111)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
```
```
In fs/proc/task_mmu.c (ffffffff8136650e)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/shmem.c (ffffffff81246288)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_swap_usage
```
```
In mm/memory.c (ffffffff812686de)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff8126b9f0)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/rmap.c (ffffffff81278bde)
Location: include/linux/pagemap.h:447
Inline: True
```
```
In mm/ksm.c (ffffffff812a8b3e)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812b410c)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812c4f6f)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812c8cda)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff812da1f4)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff81350d41)
Location: include/linux/pagemap.h:447
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
```
```
In fs/proc/task_mmu.c (ffffffff8137984e)
Location: include/linux/pagemap.h:447
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
