# Function: <code>pmd_large</code>

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
In arch/x86/xen/mmu.c (ffffffff81f62a8b)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/mm/init_64.c (ffffffff8181bcc2)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:vmemmap_populate
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c690)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (ffffffff810713a9)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/gup.c (ffffffff810719cf)
Location: arch/x86/include/asm/pgtable.h:162
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
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
In arch/x86/xen/mmu.c (ffffffff81f8ab51)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/mm/init_64.c (ffffffff81896ca1)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c4ba)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (ffffffff81071298)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/gup.c (ffffffff81071c54)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81074110)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/power/hibernate_64.c (ffffffff81760884)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/xen/mmu.c (ffffffff81fc5f3f)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/mm/init_64.c (ffffffff818cb38c)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff8107015a)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (ffffffff81074e18)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/gup.c (ffffffff810757c4)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81077c88)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d9e4)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/xen/mmu_pv.c (ffffffff820a6e14)
Location: arch/x86/include/asm/pgtable.h:206
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/mm/init_64.c (ffffffff819029b0)
Location: arch/x86/include/asm/pgtable.h:206
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:206
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff8106f888)
Location: arch/x86/include/asm/pgtable.h:206
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff810743c8)
Location: arch/x86/include/asm/pgtable.h:206
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810765a6)
Location: arch/x86/include/asm/pgtable.h:206
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/power/hibernate_64.c (ffffffff817abbc3)
Location: arch/x86/include/asm/pgtable.h:206
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_large(pmd_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025690)
Location: arch/x86/include/asm/pgtable.h:221
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff81071533)
Location: arch/x86/include/asm/pgtable.h:221
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810726b6)
Location: arch/x86/include/asm/pgtable.h:221
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81074cae)
Location: arch/x86/include/asm/pgtable.h:221
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81079e5f)
Location: arch/x86/include/asm/pgtable.h:221
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107c875)
Location: arch/x86/include/asm/pgtable.h:221
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff826c581b)
Location: arch/x86/include/asm/pgtable.h:221
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/power/hibernate_64.c (ffffffff81823181)
Location: arch/x86/include/asm/pgtable.h:221
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff81025690-ffffffff810256ce: pmd_large (STB_LOCAL)
ffffffff81070540-ffffffff8107057e: pmd_large (STB_LOCAL)
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
In arch/x86/xen/mmu_pv.c (ffffffff826d683c)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff819e921c)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810752c9)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81077754)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8107cacf)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107f574)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff826ef917)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f0363)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d479)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/xen/mmu_pv.c (ffffffff8288c785)
Location: arch/x86/include/asm/pgtable.h:233
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff81a24b62)
Location: arch/x86/include/asm/pgtable.h:233
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8107b0c9)
Location: arch/x86/include/asm/pgtable.h:233
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8107df04)
Location: arch/x86/include/asm/pgtable.h:233
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff810834ff)
Location: arch/x86/include/asm/pgtable.h:233
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81086166)
Location: arch/x86/include/asm/pgtable.h:233
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff8108a338)
Location: arch/x86/include/asm/pgtable.h:233
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a706b)
Location: arch/x86/include/asm/pgtable.h:233
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In arch/x86/power/hibernate.c (ffffffff8188f44e)
Location: arch/x86/include/asm/pgtable.h:233
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff828a3c25)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff81a94f35)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8107ea36)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81081809)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8108716f)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089b9f)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108e081)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf725)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In arch/x86/power/hibernate.c (ffffffff818d944e)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff828a6cbf)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff81acc815)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8107fac6)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810828c9)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81087e5f)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108a80f)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108ed2a)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5ba9)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In arch/x86/power/hibernate.c (ffffffff8190b44e)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_large(pmd_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102a502)
Location: arch/x86/include/asm/pgtable.h:254
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd
```
```
In arch/x86/mm/init_64.c (ffffffff8108577e)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff81087f29)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a2ff)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c88f)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81094a40)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff8109527f)
Location: arch/x86/include/asm/pgtable.h:254
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/pagewalk.c (ffffffff812a288f)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
```
```
In mm/ptdump.c (ffffffff8130cc6b)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pmd_entry
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc47e)
Location: arch/x86/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff8102a502-ffffffff8102a52d: pmd_large (STB_LOCAL)
ffffffff81085f2a-ffffffff81085f55: pmd_large (STB_LOCAL)
ffffffff81094a40-ffffffff81094a6b: pmd_large (STB_LOCAL)
ffffffff8109527f-ffffffff810952aa: pmd_large (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_large(pmd_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81bd2c5e)
Location: arch/x86/include/asm/pgtable.h:253
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd
```
```
In arch/x86/mm/init_64.c (ffffffff8108682e)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a57f)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c291)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81093e00)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81bda2ee)
Location: arch/x86/include/asm/pgtable.h:253
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In kernel/events/core.c (ffffffff8123cb83)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/pagewalk.c (ffffffff812ae1cf)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
```
```
In mm/ptdump.c (ffffffff81318bab)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pmd_entry
```
```
In arch/x86/power/hibernate.c (ffffffff81bd145e)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81bd2c5e-ffffffff81bd2c89: pmd_large (STB_LOCAL)
ffffffff81bd889e-ffffffff81bd88c9: pmd_large (STB_LOCAL)
ffffffff81093e00-ffffffff81093e2b: pmd_large (STB_LOCAL)
ffffffff81bda2ee-ffffffff81bda319: pmd_large (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_large(pmd_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81bc4e24)
Location: arch/x86/include/asm/pgtable.h:253
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/mm/init_64.c (ffffffff81087581)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff8108b1d5)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d531)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810947c0)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81bcc412)
Location: arch/x86/include/asm/pgtable.h:253
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In kernel/events/core.c (ffffffff81243e97)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/memory.c (ffffffff812a31a9)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pmd_range
```
```
In mm/pagewalk.c (ffffffff812b35be)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
```
```
In mm/vmalloc.c (ffffffff812b8ca1)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/ptdump.c (ffffffff8131ed9b)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pmd_entry
```
```
In arch/x86/power/hibernate.c (ffffffff81bc3468)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81bc4e24-ffffffff81bc4e53: pmd_large (STB_LOCAL)
ffffffff81bca745-ffffffff81bca774: pmd_large (STB_LOCAL)
ffffffff810947c0-ffffffff810947eb: pmd_large (STB_LOCAL)
ffffffff81bcc412-ffffffff81bcc441: pmd_large (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_large(pmd_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81c97600)
Location: arch/x86/include/asm/pgtable.h:224
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/mm/init_64.c (ffffffff81c9fbeb)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a775)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109cdaf)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810a46e0)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81ca2528)
Location: arch/x86/include/asm/pgtable.h:224
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In kernel/events/core.c (ffffffff8127e808)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/memory.c (ffffffff812e4483)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pmd_range
```
```
In mm/pagewalk.c (ffffffff812f516a)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
```
```
In mm/vmalloc.c (ffffffff812fb255)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/sparse-vmemmap.c (ffffffff8132c06f)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_range
```
```
In mm/ptdump.c (ffffffff8136c17b)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pmd_entry
```
```
In arch/x86/power/hibernate.c (ffffffff81c94478)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81c97600-ffffffff81c9762f: pmd_large (STB_LOCAL)
ffffffff81c9fbeb-ffffffff81c9fc1a: pmd_large (STB_LOCAL)
ffffffff810a46e0-ffffffff810a470b: pmd_large (STB_LOCAL)
ffffffff81ca2528-ffffffff81ca2557: pmd_large (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_large(pmd_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81e46aa2)
Location: arch/x86/include/asm/pgtable.h:227
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/mm/init_64.c (ffffffff810a7e40)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810ada15)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b05e5)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810b8f50)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81e51d5f)
Location: arch/x86/include/asm/pgtable.h:227
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In kernel/events/core.c (ffffffff812d3476)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/memory.c (ffffffff81345e7f)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pmd_range
```
```
In mm/pagewalk.c (ffffffff81358f8d)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
```
```
In mm/vmalloc.c (ffffffff81362757)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/sparse-vmemmap.c (ffffffff8139c015)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_range
  - mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/ptdump.c (ffffffff813ea40f)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pmd_entry
```
```
In arch/x86/power/hibernate.c (ffffffff81e434a2)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81e46aa2-ffffffff81e46ad9: pmd_large (STB_LOCAL)
ffffffff810a7e40-ffffffff810a7e73: pmd_large (STB_LOCAL)
ffffffff810b8f50-ffffffff810b8f83: pmd_large (STB_LOCAL)
ffffffff81e51d5f-ffffffff81e51d96: pmd_large (STB_LOCAL)
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
In arch/x86/xen/mmu_pv.c (ffffffff83e6faa0)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/mm/init_64.c (ffffffff820c7589)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_check_pmd
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7c15)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cac9d)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810d4d05)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0c7e)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In kernel/events/core.c (ffffffff8133b6f4)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/memory.c (ffffffff813be233)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pmd_range
```
```
In mm/pagewalk.c (ffffffff813d38f9)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
```
```
In mm/vmalloc.c (ffffffff813de0ee)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb_vmemmap.c (ffffffff8141411c)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/ksm.c (ffffffff81421bd8)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
```
```
In mm/ptdump.c (ffffffff81472510)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pmd_entry
```
```
In arch/x86/power/hibernate.c (ffffffff8201e548)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff8369085a)
Location: arch/x86/include/asm/pgtable.h:229
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/mm/init_64.c (ffffffff8214b619)
Location: arch/x86/include/asm/pgtable.h:229
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_check_pmd
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:229
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810cb355)
Location: arch/x86/include/asm/pgtable.h:229
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce2cd)
Location: arch/x86/include/asm/pgtable.h:229
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810d8205)
Location: arch/x86/include/asm/pgtable.h:229
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4d8e)
Location: arch/x86/include/asm/pgtable.h:229
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In kernel/events/core.c (ffffffff8136d09b)
Location: arch/x86/include/asm/pgtable.h:229
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/memory.c (ffffffff813f2e7c)
Location: arch/x86/include/asm/pgtable.h:229
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pmd_range
```
```
In mm/pagewalk.c (ffffffff814082e7)
Location: arch/x86/include/asm/pgtable.h:229
Inline: True
```
```
In mm/vmalloc.c (ffffffff81412948)
Location: arch/x86/include/asm/pgtable.h:229
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb_vmemmap.c (ffffffff8144767c)
Location: arch/x86/include/asm/pgtable.h:229
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/ptdump.c (ffffffff814a6c70)
Location: arch/x86/include/asm/pgtable.h:229
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pmd_entry
```
```
In arch/x86/power/hibernate.c (ffffffff8209e542)
Location: arch/x86/include/asm/pgtable.h:229
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff838c032a)
Location: arch/x86/include/asm/pgtable.h:265
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/mm/init_64.c (ffffffff8222e0c9)
Location: arch/x86/include/asm/pgtable.h:265
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_check_pmd
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:265
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810d38a5)
Location: arch/x86/include/asm/pgtable.h:265
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d69ad)
Location: arch/x86/include/asm/pgtable.h:265
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810e0a85)
Location: arch/x86/include/asm/pgtable.h:265
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f598e)
Location: arch/x86/include/asm/pgtable.h:265
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In kernel/events/core.c (ffffffff813962db)
Location: arch/x86/include/asm/pgtable.h:265
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/memory.c (ffffffff8141db6c)
Location: arch/x86/include/asm/pgtable.h:265
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pmd_range
```
```
In mm/pagewalk.c (ffffffff81434a07)
Location: arch/x86/include/asm/pgtable.h:265
Inline: True
```
```
In mm/vmalloc.c (ffffffff8143f3b8)
Location: arch/x86/include/asm/pgtable.h:265
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb_vmemmap.c (ffffffff81480de5)
Location: arch/x86/include/asm/pgtable.h:265
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_pmd_entry
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
```
```
In mm/ptdump.c (ffffffff814d7c70)
Location: arch/x86/include/asm/pgtable.h:265
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pmd_entry
```
```
In arch/x86/power/hibernate.c (ffffffff82176542)
Location: arch/x86/include/asm/pgtable.h:265
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff82894cc8)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff81a6b685)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8107eac6)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810818c9)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81086e5f)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810897cf)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108dcea)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0b41)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In arch/x86/power/hibernate.c (ffffffff818ab44e)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/mm/init_64.c (ffffffff81a27bdb)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8106de43)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810705a7)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (ffffffff81075aaf)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81078543)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff8107c80a)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8cc6)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In arch/x86/power/hibernate.c (ffffffff818653e9)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff828a7cbf)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff81ad7a95)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8107ea76)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81081879)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81086e0f)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108977f)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108dc9a)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c3a40)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In arch/x86/power/hibernate.c (ffffffff818fc44e)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff828a7cc5)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff81ae3f55)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff81080b66)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81083999)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81088f3f)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108ba1f)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8109007a)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6be6)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In arch/x86/power/hibernate.c (ffffffff8191d44e)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
