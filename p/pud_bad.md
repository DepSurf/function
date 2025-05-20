# Function: <code>pud_bad</code>

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
In mm/gup.c (ffffffff811ba837)
Location: arch/x86/include/asm/pgtable.h:615
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811bc236)
Location: arch/x86/include/asm/pgtable.h:615
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811c85e9)
Location: arch/x86/include/asm/pgtable.h:615
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811c93c9)
Location: arch/x86/include/asm/pgtable.h:615
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff811ce397)
Location: arch/x86/include/asm/pgtable.h:615
Inline: True
```
```
In mm/pagewalk.c (ffffffff811cfeb9)
Location: arch/x86/include/asm/pgtable.h:615
Inline: True
```
```
In mm/swapfile.c (ffffffff811d428e)
Location: arch/x86/include/asm/pgtable.h:615
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/gup.c (ffffffff811d4f0a)
Location: arch/x86/include/asm/pgtable.h:652
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811d8d70)
Location: arch/x86/include/asm/pgtable.h:652
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811e47c0)
Location: arch/x86/include/asm/pgtable.h:652
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e57b1)
Location: arch/x86/include/asm/pgtable.h:652
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff811eaf3d)
Location: arch/x86/include/asm/pgtable.h:652
Inline: True
```
```
In mm/pagewalk.c (ffffffff811ed008)
Location: arch/x86/include/asm/pgtable.h:652
Inline: True
```
```
In mm/swapfile.c (ffffffff811f208b)
Location: arch/x86/include/asm/pgtable.h:652
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/gup.c (ffffffff811e4f2a)
Location: arch/x86/include/asm/pgtable.h:652
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811e823b)
Location: arch/x86/include/asm/pgtable.h:652
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811f47e0)
Location: arch/x86/include/asm/pgtable.h:652
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f59f0)
Location: arch/x86/include/asm/pgtable.h:652
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff811f73f8)
Location: arch/x86/include/asm/pgtable.h:652
Inline: True
```
```
In mm/vmalloc.c (ffffffff811fc19d)
Location: arch/x86/include/asm/pgtable.h:652
Inline: True
```
```
In mm/swapfile.c (ffffffff81202a7e)
Location: arch/x86/include/asm/pgtable.h:652
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/gup.c (ffffffff811ef547)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
```
```
In mm/memory.c (ffffffff811f1a88)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811ff739)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812007ba)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff81205724)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8120daa7)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/gup.c (ffffffff81206cf0)
Location: arch/x86/include/asm/pgtable.h:799
Inline: True
```
```
In mm/memory.c (ffffffff81208811)
Location: arch/x86/include/asm/pgtable.h:799
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81217cd0)
Location: arch/x86/include/asm/pgtable.h:799
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81218f8b)
Location: arch/x86/include/asm/pgtable.h:799
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff8121f71e)
Location: arch/x86/include/asm/pgtable.h:799
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81228d3d)
Location: arch/x86/include/asm/pgtable.h:799
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/gup.c (ffffffff812274ee)
Location: arch/x86/include/asm/pgtable.h:841
Inline: True
```
```
In mm/memory.c (ffffffff8122984a)
Location: arch/x86/include/asm/pgtable.h:841
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81239b11)
Location: arch/x86/include/asm/pgtable.h:841
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
```
```
In mm/mremap.c (ffffffff8123a957)
Location: arch/x86/include/asm/pgtable.h:841
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff81240e9c)
Location: arch/x86/include/asm/pgtable.h:841
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8124a03d)
Location: arch/x86/include/asm/pgtable.h:841
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/gup.c (ffffffff8123ac91)
Location: arch/x86/include/asm/pgtable.h:866
Inline: True
```
```
In mm/memory.c (ffffffff8123cd5a)
Location: arch/x86/include/asm/pgtable.h:866
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8124d434)
Location: arch/x86/include/asm/pgtable.h:866
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124eb5a)
Location: arch/x86/include/asm/pgtable.h:866
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff81254bac)
Location: arch/x86/include/asm/pgtable.h:866
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8125e67d)
Location: arch/x86/include/asm/pgtable.h:866
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/gup.c (ffffffff8124c70e)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
```
```
In mm/memory.c (ffffffff8124e9c8)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8125fc2e)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81260eaf)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff81266f5c)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8127b8ca)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/gup.c (ffffffff8125ac3e)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
```
```
In mm/memory.c (ffffffff8125cf65)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8126e4ee)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126f648)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff8127585c)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8128b3aa)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/gup.c (ffffffff81288fa1)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
```
```
In mm/memory.c (ffffffff8128d593)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8129eee5)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff8129fb62)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
```
```
In mm/vmalloc.c (ffffffff812a7272)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff812bdd86)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130ca76)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
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
In mm/gup.c (ffffffff81292c81)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
```
```
In mm/memory.c (ffffffff8129fa44)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812aa2a9)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812aafea)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/vmalloc.c (ffffffff812b24f2)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff812c98aa)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff813189b6)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
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
In mm/gup.c (ffffffff812986b6)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
```
```
In mm/memory.c (ffffffff812a52bd)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812af6e9)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812b042c)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/vmalloc.c (ffffffff812b8c15)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812d0518)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131eba6)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
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
In mm/gup.c (ffffffff812d90f8)
Location: arch/x86/include/asm/pgtable.h:857
Inline: True
```
```
In mm/memory.c (ffffffff812e681a)
Location: arch/x86/include/asm/pgtable.h:857
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812f0f1b)
Location: arch/x86/include/asm/pgtable.h:857
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812f1c6e)
Location: arch/x86/include/asm/pgtable.h:857
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/vmalloc.c (ffffffff812fb1ca)
Location: arch/x86/include/asm/pgtable.h:857
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81315a63)
Location: arch/x86/include/asm/pgtable.h:857
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bf86)
Location: arch/x86/include/asm/pgtable.h:857
Inline: True
Inline callers:
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
In mm/gup.c (ffffffff81339098)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
```
```
In mm/memory.c (ffffffff8133d807)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81354b21)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81355832)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/vmalloc.c (ffffffff813626cd)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff81381060)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mapping_dirty_helpers.c (ffffffff813ea1b1)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
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
In mm/gup.c (ffffffff813b09ce)
Location: arch/x86/include/asm/pgtable.h:873
Inline: True
Inline callers:
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813b6827)
Location: arch/x86/include/asm/pgtable.h:873
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff813cf083)
Location: arch/x86/include/asm/pgtable.h:873
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813cffa2)
Location: arch/x86/include/asm/pgtable.h:873
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/vmalloc.c (ffffffff813de063)
Location: arch/x86/include/asm/pgtable.h:873
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff813ff84c)
Location: arch/x86/include/asm/pgtable.h:873
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mapping_dirty_helpers.c (ffffffff81472274)
Location: arch/x86/include/asm/pgtable.h:873
Inline: True
Inline callers:
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
In mm/gup.c (ffffffff813e4e08)
Location: arch/x86/include/asm/pgtable.h:874
Inline: True
Inline callers:
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813eb245)
Location: arch/x86/include/asm/pgtable.h:874
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81403757)
Location: arch/x86/include/asm/pgtable.h:874
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff81404a65)
Location: arch/x86/include/asm/pgtable.h:874
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/vmalloc.c (ffffffff814128bd)
Location: arch/x86/include/asm/pgtable.h:874
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff81432544)
Location: arch/x86/include/asm/pgtable.h:874
Inline: True
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
In mm/gup.c (ffffffff8140f61c)
Location: arch/x86/include/asm/pgtable.h:1096
Inline: True
```
```
In mm/memory.c (ffffffff8141526e)
Location: arch/x86/include/asm/pgtable.h:1096
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8142fcd7)
Location: arch/x86/include/asm/pgtable.h:1096
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff81431035)
Location: arch/x86/include/asm/pgtable.h:1096
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/vmalloc.c (ffffffff8143f32d)
Location: arch/x86/include/asm/pgtable.h:1096
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff8146b964)
Location: arch/x86/include/asm/pgtable.h:1096
Inline: True
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
In arch/powerpc/mm/hugetlbpage.c (c0000000000a5c70)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:939
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
```
```
In mm/gup.c (c0000000003b8878)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:939
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (c0000000003baf78)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:939
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (c0000000003d1f78)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:939
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d3c68)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:939
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (c0000000003dbaa4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:939
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_page_range
```
```
In mm/swapfile.c (c0000000003fcf1c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:939
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/gup.c (ffffffe000204a12)
Location: arch/riscv/include/asm/pgtable-64.h:41
Inline: True
```
```
In mm/memory.c (ffffffe00020660e)
Location: arch/riscv/include/asm/pgtable-64.h:41
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffe000211124)
Location: arch/riscv/include/asm/pgtable-64.h:41
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffe000211b18)
Location: arch/riscv/include/asm/pgtable-64.h:41
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffe0002151f6)
Location: arch/riscv/include/asm/pgtable-64.h:41
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffe0002268fc)
Location: arch/riscv/include/asm/pgtable-64.h:41
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/gup.c (ffffffff8125328e)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
```
```
In mm/memory.c (ffffffff812555b5)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81266b3e)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81267c98)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff8126deac)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8128398a)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/gup.c (ffffffff81245f80)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
```
```
In mm/memory.c (ffffffff81247cee)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff812589f4)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81259fe6)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff8125fece)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81275833)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/gup.c (ffffffff8125102e)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
```
```
In mm/memory.c (ffffffff81253355)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812648de)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81265a38)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff8126bc4c)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8128179a)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/gup.c (ffffffff812609a7)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
```
```
In mm/memory.c (ffffffff81262d65)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812742a7)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812753da)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff8127b65c)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff812914d5)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
</ul>

## Differences
