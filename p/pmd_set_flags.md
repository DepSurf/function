# Function: <code>pmd_set_flags</code>

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
In mm/migrate.c (ffffffff811f33e3)
Location: arch/x86/include/asm/pgtable.h:258
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f43d3)
Location: arch/x86/include/asm/pgtable.h:258
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
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
In mm/memory.c (ffffffff811da313)
Location: arch/x86/include/asm/pgtable.h:277
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff812131c4)
Location: arch/x86/include/asm/pgtable.h:277
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81215c06)
Location: arch/x86/include/asm/pgtable.h:277
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8121a72b)
Location: arch/x86/include/asm/pgtable.h:277
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
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
In mm/memory.c (ffffffff811e9e3b)
Location: arch/x86/include/asm/pgtable.h:277
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff8122552c)
Location: arch/x86/include/asm/pgtable.h:277
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81228226)
Location: arch/x86/include/asm/pgtable.h:277
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8122eb35)
Location: arch/x86/include/asm/pgtable.h:277
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (ffffffff8129cf1b)
Location: arch/x86/include/asm/pgtable.h:277
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
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
In mm/memory.c (ffffffff811f4f34)
Location: arch/x86/include/asm/pgtable.h:334
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff81230bfd)
Location: arch/x86/include/asm/pgtable.h:334
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812343bc)
Location: arch/x86/include/asm/pgtable.h:334
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81238803)
Location: arch/x86/include/asm/pgtable.h:334
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812abd18)
Location: arch/x86/include/asm/pgtable.h:334
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
```
In fs/proc/task_mmu.c (ffffffff812c6890)
Location: arch/x86/include/asm/pgtable.h:334
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff826ad894)
Location: arch/x86/include/asm/pgtable.h:349
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
```
In mm/memory.c (ffffffff8120d034)
Location: arch/x86/include/asm/pgtable.h:349
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff8124e97f)
Location: arch/x86/include/asm/pgtable.h:349
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81255cee)
Location: arch/x86/include/asm/pgtable.h:349
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81259c70)
Location: arch/x86/include/asm/pgtable.h:349
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (ffffffff812cf5c4)
Location: arch/x86/include/asm/pgtable.h:349
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
```
In fs/proc/task_mmu.c (ffffffff812ecdb2)
Location: arch/x86/include/asm/pgtable.h:349
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff826d6bac)
Location: arch/x86/include/asm/pgtable.h:359
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810779d2)
Location: arch/x86/include/asm/pgtable.h:359
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pti.c (ffffffff81083625)
Location: arch/x86/include/asm/pgtable.h:359
Inline: True
```
```
In mm/memory.c (ffffffff8122dbf5)
Location: arch/x86/include/asm/pgtable.h:359
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff812727a3)
Location: arch/x86/include/asm/pgtable.h:359
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81279b44)
Location: arch/x86/include/asm/pgtable.h:359
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8127c5dc)
Location: arch/x86/include/asm/pgtable.h:359
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812f9794)
Location: arch/x86/include/asm/pgtable.h:359
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813193f4)
Location: arch/x86/include/asm/pgtable.h:359
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff8288caf5)
Location: arch/x86/include/asm/pgtable.h:361
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8107e182)
Location: arch/x86/include/asm/pgtable.h:361
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pti.c (ffffffff8108a1a0)
Location: arch/x86/include/asm/pgtable.h:361
Inline: True
```
```
In mm/memory.c (ffffffff81241378)
Location: arch/x86/include/asm/pgtable.h:361
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff81286d8a)
Location: arch/x86/include/asm/pgtable.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8128e121)
Location: arch/x86/include/asm/pgtable.h:361
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81290c9f)
Location: arch/x86/include/asm/pgtable.h:361
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8130e235)
Location: arch/x86/include/asm/pgtable.h:361
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81330a08)
Location: arch/x86/include/asm/pgtable.h:361
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff828a3f8b)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81081a6f)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pti.c (ffffffff8108df20)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
```
```
In mm/memory.c (ffffffff8125383f)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff812a1313)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812a8b63)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812aba93)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81334734)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8135882f)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff828a702b)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81082b2f)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pti.c (ffffffff8108eba0)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
```
```
In mm/memory.c (ffffffff81261d9f)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff812b2733)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812ba0e3)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812bd28d)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81348304)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81370a7f)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff82ccd4b6)
Location: arch/x86/include/asm/pgtable.h:400
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c24e)
Location: arch/x86/include/asm/pgtable.h:400
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In arch/x86/mm/pti.c (ffffffff81094f48)
Location: arch/x86/include/asm/pgtable.h:400
Inline: True
```
```
In mm/memory.c (ffffffff8128c831)
Location: arch/x86/include/asm/pgtable.h:400
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_set_pmd
```
```
In mm/migrate.c (ffffffff812e7cd0)
Location: arch/x86/include/asm/pgtable.h:400
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812eecc2)
Location: arch/x86/include/asm/pgtable.h:400
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812f29be)
Location: arch/x86/include/asm/pgtable.h:400
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8138ed84)
Location: arch/x86/include/asm/pgtable.h:400
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813b8f44)
Location: arch/x86/include/asm/pgtable.h:400
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff82fb92e7)
Location: arch/x86/include/asm/pgtable.h:399
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c4ee)
Location: arch/x86/include/asm/pgtable.h:399
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In arch/x86/mm/pti.c (ffffffff81094308)
Location: arch/x86/include/asm/pgtable.h:399
Inline: True
```
```
In mm/memory.c (ffffffff81297ac3)
Location: arch/x86/include/asm/pgtable.h:399
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_set_pmd
```
```
In mm/migrate.c (ffffffff812f30bc)
Location: arch/x86/include/asm/pgtable.h:399
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812fa312)
Location: arch/x86/include/asm/pgtable.h:399
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812fcfd5)
Location: arch/x86/include/asm/pgtable.h:399
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813a0476)
Location: arch/x86/include/asm/pgtable.h:399
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813ca97b)
Location: arch/x86/include/asm/pgtable.h:399
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff831c38ed)
Location: arch/x86/include/asm/pgtable.h:399
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cf2a)
Location: arch/x86/include/asm/pgtable.h:399
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In arch/x86/mm/pti.c (ffffffff81094c79)
Location: arch/x86/include/asm/pgtable.h:399
Inline: True
```
```
In mm/memory.c (ffffffff812a1875)
Location: arch/x86/include/asm/pgtable.h:399
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_set_pmd
```
```
In mm/migrate.c (ffffffff812f9455)
Location: arch/x86/include/asm/pgtable.h:399
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff813010e1)
Location: arch/x86/include/asm/pgtable.h:399
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81303d4a)
Location: arch/x86/include/asm/pgtable.h:399
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813a6b3b)
Location: arch/x86/include/asm/pgtable.h:399
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813d19df)
Location: arch/x86/include/asm/pgtable.h:399
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff832a43e5)
Location: arch/x86/include/asm/pgtable.h:370
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109c7b6)
Location: arch/x86/include/asm/pgtable.h:370
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In arch/x86/mm/pti.c (ffffffff810a4bfb)
Location: arch/x86/include/asm/pgtable.h:370
Inline: True
```
```
In mm/memory.c (ffffffff812e285f)
Location: arch/x86/include/asm/pgtable.h:370
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_set_pmd
```
```
In mm/huge_memory.c (ffffffff8134ad51)
Location: arch/x86/include/asm/pgtable.h:370
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134daa5)
Location: arch/x86/include/asm/pgtable.h:370
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813f65cb)
Location: arch/x86/include/asm/pgtable.h:370
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81422edf)
Location: arch/x86/include/asm/pgtable.h:370
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff834536fa)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810aff5e)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In arch/x86/mm/pti.c (ffffffff810b94a4)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
```
```
In mm/memory.c (ffffffff81343045)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_set_pmd
```
```
In mm/huge_memory.c (ffffffff813c1fed)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c6cde)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81468cc8)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8149ad6e)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff83e710df)
Location: arch/x86/include/asm/pgtable.h:390
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ca5e1)
Location: arch/x86/include/asm/pgtable.h:390
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In arch/x86/mm/pti.c (ffffffff810d4fea)
Location: arch/x86/include/asm/pgtable.h:390
Inline: True
```
```
In mm/memory.c (ffffffff813bafe8)
Location: arch/x86/include/asm/pgtable.h:390
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_set_pmd
```
```
In mm/huge_memory.c (ffffffff81443fbe)
Location: arch/x86/include/asm/pgtable.h:390
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81449138)
Location: arch/x86/include/asm/pgtable.h:390
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff814f9862)
Location: arch/x86/include/asm/pgtable.h:390
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
```
```
In fs/proc/task_mmu.c (ffffffff8152f2ab)
Location: arch/x86/include/asm/pgtable.h:390
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff83691f56)
Location: arch/x86/include/asm/pgtable.h:391
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cdc12)
Location: arch/x86/include/asm/pgtable.h:391
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In arch/x86/mm/pti.c (ffffffff810d84ea)
Location: arch/x86/include/asm/pgtable.h:391
Inline: True
```
```
In mm/memory.c (ffffffff813efaee)
Location: arch/x86/include/asm/pgtable.h:391
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_set_pmd
```
```
In mm/huge_memory.c (ffffffff8147954f)
Location: arch/x86/include/asm/pgtable.h:391
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8147e91c)
Location: arch/x86/include/asm/pgtable.h:391
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81530ce6)
Location: arch/x86/include/asm/pgtable.h:391
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
```
```
In fs/proc/task_mmu.c (ffffffff8156756f)
Location: arch/x86/include/asm/pgtable.h:391
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff838c1a66)
Location: arch/x86/include/asm/pgtable.h:494
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810d3c4f)
Location: arch/x86/include/asm/pgtable.h:494
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_mkwrite
  - arch/x86/mm/pgtable.c:pmd_mkwrite
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d62f2)
Location: arch/x86/include/asm/pgtable.h:494
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
```
```
In arch/x86/mm/pti.c (ffffffff810e0d6a)
Location: arch/x86/include/asm/pgtable.h:494
Inline: True
```
```
In mm/memory.c (ffffffff8141b145)
Location: arch/x86/include/asm/pgtable.h:494
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_set_pmd
```
```
In mm/huge_memory.c (ffffffff814a8acf)
Location: arch/x86/include/asm/pgtable.h:494
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814af5b0)
Location: arch/x86/include/asm/pgtable.h:494
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81565bc6)
Location: arch/x86/include/asm/pgtable.h:494
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
```
```
In fs/proc/task_mmu.c (ffffffff8159dae5)
Location: arch/x86/include/asm/pgtable.h:494
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82895034)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81081b2f)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pti.c (ffffffff8108db60)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
```
```
In mm/memory.c (ffffffff8125a3ef)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff812aad13)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812b26c3)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b586d)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813408e4)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8136905f)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/mm/pageattr.c (ffffffff810709d5)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pti.c (ffffffff8107c66d)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
```
```
In mm/memory.c (ffffffff8124c813)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff8129c64e)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812a3a42)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812a6a7e)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81333021)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8135a30f)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff828a802b)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81081adf)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pti.c (ffffffff8108db10)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
```
```
In mm/memory.c (ffffffff8125818f)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff812a8b23)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812b04d3)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b367d)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8133e3b4)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81366b2f)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff828a8031)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81083bff)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pti.c (ffffffff8108fef0)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
```
```
In mm/memory.c (ffffffff81267b79)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
```
```
In mm/migrate.c (ffffffff812b8e43)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812c0813)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812c3ae4)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81352719)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8137a185)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
</ul>

## Differences
