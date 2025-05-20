# Function: <code>pmd_devmap</code>

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
In arch/x86/mm/gup.c (ffffffff810714ad)
Location: arch/x86/include/asm/pgtable.h:191
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
```
```
In mm/gup.c (ffffffff811d5274)
Location: arch/x86/include/asm/pgtable.h:191
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811dac2f)
Location: arch/x86/include/asm/pgtable.h:191
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811de2b5)
Location: arch/x86/include/asm/pgtable.h:191
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811e48a0)
Location: arch/x86/include/asm/pgtable.h:191
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e5c00)
Location: arch/x86/include/asm/pgtable.h:191
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff811ed10d)
Location: arch/x86/include/asm/pgtable.h:191
Inline: True
```
```
In mm/mempolicy.c (ffffffff811ff26f)
Location: arch/x86/include/asm/pgtable.h:191
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff81215ec6)
Location: arch/x86/include/asm/pgtable.h:191
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
In mm/memcontrol.c (ffffffff81220fd2)
Location: arch/x86/include/asm/pgtable.h:191
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff812a5518)
Location: arch/x86/include/asm/pgtable.h:191
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In arch/x86/mm/gup.c (ffffffff8107502d)
Location: arch/x86/include/asm/pgtable.h:191
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
```
```
In mm/gup.c (ffffffff811e528f)
Location: arch/x86/include/asm/pgtable.h:191
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811ea7f2)
Location: arch/x86/include/asm/pgtable.h:191
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811ee0c5)
Location: arch/x86/include/asm/pgtable.h:191
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811f48c0)
Location: arch/x86/include/asm/pgtable.h:191
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f5e80)
Location: arch/x86/include/asm/pgtable.h:191
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff811f74fd)
Location: arch/x86/include/asm/pgtable.h:191
Inline: True
```
```
In mm/huge_memory.c (ffffffff812284e5)
Location: arch/x86/include/asm/pgtable.h:191
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
In mm/memcontrol.c (ffffffff8123371f)
Location: arch/x86/include/asm/pgtable.h:191
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/dax.c (ffffffff8129c9bd)
Location: arch/x86/include/asm/pgtable.h:191
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff812bae68)
Location: arch/x86/include/asm/pgtable.h:191
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (ffffffff811f0e04)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
```
```
In mm/memory.c (ffffffff811f57eb)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811f90d9)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811ff80e)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81200c78)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81202755)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
```
```
In mm/huge_memory.c (ffffffff812348e6)
Location: arch/x86/include/asm/pgtable.h:231
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
In mm/memcontrol.c (ffffffff8123efdf)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/dax.c (ffffffff812aaf8a)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
```
In fs/proc/task_mmu.c (ffffffff812c7fe8)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (ffffffff81205991)
Location: arch/x86/include/asm/pgtable.h:246
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff8120e97a)
Location: arch/x86/include/asm/pgtable.h:246
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff812114a9)
Location: arch/x86/include/asm/pgtable.h:246
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81218329)
Location: arch/x86/include/asm/pgtable.h:246
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8121970c)
Location: arch/x86/include/asm/pgtable.h:246
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8121b56c)
Location: arch/x86/include/asm/pgtable.h:246
Inline: True
```
```
In mm/mempolicy.c (ffffffff81237376)
Location: arch/x86/include/asm/pgtable.h:246
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8124b976)
Location: arch/x86/include/asm/pgtable.h:246
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812529b5)
Location: arch/x86/include/asm/pgtable.h:246
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
In mm/memcontrol.c (ffffffff8125ebfc)
Location: arch/x86/include/asm/pgtable.h:246
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/hmm.c (ffffffff8126e5c2)
Location: arch/x86/include/asm/pgtable.h:246
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff812cec44)
Location: arch/x86/include/asm/pgtable.h:246
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
```
In fs/proc/task_mmu.c (ffffffff812eb9af)
Location: arch/x86/include/asm/pgtable.h:246
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
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_devmap(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81226e0d)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff81230117)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff81232249)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81239ec8)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
  - mm/mprotect.c:change_protection
```
```
In mm/mremap.c (ffffffff8123b075)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8123d402)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
```
```
In mm/mempolicy.c (ffffffff8125a8b9)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8126e36f)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81276c52)
Location: arch/x86/include/asm/pgtable.h:256
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
In mm/memcontrol.c (ffffffff81282f68)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff81288b30)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/hmm.c (ffffffff812931db)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff812f91e8)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81318e6f)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81225ea0-ffffffff81225eb4: pmd_devmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_devmap(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81239b43)
Location: arch/x86/include/asm/pgtable.h:258
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff81241e49)
Location: arch/x86/include/asm/pgtable.h:258
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff81245a19)
Location: arch/x86/include/asm/pgtable.h:258
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8124dc85)
Location: arch/x86/include/asm/pgtable.h:258
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124f2ef)
Location: arch/x86/include/asm/pgtable.h:258
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812517c7)
Location: arch/x86/include/asm/pgtable.h:258
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/mempolicy.c (ffffffff8126e77f)
Location: arch/x86/include/asm/pgtable.h:258
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812831fd)
Location: arch/x86/include/asm/pgtable.h:258
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8128bb89)
Location: arch/x86/include/asm/pgtable.h:258
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
In mm/memcontrol.c (ffffffff81298fb8)
Location: arch/x86/include/asm/pgtable.h:258
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8129d833)
Location: arch/x86/include/asm/pgtable.h:258
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/hmm.c (ffffffff812a7558)
Location: arch/x86/include/asm/pgtable.h:258
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff8130d47a)
Location: arch/x86/include/asm/pgtable.h:258
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8132ff1f)
Location: arch/x86/include/asm/pgtable.h:258
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81239610-ffffffff81239624: pmd_devmap (STB_LOCAL)
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
In mm/gup.c (ffffffff8124ad82)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff81254810)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff81257b6e)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8125ff60)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126164e)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81263a9a)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/mempolicy.c (ffffffff81289dd4)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff812a67b8)
Location: arch/x86/include/asm/pgtable.h:275
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
In mm/memcontrol.c (ffffffff812b439a)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812b8b06)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812c4688)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff81335684)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81357d51)
Location: arch/x86/include/asm/pgtable.h:275
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
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_devmap(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81259272)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff81262d70)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff8126607e)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8126e859)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126fe0a)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81271f99)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
```
```
In mm/madvise.c (ffffffff81284e54)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81299944)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812aedb6)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812b7c91)
Location: arch/x86/include/asm/pgtable.h:275
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
In mm/memcontrol.c (ffffffff812c5cba)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812ca9e6)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812d60e0)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff81349284)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8136ff81)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81258b20-ffffffff81258b34: pmd_devmap (STB_LOCAL)
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
In mm/gup.c (ffffffff8128ac78)
Location: arch/x86/include/asm/pgtable.h:280
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pmd
```
```
In mm/memory.c (ffffffff81294bde)
Location: arch/x86/include/asm/pgtable.h:280
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff812963ce)
Location: arch/x86/include/asm/pgtable.h:280
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8129eb32)
Location: arch/x86/include/asm/pgtable.h:280
Inline: True
```
```
In mm/mremap.c (ffffffff812a0388)
Location: arch/x86/include/asm/pgtable.h:280
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812a28e5)
Location: arch/x86/include/asm/pgtable.h:280
Inline: True
```
```
In mm/madvise.c (ffffffff812b7038)
Location: arch/x86/include/asm/pgtable.h:280
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff812ced0d)
Location: arch/x86/include/asm/pgtable.h:280
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812e43bb)
Location: arch/x86/include/asm/pgtable.h:280
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812ed087)
Location: arch/x86/include/asm/pgtable.h:280
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812fb9aa)
Location: arch/x86/include/asm/pgtable.h:280
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff81300828)
Location: arch/x86/include/asm/pgtable.h:280
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8130b2ff)
Location: arch/x86/include/asm/pgtable.h:280
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c95c)
Location: arch/x86/include/asm/pgtable.h:280
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/dax.c (ffffffff8138f5b6)
Location: arch/x86/include/asm/pgtable.h:280
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/proc/task_mmu.c (ffffffff813b7fac)
Location: arch/x86/include/asm/pgtable.h:280
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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81294938)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pmd
```
```
In mm/memory.c (ffffffff8129f45e)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff812a133e)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812a9ef5)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
```
```
In mm/mremap.c (ffffffff812ab8a9)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812ae225)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
```
```
In mm/madvise.c (ffffffff812c1f78)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff812da64d)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812f003a)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812f82f3)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff813075fa)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8130c9c8)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff813171bf)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131889c)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/dax.c (ffffffff813a0beb)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/proc/task_mmu.c (ffffffff813c9e6c)
Location: arch/x86/include/asm/pgtable.h:279
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
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125f9e0)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff8129a810)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pmd
```
```
In mm/memory.c (ffffffff812a4517)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff812a6b37)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812af374)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
```
```
In mm/mremap.c (ffffffff812b0ca1)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812b3614)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
```
```
In mm/madvise.c (ffffffff812c8e31)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff812e1ebd)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812f5acf)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812fe872)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff8130dd78)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff81313137)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8131d4b8)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131ea8c)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/dax.c (ffffffff813a7e67)
Location: arch/x86/include/asm/pgtable.h:279
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/proc/task_mmu.c (ffffffff813d14cc)
Location: arch/x86/include/asm/pgtable.h:279
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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129c350)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff812db1c9)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pmd
```
```
In mm/memory.c (ffffffff812e55d4)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff812e8017)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812f0ba3)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
```
```
In mm/mremap.c (ffffffff812f26d8)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812f51a0)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
```
```
In mm/madvise.c (ffffffff8130de56)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81328f9d)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81340093)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81348411)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff81358bd8)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8135f3d4)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8136a858)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136be6c)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/dax.c (ffffffff813f77c5)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/proc/task_mmu.c (ffffffff814229cc)
Location: arch/x86/include/asm/pgtable.h:250
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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f34ed)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff8133ad8b)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pmd
```
```
In mm/memory.c (ffffffff8134790e)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff8134932b)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff8134c60f)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff81354451)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
```
```
In mm/mremap.c (ffffffff81356717)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81358624)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81359013)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
```
```
In mm/madvise.c (ffffffff813771e0)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81398209)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate_device.c (ffffffff813b7603)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813be55a)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff813d2e0f)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff813d9a6c)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff813e8a60)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff813ea084)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/dax.c (ffffffff8146a5da)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/proc/task_mmu.c (ffffffff81499ae8)
Location: arch/x86/include/asm/pgtable.h:253
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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135d83d)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/vmscan.c (ffffffff8137f5bf)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
```
```
In mm/gup.c (ffffffff813b23d9)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pmd
```
```
In mm/memory.c (ffffffff813bfc9c)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff813c16f5)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff813c518e)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff813ce972)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
```
```
In mm/mremap.c (ffffffff813d0d0d)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff813d2d88)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d396c)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
```
```
In mm/madvise.c (ffffffff813f47f1)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81417f8f)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate_device.c (ffffffff814391f2)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81440dcc)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff814474bd)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
```
In mm/memcontrol.c (ffffffff8145860f)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8145fe19)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/hmm.c (ffffffff814709e0)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff81472124)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/dax.c (ffffffff814fb08a)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/proc/task_mmu.c (ffffffff8152dd1e)
Location: arch/x86/include/asm/pgtable.h:254
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
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813b0aef)
Location: arch/x86/include/asm/pgtable.h:255
Inline: True
```
```
In mm/gup.c (ffffffff813e761c)
Location: arch/x86/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pmd
```
```
In mm/memory.c (ffffffff813f4963)
Location: arch/x86/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff813f66a8)
Location: arch/x86/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff813f961b)
Location: arch/x86/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff81403265)
Location: arch/x86/include/asm/pgtable.h:255
Inline: True
```
```
In mm/mremap.c (ffffffff8140574a)
Location: arch/x86/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81407913)
Location: arch/x86/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8140834c)
Location: arch/x86/include/asm/pgtable.h:255
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff814097ed)
Location: arch/x86/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/madvise.c (ffffffff81427dbb)
Location: arch/x86/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff8144b5fe)
Location: arch/x86/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/migrate_device.c (ffffffff8146f37f)
Location: arch/x86/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81476668)
Location: arch/x86/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff8147cb8d)
Location: arch/x86/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
```
In mm/memcontrol.c (ffffffff8148e466)
Location: arch/x86/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff81495618)
Location: arch/x86/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/hmm.c (ffffffff814a4f28)
Location: arch/x86/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a6986)
Location: arch/x86/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff81524dc8)
Location: arch/x86/include/asm/pgtable.h:255
Inline: True
```
```
In fs/dax.c (ffffffff815324dd)
Location: arch/x86/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/proc/task_mmu.c (ffffffff81566185)
Location: arch/x86/include/asm/pgtable.h:255
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
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813d9ffb)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
```
```
In mm/gup.c (ffffffff8141229a)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pmd
```
```
In mm/memory.c (ffffffff81420f97)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff81422358)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff814251c3)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff8142f7f5)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
```
```
In mm/mremap.c (ffffffff81431c84)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81433f0a)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81434a6c)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff8143602c)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/madvise.c (ffffffff81461a26)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81484fee)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/migrate_device.c (ffffffff8149d219)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a5f28)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff814ac22d)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
```
In mm/memcontrol.c (ffffffff814bdcd3)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff814c4df8)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff814d3592)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:move_pages
```
```
In mm/hmm.c (ffffffff814d5fe8)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d79bd)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff81558a59)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
```
```
In fs/dax.c (ffffffff815673cd)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/proc/task_mmu.c (ffffffff8159e17e)
Location: arch/x86/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
Location: include/linux/mm.h:568
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:568
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:568
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/mm.h:568
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
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1309
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable.c:__find_linux_pte
```
```
In arch/powerpc/mm/book3s64/subpage_prot.c (c00000000009f744)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1309
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:subpage_walk_pmd_entry
```
```
In mm/gup.c (c0000000003b6de0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1309
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (c0000000003c3ff0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1309
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (c0000000003c83a0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1309
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (c0000000003d2320)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1309
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d40c8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1309
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (c0000000003d6848)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1309
Inline: True
```
```
In mm/madvise.c (c0000000003f4414)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1309
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (c000000000413094)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1309
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (c000000000434c00)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1309
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (c000000000440e1c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1309
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
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1309
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (c00000000045eba0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1309
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/hmm.c (c0000000004705c0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1309
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (c000000000515ddc)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1309
Inline: True
```
```
In fs/proc/task_mmu.c (c00000000054d410)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1309
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
Location: include/linux/mm.h:568
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:568
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:568
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/mm.h:568
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:568
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_devmap(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812518c2)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff8125b3c0)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff8125e6ce)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81266ea9)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126845a)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8126a5e9)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
```
```
In mm/madvise.c (ffffffff8127d4a4)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81291f24)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a7396)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812b0271)
Location: arch/x86/include/asm/pgtable.h:275
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
In mm/memcontrol.c (ffffffff812be29a)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812c2fc6)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812ce6c0)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff81341864)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81368561)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81251170-ffffffff81251184: pmd_devmap (STB_LOCAL)
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
In mm/gup.c (ffffffff812447a0)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff8124d3fb)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff81250b59)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81258f60)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8125a15f)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8125c90a)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
```
```
In mm/mempolicy.c (ffffffff81283b6a)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81298e06)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812a16c8)
Location: arch/x86/include/asm/pgtable.h:275
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
In mm/memcontrol.c (ffffffff812af3ba)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812b4088)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/hmm.c (ffffffff812bf447)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff813321f0)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8135989b)
Location: arch/x86/include/asm/pgtable.h:275
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
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_devmap(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124f662)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff81259160)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff8125c46e)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81264c49)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812661fa)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81268389)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
```
```
In mm/madvise.c (ffffffff8127b244)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff8128fd34)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a51a6)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812ae081)
Location: arch/x86/include/asm/pgtable.h:275
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
In mm/memcontrol.c (ffffffff812bc0aa)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812c0dd6)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812cc4d0)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff8133f334)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81366031)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8124ef10-ffffffff8124ef24: pmd_devmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_devmap(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125efd2)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff81268b60)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff8126be57)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812745ce)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81275b8b)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81277d09)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
```
```
In mm/madvise.c (ffffffff8128ae14)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff8129f1cf)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812b5cfe)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812be3d6)
Location: arch/x86/include/asm/pgtable.h:275
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
In mm/memcontrol.c (ffffffff812cc878)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812d1896)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812dd230)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff813524c9)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81379c1a)
Location: arch/x86/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8125e880-ffffffff8125e894: pmd_devmap (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
