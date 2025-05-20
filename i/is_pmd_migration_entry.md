# Function: <code>is_pmd_migration_entry</code>

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
In mm/gup.c (ffffffff81206680)
Location: include/linux/swapops.h:290
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff8120e7a0)
Location: include/linux/swapops.h:290
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff8121a9c4)
Location: include/linux/swapops.h:290
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff8123728b)
Location: include/linux/swapops.h:290
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8124ce86)
Location: include/linux/swapops.h:290
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81252ac8)
Location: include/linux/swapops.h:290
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
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
In mm/gup.c (ffffffff812275e1)
Location: include/linux/swapops.h:290
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:290
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff8123c6c3)
Location: include/linux/swapops.h:290
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff8125a7c5)
Location: include/linux/swapops.h:290
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81270986)
Location: include/linux/swapops.h:290
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81276ed6)
Location: include/linux/swapops.h:290
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
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
In mm/gup.c (ffffffff8123ad85)
Location: include/linux/swapops.h:286
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:286
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff81250ae0)
Location: include/linux/swapops.h:286
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff8126e645)
Location: include/linux/swapops.h:286
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81284fa6)
Location: include/linux/swapops.h:286
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8128bc31)
Location: include/linux/swapops.h:286
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/hmm.c (ffffffff812a75e4)
Location: include/linux/swapops.h:286
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
Location: include/linux/swapops.h:271
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff81262dc0)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff81289c85)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8129f616)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812a685f)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/hmm.c (ffffffff812c4714)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
Location: include/linux/swapops.h:271
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff81271570)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff812997f5)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812b09b6)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b7d38)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/hmm.c (ffffffff812d613e)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/gup.c (ffffffff81288986)
Location: include/linux/swapops.h:273
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:273
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff812a1e25)
Location: include/linux/swapops.h:273
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff812ceabd)
Location: include/linux/swapops.h:273
Inline: True
```
```
In mm/migrate.c (ffffffff812e6af6)
Location: include/linux/swapops.h:273
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812ed0ae)
Location: include/linux/swapops.h:273
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/hmm.c (ffffffff8130b35f)
Location: include/linux/swapops.h:273
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/gup.c (ffffffff81292666)
Location: include/linux/swapops.h:273
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:273
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff812ad64f)
Location: include/linux/swapops.h:273
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff812da3fd)
Location: include/linux/swapops.h:273
Inline: True
```
```
In mm/migrate.c (ffffffff812f1e46)
Location: include/linux/swapops.h:273
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812f8312)
Location: include/linux/swapops.h:273
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/hmm.c (ffffffff8131721f)
Location: include/linux/swapops.h:273
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int is_pmd_migration_entry(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81298106)
Location: include/linux/swapops.h:282
Inline: True
```
```
In mm/memory.c (ffffffff812a42b3)
Location: include/linux/swapops.h:282
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff812b2845)
Location: include/linux/swapops.h:282
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff812e1c5d)
Location: include/linux/swapops.h:282
Inline: True
```
```
In mm/migrate.c (ffffffff812f8176)
Location: include/linux/swapops.h:282
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812fb38a)
Location: include/linux/swapops.h:282
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_huge_pmd
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/hmm.c (ffffffff8131d518)
Location: include/linux/swapops.h:282
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812fa490-ffffffff812fa502: is_pmd_migration_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int is_pmd_migration_entry(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d8b44)
Location: include/linux/swapops.h:305
Inline: True
```
```
In mm/memory.c (ffffffff812e5710)
Location: include/linux/swapops.h:305
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff812f446a)
Location: include/linux/swapops.h:305
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff81328d40)
Location: include/linux/swapops.h:305
Inline: True
```
```
In mm/migrate.c (ffffffff813427d6)
Location: include/linux/swapops.h:305
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff813451ba)
Location: include/linux/swapops.h:305
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_huge_pmd
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/hmm.c (ffffffff8136a8b8)
Location: include/linux/swapops.h:305
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff813442f0-ffffffff81344362: is_pmd_migration_entry (STB_LOCAL)
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
In mm/memory.c (ffffffff81347a64)
Location: include/linux/swapops.h:425
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff8135845a)
Location: include/linux/swapops.h:425
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff81397f96)
Location: include/linux/swapops.h:425
Inline: True
```
```
In mm/migrate.c (ffffffff813b4d27)
Location: include/linux/swapops.h:425
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff813be573)
Location: include/linux/swapops.h:425
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/hmm.c (ffffffff813e8abc)
Location: include/linux/swapops.h:425
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/memory.c (ffffffff813bfe1a)
Location: include/linux/swapops.h:520
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff813d2a8d)
Location: include/linux/swapops.h:520
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff81417d12)
Location: include/linux/swapops.h:520
Inline: True
```
```
In mm/migrate.c (ffffffff81433ed7)
Location: include/linux/swapops.h:520
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81440de5)
Location: include/linux/swapops.h:520
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/hmm.c (ffffffff81470a45)
Location: include/linux/swapops.h:520
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/memory.c (ffffffff813f4ad5)
Location: include/linux/swapops.h:511
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff814077cd)
Location: include/linux/swapops.h:511
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81409793)
Location: include/linux/swapops.h:511
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/mempolicy.c (ffffffff8144b2e2)
Location: include/linux/swapops.h:511
Inline: True
```
```
In mm/migrate.c (ffffffff81469827)
Location: include/linux/swapops.h:511
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81476681)
Location: include/linux/swapops.h:511
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/hmm.c (ffffffff814a4fb9)
Location: include/linux/swapops.h:511
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int is_pmd_migration_entry(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81421126)
Location: include/linux/swapops.h:516
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff81433e5b)
Location: include/linux/swapops.h:516
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81435fd6)
Location: include/linux/swapops.h:516
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/mempolicy.c (ffffffff81484ccb)
Location: include/linux/swapops.h:516
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pmd
```
```
In mm/migrate.c (ffffffff81498757)
Location: include/linux/swapops.h:516
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff814a5f41)
Location: include/linux/swapops.h:516
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/hmm.c (ffffffff814d6078)
Location: include/linux/swapops.h:516
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff814a0d40-ffffffff814a0dce: is_pmd_migration_entry (STB_LOCAL)
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
In mm/gup.c (0)
Location: include/linux/swapops.h:300
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:300
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/swapops.h:300
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/swapops.h:300
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/swapops.h:300
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:300
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
In mm/gup.c (0)
Location: include/linux/swapops.h:300
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:300
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/swapops.h:300
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:300
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
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (c0000000003c3c64)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (c0000000003d57f8)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (c000000000413118)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (c000000000436f58)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (c000000000440f90)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/hmm.c (c0000000004704e8)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
Location: include/linux/swapops.h:300
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:300
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/swapops.h:300
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:300
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
In mm/gup.c (ffffffff81252af1)
Location: include/linux/swapops.h:271
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff81269bc0)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff81291dd5)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a8f96)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b0318)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/hmm.c (ffffffff812ce71e)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/gup.c (ffffffff8124589b)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff8125be6c)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff81283a4c)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8129a926)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812a17b3)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/hmm.c (ffffffff812bf48c)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
Location: include/linux/swapops.h:271
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff81267960)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff8128fbe5)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a6da6)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812ae128)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/hmm.c (ffffffff812cc52e)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
Location: include/linux/swapops.h:271
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/page_vma_mapped.c (ffffffff812772f6)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/mempolicy.c (ffffffff8129f076)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812b70d8)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812be47d)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/hmm.c (ffffffff812dd28e)
Location: include/linux/swapops.h:271
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
