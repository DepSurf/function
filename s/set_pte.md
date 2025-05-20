# Function: <code>set_pte</code>

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
In arch/x86/xen/mmu.c (ffffffff81f627fe)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/xen/p2m.c (ffffffff81024c59)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034917)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bc13)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8181baab)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
```
```
In arch/x86/mm/ioremap.c (ffffffff81f77fdd)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c3bb)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff8107122e)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff81073058)
Location: arch/x86/include/asm/paravirt.h:483
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
In arch/x86/xen/mmu.c (ffffffff81f8a405)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/xen/p2m.c (ffffffff81023f9c)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033ac9)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bd08)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff818961c5)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
```
```
In arch/x86/mm/ioremap.c (ffffffff81fa0735)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8106db59)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff810711de)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff8107461d)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81760985)
Location: arch/x86/include/asm/paravirt.h:456
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
In arch/x86/xen/mmu.c (ffffffff81fc57ff)
Location: arch/x86/include/asm/paravirt.h:447
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/xen/p2m.c (ffffffff810246cc)
Location: arch/x86/include/asm/paravirt.h:447
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810336ed)
Location: arch/x86/include/asm/paravirt.h:447
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ec82)
Location: arch/x86/include/asm/paravirt.h:447
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff818ca8e2)
Location: arch/x86/include/asm/paravirt.h:447
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
```
```
In arch/x86/mm/ioremap.c (ffffffff81fdbca6)
Location: arch/x86/include/asm/paravirt.h:447
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff810717e5)
Location: arch/x86/include/asm/paravirt.h:447
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81074d5e)
Location: arch/x86/include/asm/paravirt.h:447
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff8107819d)
Location: arch/x86/include/asm/paravirt.h:447
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178dafa)
Location: arch/x86/include/asm/paravirt.h:447
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
In arch/x86/xen/p2m.c (ffffffff8101d85e)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/xen/mmu_pv.c (ffffffff820a66b0)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81031895)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e31e)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81901e5a)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff820bcc76)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff81070fcd)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8107430c)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff81076a0e)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/power/hibernate_64.c (ffffffff817abca8)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/xen/p2m.c (ffffffff8101e4d9)
Location: arch/x86/include/asm/paravirt.h:441
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826acd79)
Location: arch/x86/include/asm/paravirt.h:441
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033b29)
Location: arch/x86/include/asm/paravirt.h:441
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81062013)
Location: arch/x86/include/asm/paravirt.h:441
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8198be97)
Location: arch/x86/include/asm/paravirt.h:441
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff826c3852)
Location: arch/x86/include/asm/paravirt.h:441
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff81076715)
Location: arch/x86/include/asm/paravirt.h:441
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81079d9c)
Location: arch/x86/include/asm/paravirt.h:441
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff8107cdbf)
Location: arch/x86/include/asm/paravirt.h:441
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5fba)
Location: arch/x86/include/asm/paravirt.h:441
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/power/hibernate_64.c (ffffffff81823268)
Location: arch/x86/include/asm/paravirt.h:441
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/xen/p2m.c (ffffffff8101f035)
Location: arch/x86/include/asm/paravirt.h:441
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826d60e0)
Location: arch/x86/include/asm/paravirt.h:441
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034e55)
Location: arch/x86/include/asm/paravirt.h:441
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810650d3)
Location: arch/x86/include/asm/paravirt.h:441
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff819e87af)
Location: arch/x86/include/asm/paravirt.h:441
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff826edad7)
Location: arch/x86/include/asm/paravirt.h:441
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff810790a5)
Location: arch/x86/include/asm/paravirt.h:441
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8107ca1a)
Location: arch/x86/include/asm/paravirt.h:441
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff8107fd77)
Location: arch/x86/include/asm/paravirt.h:441
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efd8d)
Location: arch/x86/include/asm/paravirt.h:441
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d520)
Location: arch/x86/include/asm/paravirt.h:441
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
In arch/x86/xen/p2m.c (ffffffff8101e8d7)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81036035)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ad43)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a23f5d)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/ioremap.c (ffffffff828a4669)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8107f9bc)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8108344a)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:ptep_set_access_flags
```
```
In arch/x86/mm/kmmio.c (ffffffff810868b7)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6a4a)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/power/hibernate.c (ffffffff8188f4f5)
Location: arch/x86/include/asm/paravirt.h:446
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
In arch/x86/xen/p2m.c (ffffffff81020436)
Location: arch/x86/include/asm/paravirt.h:447
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038195)
Location: arch/x86/include/asm/paravirt.h:447
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e4ff)
Location: arch/x86/include/asm/paravirt.h:447
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107d892)
Location: arch/x86/include/asm/paravirt.h:447
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
  - arch/x86/mm/init_64.c:set_pte_init
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828bcb39)
Location: arch/x86/include/asm/paravirt.h:447
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff810833b7)
Location: arch/x86/include/asm/paravirt.h:447
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff810870b0)
Location: arch/x86/include/asm/paravirt.h:447
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:ptep_set_access_flags
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a4c7)
Location: arch/x86/include/asm/paravirt.h:447
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bf0f4)
Location: arch/x86/include/asm/paravirt.h:447
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/power/hibernate.c (ffffffff818d94f5)
Location: arch/x86/include/asm/paravirt.h:447
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
In arch/x86/xen/p2m.c (ffffffff81020d96)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038965)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106faaf)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e922)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
  - arch/x86/mm/init_64.c:set_pte_init
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2fd4)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff81084487)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81087da0)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:ptep_set_access_flags
```
```
In arch/x86/mm/kmmio.c (ffffffff8108b137)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c556f)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/power/hibernate.c (ffffffff8190b4f5)
Location: arch/x86/include/asm/paravirt.h:435
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
void set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81023602)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b14a)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076fcc)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810854b1)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
Direct callers:
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce63c1)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a23f)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:ptep_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e224)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:unmap_pte_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810925f9)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce877f)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc4ed)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81022d10-ffffffff81022d1d: set_pte (STB_LOCAL)
ffffffff81085e50-ffffffff81085e5d: set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81021682)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/p2m.c (ffffffff81023bd2)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026080)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit
```
```
In arch/x86/kernel/ldt.c (ffffffff8103973b)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b95a)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103d162)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4de5)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810658b0)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810775fc)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107f690)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In arch/x86/mm/init_64.c (ffffffff81086567)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
Direct callers:
  - arch/x86/mm/init_64.c:remove_pte_table
  - arch/x86/mm/init_64.c:remove_pte_table
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff81bd96cc)
Location: arch/x86/include/asm/paravirt.h:410
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a4c1)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:ptep_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e0f4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff81091c2b)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd6192)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8125122d)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff81279307)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8129251c)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129c566)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pte_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
Direct callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff812a9b7e)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812ab54d)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In mm/rmap.c (ffffffff812b0fc9)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff812b2acd)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pte_range
```
```
In mm/ioremap.c (ffffffff812b8141)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_pte_range
```
```
In mm/madvise.c (ffffffff812c2e72)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812c7792)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812d5665)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff81c40866)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812df5ce)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812f01ed)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812f5240)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff812fbd6f)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81313fe4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/dax.c (ffffffff8139f48c)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813c7f45)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In drivers/xen/xlate_mmu.c (ffffffff81743625)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate.c (ffffffff81bd14cd)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810232e0-ffffffff810232ed: set_pte (STB_LOCAL)
ffffffff81bd8802-ffffffff81bd880f: set_pte (STB_LOCAL)
ffffffff81bd96cc-ffffffff81bd96d9: set_pte (STB_LOCAL)
ffffffff812968a0-ffffffff812968ad: set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81023a02)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/p2m.c (ffffffff81025df5)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027fc0)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit
```
```
In arch/x86/kernel/ldt.c (ffffffff8103b208)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d2f8)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103e99f)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc7234)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81065f80)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107807d)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080790)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In arch/x86/mm/init_64.c (ffffffff81087307)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff81bcb65f)
Location: arch/x86/include/asm/paravirt.h:433
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff8108b121)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:ptep_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ecb7)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff8109251e)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0bed)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81255327)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8127e2f3)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff81297fcc)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812a1a31)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
Direct callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (ffffffff812af009)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812b0950)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
```
```
In mm/rmap.c (ffffffff812b6595)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff812b7db6)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff812c9cef)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812ce10a)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812dc3c0)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff81c328c4)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812e7f0a)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812f58c7)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812fb788)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff81302cb8)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8131a1a3)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/dax.c (ffffffff813a61f6)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813cef75)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In drivers/xen/xlate_mmu.c (ffffffff81727011)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate.c (ffffffff81bc34d7)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810255e0-ffffffff810255ed: set_pte (STB_LOCAL)
ffffffff81bca6a9-ffffffff81bca6b6: set_pte (STB_LOCAL)
ffffffff81bcb65f-ffffffff81bcb66c: set_pte (STB_LOCAL)
ffffffff8129c240-ffffffff8129c24d: set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81027ca2)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/p2m.c (ffffffff8102a313)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/ldt.c (ffffffff81040c44)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042e39)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8104470f)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81c9a82d)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810700a0)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085897)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108f6b0)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In arch/x86/mm/init_64.c (ffffffff81096627)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff81ca0d97)
Location: arch/x86/include/asm/paravirt.h:433
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a6c1)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:ptep_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109e76a)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810a230e)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff832c42c5)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81290d69)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff812d8a0c)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812e2a01)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
Direct callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mprotect.c (ffffffff812f0802)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812f22e0)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
```
```
In mm/rmap.c (ffffffff812f8bd6)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff812fa4e8)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff8130ed0f)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8131358a)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81323591)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff8132c5a4)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_restore_pte
  - mm/sparse-vmemmap.c:vmemmap_remap_pte
  - mm/sparse-vmemmap.c:vmemmap_remap_range
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8132fe1b)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/kfence/core.c (ffffffff8133be39)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_unprotect
  - mm/kfence/core.c:kfence_protect
```
```
In mm/migrate.c (ffffffff8133fe95)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff813454fd)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff8134c778)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81366e90)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/dax.c (ffffffff813f5c66)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81420455)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In drivers/xen/xlate_mmu.c (ffffffff817a6091)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate.c (ffffffff81c944e7)
Location: arch/x86/include/asm/paravirt.h:433
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81029af0-ffffffff81029afd: set_pte (STB_LOCAL)
ffffffff81c9fb4f-ffffffff81c9fb5c: set_pte (STB_LOCAL)
ffffffff81ca0d97-ffffffff81ca0da4: set_pte (STB_LOCAL)
ffffffff812dcd40-ffffffff812dcd4d: set_pte (STB_LOCAL)
ffffffff8132bcf0-ffffffff8132bcfd: set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8102c121)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/p2m.c (ffffffff8102ee05)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/ldt.c (ffffffff8104859b)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104ad72)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/alternative.c (ffffffff8104cd09)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81e49c99)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107d9d4)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095c3a)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a0430)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In arch/x86/mm/init_64.c (ffffffff810a8f07)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff81e5031e)
Location: arch/x86/include/asm/paravirt.h:439
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff810ad931)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:ptep_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b214d)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810b68ad)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83476c2a)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff812e6068)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff81338a2d)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81343323)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:zap_pte_range
  - mm/memory.c:restore_exclusive_pte
Direct callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mprotect.c (ffffffff81354066)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81356085)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
```
```
In mm/rmap.c (ffffffff8135f1b8)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81361872)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff81376a02)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8137e8c6)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81391076)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff8139c62e)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_restore_pte
  - mm/sparse-vmemmap.c:vmemmap_remap_pte
  - mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff813a01e7)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/kfence/core.c (ffffffff813aea80)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_protect_page
```
```
In mm/migrate.c (ffffffff813b1ab4)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff813b742e)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813bb50b)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff813e436d)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/proc/task_mmu.c (ffffffff8149a845)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In drivers/xen/xlate_mmu.c (ffffffff818e004a)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate.c (ffffffff81e43516)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff8102e3c0-ffffffff8102e3e6: set_pte (STB_LOCAL)
ffffffff810a7c90-ffffffff810a7cb6: set_pte (STB_LOCAL)
ffffffff81e5031e-ffffffff81e50344: set_pte (STB_LOCAL)
ffffffff8133c9b0-ffffffff8133c9d6: set_pte (STB_LOCAL)
ffffffff8139b9f0-ffffffff8139ba16: set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8103305c)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/p2m.c (ffffffff81036168)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/ldt.c (ffffffff810532fb)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81056c49)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/alternative.c (ffffffff81059113)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81067f8e)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108ef54)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab870)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b7fd0)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In arch/x86/mm/init_64.c (ffffffff820c57c5)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
```
In arch/x86/mm/ioremap.c (ffffffff83e9c05c)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7ade)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:ptep_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cc9d7)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810d1af6)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83e9fe0d)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8134fcce)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff813b02a9)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813bb302)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:zap_pte_range
  - mm/memory.c:restore_exclusive_pte
Direct callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mprotect.c (ffffffff813ce4ec)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813d06c8)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
```
```
In mm/rmap.c (ffffffff813da070)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff813dd210)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff813f42f6)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff813fd44a)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff814125d2)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
Direct callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff81414374)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff820cb503)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8141f0ce)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/kfence/core.c (ffffffff8142efb1)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_protect_page
```
```
In mm/migrate.c (ffffffff8143255b)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff81439409)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8143d917)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff8146be1d)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/proc/task_mmu.c (ffffffff8152ed65)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a344eb)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate.c (ffffffff8201e5ba)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff813b4700-ffffffff813b4726: set_pte (STB_LOCAL)
ffffffff81405090-ffffffff814050b6: set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81032ffc)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/p2m.c (ffffffff810360e8)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/ldt.c (ffffffff810542dc)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81057c24)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/alternative.c (ffffffff8105a6c1)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81069816)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81091e44)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af431)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bb180)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In arch/x86/mm/init_64.c (ffffffff82149835)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
```
In arch/x86/mm/ioremap.c (ffffffff836bfafc)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff810cb224)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:ptep_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cfff7)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810d4fa6)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff836c3fb4)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81380e67)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff813e481b)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813efdde)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
Direct callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mprotect.c (ffffffff81402c4a)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81404ba2)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
```
```
In mm/rmap.c (ffffffff8140e7b3)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81410caa)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff81427b0b)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8143072c)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81445ba5)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff814478cd)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff8214f795)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81453d53)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/kfence/core.c (ffffffff814647e9)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
```
```
In mm/migrate.c (ffffffff81467f5d)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146f7d8)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81473081)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff814a095d)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_pte_zeropage
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/proc/task_mmu.c (ffffffff81567075)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a7df0a)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate.c (ffffffff8209e5b4)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff813e9380-ffffffff813e93a6: set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81039143)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
```
```
In arch/x86/xen/p2m.c (ffffffff8103c2e8)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/ldt.c (ffffffff8105b510)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105eec4)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/alternative.c (ffffffff81061a0f)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81070bc3)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099403)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5fc1)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c2d53)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In arch/x86/mm/init_64.c (ffffffff8222c2f5)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
```
```
In arch/x86/mm/ioremap.c (ffffffff838f061c)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff810d3774)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:ptep_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d86d7)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810dd746)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff838f4c34)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff813a9873)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
```
```
In mm/gup.c (ffffffff8140dfa3)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
```
```
In mm/memory.c (ffffffff8141e54f)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:zap_pte_range
Direct callers:
  - mm/memory.c:handle_pte_marker
```
```
In mm/mprotect.c (ffffffff8142f260)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8143117d)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
```
```
In mm/rmap.c (ffffffff81437933)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
```
```
In mm/vmalloc.c (ffffffff8143e2b6)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff8146131b)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff81468d73)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
```
```
In mm/hugetlb.c (ffffffff8147f7e2)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff81480afe)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff81489043)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
```
```
In mm/ksm.c (ffffffff8148d693)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
```
```
In mm/kfence/core.c (ffffffff81493911)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
```
```
In mm/migrate.c (ffffffff81497713)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
```
```
In mm/migrate_device.c (ffffffff8149cba3)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
```
```
In mm/huge_memory.c (ffffffff814a17e8)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff814cfe43)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159cb63)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
```
```
In drivers/xen/xlate_mmu.c (ffffffff81ad0143)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff821765b4)
Location: arch/x86/include/asm/paravirt.h:434
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81414060-ffffffff81414086: set_pte (STB_LOCAL)
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
In arch/arm64/kernel/efi.c (ffff8000114360cc)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/arm64/kernel/efi.c:set_permissions
```
```
In arch/arm64/mm/mmu.c (ffff8000100aeb90)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:init_pmd
```
```
In arch/arm64/mm/pageattr.c (ffff8000100b0140)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/arm64/mm/pageattr.c:change_page_range
```
```
In arch/arm64/mm/hugetlbpage.c (ffff8000100b17a8)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_clear_flush
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_set_wrprotect
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_set_access_flags
  - arch/arm64/mm/hugetlbpage.c:huge_pte_clear
  - arch/arm64/mm/hugetlbpage.c:set_huge_swap_pte_at
  - arch/arm64/mm/hugetlbpage.c:set_huge_pte_at
  - arch/arm64/mm/hugetlbpage.c:set_huge_pte_at
  - arch/arm64/mm/hugetlbpage.c:set_huge_pte_at
```
```
In kernel/events/uprobes.c (ffff8000102a5648)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffff8000102d324c)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffff8000102f1dd8)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102fa0d8)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffff8000103052f4)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffff8000103061b0)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffff80001030a0cc)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffff80001030c384)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
```
```
In mm/madvise.c (ffff80001031edac)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffff800010326144)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/sparse-vmemmap.c (ffff800010da0dfc)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffff80001033edd8)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffff800010352fb4)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffff800010355f44)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035e614)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffff800010378cc0)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/dax.c (ffff8000104077e0)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In drivers/xen/xlate_mmu.c (ffff80001083f280)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffff800010d89798)
Location: arch/arm64/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
</details>
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
In arch/riscv/mm/init.c (ffffffe000003d9a)
Location: arch/riscv/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - arch/riscv/mm/init.c:paging_init
  - arch/riscv/mm/init.c:paging_init
  - arch/riscv/mm/init.c:get_pmd_virt
  - arch/riscv/mm/init.c:get_pmd_virt
  - arch/riscv/mm/init.c:get_pte_virt
  - arch/riscv/mm/init.c:get_pte_virt
```
```
In mm/shmem.c (ffffffe0001ee3f8)
Location: arch/riscv/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffe000204926)
Location: arch/riscv/include/asm/pgtable.h:326
Inline: True
```
```
In mm/memory.c (ffffffe000209986)
Location: arch/riscv/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffe000211238)
Location: arch/riscv/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffe000211c56)
Location: arch/riscv/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffe000213f9a)
Location: arch/riscv/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffe0002158c6)
Location: arch/riscv/include/asm/pgtable.h:326
Inline: True
```
```
In mm/madvise.c (ffffffe00022071e)
Location: arch/riscv/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffe000226486)
Location: arch/riscv/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffe000230ee0)
Location: arch/riscv/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffe000048fdc)
Location: arch/riscv/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffe0002349c0)
Location: arch/riscv/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffe00023e1e6)
Location: arch/riscv/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/userfaultfd.c (ffffffe000250590)
Location: arch/riscv/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffe0002b2dca)
Location: arch/riscv/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In lib/ioremap.c (ffffffe0008b31a2)
Location: arch/riscv/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/xen/p2m.c (ffffffff81020ef6)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038ac5)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ea4f)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107d922)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
  - arch/x86/mm/init_64.c:set_pte_init
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828adfaa)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff81083487)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81086da0)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:ptep_set_access_flags
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a0f7)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b0507)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/power/hibernate.c (ffffffff818ab4f5)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81020d56)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038925)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106eeff)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107d8d2)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
  - arch/x86/mm/init_64.c:set_pte_init
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0ea9)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff81083437)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81086d50)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:ptep_set_access_flags
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a0a7)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c3406)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/power/hibernate.c (ffffffff818fc4f5)
Location: arch/x86/include/asm/paravirt.h:435
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
In arch/x86/xen/p2m.c (ffffffff81020fa6)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81039925)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107117f)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107f9c2)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
  - arch/x86/mm/init_64.c:set_pte_init
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828c3ff4)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff81085689)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81088e80)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:ptep_set_access_flags
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c347)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c65ac)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/power/hibernate.c (ffffffff8191d4f5)
Location: arch/x86/include/asm/paravirt.h:435
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
