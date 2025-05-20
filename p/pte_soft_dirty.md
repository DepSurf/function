# Function: <code>pte_soft_dirty</code>

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
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:308
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:308
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:308
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
In mm/mprotect.c (ffffffff811e4bb4)
Location: arch/x86/include/asm/pgtable.h:337
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:337
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812a4eae)
Location: arch/x86/include/asm/pgtable.h:337
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/mprotect.c (ffffffff811f4bdd)
Location: arch/x86/include/asm/pgtable.h:337
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:337
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812ba813)
Location: arch/x86/include/asm/pgtable.h:337
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:453
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:453
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:453
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
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:468
Inline: True
```
```
In mm/rmap.c (ffffffff8121d565)
Location: arch/x86/include/asm/pgtable.h:468
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:468
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812ec733)
Location: arch/x86/include/asm/pgtable.h:468
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/mprotect.c (ffffffff8123930f)
Location: arch/x86/include/asm/pgtable.h:468
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8123f571)
Location: arch/x86/include/asm/pgtable.h:468
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff8126e460)
Location: arch/x86/include/asm/pgtable.h:468
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81319f3b)
Location: arch/x86/include/asm/pgtable.h:468
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/mprotect.c (ffffffff8124d8ae)
Location: arch/x86/include/asm/pgtable.h:470
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff81253c77)
Location: arch/x86/include/asm/pgtable.h:470
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812832ee)
Location: arch/x86/include/asm/pgtable.h:470
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8133100b)
Location: arch/x86/include/asm/pgtable.h:470
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/mprotect.c (ffffffff8125f8b0)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81265e9a)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In fs/proc/task_mmu.c (ffffffff81358e10)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/mprotect.c (ffffffff8126e0c0)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812747c7)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812aea4d)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81371060)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/mprotect.c (ffffffff8129e6e1)
Location: arch/x86/include/asm/pgtable.h:526
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812a57b5)
Location: arch/x86/include/asm/pgtable.h:526
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812e4661)
Location: arch/x86/include/asm/pgtable.h:526
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813b7c8a)
Location: arch/x86/include/asm/pgtable.h:526
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
In mm/mprotect.c (ffffffff812a9aa1)
Location: arch/x86/include/asm/pgtable.h:525
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812b0b78)
Location: arch/x86/include/asm/pgtable.h:525
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812f0341)
Location: arch/x86/include/asm/pgtable.h:525
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813c971a)
Location: arch/x86/include/asm/pgtable.h:525
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
In mm/mprotect.c (ffffffff812aef2c)
Location: arch/x86/include/asm/pgtable.h:525
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812b6265)
Location: arch/x86/include/asm/pgtable.h:525
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812f5cbb)
Location: arch/x86/include/asm/pgtable.h:525
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813d0828)
Location: arch/x86/include/asm/pgtable.h:525
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
In mm/mprotect.c (ffffffff812f071c)
Location: arch/x86/include/asm/pgtable.h:496
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812f8bba)
Location: arch/x86/include/asm/pgtable.h:496
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff8133fe80)
Location: arch/x86/include/asm/pgtable.h:496
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81421e65)
Location: arch/x86/include/asm/pgtable.h:496
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
In mm/gup.c (ffffffff8133886e)
Location: arch/x86/include/asm/pgtable.h:499
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8133e0d8)
Location: arch/x86/include/asm/pgtable.h:499
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (ffffffff81353d2c)
Location: arch/x86/include/asm/pgtable.h:499
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8135f19c)
Location: arch/x86/include/asm/pgtable.h:499
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate_device.c (ffffffff813b7419)
Location: arch/x86/include/asm/pgtable.h:499
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8149b088)
Location: arch/x86/include/asm/pgtable.h:499
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
In mm/gup.c (ffffffff813b0037)
Location: arch/x86/include/asm/pgtable.h:516
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813b720c)
Location: arch/x86/include/asm/pgtable.h:516
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (ffffffff813cdd75)
Location: arch/x86/include/asm/pgtable.h:516
Inline: True
Inline callers:
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/rmap.c (ffffffff813da054)
Location: arch/x86/include/asm/pgtable.h:516
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate_device.c (ffffffff81438f58)
Location: arch/x86/include/asm/pgtable.h:516
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8152e98f)
Location: arch/x86/include/asm/pgtable.h:516
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
In mm/gup.c (ffffffff813e4663)
Location: arch/x86/include/asm/pgtable.h:517
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813ebae9)
Location: arch/x86/include/asm/pgtable.h:517
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (ffffffff81402735)
Location: arch/x86/include/asm/pgtable.h:517
Inline: True
Inline callers:
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/rmap.c (ffffffff8140e77f)
Location: arch/x86/include/asm/pgtable.h:517
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate_device.c (ffffffff8146f7c3)
Location: arch/x86/include/asm/pgtable.h:517
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81566caf)
Location: arch/x86/include/asm/pgtable.h:517
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
In mm/gup.c (ffffffff8140f00e)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff814167ad)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (ffffffff8142ed65)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/rmap.c (ffffffff8143af86)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate_device.c (ffffffff8149e53a)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8159d278)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:733
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable.h:733
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/pgtable.h:733
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
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:733
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable.h:733
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/pgtable.h:733
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
In mm/mprotect.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:502
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:502
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:502
Inline: True
```
```
In mm/huge_memory.c (c00000000043c268)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:502
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In fs/proc/task_mmu.c (c00000000054cc50)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:502
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:733
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable.h:733
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/pgtable.h:733
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
In mm/mprotect.c (ffffffff81266710)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8126ce17)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812a702d)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81369640)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/mprotect.c (ffffffff81258dd6)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff8125ee53)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff81298a66)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81359365)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/mprotect.c (ffffffff812644b0)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8126abb7)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812a4e3d)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81367110)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/mprotect.c (ffffffff81273e70)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8127a520)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812b5999)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8137a75f)
Location: arch/x86/include/asm/pgtable.h:487
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
</ul>

## Differences
