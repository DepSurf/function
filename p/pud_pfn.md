# Function: <code>pud_pfn</code>

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
In arch/x86/xen/mmu.c (ffffffff81f629fd)
Location: arch/x86/include/asm/pgtable.h:155
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff81069abe)
Location: arch/x86/include/asm/pgtable.h:155
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/fault.c (ffffffff8106a6c6)
Location: arch/x86/include/asm/pgtable.h:155
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8106d3c9)
Location: arch/x86/include/asm/pgtable.h:155
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
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
In arch/x86/xen/mmu.c (ffffffff81f8a5f1)
Location: arch/x86/include/asm/pgtable.h:166
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff81069842)
Location: arch/x86/include/asm/pgtable.h:166
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/fault.c (ffffffff8106a431)
Location: arch/x86/include/asm/pgtable.h:166
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8106dc50)
Location: arch/x86/include/asm/pgtable.h:166
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
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
In arch/x86/xen/mmu.c (ffffffff81fc59eb)
Location: arch/x86/include/asm/pgtable.h:166
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff8106d422)
Location: arch/x86/include/asm/pgtable.h:166
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/fault.c (ffffffff8106dfd1)
Location: arch/x86/include/asm/pgtable.h:166
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810718dc)
Location: arch/x86/include/asm/pgtable.h:166
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
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
In arch/x86/mm/init_64.c (ffffffff8106c9d7)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/fault.c (ffffffff8106d514)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8107091e)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
```
```
In mm/gup.c (ffffffff811f1180)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
```
```
In mm/huge_memory.c (ffffffff812331ca)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_pfn(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81071841)
Location: arch/x86/include/asm/pgtable.h:198
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/fault.c (ffffffff81072500)
Location: arch/x86/include/asm/pgtable.h:198
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81076107)
Location: arch/x86/include/asm/pgtable.h:198
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5ea9)
Location: arch/x86/include/asm/pgtable.h:198
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff81205cb4)
Location: arch/x86/include/asm/pgtable.h:198
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
```
```
In mm/huge_memory.c (ffffffff81250aaa)
Location: arch/x86/include/asm/pgtable.h:198
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
```
**Symbols:**

```
ffffffff81070580-ffffffff810705cc: pud_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_pfn(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810744f5)
Location: arch/x86/include/asm/pgtable.h:206
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81078bee)
Location: arch/x86/include/asm/pgtable.h:206
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efc67)
Location: arch/x86/include/asm/pgtable.h:206
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff81227117)
Location: arch/x86/include/asm/pgtable.h:206
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
```
```
In mm/huge_memory.c (ffffffff8127502a)
Location: arch/x86/include/asm/pgtable.h:206
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
```
**Symbols:**

```
ffffffff810731a0-ffffffff810731e9: pud_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_pfn(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107a3e5)
Location: arch/x86/include/asm/pgtable.h:208
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8107f552)
Location: arch/x86/include/asm/pgtable.h:208
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6924)
Location: arch/x86/include/asm/pgtable.h:208
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff8123a37a)
Location: arch/x86/include/asm/pgtable.h:208
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/huge_memory.c (ffffffff81289fb8)
Location: arch/x86/include/asm/pgtable.h:208
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
```
**Symbols:**

```
ffffffff81079240-ffffffff81079289: pud_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_pfn(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107e128)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81082ff6)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828befd5)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff8124b3ec)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/huge_memory.c (ffffffff812a4bf1)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In mm/hmm.c (ffffffff812c4f38)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff8107ce50-ffffffff8107ce99: pud_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_pfn(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107f1b8)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810840c6)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c544e)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff812598dc)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/huge_memory.c (ffffffff812b60b1)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In mm/hmm.c (ffffffff812d68e8)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff8107dee0-ffffffff8107df29: pud_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_pfn(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81085b30)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d8ab)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce865f)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff8128a9dd)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
```
```
In mm/huge_memory.c (ffffffff812eb1b8)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/hmm.c (ffffffff8130ba07)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff8108639c-ffffffff810863f2: pud_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_pfn(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81086bf7)
Location: arch/x86/include/asm/pgtable.h:226
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d77b)
Location: arch/x86/include/asm/pgtable.h:226
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd607d)
Location: arch/x86/include/asm/pgtable.h:226
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff8129469d)
Location: arch/x86/include/asm/pgtable.h:226
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
```
```
In mm/huge_memory.c (ffffffff812f7e47)
Location: arch/x86/include/asm/pgtable.h:226
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/hmm.c (ffffffff813178f7)
Location: arch/x86/include/asm/pgtable.h:226
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff81bd9016-ffffffff81bd906c: pud_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_pfn(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810878a9)
Location: arch/x86/include/asm/pgtable.h:226
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e341)
Location: arch/x86/include/asm/pgtable.h:226
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0ae6)
Location: arch/x86/include/asm/pgtable.h:226
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff8129a0ed)
Location: arch/x86/include/asm/pgtable.h:226
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
```
```
In mm/vmalloc.c (ffffffff812b8e0f)
Location: arch/x86/include/asm/pgtable.h:226
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/huge_memory.c (ffffffff812fe391)
Location: arch/x86/include/asm/pgtable.h:226
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/hmm.c (ffffffff8131daec)
Location: arch/x86/include/asm/pgtable.h:226
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff81bcafcd-ffffffff81bcb01d: pud_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_pfn(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81096c12)
Location: arch/x86/include/asm/pgtable.h:197
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109ddea)
Location: arch/x86/include/asm/pgtable.h:197
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff832c41c4)
Location: arch/x86/include/asm/pgtable.h:197
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff812daa90)
Location: arch/x86/include/asm/pgtable.h:197
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
```
```
In mm/vmalloc.c (ffffffff812fb3c4)
Location: arch/x86/include/asm/pgtable.h:197
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/huge_memory.c (ffffffff81347f31)
Location: arch/x86/include/asm/pgtable.h:197
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/hmm.c (ffffffff8136ae8c)
Location: arch/x86/include/asm/pgtable.h:197
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff81ca0569-ffffffff81ca05b9: pud_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_pfn(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810a96cd)
Location: arch/x86/include/asm/pgtable.h:200
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b1736)
Location: arch/x86/include/asm/pgtable.h:200
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810b9828)
Location: arch/x86/include/asm/pgtable.h:200
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In mm/gup.c (ffffffff8133a608)
Location: arch/x86/include/asm/pgtable.h:200
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
```
```
In mm/vmalloc.c (ffffffff813628b0)
Location: arch/x86/include/asm/pgtable.h:200
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/huge_memory.c (ffffffff813bc6b7)
Location: arch/x86/include/asm/pgtable.h:200
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/hmm.c (ffffffff813e8939)
Location: arch/x86/include/asm/pgtable.h:200
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff810a8200-ffffffff810a8250: pud_pfn (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff810c2ad1)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cbe75)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810d54bb)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In mm/gup.c (ffffffff813b20e0)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
```
```
In mm/vmalloc.c (ffffffff813de24f)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/huge_memory.c (ffffffff8143ec57)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/hmm.c (ffffffff81470888)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
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
In arch/x86/mm/init_64.c (ffffffff810c61b1)
Location: arch/x86/include/asm/pgtable.h:202
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cf4b5)
Location: arch/x86/include/asm/pgtable.h:202
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810d89cd)
Location: arch/x86/include/asm/pgtable.h:202
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In mm/gup.c (ffffffff813e6e80)
Location: arch/x86/include/asm/pgtable.h:202
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
```
```
In mm/vmalloc.c (ffffffff81412aaa)
Location: arch/x86/include/asm/pgtable.h:202
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/huge_memory.c (ffffffff81474428)
Location: arch/x86/include/asm/pgtable.h:202
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/hmm.c (ffffffff814a55ec)
Location: arch/x86/include/asm/pgtable.h:202
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
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
In arch/x86/mm/init_64.c (ffffffff810ce601)
Location: arch/x86/include/asm/pgtable.h:238
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d7b95)
Location: arch/x86/include/asm/pgtable.h:238
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810e124d)
Location: arch/x86/include/asm/pgtable.h:238
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In mm/gup.c (ffffffff81411b00)
Location: arch/x86/include/asm/pgtable.h:238
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
```
```
In mm/vmalloc.c (ffffffff8143f51a)
Location: arch/x86/include/asm/pgtable.h:238
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/huge_memory.c (ffffffff814a39d7)
Location: arch/x86/include/asm/pgtable.h:238
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/hmm.c (ffffffff814d65ac)
Location: arch/x86/include/asm/pgtable.h:238
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
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
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1325
Inline: True
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_pfn(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107e1b8)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810830c6)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b03e6)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff81251f2c)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/huge_memory.c (ffffffff812ae691)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In mm/hmm.c (ffffffff812ceec8)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff8107cee0-ffffffff8107cf29: pud_pfn (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff8106d418)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81071d3b)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a859f)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff81244d31)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/huge_memory.c (ffffffff8129fc74)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In mm/hmm.c (ffffffff812bfb5e)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_pfn(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107e168)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81083076)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c32e5)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff8124fccc)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/huge_memory.c (ffffffff812ac4a1)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In mm/hmm.c (ffffffff812cccd8)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff8107ce90-ffffffff8107ced9: pud_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_pfn(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81080258)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8108543d)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c648b)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff8125f666)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/huge_memory.c (ffffffff812bc821)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In mm/hmm.c (ffffffff812dda68)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff8107ef80-ffffffff8107efc9: pud_pfn (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
