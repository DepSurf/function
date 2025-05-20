# Function: <code>pud_large</code>

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
In arch/x86/xen/mmu.c (ffffffff81f62a11)
Location: arch/x86/include/asm/pgtable.h:609
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/mm/init_64.c (ffffffff8181bf03)
Location: arch/x86/include/asm/pgtable.h:609
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/fault.c (ffffffff8106a29f)
Location: arch/x86/include/asm/pgtable.h:609
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c8fe)
Location: arch/x86/include/asm/pgtable.h:609
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pgd_range
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81071359)
Location: arch/x86/include/asm/pgtable.h:609
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/gup.c (ffffffff81071900)
Location: arch/x86/include/asm/pgtable.h:609
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
In arch/x86/xen/mmu.c (ffffffff81f8aaf4)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff81069707)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff81069eed)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8106ec54)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (ffffffff81071249)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/gup.c (ffffffff81071c08)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810740af)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/power/hibernate_64.c (ffffffff81760830)
Location: arch/x86/include/asm/pgtable.h:646
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
In arch/x86/xen/mmu.c (ffffffff81fc5ee2)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff8106d2e7)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8106da8d)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810728c4)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (ffffffff81074dc9)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/gup.c (ffffffff81075778)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81077c27)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d990)
Location: arch/x86/include/asm/pgtable.h:646
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
In arch/x86/xen/mmu_pv.c (ffffffff820a6d9c)
Location: arch/x86/include/asm/pgtable.h:785
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff8106c92b)
Location: arch/x86/include/asm/pgtable.h:785
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8106d7bd)
Location: arch/x86/include/asm/pgtable.h:785
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81071e81)
Location: arch/x86/include/asm/pgtable.h:785
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81074379)
Location: arch/x86/include/asm/pgtable.h:785
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107650d)
Location: arch/x86/include/asm/pgtable.h:785
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/power/hibernate_64.c (ffffffff817abb30)
Location: arch/x86/include/asm/pgtable.h:785
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
int pud_large(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025672)
Location: arch/x86/include/asm/pgtable.h:793
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff810714cc)
Location: arch/x86/include/asm/pgtable.h:793
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810721df)
Location: arch/x86/include/asm/pgtable.h:793
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810776c2)
Location: arch/x86/include/asm/pgtable.h:793
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81079e09)
Location: arch/x86/include/asm/pgtable.h:793
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107c710)
Location: arch/x86/include/asm/pgtable.h:793
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff826c54e5)
Location: arch/x86/include/asm/pgtable.h:793
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/power/hibernate_64.c (ffffffff818230d9)
Location: arch/x86/include/asm/pgtable.h:793
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff81025672-ffffffff81025690: pud_large (STB_LOCAL)
ffffffff81070240-ffffffff8107025e: pud_large (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pud_large(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810263c3)
Location: arch/x86/include/asm/pgtable.h:835
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff8107414b)
Location: arch/x86/include/asm/pgtable.h:835
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff81075236)
Location: arch/x86/include/asm/pgtable.h:835
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8107a111)
Location: arch/x86/include/asm/pgtable.h:835
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff8107ca75)
Location: arch/x86/include/asm/pgtable.h:835
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107f41d)
Location: arch/x86/include/asm/pgtable.h:835
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff810833cf)
Location: arch/x86/include/asm/pgtable.h:835
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f01b7)
Location: arch/x86/include/asm/pgtable.h:835
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d3c7)
Location: arch/x86/include/asm/pgtable.h:835
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff810263c3-ffffffff810263e1: pud_large (STB_LOCAL)
ffffffff81073290-ffffffff810732ae: pud_large (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pud_large(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025f73)
Location: arch/x86/include/asm/pgtable.h:860
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff8107a03b)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107b036)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810808f1)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff810834a5)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81086006)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff81089f80)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a6ebf)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/power/hibernate.c (ffffffff8188f3a0)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81025f73-ffffffff81025f91: pud_large (STB_LOCAL)
ffffffff81079330-ffffffff8107934e: pud_large (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pud_large(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81027c73)
Location: arch/x86/include/asm/pgtable.h:877
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff8107dd5b)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107e9a9)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810843f1)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81087115)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089a5d)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108dd2f)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf575)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/power/hibernate.c (ffffffff818d93a0)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81027c73-ffffffff81027c91: pud_large (STB_LOCAL)
ffffffff8107cf40-ffffffff8107cf5e: pud_large (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pud_large(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810285a8)
Location: arch/x86/include/asm/pgtable.h:877
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff8107edeb)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107fa39)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81085131)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81087e05)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108a6cd)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108e98f)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c59f0)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/power/hibernate.c (ffffffff8190b3a0)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810285a8-ffffffff810285c6: pud_large (STB_LOCAL)
ffffffff8107dfd0-ffffffff8107dfee: pud_large (STB_LOCAL)
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
In arch/x86/xen/mmu_pv.c (ffffffff82ccc372)
Location: arch/x86/include/asm/pgtable.h:881
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/mm/init_64.c (ffffffff81085715)
Location: arch/x86/include/asm/pgtable.h:881
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff81086c2e)
Location: arch/x86/include/asm/pgtable.h:881
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a2a5)
Location: arch/x86/include/asm/pgtable.h:881
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108eee7)
Location: arch/x86/include/asm/pgtable.h:881
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81094cdf)
Location: arch/x86/include/asm/pgtable.h:881
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8cd0)
Location: arch/x86/include/asm/pgtable.h:881
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In mm/pagewalk.c (ffffffff812a2b2e)
Location: arch/x86/include/asm/pgtable.h:881
Inline: True
```
```
In mm/ptdump.c (ffffffff8130cd0c)
Location: arch/x86/include/asm/pgtable.h:881
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pud_entry
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc40b)
Location: arch/x86/include/asm/pgtable.h:881
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff82fb81b0)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/mm/init_64.c (ffffffff810867c5)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8108850e)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a525)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ccb1)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff8109409f)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd6756)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In kernel/events/core.c (ffffffff8123caf4)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/pagewalk.c (ffffffff812ae48c)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
```
```
In mm/ptdump.c (ffffffff81318c4c)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pud_entry
```
```
In arch/x86/power/hibernate.c (ffffffff81bd13eb)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff831c281c)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/mm/init_64.c (ffffffff81087518)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8108918d)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff8108b185)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d8a3)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81094a40)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e11a8)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In kernel/events/core.c (ffffffff81243e09)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/memory.c (ffffffff812a3439)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pud_range
```
```
In mm/pagewalk.c (ffffffff812b3852)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
```
```
In mm/vmalloc.c (ffffffff812b8bfa)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/ptdump.c (ffffffff8131ee3c)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pud_entry
```
```
In arch/x86/power/hibernate.c (ffffffff81bc33f5)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff832a3228)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/mm/init_64.c (ffffffff81096874)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810985e8)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a725)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109d12e)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810a49b2)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c4a30)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In kernel/events/core.c (ffffffff8127e77b)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/memory.c (ffffffff812e4713)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pud_range
```
```
In mm/pagewalk.c (ffffffff812f53e3)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
```
```
In mm/vmalloc.c (ffffffff812fb1af)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/ptdump.c (ffffffff8136c21c)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pud_entry
```
```
In arch/x86/power/hibernate.c (ffffffff81c94405)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff83452497)
Location: arch/x86/include/asm/pgtable.h:849
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/mm/init_64.c (ffffffff810a91a0)
Location: arch/x86/include/asm/pgtable.h:849
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810ab243)
Location: arch/x86/include/asm/pgtable.h:849
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810ad9a5)
Location: arch/x86/include/asm/pgtable.h:849
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b09ba)
Location: arch/x86/include/asm/pgtable.h:849
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810b924d)
Location: arch/x86/include/asm/pgtable.h:849
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83477459)
Location: arch/x86/include/asm/pgtable.h:849
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In kernel/events/core.c (ffffffff812d33eb)
Location: arch/x86/include/asm/pgtable.h:849
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/memory.c (ffffffff81346010)
Location: arch/x86/include/asm/pgtable.h:849
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pud_range
```
```
In mm/pagewalk.c (ffffffff813592a0)
Location: arch/x86/include/asm/pgtable.h:849
Inline: True
```
```
In mm/vmalloc.c (ffffffff813626b3)
Location: arch/x86/include/asm/pgtable.h:849
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/ptdump.c (ffffffff813ea4df)
Location: arch/x86/include/asm/pgtable.h:849
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pud_entry
```
```
In arch/x86/power/hibernate.c (ffffffff81e43431)
Location: arch/x86/include/asm/pgtable.h:849
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff83e6fa0b)
Location: arch/x86/include/asm/pgtable.h:867
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/mm/init_64.c (ffffffff820c5bd2)
Location: arch/x86/include/asm/pgtable.h:867
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810c35e5)
Location: arch/x86/include/asm/pgtable.h:867
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7b85)
Location: arch/x86/include/asm/pgtable.h:867
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cb088)
Location: arch/x86/include/asm/pgtable.h:867
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810d4bbf)
Location: arch/x86/include/asm/pgtable.h:867
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea093e)
Location: arch/x86/include/asm/pgtable.h:867
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In kernel/events/core.c (ffffffff8133b662)
Location: arch/x86/include/asm/pgtable.h:867
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff8137fed2)
Location: arch/x86/include/asm/pgtable.h:867
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/memory.c (ffffffff813be3e0)
Location: arch/x86/include/asm/pgtable.h:867
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pud_range
```
```
In mm/pagewalk.c (ffffffff813d3b70)
Location: arch/x86/include/asm/pgtable.h:867
Inline: True
```
```
In mm/vmalloc.c (ffffffff813de049)
Location: arch/x86/include/asm/pgtable.h:867
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/ptdump.c (ffffffff814725f0)
Location: arch/x86/include/asm/pgtable.h:867
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pud_entry
```
```
In arch/x86/power/hibernate.c (ffffffff8201e4d2)
Location: arch/x86/include/asm/pgtable.h:867
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
In arch/x86/xen/mmu_pv.c (ffffffff836907cb)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/mm/init_64.c (ffffffff82149c42)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810c6e35)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810cb2d5)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce6b8)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810d80cf)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4b04)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In kernel/events/core.c (ffffffff8136d040)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813b13be)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/memory.c (ffffffff813f3040)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pud_range
```
```
In mm/pagewalk.c (ffffffff81408540)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
```
```
In mm/vmalloc.c (ffffffff814128a9)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/ptdump.c (ffffffff814a6d50)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pud_entry
```
```
In arch/x86/power/hibernate.c (ffffffff8209e4d2)
Location: arch/x86/include/asm/pgtable.h:868
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
In arch/x86/xen/mmu_pv.c (ffffffff838c029b)
Location: arch/x86/include/asm/pgtable.h:1090
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/mm/init_64.c (ffffffff8222c6f2)
Location: arch/x86/include/asm/pgtable.h:1090
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810cf2f5)
Location: arch/x86/include/asm/pgtable.h:1090
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810d3825)
Location: arch/x86/include/asm/pgtable.h:1090
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d6d98)
Location: arch/x86/include/asm/pgtable.h:1090
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810e094f)
Location: arch/x86/include/asm/pgtable.h:1090
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f5704)
Location: arch/x86/include/asm/pgtable.h:1090
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In kernel/events/core.c (ffffffff81396280)
Location: arch/x86/include/asm/pgtable.h:1090
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813da93e)
Location: arch/x86/include/asm/pgtable.h:1090
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/memory.c (ffffffff8141dd30)
Location: arch/x86/include/asm/pgtable.h:1090
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pud_range
```
```
In mm/pagewalk.c (ffffffff81434c60)
Location: arch/x86/include/asm/pgtable.h:1090
Inline: True
```
```
In mm/vmalloc.c (ffffffff8143f319)
Location: arch/x86/include/asm/pgtable.h:1090
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/ptdump.c (ffffffff814d7d50)
Location: arch/x86/include/asm/pgtable.h:1090
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pud_entry
```
```
In arch/x86/power/hibernate.c (ffffffff821764d2)
Location: arch/x86/include/asm/pgtable.h:1090
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pud_large(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028708)
Location: arch/x86/include/asm/pgtable.h:877
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff8107ddeb)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107ea39)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81084131)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81086e05)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108968d)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108d94f)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0988)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/power/hibernate.c (ffffffff818ab3a0)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81028708-ffffffff81028726: pud_large (STB_LOCAL)
ffffffff8107cfd0-ffffffff8107cfee: pud_large (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff8106d0f1)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8106ddec)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81070f63)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (ffffffff81075a65)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81078427)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff8107c430)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8b0d)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/power/hibernate.c (ffffffff8186539a)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pud_large(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028568)
Location: arch/x86/include/asm/pgtable.h:877
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff8107dd9b)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107e9e9)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810840e1)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81086db5)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108963d)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108d8ff)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c3887)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/power/hibernate.c (ffffffff818fc3a0)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81028568-ffffffff81028586: pud_large (STB_LOCAL)
ffffffff8107cf80-ffffffff8107cf9e: pud_large (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pud_large(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810291f8)
Location: arch/x86/include/asm/pgtable.h:877
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff8107fe8b)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff81080ad9)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81086221)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81088ee5)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108b8dd)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108fcdf)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6a2d)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/power/hibernate.c (ffffffff8191d3a0)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810291f8-ffffffff81029216: pud_large (STB_LOCAL)
ffffffff8107f070-ffffffff8107f08e: pud_large (STB_LOCAL)
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
