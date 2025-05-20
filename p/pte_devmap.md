# Function: <code>pte_devmap</code>

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
In arch/x86/mm/gup.c (ffffffff810717a3)
Location: arch/x86/include/asm/pgtable.h:498
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:498
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
In arch/x86/mm/gup.c (ffffffff81075333)
Location: arch/x86/include/asm/pgtable.h:498
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:498
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811f0891)
Location: arch/x86/include/asm/pgtable.h:637
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
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
In mm/gup.c (ffffffff812053c0)
Location: arch/x86/include/asm/pgtable.h:652
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:652
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
In mm/gup.c (ffffffff81226af4)
Location: arch/x86/include/asm/pgtable.h:694
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8122b0f7)
Location: arch/x86/include/asm/pgtable.h:694
Inline: True
Inline callers:
  - mm/memory.c:_vm_normal_page
```
```
In mm/memory-failure.c (ffffffff81288b9e)
Location: arch/x86/include/asm/pgtable.h:694
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
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
In mm/gup.c (ffffffff81239bf5)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8123e4b7)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/memory.c:_vm_normal_page
```
```
In mm/memory-failure.c (ffffffff8129d8a1)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
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
In mm/gup.c (ffffffff8124ae25)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125030e)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/memory-failure.c (ffffffff812b8b77)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812c4454)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
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
In mm/gup.c (ffffffff81259315)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125e8be)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/memory-failure.c (ffffffff812caa57)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812d5e93)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
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
In mm/gup.c (ffffffff81288049)
Location: arch/x86/include/asm/pgtable.h:772
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8128ebae)
Location: arch/x86/include/asm/pgtable.h:772
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/memory-failure.c (ffffffff8130089e)
Location: arch/x86/include/asm/pgtable.h:772
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
In mm/gup.c (ffffffff81291d30)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129975e)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/memory-failure.c (ffffffff8130ca3e)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
In mm/gup.c (ffffffff81297850)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129e97e)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/memory-failure.c (ffffffff813131aa)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
In mm/gup.c (ffffffff812d8227)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812dfbbe)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/memory-failure.c (ffffffff8135fc7f)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8136a483)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
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
In mm/gup.c (ffffffff8133812c)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81340159)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/memory-failure.c (ffffffff813da8b9)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff813e8642)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
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
In mm/vmscan.c (ffffffff81378243)
Location: arch/x86/include/asm/pgtable.h:757
Inline: True
```
```
In mm/gup.c (ffffffff813af8d7)
Location: arch/x86/include/asm/pgtable.h:757
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813b80db)
Location: arch/x86/include/asm/pgtable.h:757
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/memory-failure.c (ffffffff81460ada)
Location: arch/x86/include/asm/pgtable.h:757
Inline: True
```
```
In mm/hmm.c (ffffffff8147056e)
Location: arch/x86/include/asm/pgtable.h:757
Inline: True
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
In mm/vmscan.c (ffffffff813aba93)
Location: arch/x86/include/asm/pgtable.h:758
Inline: True
```
```
In mm/gup.c (ffffffff813e4050)
Location: arch/x86/include/asm/pgtable.h:758
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813eceab)
Location: arch/x86/include/asm/pgtable.h:758
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/memory-failure.c (ffffffff8149528a)
Location: arch/x86/include/asm/pgtable.h:758
Inline: True
```
```
In mm/hmm.c (ffffffff814a4d49)
Location: arch/x86/include/asm/pgtable.h:758
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
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
In mm/vmscan.c (ffffffff813d61b3)
Location: arch/x86/include/asm/pgtable.h:973
Inline: True
```
```
In mm/gup.c (ffffffff8140e8b5)
Location: arch/x86/include/asm/pgtable.h:973
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8141840b)
Location: arch/x86/include/asm/pgtable.h:973
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/memory-failure.c (ffffffff814c4bef)
Location: arch/x86/include/asm/pgtable.h:973
Inline: True
```
```
In mm/hmm.c (ffffffff814d5d99)
Location: arch/x86/include/asm/pgtable.h:973
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/mm.h:1752
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:1752
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/mm.h:1752
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
In arch/powerpc/mm/pgtable.c (c000000000087aa8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:704
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable.c:__find_linux_pte
```
```
In arch/powerpc/mm/book3s64/subpage_prot.c (c00000000009f744)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:704
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:subpage_walk_pmd_entry
```
```
In mm/gup.c (c0000000003b6de0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:704
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003c3ff0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:704
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:vm_normal_page
```
```
In mm/mincore.c (c0000000003c83a0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:704
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (c0000000003d2320)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:704
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d40c8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:704
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (c0000000003d6848)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:704
Inline: True
```
```
In mm/madvise.c (c0000000003f4414)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:704
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (c000000000413094)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:704
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (c000000000434c00)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:704
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (c000000000440e1c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:704
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (c000000000456a68)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:704
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (c00000000045eba0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:704
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
```
```
In mm/hmm.c (c0000000004705c0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:704
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (c000000000515ddc)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:704
Inline: True
```
```
In fs/proc/task_mmu.c (c00000000054d410)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:704
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/gup.c (0)
Location: include/linux/mm.h:1752
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:1752
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/mm.h:1752
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
In mm/gup.c (ffffffff81251965)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81256f0e)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/memory-failure.c (ffffffff812c3037)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812ce473)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
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
In mm/gup.c (ffffffff8124483a)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124984d)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/memory-failure.c (ffffffff812b40b2)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/hmm.c (ffffffff812bf1db)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
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
In mm/gup.c (ffffffff8124f705)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81254cae)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/memory-failure.c (ffffffff812c0e47)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812cc283)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
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
In mm/gup.c (ffffffff8125f075)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8126472e)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page
```
```
In mm/memory-failure.c (ffffffff812d1907)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812dcfd7)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
```
</details>
</li>
</ul>

## Differences
