# Function: <code>pte_swp_mksoft_dirty</code>

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
In mm/memory.c (ffffffff811c1529)
Location: arch/x86/include/asm/pgtable.h:889
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:889
Inline: True
```
```
In mm/mremap.c (ffffffff811c9721)
Location: arch/x86/include/asm/pgtable.h:889
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811cb394)
Location: arch/x86/include/asm/pgtable.h:889
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:889
Inline: True
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
In mm/memory.c (ffffffff811dd037)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
```
```
In mm/mremap.c (ffffffff811e5ad4)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811e8688)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/huge_memory.c (ffffffff812162be)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/memory.c (ffffffff811ecb29)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
```
```
In mm/mremap.c (ffffffff811f5d43)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811f97b2)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/huge_memory.c (ffffffff81228872)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/memory.c (ffffffff811f7ac0)
Location: arch/x86/include/asm/pgtable.h:1147
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:1147
Inline: True
```
```
In mm/mremap.c (ffffffff81200b31)
Location: arch/x86/include/asm/pgtable.h:1147
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8120459c)
Location: arch/x86/include/asm/pgtable.h:1147
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/huge_memory.c (ffffffff81231ef5)
Location: arch/x86/include/asm/pgtable.h:1147
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff8120aa23)
Location: arch/x86/include/asm/pgtable.h:1166
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:1166
Inline: True
```
```
In mm/mremap.c (ffffffff81219567)
Location: arch/x86/include/asm/pgtable.h:1166
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8121d3db)
Location: arch/x86/include/asm/pgtable.h:1166
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff8124b78a)
Location: arch/x86/include/asm/pgtable.h:1166
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81252c62)
Location: arch/x86/include/asm/pgtable.h:1166
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1232
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:1232
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8123ae03)
Location: arch/x86/include/asm/pgtable.h:1232
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8123f2bb)
Location: arch/x86/include/asm/pgtable.h:1232
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff8126e460)
Location: arch/x86/include/asm/pgtable.h:1232
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812770d0)
Location: arch/x86/include/asm/pgtable.h:1232
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1321
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:1321
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124eff1)
Location: arch/x86/include/asm/pgtable.h:1321
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812539c4)
Location: arch/x86/include/asm/pgtable.h:1321
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812832ee)
Location: arch/x86/include/asm/pgtable.h:1321
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8128891f)
Location: arch/x86/include/asm/pgtable.h:1321
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81261353)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff81265bf1)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/huge_memory.c (ffffffff812a3560)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8126faf6)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff81274510)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812aea4d)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812b4a60)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff8128f01b)
Location: arch/x86/include/asm/pgtable.h:1302
Inline: True
Inline callers:
  - mm/memory.c:copy_one_pte
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:1302
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812a0122)
Location: arch/x86/include/asm/pgtable.h:1302
Inline: True
```
```
In mm/rmap.c (ffffffff812a57b9)
Location: arch/x86/include/asm/pgtable.h:1302
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812e41a5)
Location: arch/x86/include/asm/pgtable.h:1302
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812e9ffa)
Location: arch/x86/include/asm/pgtable.h:1302
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff8129780a)
Location: arch/x86/include/asm/pgtable.h:1298
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:1298
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812ab57f)
Location: arch/x86/include/asm/pgtable.h:1298
Inline: True
```
```
In mm/rmap.c (ffffffff812b0b78)
Location: arch/x86/include/asm/pgtable.h:1298
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812f01da)
Location: arch/x86/include/asm/pgtable.h:1298
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812f51d7)
Location: arch/x86/include/asm/pgtable.h:1298
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff8129dd5a)
Location: arch/x86/include/asm/pgtable.h:1298
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:1298
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812b0982)
Location: arch/x86/include/asm/pgtable.h:1298
Inline: True
```
```
In mm/rmap.c (ffffffff812b6265)
Location: arch/x86/include/asm/pgtable.h:1298
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812f58b4)
Location: arch/x86/include/asm/pgtable.h:1298
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812fb71e)
Location: arch/x86/include/asm/pgtable.h:1298
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff812ded4d)
Location: arch/x86/include/asm/pgtable.h:1269
Inline: True
Inline callers:
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:1269
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812f2312)
Location: arch/x86/include/asm/pgtable.h:1269
Inline: True
```
```
In mm/rmap.c (ffffffff812f8bba)
Location: arch/x86/include/asm/pgtable.h:1269
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff813402b3)
Location: arch/x86/include/asm/pgtable.h:1269
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8134557f)
Location: arch/x86/include/asm/pgtable.h:1269
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1303
Inline: True
Inline callers:
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:1303
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81356073)
Location: arch/x86/include/asm/pgtable.h:1303
Inline: True
```
```
In mm/rmap.c (ffffffff8135f19c)
Location: arch/x86/include/asm/pgtable.h:1303
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff813b1cb5)
Location: arch/x86/include/asm/pgtable.h:1303
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff813b7988)
Location: arch/x86/include/asm/pgtable.h:1303
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813bb5ae)
Location: arch/x86/include/asm/pgtable.h:1303
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1321
Inline: True
Inline callers:
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:1321
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813d06b6)
Location: arch/x86/include/asm/pgtable.h:1321
Inline: True
```
```
In mm/rmap.c (ffffffff813da054)
Location: arch/x86/include/asm/pgtable.h:1321
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff81432760)
Location: arch/x86/include/asm/pgtable.h:1321
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff81438f58)
Location: arch/x86/include/asm/pgtable.h:1321
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8143d99a)
Location: arch/x86/include/asm/pgtable.h:1321
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: True
Inline callers:
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mprotect.c (ffffffff81402f6b)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81404b90)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146fa74)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: True
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1547
Inline: True
Inline callers:
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mprotect.c (ffffffff8142f525)
Location: arch/x86/include/asm/pgtable.h:1547
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81431163)
Location: arch/x86/include/asm/pgtable.h:1547
Inline: True
```
```
In mm/rmap.c (ffffffff8143a74f)
Location: arch/x86/include/asm/pgtable.h:1547
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:1547
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149e432)
Location: arch/x86/include/asm/pgtable.h:1547
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1547
Inline: True
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:763
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:763
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable.h:763
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable.h:763
Inline: True
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:763
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:763
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable.h:763
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
In mm/memory.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:754
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:754
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:754
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:754
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:754
Inline: True
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:763
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:763
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable.h:763
Inline: True
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81268146)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8126cb60)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812a702d)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812ad040)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff81258e86)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8125a371)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8125ebb0)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8129e08f)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81265ee6)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8126a900)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812a4e3d)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812aae50)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81275888)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8127a27a)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812b5999)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812bb1a0)
Location: arch/x86/include/asm/pgtable.h:1341
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
</ul>

## Differences
