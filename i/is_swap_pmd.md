# Function: <code>is_swap_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81206a7d)
Location: include/linux/huge_mm.h:183
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff8120e75d)
Location: include/linux/huge_mm.h:183
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff812113fa)
Location: include/linux/huge_mm.h:183
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81217e54)
Location: include/linux/huge_mm.h:183
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81219139)
Location: include/linux/huge_mm.h:183
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8121b3c6)
Location: include/linux/huge_mm.h:183
Inline: True
```
```
In mm/mempolicy.c (ffffffff8123721f)
Location: include/linux/huge_mm.h:183
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8124b588)
Location: include/linux/huge_mm.h:183
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81251926)
Location: include/linux/huge_mm.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8125eb55)
Location: include/linux/huge_mm.h:183
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/dax.c (ffffffff812ce7a7)
Location: include/linux/huge_mm.h:183
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
```
In fs/proc/task_mmu.c (ffffffff812eb87b)
Location: include/linux/huge_mm.h:183
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (ffffffff812279ed)
Location: include/linux/huge_mm.h:184
Inline: True
```
```
In mm/memory.c (ffffffff8122ff85)
Location: include/linux/huge_mm.h:184
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff8123219e)
Location: include/linux/huge_mm.h:184
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81239cc7)
Location: include/linux/huge_mm.h:184
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
  - mm/mprotect.c:change_protection
```
```
In mm/mremap.c (ffffffff8123aec5)
Location: include/linux/huge_mm.h:184
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8123d13c)
Location: include/linux/huge_mm.h:184
Inline: True
```
```
In mm/mempolicy.c (ffffffff8125a762)
Location: include/linux/huge_mm.h:184
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8126e298)
Location: include/linux/huge_mm.h:184
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81275e66)
Location: include/linux/huge_mm.h:184
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81282ec5)
Location: include/linux/huge_mm.h:184
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/dax.c (ffffffff812f8de2)
Location: include/linux/huge_mm.h:184
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81318d3a)
Location: include/linux/huge_mm.h:184
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (ffffffff8123b1c4)
Location: include/linux/huge_mm.h:190
Inline: True
```
```
In mm/memory.c (ffffffff81241c7b)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff8124596e)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8124d503)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124f09f)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81251608)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/mempolicy.c (ffffffff8126e5e2)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81283126)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8128acc6)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81298f15)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/dax.c (ffffffff8130df0d)
Location: include/linux/huge_mm.h:190
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8132fdea)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (ffffffff8124c3e5)
Location: include/linux/huge_mm.h:205
Inline: True
```
```
In mm/memory.c (ffffffff812545de)
Location: include/linux/huge_mm.h:205
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff81257aba)
Location: include/linux/huge_mm.h:205
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8125fdf7)
Location: include/linux/huge_mm.h:205
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812613f8)
Location: include/linux/huge_mm.h:205
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812638cf)
Location: include/linux/huge_mm.h:205
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/mempolicy.c (ffffffff81289c22)
Location: include/linux/huge_mm.h:205
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff812a58e6)
Location: include/linux/huge_mm.h:205
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812b42f6)
Location: include/linux/huge_mm.h:205
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/dax.c (ffffffff81336135)
Location: include/linux/huge_mm.h:205
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81357c1a)
Location: include/linux/huge_mm.h:205
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (ffffffff8125a883)
Location: include/linux/huge_mm.h:210
Inline: True
```
```
In mm/memory.c (ffffffff81262b3e)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff81265fca)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8126e69d)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126fba8)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81271dcd)
Location: include/linux/huge_mm.h:210
Inline: True
```
```
In mm/madvise.c (ffffffff81284e2b)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81299792)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812aecdf)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812b6da6)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812c5c16)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/dax.c (ffffffff81349d35)
Location: include/linux/huge_mm.h:210
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8136fe4a)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int is_swap_pmd(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81287890)
Location: include/linux/huge_mm.h:246
Inline: False
```
```
In mm/memory.c (ffffffff81294a4d)
Location: include/linux/huge_mm.h:246
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff8129631a)
Location: include/linux/huge_mm.h:246
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8129ebbc)
Location: include/linux/huge_mm.h:246
Inline: True
```
```
In mm/mremap.c (ffffffff812a05fb)
Location: include/linux/huge_mm.h:246
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812a26fb)
Location: include/linux/huge_mm.h:246
Inline: True
```
```
In mm/madvise.c (ffffffff812b700f)
Location: include/linux/huge_mm.h:246
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff812cec82)
Location: include/linux/huge_mm.h:246
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812e42ec)
Location: include/linux/huge_mm.h:246
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812ebf06)
Location: include/linux/huge_mm.h:246
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812fb906)
Location: include/linux/huge_mm.h:246
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/dax.c (ffffffff8138f4b5)
Location: include/linux/huge_mm.h:246
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff813b7e7a)
Location: include/linux/huge_mm.h:246
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81287890-ffffffff812878ce: is_swap_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int is_swap_pmd(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812916d0)
Location: include/linux/huge_mm.h:225
Inline: False
```
```
In mm/memory.c (ffffffff8129f2cd)
Location: include/linux/huge_mm.h:225
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
```
```
In mm/mincore.c (ffffffff812a1287)
Location: include/linux/huge_mm.h:225
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812a9f7f)
Location: include/linux/huge_mm.h:225
Inline: True
```
```
In mm/mremap.c (ffffffff812abb64)
Location: include/linux/huge_mm.h:225
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812ae03b)
Location: include/linux/huge_mm.h:225
Inline: True
```
```
In mm/madvise.c (ffffffff812c1f4f)
Location: include/linux/huge_mm.h:225
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff812da5c2)
Location: include/linux/huge_mm.h:225
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812eff65)
Location: include/linux/huge_mm.h:225
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812f6f76)
Location: include/linux/huge_mm.h:225
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81307556)
Location: include/linux/huge_mm.h:225
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/dax.c (ffffffff813a0b43)
Location: include/linux/huge_mm.h:225
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff813c9d3a)
Location: include/linux/huge_mm.h:225
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812916d0-ffffffff8129170e: is_swap_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int is_swap_pmd(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81296bf0)
Location: include/linux/huge_mm.h:230
Inline: False
```
```
In mm/memory.c (ffffffff812a4274)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_pmd_range
```
```
In mm/mincore.c (ffffffff812a6a88)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812af3fe)
Location: include/linux/huge_mm.h:230
Inline: True
```
```
In mm/mremap.c (ffffffff812b0ff2)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812b342a)
Location: include/linux/huge_mm.h:230
Inline: True
```
```
In mm/madvise.c (ffffffff812c8e08)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff812e1e32)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812f59fa)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812fd326)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8130dcd6)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/dax.c (ffffffff813a7d2a)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff813d139a)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81296bf0-ffffffff81296c2c: is_swap_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int is_swap_pmd(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d7430)
Location: include/linux/huge_mm.h:230
Inline: False
```
```
In mm/memory.c (ffffffff812e55a5)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_pmd_range
```
```
In mm/mincore.c (ffffffff812e7f68)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812f0c2d)
Location: include/linux/huge_mm.h:230
Inline: True
```
```
In mm/mremap.c (ffffffff812f2b08)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812f4fb7)
Location: include/linux/huge_mm.h:230
Inline: True
```
```
In mm/madvise.c (ffffffff8130de2d)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81328f15)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8133ffbe)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81346fe6)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81358b36)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8135f30a)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In fs/dax.c (ffffffff813f767c)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff8142289a)
Location: include/linux/huge_mm.h:230
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812d7430-ffffffff812d746c: is_swap_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int is_swap_pmd(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81337000)
Location: include/linux/huge_mm.h:244
Inline: False
```
```
In mm/memory.c (ffffffff813478e3)
Location: include/linux/huge_mm.h:244
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_p4d_range
```
```
In mm/mincore.c (ffffffff8134925b)
Location: include/linux/huge_mm.h:244
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff8134c542)
Location: include/linux/huge_mm.h:244
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff813544fa)
Location: include/linux/huge_mm.h:244
Inline: True
```
```
In mm/mremap.c (ffffffff813566ef)
Location: include/linux/huge_mm.h:244
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8135845a)
Location: include/linux/huge_mm.h:244
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81358f22)
Location: include/linux/huge_mm.h:244
Inline: True
```
```
In mm/madvise.c (ffffffff813771b8)
Location: include/linux/huge_mm.h:244
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81398175)
Location: include/linux/huge_mm.h:244
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff813b4d27)
Location: include/linux/huge_mm.h:244
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff813b74fc)
Location: include/linux/huge_mm.h:244
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813be573)
Location: include/linux/huge_mm.h:244
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff813d2d3d)
Location: include/linux/huge_mm.h:244
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff813d999a)
Location: include/linux/huge_mm.h:244
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/hmm.c (ffffffff813e8abc)
Location: include/linux/huge_mm.h:244
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff8146a45f)
Location: include/linux/huge_mm.h:244
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff814999aa)
Location: include/linux/huge_mm.h:244
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81337000-ffffffff81337044: is_swap_pmd (STB_LOCAL)
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
In mm/gup.c (ffffffff813b0691)
Location: include/linux/huge_mm.h:229
Inline: True
```
```
In mm/memory.c (ffffffff813bfc71)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_p4d_range
```
```
In mm/mincore.c (ffffffff813c162e)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff813c50e2)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff813cea20)
Location: include/linux/huge_mm.h:229
Inline: True
```
```
In mm/mremap.c (ffffffff813d0ce5)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff813d2a8d)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d3867)
Location: include/linux/huge_mm.h:229
Inline: True
```
```
In mm/madvise.c (ffffffff813f47c9)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81417ef5)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81433ed7)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff81439067)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81440de5)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8145852e)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8145fd3a)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/hmm.c (ffffffff81470a45)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff814faf0c)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff8152dbda)
Location: include/linux/huge_mm.h:229
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (ffffffff813e4c08)
Location: include/linux/huge_mm.h:191
Inline: True
```
```
In mm/memory.c (ffffffff813f4938)
Location: include/linux/huge_mm.h:191
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_p4d_range
```
```
In mm/mincore.c (ffffffff813f65d6)
Location: include/linux/huge_mm.h:191
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff813f9550)
Location: include/linux/huge_mm.h:191
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff8140323a)
Location: include/linux/huge_mm.h:191
Inline: True
```
```
In mm/mremap.c (ffffffff81405722)
Location: include/linux/huge_mm.h:191
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff814077cd)
Location: include/linux/huge_mm.h:191
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff814081e0)
Location: include/linux/huge_mm.h:191
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81409793)
Location: include/linux/huge_mm.h:191
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/madvise.c (ffffffff81427d93)
Location: include/linux/huge_mm.h:191
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff8144b54c)
Location: include/linux/huge_mm.h:191
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/migrate.c (ffffffff81469827)
Location: include/linux/huge_mm.h:191
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff8146f316)
Location: include/linux/huge_mm.h:191
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81476681)
Location: include/linux/huge_mm.h:191
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8148e276)
Location: include/linux/huge_mm.h:191
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff81495524)
Location: include/linux/huge_mm.h:191
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/hmm.c (ffffffff814a4fb9)
Location: include/linux/huge_mm.h:191
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff8153235f)
Location: include/linux/huge_mm.h:191
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff81566026)
Location: include/linux/huge_mm.h:191
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (ffffffff8140f45c)
Location: include/linux/huge_mm.h:312
Inline: True
```
```
In mm/memory.c (ffffffff81420f6c)
Location: include/linux/huge_mm.h:312
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_p4d_range
```
```
In mm/mincore.c (ffffffff81422286)
Location: include/linux/huge_mm.h:312
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff814250f2)
Location: include/linux/huge_mm.h:312
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff8142f7ca)
Location: include/linux/huge_mm.h:312
Inline: True
```
```
In mm/mremap.c (ffffffff81431c5c)
Location: include/linux/huge_mm.h:312
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81433e5b)
Location: include/linux/huge_mm.h:312
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81434900)
Location: include/linux/huge_mm.h:312
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81435fd6)
Location: include/linux/huge_mm.h:312
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/madvise.c (ffffffff81461979)
Location: include/linux/huge_mm.h:312
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81484f2e)
Location: include/linux/huge_mm.h:312
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
  - mm/mempolicy.c:queue_folios_pmd
```
```
In mm/migrate.c (ffffffff81498757)
Location: include/linux/huge_mm.h:312
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff8149de15)
Location: include/linux/huge_mm.h:312
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a5f41)
Location: include/linux/huge_mm.h:312
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff814bdae6)
Location: include/linux/huge_mm.h:312
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff814c4d04)
Location: include/linux/huge_mm.h:312
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff814d3542)
Location: include/linux/huge_mm.h:312
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:move_pages
```
```
In mm/hmm.c (ffffffff814d6078)
Location: include/linux/huge_mm.h:312
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff8156724f)
Location: include/linux/huge_mm.h:312
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff8159e016)
Location: include/linux/huge_mm.h:312
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f2270)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffff8000102f9c28)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffff8000102fcf44)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffff800010305044)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffff800010305fb4)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffff800010307a04)
Location: include/linux/huge_mm.h:210
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/huge_mm.h:210
Inline: True
```
```
In mm/mempolicy.c (ffff800010338544)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffff800010357b30)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memcontrol.c (ffff800010368a08)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffff800010439b54)
Location: include/linux/huge_mm.h:210
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
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/linux/huge_mm.h:356
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/huge_mm.h:356
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/huge_mm.h:356
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
In arch/powerpc/mm/book3s64/subpage_prot.c (c00000000009f684)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:subpage_walk_pmd_entry
```
```
In mm/gup.c (c0000000003b83bc)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (c0000000003c3c34)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (c0000000003c8384)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (c0000000003d2070)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d4114)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (c0000000003d6840)
Location: include/linux/huge_mm.h:210
Inline: True
```
```
In mm/madvise.c (c0000000003f3cac)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (c000000000413090)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (c000000000434a9c)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (c00000000043fd78)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (c000000000456a60)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/dax.c (c0000000005169f8)
Location: include/linux/huge_mm.h:210
Inline: True
```
```
In fs/proc/task_mmu.c (c00000000054d408)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/memory.c (0)
Location: include/linux/huge_mm.h:356
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/huge_mm.h:356
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/huge_mm.h:356
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
In mm/gup.c (ffffffff81252ed3)
Location: include/linux/huge_mm.h:210
Inline: True
```
```
In mm/memory.c (ffffffff8125b18e)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff8125e61a)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81266ced)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812681f8)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8126a41d)
Location: include/linux/huge_mm.h:210
Inline: True
```
```
In mm/madvise.c (ffffffff8127d47b)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81291d72)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a72bf)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812af386)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812be1f6)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/dax.c (ffffffff81342315)
Location: include/linux/huge_mm.h:210
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8136842a)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (ffffffff81245ccd)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff8124d3ab)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff81250aaa)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81258aa9)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8125a55e)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8125c8dd)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/madvise.c (0)
Location: include/linux/huge_mm.h:210
Inline: True
```
```
In mm/mempolicy.c (ffffffff812839e2)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81298d12)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812a0876)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812af319)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/dax.c (ffffffff81332c8c)
Location: include/linux/huge_mm.h:210
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8135976a)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (ffffffff81250c73)
Location: include/linux/huge_mm.h:210
Inline: True
```
```
In mm/memory.c (ffffffff81258f2e)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff8125c3ba)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81264a8d)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81265f98)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812681bd)
Location: include/linux/huge_mm.h:210
Inline: True
```
```
In mm/madvise.c (ffffffff8127b21b)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff8128fb82)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a50cf)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812ad196)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812bc006)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/dax.c (ffffffff8133fde5)
Location: include/linux/huge_mm.h:210
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81365efa)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (ffffffff812605f4)
Location: include/linux/huge_mm.h:210
Inline: True
```
```
In mm/memory.c (ffffffff8126892e)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff8126bdaa)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81274476)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8127592d)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81277b3d)
Location: include/linux/huge_mm.h:210
Inline: True
```
```
In mm/madvise.c (ffffffff8128adeb)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff8129f012)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812b5c27)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812bd516)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812cc7d6)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/dax.c (ffffffff813523a5)
Location: include/linux/huge_mm.h:210
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81379aea)
Location: include/linux/huge_mm.h:210
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
