# Function: <code>set_pmd_at</code>

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
In mm/pgtable-generic.c (ffffffff811d0696)
Location: arch/x86/include/asm/paravirt.h:503
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/migrate.c (ffffffff811f3446)
Location: arch/x86/include/asm/paravirt.h:503
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f43f0)
Location: arch/x86/include/asm/paravirt.h:503
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In fs/proc/task_mmu.c (ffffffff81278faf)
Location: arch/x86/include/asm/paravirt.h:503
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff811da34c)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/pgtable-generic.c (ffffffff811ed806)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/migrate.c (ffffffff81213230)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81215c17)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8121a7c6)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff812a5847)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff811e9e73)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/pgtable-generic.c (ffffffff811f7bd6)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/migrate.c (ffffffff81225598)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81228237)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8122ebd8)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (ffffffff8129cf2b)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff812bb191)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff811f4f6d)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/pgtable-generic.c (ffffffff81202dc6)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/rmap.c (ffffffff81203293)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/migrate.c (ffffffff81230c68)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8123444f)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8123889e)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812abd32)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff812c68bc)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff8120d05c)
Location: arch/x86/include/asm/pgtable.h:989
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/pgtable-generic.c (0)
Location: arch/x86/include/asm/pgtable.h:989
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:989
Inline: True
```
```
In mm/migrate.c (ffffffff8124e9cc)
Location: arch/x86/include/asm/pgtable.h:989
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81255cc4)
Location: arch/x86/include/asm/pgtable.h:989
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81259cf2)
Location: arch/x86/include/asm/pgtable.h:989
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:989
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:989
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
In mm/memory.c (ffffffff8122dc25)
Location: arch/x86/include/asm/pgtable.h:1040
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/rmap.c (ffffffff8123dc55)
Location: arch/x86/include/asm/pgtable.h:1040
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/migrate.c (ffffffff81272802)
Location: arch/x86/include/asm/pgtable.h:1040
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81279b88)
Location: arch/x86/include/asm/pgtable.h:1040
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8127c656)
Location: arch/x86/include/asm/pgtable.h:1040
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812f86b9)
Location: arch/x86/include/asm/pgtable.h:1040
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff81319411)
Location: arch/x86/include/asm/pgtable.h:1040
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
In mm/memory.c (ffffffff812413c8)
Location: arch/x86/include/asm/pgtable.h:1065
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mremap.c (ffffffff8124f49a)
Location: arch/x86/include/asm/pgtable.h:1065
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8125223b)
Location: arch/x86/include/asm/pgtable.h:1065
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/migrate.c (ffffffff81286db5)
Location: arch/x86/include/asm/pgtable.h:1065
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8128e165)
Location: arch/x86/include/asm/pgtable.h:1065
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81290d22)
Location: arch/x86/include/asm/pgtable.h:1065
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8130c43f)
Location: arch/x86/include/asm/pgtable.h:1065
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81330a25)
Location: arch/x86/include/asm/pgtable.h:1065
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
In mm/memory.c (ffffffff8125388d)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mremap.c (ffffffff812617ec)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff81264a9f)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/migrate.c (ffffffff812a1341)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812a8ad8)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812abb3c)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81333981)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8135884c)
Location: arch/x86/include/asm/pgtable.h:1085
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
In mm/memory.c (ffffffff81261ded)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mremap.c (ffffffff8126ffaa)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff81273326)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff81285360)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff812b2761)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812ba058)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812bd336)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81347546)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81370a9c)
Location: arch/x86/include/asm/pgtable.h:1085
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
In mm/memory.c (ffffffff8128c898)
Location: arch/x86/include/asm/pgtable.h:1045
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/mremap.c (ffffffff8129fe8b)
Location: arch/x86/include/asm/pgtable.h:1045
Inline: True
Inline callers:
  - mm/mremap.c:move_normal_pmd
```
```
In mm/rmap.c (ffffffff812a3f01)
Location: arch/x86/include/asm/pgtable.h:1045
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812b7957)
Location: arch/x86/include/asm/pgtable.h:1045
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff812e7d00)
Location: arch/x86/include/asm/pgtable.h:1045
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812eec36)
Location: arch/x86/include/asm/pgtable.h:1045
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812f2a30)
Location: arch/x86/include/asm/pgtable.h:1045
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8138d929)
Location: arch/x86/include/asm/pgtable.h:1045
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813b8f52)
Location: arch/x86/include/asm/pgtable.h:1045
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
In mm/memory.c (ffffffff81297b23)
Location: arch/x86/include/asm/pgtable.h:1041
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/mremap.c (ffffffff812ab2fc)
Location: arch/x86/include/asm/pgtable.h:1041
Inline: True
```
```
In mm/rmap.c (ffffffff812afc0b)
Location: arch/x86/include/asm/pgtable.h:1041
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812c2892)
Location: arch/x86/include/asm/pgtable.h:1041
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff812f30ec)
Location: arch/x86/include/asm/pgtable.h:1041
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812fa292)
Location: arch/x86/include/asm/pgtable.h:1041
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812fd044)
Location: arch/x86/include/asm/pgtable.h:1041
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8139f3a9)
Location: arch/x86/include/asm/pgtable.h:1041
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813ca989)
Location: arch/x86/include/asm/pgtable.h:1041
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
In mm/memory.c (ffffffff812a18d6)
Location: arch/x86/include/asm/pgtable.h:1041
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/mremap.c (ffffffff812b06fb)
Location: arch/x86/include/asm/pgtable.h:1041
Inline: True
```
```
In mm/rmap.c (ffffffff812b51ac)
Location: arch/x86/include/asm/pgtable.h:1041
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812c9718)
Location: arch/x86/include/asm/pgtable.h:1041
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff812f9485)
Location: arch/x86/include/asm/pgtable.h:1041
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8130106d)
Location: arch/x86/include/asm/pgtable.h:1041
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81303db9)
Location: arch/x86/include/asm/pgtable.h:1041
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813a6116)
Location: arch/x86/include/asm/pgtable.h:1041
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813d19ed)
Location: arch/x86/include/asm/pgtable.h:1041
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
In mm/memory.c (ffffffff812e28b9)
Location: arch/x86/include/asm/pgtable.h:1012
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/rmap.c (ffffffff812f6d48)
Location: arch/x86/include/asm/pgtable.h:1012
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8130e73a)
Location: arch/x86/include/asm/pgtable.h:1012
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff8134acdd)
Location: arch/x86/include/asm/pgtable.h:1012
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134db1b)
Location: arch/x86/include/asm/pgtable.h:1012
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813f5b86)
Location: arch/x86/include/asm/pgtable.h:1012
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81422eed)
Location: arch/x86/include/asm/pgtable.h:1012
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
In mm/memory.c (ffffffff813430a3)
Location: arch/x86/include/asm/pgtable.h:1011
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/rmap.c (ffffffff8135b245)
Location: arch/x86/include/asm/pgtable.h:1011
Inline: True
```
```
In mm/madvise.c (ffffffff81377b41)
Location: arch/x86/include/asm/pgtable.h:1011
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff813c1e78)
Location: arch/x86/include/asm/pgtable.h:1011
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c6d48)
Location: arch/x86/include/asm/pgtable.h:1011
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81468cc8)
Location: arch/x86/include/asm/pgtable.h:1011
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8149ad7c)
Location: arch/x86/include/asm/pgtable.h:1011
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
In mm/memory.c (ffffffff813bb055)
Location: arch/x86/include/asm/pgtable.h:1029
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/rmap.c (ffffffff813d6143)
Location: arch/x86/include/asm/pgtable.h:1029
Inline: True
```
```
In mm/madvise.c (ffffffff813f52e3)
Location: arch/x86/include/asm/pgtable.h:1029
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff81444096)
Location: arch/x86/include/asm/pgtable.h:1029
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814491aa)
Location: arch/x86/include/asm/pgtable.h:1029
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff814f9862)
Location: arch/x86/include/asm/pgtable.h:1029
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
```
```
In fs/proc/task_mmu.c (ffffffff8152f2b9)
Location: arch/x86/include/asm/pgtable.h:1029
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
In mm/memory.c (ffffffff813efb56)
Location: arch/x86/include/asm/pgtable.h:1030
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/rmap.c (ffffffff8140b247)
Location: arch/x86/include/asm/pgtable.h:1030
Inline: True
```
```
In mm/madvise.c (ffffffff81428496)
Location: arch/x86/include/asm/pgtable.h:1030
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff8147962b)
Location: arch/x86/include/asm/pgtable.h:1030
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8147e99b)
Location: arch/x86/include/asm/pgtable.h:1030
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81530ce6)
Location: arch/x86/include/asm/pgtable.h:1030
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
```
```
In fs/proc/task_mmu.c (ffffffff8156757d)
Location: arch/x86/include/asm/pgtable.h:1030
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
In mm/memory.c (ffffffff8141b1b3)
Location: arch/x86/include/asm/pgtable.h:1245
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/rmap.c (ffffffff81437b9a)
Location: arch/x86/include/asm/pgtable.h:1245
Inline: True
```
```
In mm/madvise.c (ffffffff81461d91)
Location: arch/x86/include/asm/pgtable.h:1245
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff814a8bc1)
Location: arch/x86/include/asm/pgtable.h:1245
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814af64e)
Location: arch/x86/include/asm/pgtable.h:1245
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81565bc6)
Location: arch/x86/include/asm/pgtable.h:1245
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
```
```
In fs/proc/task_mmu.c (ffffffff8159db23)
Location: arch/x86/include/asm/pgtable.h:1245
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void set_pmd_at(struct mm_struct *mm, long unsigned int addr, pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/pgtable.c (c000000000090ac0)
Location: arch/powerpc/mm/book3s64/pgtable.c:64
Inline: False
Direct callers:
  - mm/memory.c:alloc_set_pte
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
c000000000090ac0-c000000000090c04: set_pmd_at (STB_GLOBAL)
```
</details>
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
In mm/memory.c (ffffffff8125a43d)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mremap.c (ffffffff812685fa)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8126b976)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8127d9b0)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff812aad41)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812b2638)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b5916)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8133fb26)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8136907c)
Location: arch/x86/include/asm/pgtable.h:1085
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
In mm/memory.c (ffffffff8124c866)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mremap.c (ffffffff8125a818)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8125d587)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8126fc7f)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff8129c681)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812a39ca)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812a6b25)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81330747)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8135a295)
Location: arch/x86/include/asm/pgtable.h:1085
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
In mm/memory.c (ffffffff812581dd)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mremap.c (ffffffff8126639a)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff81269716)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8127b750)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff812a8b51)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812b0448)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b3726)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8133d5f6)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81366b4c)
Location: arch/x86/include/asm/pgtable.h:1085
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
In mm/memory.c (ffffffff81267bc7)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mremap.c (ffffffff81275d2b)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8127922f)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8128b722)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff812b8e71)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812c0788)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812c3b8d)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8135050c)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8137a1a2)
Location: arch/x86/include/asm/pgtable.h:1085
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
