# Function: <code>pmd_clear_flags</code>

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
In mm/pgtable-generic.c (ffffffff811d067f)
Location: arch/x86/include/asm/pgtable.h:265
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/huge_memory.c (ffffffff811f5e7c)
Location: arch/x86/include/asm/pgtable.h:265
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81278f7c)
Location: arch/x86/include/asm/pgtable.h:265
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/pgtable-generic.c (ffffffff811ed7ef)
Location: arch/x86/include/asm/pgtable.h:284
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/huge_memory.c (ffffffff812183d8)
Location: arch/x86/include/asm/pgtable.h:284
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff812a5828)
Location: arch/x86/include/asm/pgtable.h:284
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/pgtable-generic.c (ffffffff811f7bbf)
Location: arch/x86/include/asm/pgtable.h:284
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/huge_memory.c (ffffffff8122a97c)
Location: arch/x86/include/asm/pgtable.h:284
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/dax.c (ffffffff8129bb9b)
Location: arch/x86/include/asm/pgtable.h:284
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812bb172)
Location: arch/x86/include/asm/pgtable.h:284
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/pgtable-generic.c (ffffffff81202daf)
Location: arch/x86/include/asm/pgtable.h:341
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/rmap.c (ffffffff81203274)
Location: arch/x86/include/asm/pgtable.h:341
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff812365f1)
Location: arch/x86/include/asm/pgtable.h:341
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/dax.c (ffffffff812aaae8)
Location: arch/x86/include/asm/pgtable.h:341
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff812c689e)
Location: arch/x86/include/asm/pgtable.h:341
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/mm/pti.c (ffffffff826c5792)
Location: arch/x86/include/asm/pgtable.h:356
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In mm/gup.c (ffffffff812067c6)
Location: arch/x86/include/asm/pgtable.h:356
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff8120e7a0)
Location: arch/x86/include/asm/pgtable.h:356
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff8121ab9a)
Location: arch/x86/include/asm/pgtable.h:356
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff8121bb06)
Location: arch/x86/include/asm/pgtable.h:356
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/rmap.c (ffffffff8121be0a)
Location: arch/x86/include/asm/pgtable.h:356
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/mempolicy.c (ffffffff8123757e)
Location: arch/x86/include/asm/pgtable.h:356
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8124cec2)
Location: arch/x86/include/asm/pgtable.h:356
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81255bde)
Location: arch/x86/include/asm/pgtable.h:356
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/dax.c (ffffffff812ce332)
Location: arch/x86/include/asm/pgtable.h:356
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff812ec4ad)
Location: arch/x86/include/asm/pgtable.h:356
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/mm/pti.c (ffffffff810835d2)
Location: arch/x86/include/asm/pgtable.h:366
Inline: True
```
```
In mm/gup.c (ffffffff812275e5)
Location: arch/x86/include/asm/pgtable.h:366
Inline: True
```
```
In mm/memory.c (ffffffff8122ffb8)
Location: arch/x86/include/asm/pgtable.h:366
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff8123cb38)
Location: arch/x86/include/asm/pgtable.h:366
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8123dc55)
Location: arch/x86/include/asm/pgtable.h:366
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/mempolicy.c (ffffffff8125aa7b)
Location: arch/x86/include/asm/pgtable.h:366
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812709cc)
Location: arch/x86/include/asm/pgtable.h:366
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81279afe)
Location: arch/x86/include/asm/pgtable.h:366
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/dax.c (ffffffff812f86b9)
Location: arch/x86/include/asm/pgtable.h:366
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff81319aec)
Location: arch/x86/include/asm/pgtable.h:366
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/gup.c (ffffffff8123ad89)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
```
```
In mm/memory.c (ffffffff81241caa)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff8125100e)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8125223b)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/mempolicy.c (ffffffff8126e9b6)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81284fec)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8128e0db)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff812a7691)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff8130c43f)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81330bc5)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/gup.c (ffffffff8124bfb8)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
```
```
In mm/memory.c (ffffffff81254611)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff812632fa)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81264a9f)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/mempolicy.c (ffffffff81289e24)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8129f65c)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812a8a5d)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff812c47c1)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff81333981)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813589e6)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/gup.c (ffffffff8125a4a1)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
```
```
In mm/memory.c (ffffffff81262b71)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff81271aaa)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81273326)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff81285360)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81299994)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812b09fc)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b9fdd)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff812d61e4)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff81347546)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81370c36)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/gup.c (ffffffff812889d8)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
```
```
In mm/memory.c (ffffffff81294a85)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff812a1e50)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812a3f01)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812b7957)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff812cebd0)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
```
```
In mm/migrate.c (ffffffff812e6b3c)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812eebba)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff8130b405)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff8138d929)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813b8f52)
Location: arch/x86/include/asm/pgtable.h:407
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/gup.c (ffffffff812926b8)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
```
```
In mm/memory.c (ffffffff8129f305)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff812ad914)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812afc0b)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812c2892)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff812da510)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
```
```
In mm/migrate.c (ffffffff812f1e8c)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812fa21a)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff813172c5)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff8139f3a9)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813ca989)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/gup.c (ffffffff81298170)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
```
```
In mm/memory.c (ffffffff812a42c7)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff812b2d78)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812b51ac)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812c9718)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff812e1d6c)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
```
```
In mm/migrate.c (ffffffff812f81bc)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81300f55)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff8131d5d8)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff813a6116)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813d0cda)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/gup.c (ffffffff812d8bae)
Location: arch/x86/include/asm/pgtable.h:377
Inline: True
```
```
In mm/memory.c (ffffffff812e5724)
Location: arch/x86/include/asm/pgtable.h:377
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff812f4938)
Location: arch/x86/include/asm/pgtable.h:377
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812f6d48)
Location: arch/x86/include/asm/pgtable.h:377
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8130e73a)
Location: arch/x86/include/asm/pgtable.h:377
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81328e4a)
Location: arch/x86/include/asm/pgtable.h:377
Inline: True
```
```
In mm/migrate.c (ffffffff8134281c)
Location: arch/x86/include/asm/pgtable.h:377
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8134abc5)
Location: arch/x86/include/asm/pgtable.h:377
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff8136a978)
Location: arch/x86/include/asm/pgtable.h:377
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff813f5b86)
Location: arch/x86/include/asm/pgtable.h:377
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81422499)
Location: arch/x86/include/asm/pgtable.h:377
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff81347a78)
Location: arch/x86/include/asm/pgtable.h:380
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff81358877)
Location: arch/x86/include/asm/pgtable.h:380
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8135b245)
Location: arch/x86/include/asm/pgtable.h:380
Inline: True
```
```
In mm/madvise.c (ffffffff81377b41)
Location: arch/x86/include/asm/pgtable.h:380
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81397fda)
Location: arch/x86/include/asm/pgtable.h:380
Inline: True
```
```
In mm/migrate.c (ffffffff813b4d5f)
Location: arch/x86/include/asm/pgtable.h:380
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff813c1d53)
Location: arch/x86/include/asm/pgtable.h:380
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff813e8af9)
Location: arch/x86/include/asm/pgtable.h:380
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8149b777)
Location: arch/x86/include/asm/pgtable.h:380
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff813bfe2e)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff813d2f74)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff813d6143)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
```
```
In mm/madvise.c (ffffffff813f52e3)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81417d54)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
```
```
In mm/migrate.c (ffffffff81433f0f)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81443f33)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff81470a81)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8152fc5a)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (ffffffff813f4ae9)
Location: arch/x86/include/asm/pgtable.h:398
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff81407bcc)
Location: arch/x86/include/asm/pgtable.h:398
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff814098a7)
Location: arch/x86/include/asm/pgtable.h:398
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/rmap.c (ffffffff8140b247)
Location: arch/x86/include/asm/pgtable.h:398
Inline: True
```
```
In mm/madvise.c (ffffffff81428496)
Location: arch/x86/include/asm/pgtable.h:398
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff8144b48f)
Location: arch/x86/include/asm/pgtable.h:398
Inline: True
```
```
In mm/migrate.c (ffffffff8146985b)
Location: arch/x86/include/asm/pgtable.h:398
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff814794b3)
Location: arch/x86/include/asm/pgtable.h:398
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff814a4ff5)
Location: arch/x86/include/asm/pgtable.h:398
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81567b7c)
Location: arch/x86/include/asm/pgtable.h:398
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/mm/pgtable.c (ffffffff810d3c74)
Location: arch/x86/include/asm/pgtable.h:501
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_mkwrite
```
```
In mm/memory.c (ffffffff8142113a)
Location: arch/x86/include/asm/pgtable.h:501
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff81434290)
Location: arch/x86/include/asm/pgtable.h:501
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81436108)
Location: arch/x86/include/asm/pgtable.h:501
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/rmap.c (ffffffff81437b89)
Location: arch/x86/include/asm/pgtable.h:501
Inline: True
```
```
In mm/madvise.c (ffffffff81461d91)
Location: arch/x86/include/asm/pgtable.h:501
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81484e61)
Location: arch/x86/include/asm/pgtable.h:501
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pmd
  - mm/mempolicy.c:queue_folios_pmd
```
```
In mm/migrate.c (ffffffff8149878b)
Location: arch/x86/include/asm/pgtable.h:501
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff814a8a46)
Location: arch/x86/include/asm/pgtable.h:501
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff814d60b4)
Location: arch/x86/include/asm/pgtable.h:501
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8159ee01)
Location: arch/x86/include/asm/pgtable.h:501
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81252af1)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
```
```
In mm/memory.c (ffffffff8125b1c1)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff8126a0fa)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8126b976)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8127d9b0)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81291f74)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a8fdc)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b25bd)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff812ce7c4)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff8133fb26)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81369216)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff8125c218)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8125d583)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8126fc68)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812a393d)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
```
```
In fs/dax.c (ffffffff8133073f)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813594e8)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/gup.c (ffffffff81250891)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
```
```
In mm/memory.c (ffffffff81258f61)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff81267e9a)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81269716)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8127b750)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff8128fd84)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a6dec)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b03cd)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff812cc5d4)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff8133d5f6)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81366ce6)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/gup.c (ffffffff8126021a)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
```
```
In mm/memory.c (ffffffff81268961)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff81277819)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8127922f)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8128b722)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff8129f21d)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812b711d)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812c070d)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/hmm.c (ffffffff812dd334)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff8135050c)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8137a336)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
</ul>

## Differences
