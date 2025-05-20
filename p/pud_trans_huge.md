# Function: <code>pud_trans_huge</code>

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
In mm/memory.c (ffffffff811f5732)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (ffffffff81202454)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
```
```
In mm/huge_memory.c (ffffffff812346fb)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
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
In mm/memory.c (ffffffff8120e64f)
Location: arch/x86/include/asm/pgtable.h:233
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (ffffffff8121b084)
Location: arch/x86/include/asm/pgtable.h:233
Inline: True
```
```
In mm/huge_memory.c (ffffffff812525fb)
Location: arch/x86/include/asm/pgtable.h:233
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
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
In mm/memory.c (ffffffff8122fddc)
Location: arch/x86/include/asm/pgtable.h:243
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (ffffffff8123d026)
Location: arch/x86/include/asm/pgtable.h:243
Inline: True
```
```
In mm/huge_memory.c (ffffffff81276a2b)
Location: arch/x86/include/asm/pgtable.h:243
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
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
In mm/memory.c (ffffffff81241acc)
Location: arch/x86/include/asm/pgtable.h:245
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (ffffffff812514d9)
Location: arch/x86/include/asm/pgtable.h:245
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/huge_memory.c (ffffffff8128b951)
Location: arch/x86/include/asm/pgtable.h:245
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
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
In mm/memory.c (ffffffff81254438)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (ffffffff812637a3)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/huge_memory.c (ffffffff812a6565)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
```
```
In mm/hmm.c (ffffffff812c4d5c)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff81262998)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (ffffffff81272291)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/huge_memory.c (ffffffff812b7a43)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
```
```
In mm/hmm.c (ffffffff812d670c)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff812948d6)
Location: arch/x86/include/asm/pgtable.h:267
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (ffffffff812a2a56)
Location: arch/x86/include/asm/pgtable.h:267
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ecc13)
Location: arch/x86/include/asm/pgtable.h:267
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
```
```
In mm/hmm.c (ffffffff8130b864)
Location: arch/x86/include/asm/pgtable.h:267
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130ca4c)
Location: arch/x86/include/asm/pgtable.h:267
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
In mm/memory.c (ffffffff8129f156)
Location: arch/x86/include/asm/pgtable.h:266
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
```
```
In mm/pagewalk.c (ffffffff812ae396)
Location: arch/x86/include/asm/pgtable.h:266
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f7ca3)
Location: arch/x86/include/asm/pgtable.h:266
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
```
```
In mm/hmm.c (ffffffff81317754)
Location: arch/x86/include/asm/pgtable.h:266
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131898c)
Location: arch/x86/include/asm/pgtable.h:266
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
In mm/memory.c (ffffffff812a40eb)
Location: arch/x86/include/asm/pgtable.h:266
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
```
```
In mm/pagewalk.c (ffffffff812b3787)
Location: arch/x86/include/asm/pgtable.h:266
Inline: True
```
```
In mm/huge_memory.c (ffffffff812fe253)
Location: arch/x86/include/asm/pgtable.h:266
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
```
```
In mm/hmm.c (ffffffff8131d954)
Location: arch/x86/include/asm/pgtable.h:266
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131eb7c)
Location: arch/x86/include/asm/pgtable.h:266
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
In mm/memory.c (ffffffff812e5417)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
```
```
In mm/mremap.c (ffffffff812f2840)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812f5314)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
```
```
In mm/huge_memory.c (ffffffff81347df3)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
```
```
In mm/hmm.c (ffffffff8136acf4)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bf5c)
Location: arch/x86/include/asm/pgtable.h:237
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
In mm/memory.c (ffffffff8134770f)
Location: arch/x86/include/asm/pgtable.h:240
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
```
```
In mm/mremap.c (ffffffff81356385)
Location: arch/x86/include/asm/pgtable.h:240
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff813591c9)
Location: arch/x86/include/asm/pgtable.h:240
Inline: True
```
```
In mm/huge_memory.c (ffffffff813be281)
Location: arch/x86/include/asm/pgtable.h:240
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
```
```
In mm/hmm.c (ffffffff813e8744)
Location: arch/x86/include/asm/pgtable.h:240
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff813ea189)
Location: arch/x86/include/asm/pgtable.h:240
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
In mm/memory.c (ffffffff813bfac9)
Location: arch/x86/include/asm/pgtable.h:241
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
```
```
In mm/mremap.c (ffffffff813d09a9)
Location: arch/x86/include/asm/pgtable.h:241
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff813d3ae5)
Location: arch/x86/include/asm/pgtable.h:241
Inline: True
```
```
In mm/huge_memory.c (ffffffff81440ad1)
Location: arch/x86/include/asm/pgtable.h:241
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
```
```
In mm/hmm.c (ffffffff814706c4)
Location: arch/x86/include/asm/pgtable.h:241
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff81472246)
Location: arch/x86/include/asm/pgtable.h:241
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
In mm/memory.c (ffffffff813f4792)
Location: arch/x86/include/asm/pgtable.h:242
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
```
```
In mm/mremap.c (ffffffff814053c9)
Location: arch/x86/include/asm/pgtable.h:242
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff814084b5)
Location: arch/x86/include/asm/pgtable.h:242
Inline: True
```
```
In mm/huge_memory.c (ffffffff8147638a)
Location: arch/x86/include/asm/pgtable.h:242
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
```
```
In mm/hmm.c (ffffffff814a53f4)
Location: arch/x86/include/asm/pgtable.h:242
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a69c9)
Location: arch/x86/include/asm/pgtable.h:242
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
In mm/memory.c (ffffffff81420d95)
Location: arch/x86/include/asm/pgtable.h:278
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
```
```
In mm/mremap.c (ffffffff814318dc)
Location: arch/x86/include/asm/pgtable.h:278
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81434bd5)
Location: arch/x86/include/asm/pgtable.h:278
Inline: True
```
```
In mm/huge_memory.c (ffffffff814a5c36)
Location: arch/x86/include/asm/pgtable.h:278
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
```
```
In mm/hmm.c (ffffffff814d63b4)
Location: arch/x86/include/asm/pgtable.h:278
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d78c9)
Location: arch/x86/include/asm/pgtable.h:278
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:909
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:909
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable.h:909
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:909
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:909
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:909
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable.h:909
Inline: True
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:909
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
In mm/memory.c (ffffffff8125afe8)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (ffffffff8126a8e1)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/huge_memory.c (ffffffff812b0023)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
```
```
In mm/hmm.c (ffffffff812cecec)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff8124d320)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (0)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a14f6)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
```
```
In mm/hmm.c (ffffffff812bf99f)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff81258d88)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (ffffffff81268681)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/huge_memory.c (ffffffff812ade33)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
```
```
In mm/hmm.c (ffffffff812ccafc)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff81268788)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/pagewalk.c (ffffffff81278008)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/huge_memory.c (ffffffff812be185)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:copy_huge_pud
```
```
In mm/hmm.c (ffffffff812dd88c)
Location: arch/x86/include/asm/pgtable.h:262
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
</details>
</li>
</ul>

## Differences
