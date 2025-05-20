# Function: <code>pmd_populate_kernel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81068ee0)
Location: arch/x86/include/asm/pgalloc.h:62
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/ioremap.c (ffffffff81f77e6b)
Location: arch/x86/include/asm/pgalloc.h:62
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In mm/memory.c (ffffffff811bd3dd)
Location: arch/x86/include/asm/pgalloc.h:62
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff8181f33f)
Location: arch/x86/include/asm/pgalloc.h:62
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff81068ee0-ffffffff81068f56: pmd_populate_kernel.constprop.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81068ec0)
Location: arch/x86/include/asm/pgalloc.h:62
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/ioremap.c (ffffffff81fa05e0)
Location: arch/x86/include/asm/pgalloc.h:62
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In mm/memory.c (ffffffff811d8160)
Location: arch/x86/include/asm/pgalloc.h:62
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff81899a03)
Location: arch/x86/include/asm/pgalloc.h:62
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff81068c00-ffffffff81068c91: pmd_populate_kernel.constprop.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106cb10)
Location: arch/x86/include/asm/pgalloc.h:62
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/ioremap.c (ffffffff81fdbb51)
Location: arch/x86/include/asm/pgalloc.h:62
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In mm/memory.c (ffffffff811e7e30)
Location: arch/x86/include/asm/pgalloc.h:62
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff818ce0b5)
Location: arch/x86/include/asm/pgalloc.h:62
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff8106c850-ffffffff8106c8e1: pmd_populate_kernel.constprop.8 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff8106bd95)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/ioremap.c (ffffffff820bcb2b)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In mm/memory.c (ffffffff811f2fd0)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff8190554a)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff8106bc80-ffffffff8106bd0c: pmd_populate_kernel.constprop.16 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81070785)
Location: arch/x86/include/asm/pgalloc.h:76
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/ioremap.c (ffffffff826c36fd)
Location: arch/x86/include/asm/pgalloc.h:76
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In mm/memory.c (ffffffff8120a140)
Location: arch/x86/include/asm/pgalloc.h:76
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff8198f597)
Location: arch/x86/include/asm/pgalloc.h:76
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff810704a0-ffffffff81070538: pmd_populate_kernel.constprop.17 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff810735c7)
Location: arch/x86/include/asm/pgalloc.h:76
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/ioremap.c (ffffffff826ed96b)
Location: arch/x86/include/asm/pgalloc.h:76
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In mm/memory.c (ffffffff8122af4f)
Location: arch/x86/include/asm/pgalloc.h:76
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff819ebe1d)
Location: arch/x86/include/asm/pgalloc.h:76
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff810734b0-ffffffff8107353d: pmd_populate_kernel.constprop.17 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81079637)
Location: arch/x86/include/asm/pgalloc.h:76
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff828a44fd)
Location: arch/x86/include/asm/pgalloc.h:76
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In mm/memory.c (ffffffff8123e30f)
Location: arch/x86/include/asm/pgalloc.h:76
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff81a2708b)
Location: arch/x86/include/asm/pgalloc.h:76
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
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
In arch/x86/mm/init_64.c (ffffffff8107d367)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828bc9cc)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In mm/memory.c (ffffffff812501b2)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff81a9792f)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff8107d0d0-ffffffff8107d15d: pmd_populate_kernel.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff8107e3f7)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2e73)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In mm/memory.c (ffffffff8125e762)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff81acf1fd)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff8107e160-ffffffff8107e1ed: pmd_populate_kernel.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81bc4754)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce626b)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In mm/memory.c (ffffffff8128e782)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7bba)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
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
In arch/x86/mm/init_64.c (ffffffff81c3d64d)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff82fd3bf1)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In mm/memory.c (ffffffff812993a2)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff81c408e5)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
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
In arch/x86/mm/init_64.c (ffffffff81086f78)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/ioremap.c (ffffffff81bcb72c)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In mm/memory.c (ffffffff8129e632)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff81bdacfd)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff81bcb0ae-ffffffff81bcb13f: pmd_populate_kernel.constprop.0 (STB_LOCAL)
ffffffff81bcb72c-ffffffff81bcb7be: pmd_populate_kernel.constprop.0 (STB_LOCAL)
ffffffff81bdacfd-ffffffff81bdad8e: pmd_populate_kernel.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81096288)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/ioremap.c (ffffffff81ca0e9a)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In mm/memory.c (ffffffff812df872)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff8132bdb0)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_remap_range
  - mm/sparse-vmemmap.c:vmemmap_remap_range
```
**Symbols:**

```
ffffffff81ca064a-ffffffff81ca06db: pmd_populate_kernel.constprop.0 (STB_LOCAL)
ffffffff81ca0e9a-ffffffff81ca0f2c: pmd_populate_kernel.constprop.0 (STB_LOCAL)
ffffffff8132bdb0-ffffffff8132be41: pmd_populate_kernel.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff810a8b2f)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/ioremap.c (ffffffff81e50447)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In mm/percpu.c (ffffffff81e6c82b)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff8133fdc3)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff8139bb80)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd
  - mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd
```
**Symbols:**

```
ffffffff810a8360-ffffffff810a8408: pmd_populate_kernel.constprop.0 (STB_LOCAL)
ffffffff81e50447-ffffffff81e504f0: pmd_populate_kernel.constprop.0 (STB_LOCAL)
ffffffff81e6c82b-ffffffff81e6c8d3: pmd_populate_kernel.constprop.0 (STB_LOCAL)
ffffffff8139bb80-ffffffff8139bc28: pmd_populate_kernel.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff820c64aa)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff810c5800)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In mm/percpu.c (ffffffff8139af30)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff813b7d12)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/hugetlb_vmemmap.c (ffffffff81413430)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Direct callers:
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff8141bb20)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff810c5800-ffffffff810c58a9: pmd_populate_kernel.constprop.0 (STB_LOCAL)
ffffffff8139af30-ffffffff8139afd8: pmd_populate_kernel.constprop.0 (STB_LOCAL)
ffffffff81413430-ffffffff814134d8: pmd_populate_kernel.constprop.0 (STB_LOCAL)
ffffffff8141bb20-ffffffff8141bbc8: pmd_populate_kernel.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8214a4f4)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff810c8ef0)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In mm/percpu.c (ffffffff813cdff0)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff813eca82)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/hugetlb_vmemmap.c (ffffffff81446990)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Direct callers:
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff8144f120)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff810c8ef0-ffffffff810c8f99: pmd_populate_kernel.constprop.0 (STB_LOCAL)
ffffffff813cdff0-ffffffff813ce098: pmd_populate_kernel.constprop.0 (STB_LOCAL)
ffffffff81446990-ffffffff81446a38: pmd_populate_kernel.constprop.0 (STB_LOCAL)
ffffffff8144f120-ffffffff8144f1c8: pmd_populate_kernel.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8222cfa4)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff838f04b8)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In mm/percpu.c (ffffffff813f8960)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff81417fa1)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/hugetlb_vmemmap.c (ffffffff814804c0)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Direct callers:
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff81488ce0)
Location: arch/x86/include/asm/pgalloc.h:64
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff813f8960-ffffffff813f8a08: pmd_populate_kernel.constprop.0 (STB_LOCAL)
ffffffff814804c0-ffffffff81480568: pmd_populate_kernel.constprop.0 (STB_LOCAL)
ffffffff81488ce0-ffffffff81488d88: pmd_populate_kernel.constprop.0 (STB_LOCAL)
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
In mm/memory.c (ffff8000102f6164)
Location: arch/arm64/include/asm/pgalloc.h:106
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffff800010da0e5c)
Location: arch/arm64/include/asm/pgalloc.h:106
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
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
In arch/arm/mm/mmu.c (c1508eb0)
Location: arch/arm/include/asm/pgalloc.h:129
Inline: True
Inline callers:
  - arch/arm/mm/mmu.c:early_fixmap_init
```
```
In mm/memory.c (c051813c)
Location: arch/arm/include/asm/pgalloc.h:129
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
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
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000094b04)
Location: arch/powerpc/include/asm/book3s/64/pgalloc.h:152
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page
```
```
In mm/memory.c (c0000000003bdad4)
Location: arch/powerpc/include/asm/book3s/64/pgalloc.h:152
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (c000000000eedd0c)
Location: arch/powerpc/include/asm/book3s/64/pgalloc.h:152
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
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
In mm/memory.c (ffffffe00020735a)
Location: arch/riscv/include/asm/pgalloc.h:15
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffe00004904c)
Location: arch/riscv/include/asm/pgalloc.h:15
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
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
In arch/x86/mm/init_64.c (ffffffff8107d3f7)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828ade49)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In mm/memory.c (ffffffff81256db2)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e06d)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff8107d160-ffffffff8107d1ed: pmd_populate_kernel.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81a26bb7)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff828a60ae)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In mm/memory.c (ffffffff8124974c)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a568)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
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
In arch/x86/mm/init_64.c (ffffffff8107d3a7)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0d48)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In mm/memory.c (ffffffff81254b52)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff81ada47d)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff8107d110-ffffffff8107d19d: pmd_populate_kernel.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff8107f497)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828c3e93)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In mm/memory.c (ffffffff812645d2)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/sparse-vmemmap.c (ffffffff81ae6933)
Location: arch/x86/include/asm/pgalloc.h:63
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
**Symbols:**

```
ffffffff8107f200-ffffffff8107f28d: pmd_populate_kernel.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
