# Function: <code>pmd_swp_uffd_wp</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ea2e8)
Location: arch/x86/include/asm/pgtable.h:1356
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f5509)
Location: arch/x86/include/asm/pgtable.h:1352
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
In mm/gup.c (ffffffff81298174)
Location: arch/x86/include/asm/pgtable.h:1352
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1352
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff812b2d7c)
Location: arch/x86/include/asm/pgtable.h:1352
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff812e1da8)
Location: arch/x86/include/asm/pgtable.h:1352
Inline: True
```
```
In mm/migrate.c (ffffffff812f82a8)
Location: arch/x86/include/asm/pgtable.h:1352
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81300f59)
Location: arch/x86/include/asm/pgtable.h:1352
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff8131d5dc)
Location: arch/x86/include/asm/pgtable.h:1352
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813d1093)
Location: arch/x86/include/asm/pgtable.h:1352
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
In mm/gup.c (ffffffff812d8bb2)
Location: arch/x86/include/asm/pgtable.h:1323
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1323
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff812f493c)
Location: arch/x86/include/asm/pgtable.h:1323
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff81328e8d)
Location: arch/x86/include/asm/pgtable.h:1323
Inline: True
```
```
In mm/migrate.c (ffffffff813428fe)
Location: arch/x86/include/asm/pgtable.h:1323
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8134abc9)
Location: arch/x86/include/asm/pgtable.h:1323
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff8136a97c)
Location: arch/x86/include/asm/pgtable.h:1323
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8142249d)
Location: arch/x86/include/asm/pgtable.h:1323
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1357
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff8135887b)
Location: arch/x86/include/asm/pgtable.h:1357
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff813980fd)
Location: arch/x86/include/asm/pgtable.h:1357
Inline: True
```
```
In mm/migrate.c (ffffffff813b4e2d)
Location: arch/x86/include/asm/pgtable.h:1357
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff813c1d57)
Location: arch/x86/include/asm/pgtable.h:1357
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff813e8afd)
Location: arch/x86/include/asm/pgtable.h:1357
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8149b8a4)
Location: arch/x86/include/asm/pgtable.h:1357
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1375
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff813d2f78)
Location: arch/x86/include/asm/pgtable.h:1375
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff81417e91)
Location: arch/x86/include/asm/pgtable.h:1375
Inline: True
```
```
In mm/migrate.c (ffffffff81433fdd)
Location: arch/x86/include/asm/pgtable.h:1375
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81443f37)
Location: arch/x86/include/asm/pgtable.h:1375
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
In mm/hmm.c (ffffffff81470a85)
Location: arch/x86/include/asm/pgtable.h:1375
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81530040)
Location: arch/x86/include/asm/pgtable.h:1375
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1373
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff81407bda)
Location: arch/x86/include/asm/pgtable.h:1373
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff814098ab)
Location: arch/x86/include/asm/pgtable.h:1373
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/mempolicy.c (ffffffff8144b4c7)
Location: arch/x86/include/asm/pgtable.h:1373
Inline: True
```
```
In mm/migrate.c (ffffffff8146985f)
Location: arch/x86/include/asm/pgtable.h:1373
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff814794b7)
Location: arch/x86/include/asm/pgtable.h:1373
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/hmm.c (ffffffff814a4ff9)
Location: arch/x86/include/asm/pgtable.h:1373
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81567ec8)
Location: arch/x86/include/asm/pgtable.h:1373
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1601
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff8143429e)
Location: arch/x86/include/asm/pgtable.h:1601
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff8143610c)
Location: arch/x86/include/asm/pgtable.h:1601
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/mempolicy.c (ffffffff81484e9d)
Location: arch/x86/include/asm/pgtable.h:1601
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pmd
```
```
In mm/migrate.c (ffffffff8149878f)
Location: arch/x86/include/asm/pgtable.h:1601
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff814a8a4a)
Location: arch/x86/include/asm/pgtable.h:1601
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/hmm.c (ffffffff814d60b8)
Location: arch/x86/include/asm/pgtable.h:1601
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8159edbe)
Location: arch/x86/include/asm/pgtable.h:1601
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
