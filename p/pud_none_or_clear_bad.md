# Function: <code>pud_none_or_clear_bad</code>

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
In mm/memory.c (ffffffff811bcd3c)
Location: include/asm-generic/pgtable.h:371
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811c85e0)
Location: include/asm-generic/pgtable.h:371
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811c93c0)
Location: include/asm-generic/pgtable.h:371
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff811ce392)
Location: include/asm-generic/pgtable.h:371
Inline: True
```
```
In mm/pagewalk.c (ffffffff811cfeb0)
Location: include/asm-generic/pgtable.h:371
Inline: True
```
```
In mm/swapfile.c (ffffffff811d4152)
Location: include/asm-generic/pgtable.h:371
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
In mm/memory.c (ffffffff811d8d2f)
Location: include/asm-generic/pgtable.h:376
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811e475e)
Location: include/asm-generic/pgtable.h:376
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e57a4)
Location: include/asm-generic/pgtable.h:376
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff811eae30)
Location: include/asm-generic/pgtable.h:376
Inline: True
```
```
In mm/pagewalk.c (ffffffff811ecffb)
Location: include/asm-generic/pgtable.h:376
Inline: True
```
```
In mm/swapfile.c (ffffffff811f1f75)
Location: include/asm-generic/pgtable.h:376
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
In mm/memory.c (ffffffff811e81fc)
Location: include/asm-generic/pgtable.h:400
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811f477e)
Location: include/asm-generic/pgtable.h:400
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f59e3)
Location: include/asm-generic/pgtable.h:400
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff811f73eb)
Location: include/asm-generic/pgtable.h:400
Inline: True
```
```
In mm/vmalloc.c (ffffffff811fc090)
Location: include/asm-generic/pgtable.h:400
Inline: True
```
```
In mm/swapfile.c (ffffffff81202965)
Location: include/asm-generic/pgtable.h:400
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
In mm/memory.c (ffffffff811f73b8)
Location: include/asm-generic/pgtable.h:505
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811ff6d8)
Location: include/asm-generic/pgtable.h:505
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812007ad)
Location: include/asm-generic/pgtable.h:505
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff81206e52)
Location: include/asm-generic/pgtable.h:505
Inline: True
```
```
In mm/swapfile.c (ffffffff8120daa7)
Location: include/asm-generic/pgtable.h:505
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
In mm/memory.c (ffffffff8120f8f9)
Location: include/asm-generic/pgtable.h:506
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81217cd0)
Location: include/asm-generic/pgtable.h:506
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81218f7e)
Location: include/asm-generic/pgtable.h:506
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff8121ff11)
Location: include/asm-generic/pgtable.h:506
Inline: True
```
```
In mm/swapfile.c (ffffffff81228beb)
Location: include/asm-generic/pgtable.h:506
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
In mm/memory.c (ffffffff8123069f)
Location: include/asm-generic/pgtable.h:549
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81239b04)
Location: include/asm-generic/pgtable.h:549
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
```
```
In mm/mremap.c (ffffffff8123a947)
Location: include/asm-generic/pgtable.h:549
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff81241161)
Location: include/asm-generic/pgtable.h:549
Inline: True
```
```
In mm/swapfile.c (ffffffff8124a030)
Location: include/asm-generic/pgtable.h:549
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
In mm/memory.c (ffffffff81243a12)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8124d427)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124eb4a)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff81255841)
Location: include/asm-generic/pgtable.h:587
Inline: True
```
```
In mm/swapfile.c (ffffffff8125e670)
Location: include/asm-generic/pgtable.h:587
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
In mm/memory.c (ffffffff81255870)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8125fc21)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81260e9f)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff81267ba7)
Location: include/asm-generic/pgtable.h:587
Inline: True
```
```
In mm/swapfile.c (ffffffff8127b880)
Location: include/asm-generic/pgtable.h:587
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
In mm/memory.c (ffffffff81263de0)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8126e4e1)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126f638)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff812764f7)
Location: include/asm-generic/pgtable.h:587
Inline: True
```
```
In mm/swapfile.c (ffffffff8128b360)
Location: include/asm-generic/pgtable.h:587
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
In mm/memory.c (ffffffff812934dd)
Location: include/linux/pgtable.h:761
Inline: True
Inline callers:
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8129eedc)
Location: include/linux/pgtable.h:761
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff8129fb56)
Location: include/linux/pgtable.h:761
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
```
```
In mm/vmalloc.c (ffffffff812a7d0b)
Location: include/linux/pgtable.h:761
Inline: True
```
```
In mm/swapfile.c (ffffffff812bdd76)
Location: include/linux/pgtable.h:761
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
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
In mm/memory.c (ffffffff8129df1d)
Location: include/linux/pgtable.h:810
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812aa29c)
Location: include/linux/pgtable.h:810
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812aafde)
Location: include/linux/pgtable.h:810
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/vmalloc.c (ffffffff812b2ddb)
Location: include/linux/pgtable.h:810
Inline: True
```
```
In mm/swapfile.c (ffffffff812c989a)
Location: include/linux/pgtable.h:810
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
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
In mm/memory.c (ffffffff812a036b)
Location: include/linux/pgtable.h:810
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812af6e0)
Location: include/linux/pgtable.h:810
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812b041c)
Location: include/linux/pgtable.h:810
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/vmalloc.c (ffffffff812bc52c)
Location: include/linux/pgtable.h:810
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812d0508)
Location: include/linux/pgtable.h:810
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/memory.c (ffffffff812e1307)
Location: include/linux/pgtable.h:829
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812f0f12)
Location: include/linux/pgtable.h:829
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812f1c5e)
Location: include/linux/pgtable.h:829
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/vmalloc.c (ffffffff812feb31)
Location: include/linux/pgtable.h:829
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81315a53)
Location: include/linux/pgtable.h:829
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/memory.c (ffffffff81341cc6)
Location: include/linux/pgtable.h:862
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81354b18)
Location: include/linux/pgtable.h:862
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81355822)
Location: include/linux/pgtable.h:862
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/vmalloc.c (ffffffff81361311)
Location: include/linux/pgtable.h:862
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff81380fe4)
Location: include/linux/pgtable.h:862
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
In mm/memory.c (ffffffff813b9bf6)
Location: include/linux/pgtable.h:898
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff813cf07a)
Location: include/linux/pgtable.h:898
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813cff92)
Location: include/linux/pgtable.h:898
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/vmalloc.c (ffffffff813dccae)
Location: include/linux/pgtable.h:898
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff813ff826)
Location: include/linux/pgtable.h:898
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
In mm/memory.c (ffffffff813ee955)
Location: include/linux/pgtable.h:910
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8140374a)
Location: include/linux/pgtable.h:910
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff81404a55)
Location: include/linux/pgtable.h:910
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/vmalloc.c (ffffffff8141151e)
Location: include/linux/pgtable.h:910
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff81432505)
Location: include/linux/pgtable.h:910
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
In mm/memory.c (ffffffff8141a435)
Location: include/linux/pgtable.h:1041
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8142fcca)
Location: include/linux/pgtable.h:1041
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff81431025)
Location: include/linux/pgtable.h:1041
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/vmalloc.c (ffffffff8143dd0e)
Location: include/linux/pgtable.h:1041
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff8146b925)
Location: include/linux/pgtable.h:1041
Inline: True
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
In virt/kvm/arm/mmu.c (ffff8000100c8dd4)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
```
```
In mm/memory.c (ffff8000102f6bc0)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffff800010304fec)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffff800010305edc)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffff80001030c6e4)
Location: include/asm-generic/pgtable.h:587
Inline: True
```
```
In mm/swapfile.c (ffff80001032670c)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In arch/arm/mm/pgd.c (0)
Location: include/asm-generic/pgtable.h:587
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:587
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:587
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:587
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:587
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:587
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
In arch/powerpc/mm/hugetlbpage.c (c0000000000a5c68)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
```
```
In mm/memory.c (c0000000003bfc10)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (c0000000003d1f70)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d3c60)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (c0000000003dcbf0)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_page_range
```
```
In mm/swapfile.c (c0000000003fcec0)
Location: include/asm-generic/pgtable.h:587
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
In mm/memory.c (ffffffe00020750c)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffe000211120)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffe000211b12)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffe000215636)
Location: include/asm-generic/pgtable.h:587
Inline: True
```
```
In mm/swapfile.c (ffffffe0002268d2)
Location: include/asm-generic/pgtable.h:587
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
In mm/memory.c (ffffffff8125c430)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81266b31)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81267c88)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff8126eb47)
Location: include/asm-generic/pgtable.h:587
Inline: True
```
```
In mm/swapfile.c (ffffffff81283940)
Location: include/asm-generic/pgtable.h:587
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
In mm/memory.c (ffffffff8124e9b9)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff812589e7)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81259fd6)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff812604b9)
Location: include/asm-generic/pgtable.h:587
Inline: True
```
```
In mm/swapfile.c (ffffffff812757ee)
Location: include/asm-generic/pgtable.h:587
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
In mm/memory.c (ffffffff8125a1d0)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812648d1)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81265a28)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff8126c8e7)
Location: include/asm-generic/pgtable.h:587
Inline: True
```
```
In mm/swapfile.c (ffffffff81281750)
Location: include/asm-generic/pgtable.h:587
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
In mm/memory.c (ffffffff81269bd0)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8127429a)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812753ca)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff8127c427)
Location: include/asm-generic/pgtable.h:587
Inline: True
```
```
In mm/swapfile.c (ffffffff8129148b)
Location: include/asm-generic/pgtable.h:587
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
</ul>

## Differences
