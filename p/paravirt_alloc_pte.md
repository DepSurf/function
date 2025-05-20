# Function: <code>paravirt_alloc_pte</code>

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
In arch/x86/xen/p2m.c (ffffffff81024aa1)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810347cc)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81068f0f)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff81f77eaa)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8106d687)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In mm/memory.c (ffffffff811bd2c3)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff8181f35c)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff811f38ec)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
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
In arch/x86/xen/p2m.c (ffffffff81023dea)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103398d)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81068ec7)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff81fa0603)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8106d45c)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In mm/memory.c (ffffffff811da43d)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81899a23)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff812161e4)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8121a955)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In arch/x86/xen/p2m.c (ffffffff8102451a)
Location: arch/x86/include/asm/paravirt.h:332
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810335b7)
Location: arch/x86/include/asm/paravirt.h:332
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff8106cb17)
Location: arch/x86/include/asm/paravirt.h:332
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff81fdbb74)
Location: arch/x86/include/asm/paravirt.h:332
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff810710a6)
Location: arch/x86/include/asm/paravirt.h:332
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In mm/memory.c (ffffffff811e9f61)
Location: arch/x86/include/asm/paravirt.h:332
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff818ce0d5)
Location: arch/x86/include/asm/paravirt.h:332
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff8122878d)
Location: arch/x86/include/asm/paravirt.h:332
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8122eca4)
Location: arch/x86/include/asm/paravirt.h:332
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In arch/x86/xen/p2m.c (ffffffff8101d6dd)
Location: arch/x86/include/asm/paravirt.h:330
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81031775)
Location: arch/x86/include/asm/paravirt.h:330
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff8106bdb2)
Location: arch/x86/include/asm/paravirt.h:330
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff820bcb4e)
Location: arch/x86/include/asm/paravirt.h:330
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81070819)
Location: arch/x86/include/asm/paravirt.h:330
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In mm/memory.c (ffffffff811f51ad)
Location: arch/x86/include/asm/paravirt.h:330
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff8190556a)
Location: arch/x86/include/asm/paravirt.h:330
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff81231e3a)
Location: arch/x86/include/asm/paravirt.h:330
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812389df)
Location: arch/x86/include/asm/paravirt.h:330
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In arch/x86/xen/p2m.c (ffffffff8101e3c7)
Location: arch/x86/include/asm/paravirt.h:322
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810339f2)
Location: arch/x86/include/asm/paravirt.h:322
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff810707a2)
Location: arch/x86/include/asm/paravirt.h:322
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff826c3720)
Location: arch/x86/include/asm/paravirt.h:322
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81075ed9)
Location: arch/x86/include/asm/paravirt.h:322
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In mm/memory.c (ffffffff8120d290)
Location: arch/x86/include/asm/paravirt.h:322
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff8198f5b7)
Location: arch/x86/include/asm/paravirt.h:322
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff81252bb7)
Location: arch/x86/include/asm/paravirt.h:322
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812592da)
Location: arch/x86/include/asm/paravirt.h:322
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In arch/x86/xen/p2m.c (ffffffff8101ee05)
Location: arch/x86/include/asm/paravirt.h:322
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034d51)
Location: arch/x86/include/asm/paravirt.h:322
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff810735de)
Location: arch/x86/include/asm/paravirt.h:322
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff826ed97f)
Location: arch/x86/include/asm/paravirt.h:322
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81078939)
Location: arch/x86/include/asm/paravirt.h:322
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In mm/memory.c (ffffffff8122de5e)
Location: arch/x86/include/asm/paravirt.h:322
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff819ebe47)
Location: arch/x86/include/asm/paravirt.h:322
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff81276ffa)
Location: arch/x86/include/asm/paravirt.h:322
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff8127ca55)
Location: arch/x86/include/asm/paravirt.h:322
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In arch/x86/xen/p2m.c (ffffffff8101e6b5)
Location: arch/x86/include/asm/paravirt.h:336
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035f31)
Location: arch/x86/include/asm/paravirt.h:336
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81a23c33)
Location: arch/x86/include/asm/paravirt.h:336
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff828a4511)
Location: arch/x86/include/asm/paravirt.h:336
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8107f128)
Location: arch/x86/include/asm/paravirt.h:336
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In mm/memory.c (ffffffff812414c0)
Location: arch/x86/include/asm/paravirt.h:336
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81a270b5)
Location: arch/x86/include/asm/paravirt.h:336
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff81288852)
Location: arch/x86/include/asm/paravirt.h:336
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812910fe)
Location: arch/x86/include/asm/paravirt.h:336
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In arch/x86/xen/p2m.c (ffffffff81020222)
Location: arch/x86/include/asm/paravirt.h:336
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038091)
Location: arch/x86/include/asm/paravirt.h:336
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81a93f61)
Location: arch/x86/include/asm/paravirt.h:336
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff828bc9e3)
Location: arch/x86/include/asm/paravirt.h:336
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81082936)
Location: arch/x86/include/asm/paravirt.h:336
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In mm/memory.c (ffffffff81253632)
Location: arch/x86/include/asm/paravirt.h:336
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81a97959)
Location: arch/x86/include/asm/paravirt.h:336
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff812a348f)
Location: arch/x86/include/asm/paravirt.h:336
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812abbff)
Location: arch/x86/include/asm/paravirt.h:336
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In arch/x86/xen/p2m.c (ffffffff81020b82)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038861)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81acb841)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2e8a)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81083a06)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In mm/memory.c (ffffffff81261b92)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81acf227)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff812b498f)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812bd440)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81022e4a)
Location: arch/x86/include/asm/paravirt.h:338
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b323)
Location: arch/x86/include/asm/paravirt.h:338
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81bc46ab)
Location: arch/x86/include/asm/paravirt.h:338
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce6282)
Location: arch/x86/include/asm/paravirt.h:338
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d848)
Location: arch/x86/include/asm/paravirt.h:338
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In mm/memory.c (ffffffff8128e0ec)
Location: arch/x86/include/asm/paravirt.h:338
Inline: True
Inline callers:
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7be4)
Location: arch/x86/include/asm/paravirt.h:338
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff812e9f1c)
Location: arch/x86/include/asm/paravirt.h:338
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff812f2b54)
Location: arch/x86/include/asm/paravirt.h:338
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81022d90-ffffffff81022da7: paravirt_alloc_pte.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8102341a)
Location: arch/x86/include/asm/paravirt.h:334
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103bb33)
Location: arch/x86/include/asm/paravirt.h:334
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81c3d5a4)
Location: arch/x86/include/asm/paravirt.h:334
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff82fd3c08)
Location: arch/x86/include/asm/paravirt.h:334
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d718)
Location: arch/x86/include/asm/paravirt.h:334
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In mm/memory.c (ffffffff81298d8c)
Location: arch/x86/include/asm/paravirt.h:334
Inline: True
Inline callers:
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81c4090f)
Location: arch/x86/include/asm/paravirt.h:334
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff812f50fc)
Location: arch/x86/include/asm/paravirt.h:334
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff812fd17e)
Location: arch/x86/include/asm/paravirt.h:334
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81023360-ffffffff81023377: paravirt_alloc_pte.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff810258ca)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d4d4)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81c2f9af)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff81bcb765)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e2d8)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In mm/filemap.c (ffffffff8125c368)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - mm/filemap.c:pmd_populate
```
```
In mm/memory.c (ffffffff812a1bf1)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81bdad35)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
```
```
In mm/huge_memory.c (ffffffff812fa2e7)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff81303ef6)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81025660-ffffffff81025677: paravirt_alloc_pte.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81029dda)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042f32)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81d4e0fe)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff81ca0ed3)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109dd85)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In mm/filemap.c (ffffffff81298218)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - mm/filemap.c:pmd_populate
```
```
In mm/memory.c (ffffffff812e2bc1)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/mremap.c (ffffffff812f2064)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8132bde8)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
```
```
In mm/huge_memory.c (ffffffff81344147)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff8134dc37)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81029b70-ffffffff81029b87: paravirt_alloc_pte.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8102e8b6)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104ae6b)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/mm/init_64.c (ffffffff81f1dea7)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff81e50480)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b16d2)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In mm/percpu.c (ffffffff81e6c863)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
```
```
In mm/memory.c (ffffffff8133fdec)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:pmd_install
```
```
In mm/mremap.c (ffffffff81355dd1)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8139bbb8)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
```
```
In mm/huge_memory.c (ffffffff813b9672)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff813c6e83)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8102e4a0-ffffffff8102e4d0: paravirt_alloc_pte.constprop.0 (STB_LOCAL)
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
In arch/x86/xen/p2m.c (ffffffff810358b8)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81056b32)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/mm/init_64.c (ffffffff820c6239)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff810c5839)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cbe10)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In mm/percpu.c (ffffffff8139af68)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
```
```
In mm/memory.c (ffffffff813b7d3b)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:pmd_install
```
```
In mm/mremap.c (ffffffff813d03f2)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
```
```
In mm/hugetlb_vmemmap.c (ffffffff81413468)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8141bb58)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143b95b)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff81446e68)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
Inline callers:
  - mm/khugepaged.c:pmd_populate
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
In arch/x86/xen/p2m.c (ffffffff81035838)
Location: arch/x86/include/asm/paravirt.h:352
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81057b00)
Location: arch/x86/include/asm/paravirt.h:352
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/mm/init_64.c (ffffffff8214a287)
Location: arch/x86/include/asm/paravirt.h:352
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff810c8f29)
Location: arch/x86/include/asm/paravirt.h:352
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cf450)
Location: arch/x86/include/asm/paravirt.h:352
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In mm/percpu.c (ffffffff813ce028)
Location: arch/x86/include/asm/paravirt.h:352
Inline: True
```
```
In mm/memory.c (ffffffff813ecaab)
Location: arch/x86/include/asm/paravirt.h:352
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:pmd_install
```
```
In mm/mremap.c (ffffffff81405162)
Location: arch/x86/include/asm/paravirt.h:352
Inline: True
```
```
In mm/hugetlb_vmemmap.c (ffffffff814469c8)
Location: arch/x86/include/asm/paravirt.h:352
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8144f158)
Location: arch/x86/include/asm/paravirt.h:352
Inline: True
```
```
In mm/huge_memory.c (ffffffff814712bd)
Location: arch/x86/include/asm/paravirt.h:352
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff8147c5e8)
Location: arch/x86/include/asm/paravirt.h:352
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
In arch/x86/xen/p2m.c (ffffffff8103bd98)
Location: arch/x86/include/asm/paravirt.h:354
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105eda0)
Location: arch/x86/include/asm/paravirt.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/mm/init_64.c (ffffffff8222cd37)
Location: arch/x86/include/asm/paravirt.h:354
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff838f04cf)
Location: arch/x86/include/asm/paravirt.h:354
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d7b30)
Location: arch/x86/include/asm/paravirt.h:354
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In mm/percpu.c (ffffffff813f8998)
Location: arch/x86/include/asm/paravirt.h:354
Inline: True
```
```
In mm/memory.c (ffffffff81417fbb)
Location: arch/x86/include/asm/paravirt.h:354
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:pmd_install
```
```
In mm/mremap.c (ffffffff81431642)
Location: arch/x86/include/asm/paravirt.h:354
Inline: True
```
```
In mm/hugetlb_vmemmap.c (ffffffff814804f8)
Location: arch/x86/include/asm/paravirt.h:354
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81488d18)
Location: arch/x86/include/asm/paravirt.h:354
Inline: True
```
```
In mm/huge_memory.c (ffffffff814a0e4d)
Location: arch/x86/include/asm/paravirt.h:354
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff814aba38)
Location: arch/x86/include/asm/paravirt.h:354
Inline: True
Inline callers:
  - mm/khugepaged.c:pmd_populate
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
In arch/x86/xen/p2m.c (ffffffff81020ce2)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810389c1)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81a6a6b1)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff828ade60)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81082a06)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In mm/memory.c (ffffffff8125a1e2)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e097)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff812acf6f)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b5a20)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In arch/x86/kernel/espfix_64.c (0)
Location: arch/x86/include/asm/pgalloc.h:19
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgalloc.h:19
Inline: True
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgalloc.h:19
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgalloc.h:19
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgalloc.h:19
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/x86/include/asm/pgalloc.h:19
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgalloc.h:19
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgalloc.h:19
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
In arch/x86/xen/p2m.c (ffffffff81020b42)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038821)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81ad6ac1)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0d5f)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff810829b6)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In mm/memory.c (ffffffff81257f82)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81ada4a7)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff812aad7f)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b3830)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In arch/x86/xen/p2m.c (ffffffff81020d92)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81039821)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81ae2f81)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff828c3eaa)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81084ad6)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In mm/memory.c (ffffffff8126796e)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81ae695d)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff812bb0cf)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812c3c4e)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
</details>
</li>
</ul>

## Differences
