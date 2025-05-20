# Function: <code>pmd_bad</code>

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
In mm/gup.c (ffffffff811ba3f2)
Location: arch/x86/include/asm/pgtable.h:570
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811bc2a2)
Location: arch/x86/include/asm/pgtable.h:570
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811c2768)
Location: arch/x86/include/asm/pgtable.h:570
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811c8b05)
Location: arch/x86/include/asm/pgtable.h:570
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff811ce461)
Location: arch/x86/include/asm/pgtable.h:570
Inline: True
```
```
In mm/pagewalk.c (ffffffff811cffc0)
Location: arch/x86/include/asm/pgtable.h:570
Inline: True
```
```
In mm/madvise.c (ffffffff811d14ec)
Location: arch/x86/include/asm/pgtable.h:570
Inline: True
Inline callers:
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff811d434c)
Location: arch/x86/include/asm/pgtable.h:570
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff811e006d)
Location: arch/x86/include/asm/pgtable.h:570
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memcontrol.c (ffffffff811fafce)
Location: arch/x86/include/asm/pgtable.h:570
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff812782f3)
Location: arch/x86/include/asm/pgtable.h:570
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
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
In mm/gup.c (ffffffff811d52ab)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811dac6f)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mincore.c (ffffffff811de34c)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811e4989)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e5c4b)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff811eae06)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
```
```
In mm/pagewalk.c (ffffffff811ed162)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
```
```
In mm/madvise.c (ffffffff811eeaf7)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff811f2151)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff811fed83)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memcontrol.c (ffffffff812210c7)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff812a5606)
Location: arch/x86/include/asm/pgtable.h:607
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
In mm/gup.c (ffffffff811e52c6)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811ea832)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mincore.c (ffffffff811ee15c)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811f497b)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f5ed3)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff811f7552)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
```
```
In mm/vmalloc.c (ffffffff811fc066)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
```
```
In mm/madvise.c (ffffffff811ff437)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81202b49)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff812105bf)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memcontrol.c (ffffffff8123380d)
Location: arch/x86/include/asm/pgtable.h:607
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff812baf56)
Location: arch/x86/include/asm/pgtable.h:607
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
In mm/gup.c (ffffffff811eeeb8)
Location: arch/x86/include/asm/pgtable.h:746
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f1b21)
Location: arch/x86/include/asm/pgtable.h:746
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mincore.c (ffffffff811f9169)
Location: arch/x86/include/asm/pgtable.h:746
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811ff8ce)
Location: arch/x86/include/asm/pgtable.h:746
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81200ccb)
Location: arch/x86/include/asm/pgtable.h:746
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81202366)
Location: arch/x86/include/asm/pgtable.h:746
Inline: True
```
```
In mm/vmalloc.c (ffffffff812057ad)
Location: arch/x86/include/asm/pgtable.h:746
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8120a0e9)
Location: arch/x86/include/asm/pgtable.h:746
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8120dbfd)
Location: arch/x86/include/asm/pgtable.h:746
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff8121bfb7)
Location: arch/x86/include/asm/pgtable.h:746
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memcontrol.c (ffffffff8123f0b3)
Location: arch/x86/include/asm/pgtable.h:746
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff812c80d6)
Location: arch/x86/include/asm/pgtable.h:746
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
In mm/gup.c (ffffffff81206b2a)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81208955)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mincore.c (ffffffff81211556)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81217fe9)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81219315)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8121b493)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In mm/vmalloc.c (ffffffff8121f7a1)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff81223343)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81228e62)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff812373f0)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8124b905)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff8125ed06)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/hmm.c (ffffffff8126e79b)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff812eba2b)
Location: arch/x86/include/asm/pgtable.h:755
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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81226286)
Location: arch/x86/include/asm/pgtable.h:797
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812299bd)
Location: arch/x86/include/asm/pgtable.h:797
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mincore.c (ffffffff812322c7)
Location: arch/x86/include/asm/pgtable.h:797
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81239e60)
Location: arch/x86/include/asm/pgtable.h:797
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8123ab9c)
Location: arch/x86/include/asm/pgtable.h:797
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8123d1ef)
Location: arch/x86/include/asm/pgtable.h:797
Inline: True
```
```
In mm/vmalloc.c (ffffffff81240f12)
Location: arch/x86/include/asm/pgtable.h:797
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff812461af)
Location: arch/x86/include/asm/pgtable.h:797
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8124a14b)
Location: arch/x86/include/asm/pgtable.h:797
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff8125a927)
Location: arch/x86/include/asm/pgtable.h:797
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8126e516)
Location: arch/x86/include/asm/pgtable.h:797
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff81282fda)
Location: arch/x86/include/asm/pgtable.h:797
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/hmm.c (ffffffff81293429)
Location: arch/x86/include/asm/pgtable.h:797
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81318edf)
Location: arch/x86/include/asm/pgtable.h:797
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
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8123a5e2)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8123cee0)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mincore.c (ffffffff81245a97)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8124d640)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124eda8)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812516c7)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff81254c22)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8125a5cf)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8125e78b)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff8126e7ed)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812833a4)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff8129902a)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/hmm.c (ffffffff812a7966)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8132ff8f)
Location: arch/x86/include/asm/pgtable.h:822
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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124b902)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124eb4b)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff81257be8)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8125fe65)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812610ff)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8126398e)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff81266fd2)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff812756b0)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8127b9e0)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff81289eb4)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memcontrol.c (ffffffff812b4418)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/hmm.c (ffffffff812c4afb)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81357dc1)
Location: arch/x86/include/asm/pgtable.h:839
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
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81259df2)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125d102)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff812660f8)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8126e71d)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8126f898)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81271e6f)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
```
```
In mm/vmalloc.c (ffffffff812758d2)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff81284680)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8128b4c0)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff81299a24)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812aee5f)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff812c5d38)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/hmm.c (ffffffff812d64bd)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8136fff1)
Location: arch/x86/include/asm/pgtable.h:839
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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812882f1)
Location: arch/x86/include/asm/pgtable.h:848
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8128d75a)
Location: arch/x86/include/asm/pgtable.h:848
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff81296440)
Location: arch/x86/include/asm/pgtable.h:848
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8129e4e9)
Location: arch/x86/include/asm/pgtable.h:848
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812a041d)
Location: arch/x86/include/asm/pgtable.h:848
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812a27b4)
Location: arch/x86/include/asm/pgtable.h:848
Inline: True
```
```
In mm/vmalloc.c (ffffffff812a72f0)
Location: arch/x86/include/asm/pgtable.h:848
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff812b6815)
Location: arch/x86/include/asm/pgtable.h:848
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812bde24)
Location: arch/x86/include/asm/pgtable.h:848
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/mempolicy.c (ffffffff812ced7c)
Location: arch/x86/include/asm/pgtable.h:848
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812e445d)
Location: arch/x86/include/asm/pgtable.h:848
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff812fba20)
Location: arch/x86/include/asm/pgtable.h:848
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/hmm.c (ffffffff8130b4cf)
Location: arch/x86/include/asm/pgtable.h:848
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c915)
Location: arch/x86/include/asm/pgtable.h:848
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/proc/task_mmu.c (ffffffff813b8014)
Location: arch/x86/include/asm/pgtable.h:848
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
In mm/gup.c (ffffffff81291fd1)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129fc0b)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff812a13b3)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812a98a9)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812ab938)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812ae0f4)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
```
```
In mm/vmalloc.c (ffffffff812b2570)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff812c2a65)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812c9948)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/mempolicy.c (ffffffff812da6bc)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812f00b3)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff81307670)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/hmm.c (ffffffff8131738f)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff81318855)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/proc/task_mmu.c (ffffffff813c9ed4)
Location: arch/x86/include/asm/pgtable.h:847
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
In mm/filemap.c (0)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff81297b9e)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812a54a3)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff812a6bb0)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812aed39)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812b0d28)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812b34e3)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
```
```
In mm/vmalloc.c (ffffffff812b8cc6)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff812c98e5)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812d05b1)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff812e1f2c)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812f5b48)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff8130ddf0)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/hmm.c (ffffffff8131d7c3)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131ea45)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/proc/task_mmu.c (ffffffff813d1534)
Location: arch/x86/include/asm/pgtable.h:847
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
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
In mm/filemap.c (0)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff812d85de)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812e699a)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff812e8090)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812f0529)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812f2767)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812f5070)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
```
```
In mm/vmalloc.c (ffffffff812fb27a)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
```
```
In mm/madvise.c (ffffffff8130e905)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81315afb)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff8132900c)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8134010d)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff81358c50)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8135f444)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/hmm.c (ffffffff8136ab63)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136be25)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/proc/task_mmu.c (ffffffff81422a34)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
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
In mm/filemap.c (0)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff81338536)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8133d86c)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff813493a9)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81353a5d)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81356796)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81359080)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
```
```
In mm/vmalloc.c (ffffffff81362783)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/madvise.c (ffffffff8137679a)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81381101)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff81398271)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate_device.c (ffffffff813b7676)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff813d2e77)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff813d9b5d)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/hmm.c (ffffffff813e8dd2)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff813ea03d)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/proc/task_mmu.c (ffffffff81499b4e)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
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
In mm/filemap.c (ffffffff8135d933)
Location: arch/x86/include/asm/pgtable.h:833
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff813afd74)
Location: arch/x86/include/asm/pgtable.h:833
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813b688c)
Location: arch/x86/include/asm/pgtable.h:833
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff813c1779)
Location: arch/x86/include/asm/pgtable.h:833
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff813cdf08)
Location: arch/x86/include/asm/pgtable.h:833
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813d0d8e)
Location: arch/x86/include/asm/pgtable.h:833
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff813d37bd)
Location: arch/x86/include/asm/pgtable.h:833
Inline: True
```
```
In mm/vmalloc.c (ffffffff813de11b)
Location: arch/x86/include/asm/pgtable.h:833
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/madvise.c (ffffffff813f40f6)
Location: arch/x86/include/asm/pgtable.h:833
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff813ff952)
Location: arch/x86/include/asm/pgtable.h:833
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff81418003)
Location: arch/x86/include/asm/pgtable.h:833
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate_device.c (ffffffff814392c8)
Location: arch/x86/include/asm/pgtable.h:833
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff814474cd)
Location: arch/x86/include/asm/pgtable.h:833
Inline: True
Inline callers:
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
```
In mm/memcontrol.c (ffffffff81458689)
Location: arch/x86/include/asm/pgtable.h:833
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8145ff15)
Location: arch/x86/include/asm/pgtable.h:833
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/hmm.c (ffffffff81470d33)
Location: arch/x86/include/asm/pgtable.h:833
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff814720fa)
Location: arch/x86/include/asm/pgtable.h:833
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/proc/task_mmu.c (ffffffff8152dd92)
Location: arch/x86/include/asm/pgtable.h:833
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
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
In mm/memory.c (ffffffff813f2e98)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81409801)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/vmalloc.c (ffffffff81412975)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/khugepaged.c (ffffffff8147cb9d)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
```
In mm/hmm.c (ffffffff814a4f52)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/memory.c (ffffffff8141db88)
Location: arch/x86/include/asm/pgtable.h:1056
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81436040)
Location: arch/x86/include/asm/pgtable.h:1056
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/vmalloc.c (ffffffff8143f3e5)
Location: arch/x86/include/asm/pgtable.h:1056
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/khugepaged.c (ffffffff814ac23d)
Location: arch/x86/include/asm/pgtable.h:1056
Inline: True
Inline callers:
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
```
In mm/hmm.c (ffffffff814d6012)
Location: arch/x86/include/asm/pgtable.h:1056
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a5d18)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:904
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
```
```
In mm/gup.c (c0000000003b841c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:904
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003bb114)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:904
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mincore.c (c0000000003c8604)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:904
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (c0000000003d212c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:904
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d3f10)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:904
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (c0000000003d6b20)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:904
Inline: True
```
```
In mm/vmalloc.c (c0000000003dbb4c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:904
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_page_range
```
```
In mm/madvise.c (c0000000003f2ffc)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:904
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (c0000000003fd040)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:904
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (c0000000004133d4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:904
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (c000000000435154)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:904
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (c000000000456e8c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:904
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/hmm.c (c000000000470660)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:904
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (c00000000054d6c4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:904
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
In mm/gup.c (ffffffe000204604)
Location: arch/riscv/include/asm/pgtable.h:133
Inline: True
```
```
In mm/memory.c (ffffffe000206716)
Location: arch/riscv/include/asm/pgtable.h:133
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffe000211186)
Location: arch/riscv/include/asm/pgtable.h:133
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffe00021521c)
Location: arch/riscv/include/asm/pgtable.h:133
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffe000220958)
Location: arch/riscv/include/asm/pgtable.h:133
Inline: True
Inline callers:
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffe00022695c)
Location: arch/riscv/include/asm/pgtable.h:133
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hmm.c (0)
Location: arch/riscv/include/asm/pgtable.h:133
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
In mm/gup.c (ffffffff81252442)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81255752)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff8125e748)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81266d6d)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81267ee8)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8126a4bf)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
```
```
In mm/vmalloc.c (ffffffff8126df22)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8127ccd0)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81283aa0)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff81292004)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a743f)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff812be318)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/hmm.c (ffffffff812cea9d)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813685d1)
Location: arch/x86/include/asm/pgtable.h:839
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
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81245d7f)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81247e46)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mincore.c (ffffffff81250bb5)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81258ba5)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8125a1d3)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8125c975)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff8125ff2e)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8126eb56)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81275943)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff81283bca)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81298dcc)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff812af416)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/hmm.c (ffffffff812bf79c)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813598ef)
Location: arch/x86/include/asm/pgtable.h:839
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
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812501e2)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812534f2)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff8125c4e8)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81264b0d)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81265c88)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8126825f)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
```
```
In mm/vmalloc.c (ffffffff8126bcc2)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8127aa70)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812818b0)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff8128fe14)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a524f)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff812bc128)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/hmm.c (ffffffff812cc8ad)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813660a1)
Location: arch/x86/include/asm/pgtable.h:839
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
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125fb72)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81262eec)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff8126bed1)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812744dd)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8127562a)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81277bdf)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
```
```
In mm/vmalloc.c (ffffffff8127b6d2)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8128a650)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812915da)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff8129f2ae)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812b5da5)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff812cc8f6)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/hmm.c (ffffffff812dd60a)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81379c8a)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
</ul>

## Differences
