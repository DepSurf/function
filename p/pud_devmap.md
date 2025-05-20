# Function: <code>pud_devmap</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811f1032)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
```
```
In mm/memory.c (ffffffff811f5750)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (ffffffff8120246e)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
```
```
In mm/huge_memory.c (ffffffff8123477a)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
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
In mm/gup.c (ffffffff81205c8e)
Location: arch/x86/include/asm/pgtable.h:252
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff8120e925)
Location: arch/x86/include/asm/pgtable.h:252
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (ffffffff8121b28a)
Location: arch/x86/include/asm/pgtable.h:252
Inline: True
```
```
In mm/huge_memory.c (ffffffff8125267a)
Location: arch/x86/include/asm/pgtable.h:252
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
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
In mm/gup.c (ffffffff812270fa)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff8122ff0c)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (ffffffff8123d34b)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
```
```
In mm/huge_memory.c (ffffffff81276abd)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff81288aaf)
Location: arch/x86/include/asm/pgtable.h:262
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
In mm/gup.c (ffffffff8123a1f0)
Location: arch/x86/include/asm/pgtable.h:264
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff81241c02)
Location: arch/x86/include/asm/pgtable.h:264
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (ffffffff812514f9)
Location: arch/x86/include/asm/pgtable.h:264
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/huge_memory.c (ffffffff8128b9fa)
Location: arch/x86/include/asm/pgtable.h:264
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff8129d7b2)
Location: arch/x86/include/asm/pgtable.h:264
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
In mm/gup.c (ffffffff8124b3bf)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff81254565)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (ffffffff812637c3)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/huge_memory.c (ffffffff812a65fe)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff812b8a82)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812c4d7b)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
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
In mm/gup.c (ffffffff812598af)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff81262ac5)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (ffffffff812722ad)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/huge_memory.c (ffffffff812b7ad3)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff812ca962)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812d672b)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
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
In mm/gup.c (ffffffff8128a9b8)
Location: arch/x86/include/asm/pgtable.h:286
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
```
```
In mm/memory.c (ffffffff812948e8)
Location: arch/x86/include/asm/pgtable.h:286
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (ffffffff812a2a76)
Location: arch/x86/include/asm/pgtable.h:286
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ecca3)
Location: arch/x86/include/asm/pgtable.h:286
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff8130079f)
Location: arch/x86/include/asm/pgtable.h:286
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8130b880)
Location: arch/x86/include/asm/pgtable.h:286
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130ca68)
Location: arch/x86/include/asm/pgtable.h:286
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
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
In mm/gup.c (ffffffff81294678)
Location: arch/x86/include/asm/pgtable.h:285
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
```
```
In mm/memory.c (ffffffff8129f168)
Location: arch/x86/include/asm/pgtable.h:285
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
```
```
In mm/pagewalk.c (ffffffff812ae3b6)
Location: arch/x86/include/asm/pgtable.h:285
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f7d33)
Location: arch/x86/include/asm/pgtable.h:285
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff8130c93f)
Location: arch/x86/include/asm/pgtable.h:285
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff81317770)
Location: arch/x86/include/asm/pgtable.h:285
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff813189a8)
Location: arch/x86/include/asm/pgtable.h:285
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
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
In mm/gup.c (ffffffff8129a0c8)
Location: arch/x86/include/asm/pgtable.h:285
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
```
```
In mm/memory.c (ffffffff812a40fe)
Location: arch/x86/include/asm/pgtable.h:285
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
```
```
In mm/pagewalk.c (ffffffff812b37a7)
Location: arch/x86/include/asm/pgtable.h:285
Inline: True
```
```
In mm/huge_memory.c (ffffffff812fe2e3)
Location: arch/x86/include/asm/pgtable.h:285
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff813130af)
Location: arch/x86/include/asm/pgtable.h:285
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8131d970)
Location: arch/x86/include/asm/pgtable.h:285
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131eb98)
Location: arch/x86/include/asm/pgtable.h:285
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
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
In mm/gup.c (ffffffff812daa6b)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
```
```
In mm/memory.c (ffffffff812e542a)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
```
```
In mm/mremap.c (ffffffff812f2506)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812f5334)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
```
```
In mm/huge_memory.c (ffffffff81347e83)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff8135fb85)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8136ad10)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bf78)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
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
In mm/gup.c (ffffffff8133a5e4)
Location: arch/x86/include/asm/pgtable.h:259
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
```
```
In mm/memory.c (ffffffff81347722)
Location: arch/x86/include/asm/pgtable.h:259
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
```
```
In mm/mremap.c (ffffffff813563a7)
Location: arch/x86/include/asm/pgtable.h:259
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff813591e8)
Location: arch/x86/include/asm/pgtable.h:259
Inline: True
```
```
In mm/huge_memory.c (ffffffff813be31f)
Location: arch/x86/include/asm/pgtable.h:259
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff813da7c1)
Location: arch/x86/include/asm/pgtable.h:259
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff813e875f)
Location: arch/x86/include/asm/pgtable.h:259
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff813ea1a4)
Location: arch/x86/include/asm/pgtable.h:259
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
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
In mm/gup.c (ffffffff813b2a5c)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813bfadc)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
```
```
In mm/mremap.c (ffffffff813d09cb)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff813d3b00)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
```
```
In mm/huge_memory.c (ffffffff81440b6f)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff814609de)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
```
```
In mm/hmm.c (ffffffff814706df)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff81472264)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
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
In mm/gup.c (ffffffff813e759e)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813f47a6)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
```
```
In mm/mremap.c (ffffffff814053eb)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff814084d0)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
```
```
In mm/huge_memory.c (ffffffff81476425)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff814951b1)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
```
```
In mm/hmm.c (ffffffff814a540f)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a6a45)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
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
In mm/gup.c (ffffffff8141221c)
Location: arch/x86/include/asm/pgtable.h:297
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
```
```
In mm/memory.c (ffffffff81420da8)
Location: arch/x86/include/asm/pgtable.h:297
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
```
```
In mm/mremap.c (ffffffff81431902)
Location: arch/x86/include/asm/pgtable.h:297
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81434bf0)
Location: arch/x86/include/asm/pgtable.h:297
Inline: True
```
```
In mm/huge_memory.c (ffffffff814a5ccd)
Location: arch/x86/include/asm/pgtable.h:297
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff814c4b1d)
Location: arch/x86/include/asm/pgtable.h:297
Inline: True
```
```
In mm/hmm.c (ffffffff814d63cf)
Location: arch/x86/include/asm/pgtable.h:297
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d794f)
Location: arch/x86/include/asm/pgtable.h:297
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
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
Location: arch/arm64/include/asm/pgtable.h:688
Inline: True
```
```
In mm/memory.c (0)
Location: arch/arm64/include/asm/pgtable.h:688
Inline: True
```
```
In mm/pagewalk.c (0)
Location: arch/arm64/include/asm/pgtable.h:688
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/arm64/include/asm/pgtable.h:688
Inline: True
```
```
In mm/memory-failure.c (0)
Location: arch/arm64/include/asm/pgtable.h:688
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
Location: include/linux/mm.h:572
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:572
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
In mm/gup.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1314
Inline: True
```
```
In mm/memory.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1314
Inline: True
```
```
In mm/pagewalk.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1314
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1314
Inline: True
```
```
In mm/memory-failure.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1314
Inline: True
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
Location: include/linux/mm.h:572
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:572
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
In mm/gup.c (ffffffff81251eff)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff8125b115)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (ffffffff8126a8fd)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/huge_memory.c (ffffffff812b00b3)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff812c2f42)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812ced0b)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
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
In mm/gup.c (ffffffff81244cf6)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff8124d339)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (ffffffff8125c673)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/huge_memory.c (ffffffff812a157c)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff812b403f)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/hmm.c (ffffffff812bf9aa)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
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
In mm/gup.c (ffffffff8124fc9f)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff81258eb5)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (ffffffff8126869d)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/huge_memory.c (ffffffff812adec3)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff812c0d52)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812ccb1b)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
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
In mm/gup.c (ffffffff8125f639)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff812688b5)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (ffffffff81278024)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/huge_memory.c (ffffffff812be21c)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff812d1812)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812dd8ab)
Location: arch/x86/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
</details>
</li>
</ul>

## Differences
