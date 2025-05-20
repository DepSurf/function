# Function: <code>pmd_to_swp_entry</code>

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
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
swp_entry_t pmd_to_swp_entry(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81206680)
Location: include/linux/swapops.h:272
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff8120e7a0)
Location: include/linux/swapops.h:272
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff8121ab9a)
Location: include/linux/swapops.h:272
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff8123757e)
Location: include/linux/swapops.h:272
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8124cec2)
Location: include/linux/swapops.h:272
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81255bb8)
Location: include/linux/swapops.h:272
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff812ec4ad)
Location: include/linux/swapops.h:272
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8121a430-ffffffff8121a495: pmd_to_swp_entry (STB_LOCAL)
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
In mm/gup.c (0)
Location: include/linux/swapops.h:272
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:272
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff8123cb1b)
Location: include/linux/swapops.h:272
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (0)
Location: include/linux/swapops.h:272
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812709fc)
Location: include/linux/swapops.h:272
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81279a53)
Location: include/linux/swapops.h:272
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81319aec)
Location: include/linux/swapops.h:272
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (0)
Location: include/linux/swapops.h:268
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:268
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff81250ff1)
Location: include/linux/swapops.h:268
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (0)
Location: include/linux/swapops.h:268
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8128501c)
Location: include/linux/swapops.h:268
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8128e033)
Location: include/linux/swapops.h:268
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:268
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81330bc5)
Location: include/linux/swapops.h:268
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (0)
Location: include/linux/swapops.h:253
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff812632d8)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8129f68b)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812a89bd)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813589e6)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (0)
Location: include/linux/swapops.h:253
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff81271a88)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812b0a2b)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b9f3d)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81370c36)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
swp_entry_t pmd_to_swp_entry(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/swapops.h:255
Inline: True
```
```
In mm/memory.c (ffffffff81294a85)
Location: include/linux/swapops.h:255
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff812a208d)
Location: include/linux/swapops.h:255
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (0)
Location: include/linux/swapops.h:255
Inline: True
```
```
In mm/migrate.c (ffffffff812e6b6b)
Location: include/linux/swapops.h:255
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812eeb1d)
Location: include/linux/swapops.h:255
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:255
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813b86f2)
Location: include/linux/swapops.h:255
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff812a16f0-ffffffff812a1748: pmd_to_swp_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
swp_entry_t pmd_to_swp_entry(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/swapops.h:255
Inline: True
```
```
In mm/memory.c (ffffffff8129f305)
Location: include/linux/swapops.h:255
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff812ad9d4)
Location: include/linux/swapops.h:255
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (0)
Location: include/linux/swapops.h:255
Inline: True
```
```
In mm/migrate.c (ffffffff812f1ebb)
Location: include/linux/swapops.h:255
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812fa17d)
Location: include/linux/swapops.h:255
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:255
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813ca122)
Location: include/linux/swapops.h:255
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff812acfb0-ffffffff812ad008: pmd_to_swp_entry (STB_LOCAL)
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
In mm/gup.c (ffffffff8129816b)
Location: include/linux/swapops.h:262
Inline: True
```
```
In mm/memory.c (ffffffff812a42b3)
Location: include/linux/swapops.h:262
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff812b2d61)
Location: include/linux/swapops.h:262
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff812e1d67)
Location: include/linux/swapops.h:262
Inline: True
```
```
In mm/migrate.c (ffffffff812f81b3)
Location: include/linux/swapops.h:262
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81300f2e)
Location: include/linux/swapops.h:262
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff8131d5d0)
Location: include/linux/swapops.h:262
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813d0cce)
Location: include/linux/swapops.h:262
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (ffffffff812d8ba9)
Location: include/linux/swapops.h:285
Inline: True
```
```
In mm/memory.c (ffffffff812e5710)
Location: include/linux/swapops.h:285
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff812f4921)
Location: include/linux/swapops.h:285
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff81328e45)
Location: include/linux/swapops.h:285
Inline: True
```
```
In mm/migrate.c (ffffffff81342813)
Location: include/linux/swapops.h:285
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8134ab9e)
Location: include/linux/swapops.h:285
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff8136a970)
Location: include/linux/swapops.h:285
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81422491)
Location: include/linux/swapops.h:285
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
swp_entry_t pmd_to_swp_entry(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81347a64)
Location: include/linux/swapops.h:405
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff81358854)
Location: include/linux/swapops.h:405
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff81397fd0)
Location: include/linux/swapops.h:405
Inline: True
```
```
In mm/migrate.c (ffffffff813b4d56)
Location: include/linux/swapops.h:405
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff813c1d2c)
Location: include/linux/swapops.h:405
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff813e8af1)
Location: include/linux/swapops.h:405
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8149b76b)
Location: include/linux/swapops.h:405
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff813b97e0-ffffffff813b9868: pmd_to_swp_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
swp_entry_t pmd_to_swp_entry(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bfe1a)
Location: include/linux/swapops.h:500
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff813d2f51)
Location: include/linux/swapops.h:500
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff81417d4b)
Location: include/linux/swapops.h:500
Inline: True
```
```
In mm/migrate.c (ffffffff81433f06)
Location: include/linux/swapops.h:500
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81443f0c)
Location: include/linux/swapops.h:500
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff81470a79)
Location: include/linux/swapops.h:500
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8152fc4e)
Location: include/linux/swapops.h:500
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8143bc00-ffffffff8143bc8a: pmd_to_swp_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
swp_entry_t pmd_to_swp_entry(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f4ad5)
Location: include/linux/swapops.h:491
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff81407bcc)
Location: include/linux/swapops.h:491
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff8140989f)
Location: include/linux/swapops.h:491
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/mempolicy.c (ffffffff8144b48a)
Location: include/linux/swapops.h:491
Inline: True
```
```
In mm/migrate.c (ffffffff81469856)
Location: include/linux/swapops.h:491
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8147948c)
Location: include/linux/swapops.h:491
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/hmm.c (ffffffff814a4fed)
Location: include/linux/swapops.h:491
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81567b70)
Location: include/linux/swapops.h:491
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81471440-ffffffff814714b2: pmd_to_swp_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
swp_entry_t pmd_to_swp_entry(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81421126)
Location: include/linux/swapops.h:496
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff81434290)
Location: include/linux/swapops.h:496
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81436100)
Location: include/linux/swapops.h:496
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/mempolicy.c (ffffffff81484e5c)
Location: include/linux/swapops.h:496
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pmd
```
```
In mm/migrate.c (ffffffff81498786)
Location: include/linux/swapops.h:496
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff814a8a1f)
Location: include/linux/swapops.h:496
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff814d60ac)
Location: include/linux/swapops.h:496
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8159ede1)
Location: include/linux/swapops.h:496
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff814a0b80-ffffffff814a0bf2: pmd_to_swp_entry (STB_LOCAL)
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
In mm/page_vma_mapped.c (0)
Location: include/linux/swapops.h:290
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/swapops.h:290
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (0)
Location: include/linux/swapops.h:290
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
In mm/gup.c (c0000000003b7df0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (c0000000003c3c64)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (c0000000003d57f8)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (c000000000413120)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (c000000000436f60)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (c0000000004443a0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (c0000000004704f0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (c00000000054cafc)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (0)
Location: include/linux/swapops.h:290
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
In mm/gup.c (0)
Location: include/linux/swapops.h:253
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff8126a0d8)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a900b)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b251d)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81369216)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff8125c218)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8129a987)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812a38ad)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813594e8)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (0)
Location: include/linux/swapops.h:253
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff81267e78)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a6e1b)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b032d)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81366ce6)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (0)
Location: include/linux/swapops.h:253
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff812777f7)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812b714d)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812c066d)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8137a336)
Location: include/linux/swapops.h:253
Inline: True
Inline callers:
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
