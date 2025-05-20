# Function: <code>set_pud</code>

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
In arch/x86/xen/mmu.c (ffffffff81f628bb)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103469a)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105badf)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107d4d3)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pud_clear
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c237)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pgd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81071387)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In mm/memory.c (ffffffff811bcf1e)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:__pmd_alloc
```
```
In mm/pgtable-generic.c (ffffffff811d03e1)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff811dd5f3)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8181f464)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
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
In arch/x86/xen/mmu.c (ffffffff81f8ac3e)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033865)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bbc8)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff818960f7)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c0a5)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81071278)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In mm/memory.c (ffffffff811daa0a)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff811ed591)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff811fb8c5)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81899b41)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff817606a3)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/xen/mmu.c (ffffffff81fc602c)
Location: arch/x86/include/asm/paravirt.h:517
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033492)
Location: arch/x86/include/asm/paravirt.h:517
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105eb42)
Location: arch/x86/include/asm/paravirt.h:517
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff818ca814)
Location: arch/x86/include/asm/paravirt.h:517
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff8106fcc5)
Location: arch/x86/include/asm/paravirt.h:517
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81074df8)
Location: arch/x86/include/asm/paravirt.h:517
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In mm/memory.c (ffffffff811ea577)
Location: arch/x86/include/asm/paravirt.h:517
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff811f7981)
Location: arch/x86/include/asm/paravirt.h:517
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8120c3bd)
Location: arch/x86/include/asm/paravirt.h:517
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff818ce1f3)
Location: arch/x86/include/asm/paravirt.h:517
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d803)
Location: arch/x86/include/asm/paravirt.h:517
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/xen/mmu_pv.c (ffffffff820a6ee0)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81031655)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e1e1)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81901d8d)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff8106f3f5)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff810743a8)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In mm/memory.c (ffffffff811f55cf)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81202b11)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff81217d5d)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81905688)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff817ab99b)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826a645c)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826ad650)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810338ac)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061eb8)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8198bdc5)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff8107479f)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81079f5e)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pti.c (ffffffff826c555a)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff8120e4b4)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8121b881)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff81232aca)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8198f6f2)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff81822f1d)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826cf5ee)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826d694b)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034c24)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81064f61)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff819e86d8)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff8107720c)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8107cbfd)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pti.c (ffffffff81083441)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff8122eea9)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8123d661)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff81255b1c)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff819ebf6a)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d212)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288561b)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8288c894)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035e04)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106abd1)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a23e56)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff8107d93c)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8108362b)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pti.c (ffffffff81089ff2)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff81241939)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81251bb1)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff81269f6c)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a271d8)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff8188d0c2)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff8188f3d3)
Location: arch/x86/include/asm/paravirt.h:500
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289c699)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a3d30)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81037f64)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e38a)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a941a0)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff8108123c)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8108729f)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pti.c (ffffffff8108dda1)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff812542b8)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81263e82)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8128509f)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a97a83)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff818d7af2)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff818d93d3)
Location: arch/x86/include/asm/paravirt.h:501
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289f689)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a6dca)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038734)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f93a)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81acba80)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff810822fc)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81087f8f)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pti.c (ffffffff8108ea01)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff81262818)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff812726f2)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff81294c3f)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81acf351)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff81909e32)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff8190b3d3)
Location: arch/x86/include/asm/paravirt.h:489
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
void set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82cc5b75)
Location: arch/x86/include/asm/paravirt.h:503
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82ccd026)
Location: arch/x86/include/asm/paravirt.h:503
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b259)
Location: arch/x86/include/asm/paravirt.h:503
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076e42)
Location: arch/x86/include/asm/paravirt.h:503
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81bc4b74)
Location: arch/x86/include/asm/paravirt.h:503
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a42f)
Location: arch/x86/include/asm/paravirt.h:503
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c5c2)
Location: arch/x86/include/asm/paravirt.h:503
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In arch/x86/mm/pti.c (ffffffff81094d51)
Location: arch/x86/include/asm/paravirt.h:503
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff81292718)
Location: arch/x86/include/asm/paravirt.h:503
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff812a3492)
Location: arch/x86/include/asm/paravirt.h:503
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff812c8235)
Location: arch/x86/include/asm/paravirt.h:503
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7d0c)
Location: arch/x86/include/asm/paravirt.h:503
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bba70c)
Location: arch/x86/include/asm/paravirt.h:503
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc55a)
Location: arch/x86/include/asm/paravirt.h:503
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81085e84-ffffffff81085e91: set_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82fb1469)
Location: arch/x86/include/asm/paravirt.h:430
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82fb8e68)
Location: arch/x86/include/asm/paravirt.h:430
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103ba69)
Location: arch/x86/include/asm/paravirt.h:430
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077472)
Location: arch/x86/include/asm/paravirt.h:430
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81c3da6d)
Location: arch/x86/include/asm/paravirt.h:430
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a686)
Location: arch/x86/include/asm/paravirt.h:430
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ccd3)
Location: arch/x86/include/asm/paravirt.h:430
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In arch/x86/mm/pti.c (ffffffff81094111)
Location: arch/x86/include/asm/paravirt.h:430
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff8129cffe)
Location: arch/x86/include/asm/paravirt.h:430
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff812ab08f)
Location: arch/x86/include/asm/paravirt.h:430
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812aed86)
Location: arch/x86/include/asm/paravirt.h:430
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff812d3df9)
Location: arch/x86/include/asm/paravirt.h:430
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81c40a37)
Location: arch/x86/include/asm/paravirt.h:430
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bcee3c)
Location: arch/x86/include/asm/paravirt.h:430
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bd153a)
Location: arch/x86/include/asm/paravirt.h:430
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81bd8836-ffffffff81bd8843: set_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff831bb5f4)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff831c3489)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d40a)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077efb)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086e78)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pgtable.c (ffffffff8108b2d6)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d8c5)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In arch/x86/mm/pti.c (ffffffff81094ab3)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff812a26e2)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff812b058f)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812b42b6)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff812dad05)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81bdacec)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bc27f5)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bc3544)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81bca6dd-ffffffff81bca6ea: set_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8329bb28)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff832a3ec3)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81043052)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8108570c)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81096188)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a876)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109d150)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In arch/x86/mm/pti.c (ffffffff810a4a25)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff812e3a52)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff812f28b6)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff812f5e96)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff81321d26)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81cc0787)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81c92eb5)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81c94553)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81c9fb83-ffffffff81c9fb90: set_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_pud(pud_t *pudp, pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8344a31c)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83453148)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104af87)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095ad8)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a8a1d)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pgtable.c (ffffffff810adb44)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b09da)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In arch/x86/mm/pti.c (ffffffff810b92bc)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/percpu.c (ffffffff81e6c801)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
```
```
In mm/memory.c (ffffffff81344dde)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff8135665a)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81359e04)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8138ee72)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81e72bab)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81e4284d)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81e43597)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810a7d30-ffffffff810a7d56: set_pud (STB_LOCAL)
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83e64929)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e70674)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81056a01)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab71a)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff820c5d0f)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7d57)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cb0a8)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In arch/x86/mm/pti.c (ffffffff810d4c2b)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/percpu.c (ffffffff8139aeeb)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
```
```
In mm/memory.c (ffffffff813bd00b)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff813d0c7b)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff813d4814)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8140d95a)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8141badb)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff8201d276)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff8201e63b)
Location: arch/x86/include/asm/paravirt.h:462
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83684fa9)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff836914ee)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810579d0)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af2da)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff82149d79)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/pgtable.c (ffffffff810cb497)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce6d2)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In arch/x86/mm/pti.c (ffffffff810d8135)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/percpu.c (ffffffff813cdfab)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
```
```
In mm/memory.c (ffffffff813f1d51)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff814056ad)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff814091e4)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff81440d0d)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8144f0db)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff8209d906)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff8209e635)
Location: arch/x86/include/asm/paravirt.h:457
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b4149)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c0ffe)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105ec70)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5e6a)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8222c829)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/pgtable.c (ffffffff810d39e7)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d6db2)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In arch/x86/mm/pti.c (ffffffff810e09b5)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/percpu.c (ffffffff813f891b)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
```
```
In mm/memory.c (ffffffff8141751f)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:pud_populate
```
```
In mm/mremap.c (ffffffff81431bd5)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:pud_populate
```
```
In mm/pgtable-generic.c (ffffffff814359d4)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8147ae3d)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:pud_populate
```
```
In mm/sparse-vmemmap.c (ffffffff81488c9b)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff82175106)
Location: arch/x86/include/asm/paravirt.h:456
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff82176635)
Location: arch/x86/include/asm/paravirt.h:456
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/mmu.c (ffff8000100af540)
Location: arch/arm64/include/asm/pgtable.h:530
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:pud_free_pmd_page
  - arch/arm64/mm/mmu.c:pud_clear_huge
  - arch/arm64/mm/mmu.c:pud_set_huge
  - arch/arm64/mm/mmu.c:alloc_init_pud
  - arch/arm64/mm/mmu.c:early_fixmap_init
```
```
In virt/kvm/arm/mmu.c (ffff8000100cafb8)
Location: arch/arm64/include/asm/pgtable.h:530
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
```
```
In mm/memory.c (ffff8000102f9a70)
Location: arch/arm64/include/asm/pgtable.h:530
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffff800010307f5c)
Location: arch/arm64/include/asm/pgtable.h:530
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffff80001033399c)
Location: arch/arm64/include/asm/pgtable.h:530
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffff800010da0f2c)
Location: arch/arm64/include/asm/pgtable.h:530
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
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
In arch/riscv/mm/fault.c (ffffffe0000b9de2)
Location: arch/riscv/include/asm/pgtable-64.h:46
Inline: True
Inline callers:
  - arch/riscv/mm/fault.c:do_page_fault
```
```
In mm/memory.c (ffffffe00020979a)
Location: arch/riscv/include/asm/pgtable-64.h:46
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffe000212e24)
Location: arch/riscv/include/asm/pgtable-64.h:46
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffe00022fb0a)
Location: arch/riscv/include/asm/pgtable-64.h:46
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffe0000490a4)
Location: arch/riscv/include/asm/pgtable-64.h:46
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288d689)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82894dd3)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038894)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e8da)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a6a8f0)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff810812fc)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81086f8f)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pti.c (ffffffff8108d9c1)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff8125ae68)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff8126ad42)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8128d21f)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e1c1)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff818a91f2)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff818ab3d3)
Location: arch/x86/include/asm/paravirt.h:489
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a0689)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7dca)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810386f4)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ed8a)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ad6d00)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff810812ac)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81086f3f)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pti.c (ffffffff8108d971)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff81258c08)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81268ae2)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8128b02f)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81ada5d1)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff818fa852)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff818fc3d3)
Location: arch/x86/include/asm/paravirt.h:489
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a068e)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7dd0)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810396f4)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107100a)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ae31c0)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff810833cc)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8108906f)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pti.c (ffffffff8108fd51)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff81268608)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81278472)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8129ae4f)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81ae6a87)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff8191b9b2)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff8191d3d3)
Location: arch/x86/include/asm/paravirt.h:489
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
