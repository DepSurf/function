# Function: <code>pmd_swp_soft_dirty</code>

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
In mm/gup.c (ffffffff812067bf)
Location: arch/x86/include/asm/pgtable.h:1187
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1187
Inline: False
```
```
In mm/page_vma_mapped.c (ffffffff8121a438)
Location: arch/x86/include/asm/pgtable.h:1187
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/pgtable.h:1187
Inline: True
```
```
In mm/migrate.c (ffffffff8124cef5)
Location: arch/x86/include/asm/pgtable.h:1187
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1187
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff812ec4f7)
Location: arch/x86/include/asm/pgtable.h:1187
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
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:1253
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1253
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff8123cb1b)
Location: arch/x86/include/asm/pgtable.h:1253
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/pgtable.h:1253
Inline: True
```
```
In mm/migrate.c (ffffffff812709fc)
Location: arch/x86/include/asm/pgtable.h:1253
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81279a53)
Location: arch/x86/include/asm/pgtable.h:1253
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81319aec)
Location: arch/x86/include/asm/pgtable.h:1253
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:1342
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1342
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81250ff1)
Location: arch/x86/include/asm/pgtable.h:1342
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/pgtable.h:1342
Inline: True
```
```
In mm/migrate.c (ffffffff8128501c)
Location: arch/x86/include/asm/pgtable.h:1342
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8128e033)
Location: arch/x86/include/asm/pgtable.h:1342
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1342
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81330bc5)
Location: arch/x86/include/asm/pgtable.h:1342
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812632d8)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In mm/migrate.c (ffffffff8129f68b)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812a89bd)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813589e6)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81271a88)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In mm/migrate.c (ffffffff812b0a2b)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b9f3d)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81370c36)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:1323
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1323
Inline: False
```
```
In mm/page_vma_mapped.c (ffffffff812a208d)
Location: arch/x86/include/asm/pgtable.h:1323
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/pgtable.h:1323
Inline: True
```
```
In mm/migrate.c (ffffffff812e6b6b)
Location: arch/x86/include/asm/pgtable.h:1323
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1323
Inline: False
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1323
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff813b86f2)
Location: arch/x86/include/asm/pgtable.h:1323
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: False
```
```
In mm/page_vma_mapped.c (ffffffff812ad9d4)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: True
```
```
In mm/migrate.c (ffffffff812f1ebb)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: False
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff813ca122)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
Location: arch/x86/include/asm/pgtable.h:1319
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: False
```
```
In mm/page_vma_mapped.c (ffffffff812b2d61)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff812e1d67)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: True
```
```
In mm/migrate.c (ffffffff812f81b3)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: False
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff813d0cce)
Location: arch/x86/include/asm/pgtable.h:1319
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
Location: arch/x86/include/asm/pgtable.h:1290
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1290
Inline: False
```
```
In mm/page_vma_mapped.c (ffffffff812f4921)
Location: arch/x86/include/asm/pgtable.h:1290
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff81328e45)
Location: arch/x86/include/asm/pgtable.h:1290
Inline: True
```
```
In mm/migrate.c (ffffffff81342813)
Location: arch/x86/include/asm/pgtable.h:1290
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1290
Inline: False
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1290
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff81422491)
Location: arch/x86/include/asm/pgtable.h:1290
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
Location: arch/x86/include/asm/pgtable.h:1324
Inline: False
```
```
In mm/page_vma_mapped.c (ffffffff81358854)
Location: arch/x86/include/asm/pgtable.h:1324
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff81397fd0)
Location: arch/x86/include/asm/pgtable.h:1324
Inline: True
```
```
In mm/migrate.c (ffffffff813b4d56)
Location: arch/x86/include/asm/pgtable.h:1324
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1324
Inline: False
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1324
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff8149b76b)
Location: arch/x86/include/asm/pgtable.h:1324
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
Location: arch/x86/include/asm/pgtable.h:1342
Inline: False
```
```
In mm/page_vma_mapped.c (ffffffff813d2f51)
Location: arch/x86/include/asm/pgtable.h:1342
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff81417d4b)
Location: arch/x86/include/asm/pgtable.h:1342
Inline: True
```
```
In mm/migrate.c (ffffffff81433f06)
Location: arch/x86/include/asm/pgtable.h:1342
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1342
Inline: False
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1342
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff8152fc4e)
Location: arch/x86/include/asm/pgtable.h:1342
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
Location: arch/x86/include/asm/pgtable.h:1340
Inline: False
```
```
In mm/page_vma_mapped.c (ffffffff81407bcc)
Location: arch/x86/include/asm/pgtable.h:1340
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff8140989f)
Location: arch/x86/include/asm/pgtable.h:1340
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/mempolicy.c (ffffffff8144b48a)
Location: arch/x86/include/asm/pgtable.h:1340
Inline: True
```
```
In mm/migrate.c (ffffffff81469856)
Location: arch/x86/include/asm/pgtable.h:1340
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1340
Inline: False
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1340
Inline: False
```
```
In fs/proc/task_mmu.c (ffffffff81567b70)
Location: arch/x86/include/asm/pgtable.h:1340
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
In mm/memory.c (ffffffff81421126)
Location: arch/x86/include/asm/pgtable.h:1568
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff81434290)
Location: arch/x86/include/asm/pgtable.h:1568
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81436100)
Location: arch/x86/include/asm/pgtable.h:1568
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/mempolicy.c (ffffffff81484e5c)
Location: arch/x86/include/asm/pgtable.h:1568
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pmd
```
```
In mm/migrate.c (ffffffff81498786)
Location: arch/x86/include/asm/pgtable.h:1568
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff814a8a1f)
Location: arch/x86/include/asm/pgtable.h:1568
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff814d60ac)
Location: arch/x86/include/asm/pgtable.h:1568
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8159edc1)
Location: arch/x86/include/asm/pgtable.h:1568
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable.h:783
Inline: True
```
</details>
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff8126a0d8)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In mm/migrate.c (ffffffff812a900b)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b251d)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81369216)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff8125c218)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In mm/migrate.c (ffffffff8129a987)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812a38ad)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813594e8)
Location: arch/x86/include/asm/pgtable.h:1362
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
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81267e78)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In mm/migrate.c (ffffffff812a6e1b)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b032d)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81366ce6)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812777f7)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In mm/migrate.c (ffffffff812b714d)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812c066d)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8137a336)
Location: arch/x86/include/asm/pgtable.h:1362
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
</ul>

## Differences
