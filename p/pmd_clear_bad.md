# Function: <code>pmd_clear_bad</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff811d03f0)
Location: mm/pgtable-generic.c:31
Inline: False
Direct callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/mincore.c:mincore_pte_range
  - mm/mprotect.c:change_protection_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:unuse_mm
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff811d03f0-ffffffff811d043e: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff811ed5a0)
Location: mm/pgtable-generic.c:31
Inline: False
Direct callers:
  - mm/gup.c:follow_page_mask
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mincore.c:mincore_pte_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:unuse_mm
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff811ed5a0-ffffffff811ed5ee: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff811f7990)
Location: mm/pgtable-generic.c:31
Inline: False
Direct callers:
  - mm/gup.c:follow_page_mask
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mincore.c:mincore_pte_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:unuse_mm
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff811f7990-ffffffff811f79de: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81202b20)
Location: mm/pgtable-generic.c:37
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mincore.c:mincore_pte_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:unuse_mm
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81202b20-ffffffff81202b6e: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8121b890)
Location: mm/pgtable-generic.c:38
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mincore.c:mincore_pte_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:unuse_mm
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8121b890-ffffffff8121b8de: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8123d670)
Location: mm/pgtable-generic.c:38
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mincore.c:mincore_pte_range
  - mm/mprotect.c:change_protection
  - mm/mprotect.c:change_pte_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:unuse_vma
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8123d670-ffffffff8123d6be: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81251bc0)
Location: mm/pgtable-generic.c:39
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mincore.c:mincore_pte_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/pagewalk.c:walk_pgd_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:unuse_vma
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81251bc0-ffffffff81251c0e: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81263e90)
Location: mm/pgtable-generic.c:39
Inline: False
Direct callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
  - mm/mincore.c:mincore_pte_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
  - mm/mremap.c:move_page_tables
  - mm/pagewalk.c:walk_pgd_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81263e90-ffffffff81263ee0: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81272700)
Location: mm/pgtable-generic.c:39
Inline: False
Direct callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
  - mm/mincore.c:mincore_pte_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81272700-ffffffff81272750: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812a34b0)
Location: mm/pgtable-generic.c:48
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
  - mm/mincore.c:mincore_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:unuse_p4d_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812a34b0-ffffffff812a3502: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812aeda0)
Location: mm/pgtable-generic.c:48
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
  - mm/mincore.c:mincore_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:unuse_p4d_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812aeda0-ffffffff812aede8: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812b42d0)
Location: mm/pgtable-generic.c:48
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:free_pud_range
  - mm/mincore.c:mincore_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:unuse_vma
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812b42d0-ffffffff812b4318: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812f5eb0)
Location: mm/pgtable-generic.c:48
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:free_pud_range
  - mm/mincore.c:mincore_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mremap.c:move_page_tables
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:unuse_vma
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812f5eb0-ffffffff812f5ef8: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81359e30)
Location: mm/pgtable-generic.c:49
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
  - mm/mincore.c:mincore_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mremap.c:move_page_tables
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:unuse_vma
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81359e30-ffffffff81359e8f: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff813d4850)
Location: mm/pgtable-generic.c:49
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
  - mm/mincore.c:mincore_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mremap.c:move_page_tables
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:unuse_vma
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff813d4850-ffffffff813d48af: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81409220)
Location: mm/pgtable-generic.c:51
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
  - mm/pgtable-generic.c:__pte_offset_map
  - mm/vmalloc.c:vunmap_p4d_range
```
**Symbols:**

```
ffffffff81409220-ffffffff8140927f: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81435a10)
Location: mm/pgtable-generic.c:52
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
  - mm/pgtable-generic.c:__pte_offset_map
  - mm/vmalloc.c:vunmap_p4d_range
```
**Symbols:**

```
ffffffff81435a10-ffffffff81435a6f: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffff800010307f70)
Location: mm/pgtable-generic.c:39
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
**Symbols:**

```
ffff800010307f70-ffff800010307fac: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (c0525434)
Location: mm/pgtable-generic.c:39
Inline: False
Direct callers:
  - arch/arm/mm/pgd.c:pgd_free
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
c0525434-c0525484: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (c0000000003d7518)
Location: mm/pgtable-generic.c:39
Inline: False
Direct callers:
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
  - mm/gup.c:follow_pmd_mask
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mincore.c:mincore_pte_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/vmalloc.c:vunmap_page_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
c0000000003d7518-c0000000003d7578: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffe000212e32)
Location: mm/pgtable-generic.c:39
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffffffe000212e32-ffffffe000212e74: pmd_clear_bad (STB_GLOBAL)
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
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8126ad50)
Location: mm/pgtable-generic.c:39
Inline: False
Direct callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
  - mm/mincore.c:mincore_pte_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8126ad50-ffffffff8126ada0: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8125d208)
Location: mm/pgtable-generic.c:39
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mincore.c:mincore_pte_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/pagewalk.c:walk_pgd_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8125d208-ffffffff8125d23d: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81268af0)
Location: mm/pgtable-generic.c:39
Inline: False
Direct callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
  - mm/mincore.c:mincore_pte_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81268af0-ffffffff81268b40: pmd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81278480)
Location: mm/pgtable-generic.c:39
Inline: False
Direct callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
  - mm/mincore.c:mincore_pte_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81278480-ffffffff812784d0: pmd_clear_bad (STB_GLOBAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
