# Function: <code>pud_alloc</code>

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
In arch/x86/kernel/tboot.c (ffffffff81f6a326)
Location: include/linux/mm.h:1509
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In mm/memory.c (ffffffff811bec9c)
Location: include/linux/mm.h:1509
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mremap.c (ffffffff811c9464)
Location: include/linux/mm.h:1509
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff811cdf3c)
Location: include/linux/mm.h:1509
Inline: True
```
```
In mm/hugetlb.c (ffffffff811de71d)
Location: include/linux/mm.h:1509
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/userfaultfd.c (ffffffff8120773a)
Location: include/linux/mm.h:1509
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff813eb0f6)
Location: include/linux/mm.h:1509
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
In arch/x86/kernel/tboot.c (ffffffff81f9259b)
Location: include/linux/mm.h:1625
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In mm/memory.c (ffffffff811dab50)
Location: include/linux/mm.h:1625
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff811e5852)
Location: include/linux/mm.h:1625
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff811eaac4)
Location: include/linux/mm.h:1625
Inline: True
```
```
In mm/hugetlb.c (ffffffff811fcb6e)
Location: include/linux/mm.h:1625
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/userfaultfd.c (ffffffff8122d00a)
Location: include/linux/mm.h:1625
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff8143146b)
Location: include/linux/mm.h:1625
Inline: True
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
In arch/x86/kernel/tboot.c (ffffffff81fcd867)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In mm/memory.c (ffffffff811ea712)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff811f5a88)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff811fbd45)
Location: include/linux/mm.h:1599
Inline: True
```
```
In mm/hugetlb.c (ffffffff8120d64e)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/userfaultfd.c (ffffffff8123f52a)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff8144d6db)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff820adea8)
Location: include/linux/mm.h:1650
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107de10)
Location: include/linux/mm.h:1650
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/memory.c (ffffffff811f56dd)
Location: include/linux/mm.h:1650
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff81200864)
Location: include/linux/mm.h:1650
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff81206a45)
Location: include/linux/mm.h:1650
Inline: True
```
```
In mm/hugetlb.c (ffffffff8121949e)
Location: include/linux/mm.h:1650
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/userfaultfd.c (ffffffff8124ae81)
Location: include/linux/mm.h:1650
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff818ed38c)
Location: include/linux/mm.h:1650
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8107de10-ffffffff8107de50: pud_alloc.constprop.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff826b43a6)
Location: include/linux/mm.h:1752
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8108462f)
Location: include/linux/mm.h:1752
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/memory.c (ffffffff8120e5e0)
Location: include/linux/mm.h:1752
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff81219032)
Location: include/linux/mm.h:1752
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff8121fa85)
Location: include/linux/mm.h:1752
Inline: True
```
```
In mm/hugetlb.c (ffffffff812344a6)
Location: include/linux/mm.h:1752
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/migrate.c (ffffffff81249f3d)
Location: include/linux/mm.h:1752
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8126b0f3)
Location: include/linux/mm.h:1752
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81973445)
Location: include/linux/mm.h:1752
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8108462f-ffffffff8108467a: pud_alloc.constprop.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff826ddb7f)
Location: include/linux/mm.h:1839
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81087922)
Location: include/linux/mm.h:1839
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/memory.c (ffffffff8122fd83)
Location: include/linux/mm.h:1839
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff8123a9f6)
Location: include/linux/mm.h:1839
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff81240b17)
Location: include/linux/mm.h:1839
Inline: True
```
```
In mm/hugetlb.c (ffffffff8125744f)
Location: include/linux/mm.h:1839
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/migrate.c (ffffffff8126eebb)
Location: include/linux/mm.h:1839
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8128fae5)
Location: include/linux/mm.h:1839
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff819cf953)
Location: include/linux/mm.h:1839
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81087922-ffffffff8108796d: pud_alloc.constprop.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff82893fc7)
Location: include/linux/mm.h:1917
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8108f078)
Location: include/linux/mm.h:1917
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/memory.c (ffffffff81241a73)
Location: include/linux/mm.h:1917
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff8124ebff)
Location: include/linux/mm.h:1917
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff812553fe)
Location: include/linux/mm.h:1917
Inline: True
```
```
In mm/hugetlb.c (ffffffff8126bacf)
Location: include/linux/mm.h:1917
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/migrate.c (ffffffff8128356b)
Location: include/linux/mm.h:1917
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812a4a05)
Location: include/linux/mm.h:1917
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81a08dc2)
Location: include/linux/mm.h:1917
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8108f078-ffffffff8108f0c3: pud_alloc.constprop.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff828ab777)
Location: include/linux/mm.h:1912
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81092eff)
Location: include/linux/mm.h:1912
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/memory.c (ffffffff812543df)
Location: include/linux/mm.h:1912
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff81260f57)
Location: include/linux/mm.h:1912
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff8126774e)
Location: include/linux/mm.h:1912
Inline: True
```
```
In mm/hugetlb.c (ffffffff81286dc4)
Location: include/linux/mm.h:1912
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/userfaultfd.c (ffffffff812bffc9)
Location: include/linux/mm.h:1912
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81a78670)
Location: include/linux/mm.h:1912
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81092eff-ffffffff81092f4a: pud_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff828ae785)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81093f6f)
Location: include/linux/mm.h:1884
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/memory.c (ffffffff8126293f)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff8126f6f0)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff812760ae)
Location: include/linux/mm.h:1884
Inline: True
```
```
In mm/hugetlb.c (ffffffff812969c4)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/migrate.c (ffffffff812aefed)
Location: include/linux/mm.h:1884
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812d1f19)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81aafa20)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81093f6f-ffffffff81093fba: pud_alloc.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/tboot.c (ffffffff810479e5)
Location: include/linux/mm.h:2111
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82ceab69)
Location: include/linux/mm.h:2111
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff82cec3bb)
Location: include/linux/mm.h:2111
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog
```
```
In mm/memory.c (ffffffff81294724)
Location: include/linux/mm.h:2111
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff8129fc88)
Location: include/linux/mm.h:2111
Inline: True
```
```
In mm/hugetlb.c (ffffffff812c9f8b)
Location: include/linux/mm.h:2111
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/migrate.c (ffffffff812e5080)
Location: include/linux/mm.h:2111
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81307d08)
Location: include/linux/mm.h:2111
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In arch/x86/kernel/tboot.c (ffffffff81bd4c6b)
Location: include/linux/mm.h:2156
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff82fd3348)
Location: include/linux/mm.h:2156
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82fd83f0)
Location: include/linux/mm.h:2156
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/memory.c (ffffffff8129efa4)
Location: include/linux/mm.h:2156
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_p4d_range
```
```
In mm/mremap.c (ffffffff812ab1a4)
Location: include/linux/mm.h:2156
Inline: True
```
```
In mm/hugetlb.c (ffffffff812d5bcb)
Location: include/linux/mm.h:2156
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/migrate.c (ffffffff812f0443)
Location: include/linux/mm.h:2156
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81313a38)
Location: include/linux/mm.h:2156
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In arch/x86/kernel/tboot.c (ffffffff81bc70c2)
Location: include/linux/mm.h:2164
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff831de1ce)
Location: include/linux/mm.h:2164
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff831e2dec)
Location: include/linux/mm.h:2164
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/memory.c (ffffffff812a3ff9)
Location: include/linux/mm.h:2164
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_p4d_range
```
```
In mm/mremap.c (ffffffff812b04ce)
Location: include/linux/mm.h:2164
Inline: True
```
```
In mm/hugetlb.c (ffffffff812dc85f)
Location: include/linux/mm.h:2164
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/migrate.c (ffffffff812f675b)
Location: include/linux/mm.h:2164
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81319be6)
Location: include/linux/mm.h:2164
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In arch/x86/kernel/tboot.c (ffffffff81c9a6c2)
Location: include/linux/mm.h:2193
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff832c141d)
Location: include/linux/mm.h:2193
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff832c678f)
Location: include/linux/mm.h:2193
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/memory.c (ffffffff812e5322)
Location: include/linux/mm.h:2193
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
```
```
In mm/mremap.c (ffffffff812f1d2b)
Location: include/linux/mm.h:2193
Inline: True
```
```
In mm/hugetlb.c (ffffffff81323a2d)
Location: include/linux/mm.h:2193
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/migrate.c (ffffffff81340da5)
Location: include/linux/mm.h:2193
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81366993)
Location: include/linux/mm.h:2193
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In arch/x86/kernel/tboot.c (ffffffff81e49b2c)
Location: include/linux/mm.h:2271
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff83473a74)
Location: include/linux/mm.h:2271
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff834794ff)
Location: include/linux/mm.h:2271
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/memory.c (ffffffff81347619)
Location: include/linux/mm.h:2271
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
```
```
In mm/mprotect.c (ffffffff813549cf)
Location: include/linux/mm.h:2271
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81355a6b)
Location: include/linux/mm.h:2271
Inline: True
```
```
In mm/hugetlb.c (ffffffff8139161c)
Location: include/linux/mm.h:2271
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/migrate_device.c (ffffffff813b7c85)
Location: include/linux/mm.h:2271
Inline: True
```
```
In mm/userfaultfd.c (ffffffff813e3d23)
Location: include/linux/mm.h:2271
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In arch/x86/kernel/tboot.c (ffffffff81067e8d)
Location: include/linux/mm.h:2435
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff83e9b28d)
Location: include/linux/mm.h:2435
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83ea3677)
Location: include/linux/mm.h:2435
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/memory.c (ffffffff813bfa1f)
Location: include/linux/mm.h:2435
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
```
```
In mm/mprotect.c (ffffffff813cef2d)
Location: include/linux/mm.h:2435
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813d006b)
Location: include/linux/mm.h:2435
Inline: True
```
```
In mm/hugetlb.c (ffffffff8140e61c)
Location: include/linux/mm.h:2435
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/migrate_device.c (ffffffff81439940)
Location: include/linux/mm.h:2435
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8146b743)
Location: include/linux/mm.h:2435
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In arch/x86/kernel/tboot.c (ffffffff8106973d)
Location: include/linux/mm.h:2755
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff836bed2d)
Location: include/linux/mm.h:2755
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff836c7907)
Location: include/linux/mm.h:2755
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/memory.c (ffffffff813f46e8)
Location: include/linux/mm.h:2755
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
```
```
In mm/mprotect.c (ffffffff8140362f)
Location: include/linux/mm.h:2755
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff81404dce)
Location: include/linux/mm.h:2755
Inline: True
```
```
In mm/hugetlb.c (ffffffff814419df)
Location: include/linux/mm.h:2755
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/migrate_device.c (ffffffff8146e6ec)
Location: include/linux/mm.h:2755
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814a0546)
Location: include/linux/mm.h:2755
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In arch/x86/kernel/tboot.c (ffffffff81070c7d)
Location: include/linux/mm.h:2796
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff838ef7cd)
Location: include/linux/mm.h:2796
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff838f8507)
Location: include/linux/mm.h:2796
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/memory.c (ffffffff81420cd9)
Location: include/linux/mm.h:2796
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
```
```
In mm/mprotect.c (ffffffff8142fbaf)
Location: include/linux/mm.h:2796
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff814313ce)
Location: include/linux/mm.h:2796
Inline: True
```
```
In mm/hugetlb.c (ffffffff8147bc4f)
Location: include/linux/mm.h:2796
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/migrate_device.c (ffffffff8149d160)
Location: include/linux/mm.h:2796
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/userfaultfd.c (ffffffff814cfbe6)
Location: include/linux/mm.h:2796
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/linux/mm.h:1884
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/mm.h:1884
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/mm.h:1884
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/mm.h:1884
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:1884
Inline: True
```
```
In lib/ioremap.c (0)
Location: include/linux/mm.h:1884
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8289c7a4)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81092f2f)
Location: include/linux/mm.h:1884
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/memory.c (ffffffff8125af8f)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff81267d40)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff8126e6fe)
Location: include/linux/mm.h:1884
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128efa4)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/migrate.c (ffffffff812a75cd)
Location: include/linux/mm.h:1884
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812ca4f9)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81a4e870)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81092f2f-ffffffff81092f7a: pud_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8289497e)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810819af)
Location: include/linux/mm.h:1884
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/memory.c (ffffffff8124d2cf)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff8125a059)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff812607e3)
Location: include/linux/mm.h:1884
Inline: True
```
```
In mm/hugetlb.c (ffffffff81280cc1)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/migrate.c (ffffffff8129901a)
Location: include/linux/mm.h:1884
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812bb534)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81a0b960)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff810819af-ffffffff81081a09: pud_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff828af767)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81092edf)
Location: include/linux/mm.h:1884
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/memory.c (ffffffff81258d2f)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff81265ae0)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff8126c49e)
Location: include/linux/mm.h:1884
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128cdb4)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/migrate.c (ffffffff812a53dd)
Location: include/linux/mm.h:1884
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812c8309)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81abac60)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81092edf-ffffffff81092f2a: pud_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff828af795)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8109542f)
Location: include/linux/mm.h:1884
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/memory.c (ffffffff8126872f)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff81275482)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff8127bfde)
Location: include/linux/mm.h:1884
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129cb84)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/migrate.c (ffffffff812b4b0d)
Location: include/linux/mm.h:1884
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812d9019)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81ac70b0)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8109542f-ffffffff8109547a: pud_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
