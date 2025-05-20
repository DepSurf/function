# Function: <code>pgd_bad</code>

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
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:654
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:654
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:654
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable.h:654
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:654
Inline: True
```
```
In mm/pagewalk.c (0)
Location: arch/x86/include/asm/pgtable.h:654
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:654
Inline: True
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
In mm/gup.c (ffffffff811d4e99)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811d8c99)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811e46e8)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e575f)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff811eae84)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
```
```
In mm/pagewalk.c (ffffffff811ecf7c)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
```
```
In mm/swapfile.c (ffffffff811f1fd7)
Location: arch/x86/include/asm/pgtable.h:691
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
In mm/gup.c (ffffffff811e4eb9)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811e8169)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811f4708)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f599e)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff811f736c)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
```
```
In mm/vmalloc.c (ffffffff811fc0e4)
Location: arch/x86/include/asm/pgtable.h:691
Inline: True
```
```
In mm/swapfile.c (ffffffff812029c7)
Location: arch/x86/include/asm/pgtable.h:691
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
In mm/gup.c (0)
Location: include/asm-generic/pgtable-nop4d.h:21
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:21
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable-nop4d.h:21
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:21
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable-nop4d.h:21
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable-nop4d.h:21
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable-nop4d.h:21
Inline: True
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
In mm/gup.c (0)
Location: include/asm-generic/pgtable-nop4d.h:22
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:22
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable-nop4d.h:22
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:22
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable-nop4d.h:22
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable-nop4d.h:22
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable-nop4d.h:22
Inline: True
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
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
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
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
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
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
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
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
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
In mm/gup.c (ffffffff8128910f)
Location: arch/x86/include/asm/pgtable.h:964
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8128d4a1)
Location: arch/x86/include/asm/pgtable.h:964
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8129f0b0)
Location: arch/x86/include/asm/pgtable.h:964
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8129fa6e)
Location: arch/x86/include/asm/pgtable.h:964
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
```
```
In mm/pagewalk.c (ffffffff812a2e1c)
Location: arch/x86/include/asm/pgtable.h:964
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff812a8304)
Location: arch/x86/include/asm/pgtable.h:964
Inline: True
Inline callers:
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:unmap_kernel_range_noflush
```
```
In mm/swapfile.c (ffffffff812bdfee)
Location: arch/x86/include/asm/pgtable.h:964
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/gup.c (ffffffff81292def)
Location: arch/x86/include/asm/pgtable.h:963
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8129f984)
Location: arch/x86/include/asm/pgtable.h:963
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff812aa470)
Location: arch/x86/include/asm/pgtable.h:963
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812aaefe)
Location: arch/x86/include/asm/pgtable.h:963
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff812ae73c)
Location: arch/x86/include/asm/pgtable.h:963
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff812b33ce)
Location: arch/x86/include/asm/pgtable.h:963
Inline: True
Inline callers:
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:unmap_kernel_range_noflush
```
```
In mm/swapfile.c (ffffffff812c9b0e)
Location: arch/x86/include/asm/pgtable.h:963
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/gup.c (ffffffff81298826)
Location: arch/x86/include/asm/pgtable.h:963
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff812a51fc)
Location: arch/x86/include/asm/pgtable.h:963
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff812af8b0)
Location: arch/x86/include/asm/pgtable.h:963
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812b0372)
Location: arch/x86/include/asm/pgtable.h:963
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff812b3afc)
Location: arch/x86/include/asm/pgtable.h:963
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff812b8b45)
Location: arch/x86/include/asm/pgtable.h:963
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812d037c)
Location: arch/x86/include/asm/pgtable.h:963
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pgd_bad(pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d9287)
Location: arch/x86/include/asm/pgtable.h:934
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff812e4a88)
Location: arch/x86/include/asm/pgtable.h:934
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
Direct callers:
  - mm/memory.c:follow_invalidate_pte
```
```
In mm/mprotect.c (ffffffff812f10f8)
Location: arch/x86/include/asm/pgtable.h:934
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812f1bb4)
Location: arch/x86/include/asm/pgtable.h:934
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff812f569b)
Location: arch/x86/include/asm/pgtable.h:934
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff812fb0f7)
Location: arch/x86/include/asm/pgtable.h:934
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813158c7)
Location: arch/x86/include/asm/pgtable.h:934
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff812dce90-ffffffff812dced1: pgd_bad (STB_LOCAL)
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
In mm/gup.c (ffffffff81339260)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8133d747)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81354915)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81355779)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff81359568)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff813625fc)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81380e75)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/gup.c (ffffffff813b0b5a)
Location: arch/x86/include/asm/pgtable.h:950
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff813b6767)
Location: arch/x86/include/asm/pgtable.h:950
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff813cee69)
Location: arch/x86/include/asm/pgtable.h:950
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813cfee9)
Location: arch/x86/include/asm/pgtable.h:950
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff813d3e48)
Location: arch/x86/include/asm/pgtable.h:950
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff813ddf92)
Location: arch/x86/include/asm/pgtable.h:950
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:__vunmap_range_noflush
  - mm/vmalloc.c:__vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813ff6c0)
Location: arch/x86/include/asm/pgtable.h:950
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/gup.c (ffffffff813e4f8d)
Location: arch/x86/include/asm/pgtable.h:951
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff813eb188)
Location: arch/x86/include/asm/pgtable.h:951
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81403a92)
Location: arch/x86/include/asm/pgtable.h:951
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff814049ac)
Location: arch/x86/include/asm/pgtable.h:951
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff81408818)
Location: arch/x86/include/asm/pgtable.h:951
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff814127f2)
Location: arch/x86/include/asm/pgtable.h:951
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:__vunmap_range_noflush
  - mm/vmalloc.c:__vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81432735)
Location: arch/x86/include/asm/pgtable.h:951
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/gup.c (ffffffff8140f7c0)
Location: arch/x86/include/asm/pgtable.h:1173
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff814151ae)
Location: arch/x86/include/asm/pgtable.h:1173
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81430012)
Location: arch/x86/include/asm/pgtable.h:1173
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81430f7c)
Location: arch/x86/include/asm/pgtable.h:1173
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff81434f38)
Location: arch/x86/include/asm/pgtable.h:1173
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff8143f262)
Location: arch/x86/include/asm/pgtable.h:1173
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:__vunmap_range_noflush
  - mm/vmalloc.c:__vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8146bb55)
Location: arch/x86/include/asm/pgtable.h:1173
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mm/fault.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:28
Inline: True
```
```
In arch/arm/mm/pgd.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:28
Inline: True
```
```
In mm/gup.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:28
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:28
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:28
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:28
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:28
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:28
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:28
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
In arch/powerpc/mm/hugetlbpage.c (c0000000000a5bc0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:979
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
```
```
In mm/gup.c (c0000000003b87d4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:979
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (c0000000003baef0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:979
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (c0000000003d1ea0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:979
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d3bec)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:979
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (c0000000003d665c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:979
Inline: True
```
```
In mm/vmalloc.c (c0000000003dcb08)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:979
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_page_range
```
```
In mm/swapfile.c (c0000000003fce3c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:979
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
In mm/gup.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
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
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
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
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
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
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
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
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
