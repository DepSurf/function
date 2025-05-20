# Function: <code>__pud_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, pgd_t *pgd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811be9c0)
Location: mm/memory.c:3475
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:__get_locked_pte
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pte_alloc
  - mm/userfaultfd.c:mm_alloc_pmd
```
**Symbols:**

```
ffffffff811be9c0-ffffffff811bea9c: __pud_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, pgd_t *pgd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811da7e0)
Location: mm/memory.c:3670
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pte_alloc
  - mm/userfaultfd.c:mm_alloc_pmd
```
**Symbols:**

```
ffffffff811da7e0-ffffffff811da8d9: __pud_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, pgd_t *pgd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ea350)
Location: mm/memory.c:3725
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pte_alloc
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff811ea350-ffffffff811ea449: __pud_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, p4d_t *p4d, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f53d0)
Location: mm/memory.c:3988
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pte_alloc
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff811f53d0-ffffffff811f54ca: __pud_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, p4d_t *p4d, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120e290)
Location: mm/memory.c:4164
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pte_alloc
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8120e290-ffffffff8120e39d: __pud_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, p4d_t *p4d, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122ec90)
Location: mm/memory.c:4209
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pte_alloc
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8122ec90-ffffffff8122eda0: __pud_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, p4d_t *p4d, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81241720)
Location: mm/memory.c:3999
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pte_alloc
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81241720-ffffffff81241830: __pud_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, p4d_t *p4d, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812540a0)
Location: mm/memory.c:4048
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pte_alloc
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff812540a0-ffffffff812541aa: __pud_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, p4d_t *p4d, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81262600)
Location: mm/memory.c:4073
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pte_alloc
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81262600-ffffffff8126270a: __pud_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, p4d_t *p4d, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81292500)
Location: mm/memory.c:4454
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/vmalloc.c:vmap_p4d_range
  - mm/hugetlb.c:huge_pte_alloc
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81292500-ffffffff8129260a: __pud_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, p4d_t *p4d, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129cdb0)
Location: mm/memory.c:4677
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_p4d_range
  - mm/vmalloc.c:vmap_p4d_range
  - mm/ioremap.c:ioremap_page_range
  - mm/hugetlb.c:huge_pte_alloc
  - mm/userfaultfd.c:mm_alloc_pmd
```
**Symbols:**

```
ffffffff8129cdb0-ffffffff8129ceba: __pud_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, p4d_t *p4d, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a2490)
Location: mm/memory.c:4704
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_p4d_range
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
  - mm/hugetlb.c:huge_pte_alloc
  - mm/userfaultfd.c:mm_alloc_pmd
```
**Symbols:**

```
ffffffff812a2490-ffffffff812a2599: __pud_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, p4d_t *p4d, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e3800)
Location: mm/memory.c:4850
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
  - mm/hugetlb.c:huge_pte_alloc
  - mm/userfaultfd.c:mm_alloc_pmd
```
**Symbols:**

```
ffffffff812e3800-ffffffff812e3909: __pud_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, p4d_t *p4d, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81344ba0)
Location: mm/memory.c:5193
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
  - mm/mprotect.c:change_protection_range
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
  - mm/hugetlb.c:huge_pte_alloc
  - mm/userfaultfd.c:mm_alloc_pmd
```
**Symbols:**

```
ffffffff81344ba0-ffffffff81344cbf: __pud_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, p4d_t *p4d, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bcdc0)
Location: mm/memory.c:5273
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
  - mm/mprotect.c:change_protection_range
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
  - mm/hugetlb.c:huge_pte_alloc
  - mm/userfaultfd.c:mm_alloc_pmd
```
**Symbols:**

```
ffffffff813bcdc0-ffffffff813bcedf: __pud_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, p4d_t *p4d, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f1af0)
Location: mm/memory.c:5465
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
  - mm/mprotect.c:change_p4d_range
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
  - mm/hugetlb.c:huge_pte_alloc
  - mm/userfaultfd.c:mm_alloc_pmd
```
**Symbols:**

```
ffffffff813f1af0-ffffffff813f1c15: __pud_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, p4d_t *p4d, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141c7a0)
Location: mm/memory.c:5691
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
  - mm/mprotect.c:change_p4d_range
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
  - mm/hugetlb.c:huge_pte_alloc
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/userfaultfd.c:mm_alloc_pmd
```
**Symbols:**

```
ffffffff8141c7a0-ffffffff8141c90a: __pud_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, pgd_t *p4d, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f9810)
Location: mm/memory.c:4073
Inline: False
Direct callers:
  - arch/arm64/mm/hugetlbpage.c:huge_pte_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffff8000102f9810-ffff8000102f9984: __pud_alloc (STB_GLOBAL)
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
Location: include/linux/mm.h:1781
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:1781
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/mm.h:1781
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/mm.h:1781
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:1781
Inline: True
```
```
In lib/ioremap.c (0)
Location: include/linux/mm.h:1781
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, pgd_t *p4d, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c3760)
Location: mm/memory.c:4073
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/hash_pgtable.c:hash__map_kernel_page
  - arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page
  - arch/powerpc/mm/hugetlbpage.c:huge_pte_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/vmalloc.c:vmap_page_range_noflush
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
c0000000003c3760-c0000000003c38d8: __pud_alloc (STB_GLOBAL)
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
In mm/memory.c (0)
Location: include/linux/mm.h:1781
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/mm.h:1781
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/mm.h:1781
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/mm.h:1781
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:1781
Inline: True
```
```
In lib/ioremap.c (0)
Location: include/linux/mm.h:1781
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, p4d_t *p4d, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125ac50)
Location: mm/memory.c:4073
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pte_alloc
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8125ac50-ffffffff8125ad5a: __pud_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, p4d_t *p4d, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124d020)
Location: mm/memory.c:4073
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pte_alloc
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8124d020-ffffffff8124d0ea: __pud_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, p4d_t *p4d, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812589f0)
Location: mm/memory.c:4073
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pte_alloc
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff812589f0-ffffffff81258afa: __pud_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __pud_alloc(struct mm_struct *mm, p4d_t *p4d, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812683f0)
Location: mm/memory.c:4073
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pte_alloc
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff812683f0-ffffffff812684f8: __pud_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>p4d_t *p4d</code>
</li>
<li>
<b>Param removed. </b>
<code>pgd_t *pgd</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>p4d_t *p4d</code> ➡️ <code>pgd_t *p4d</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>p4d_t *p4d</code> ➡️ <code>pgd_t *p4d</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
