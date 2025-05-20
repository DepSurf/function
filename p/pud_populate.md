# Function: <code>pud_populate</code>

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
In arch/x86/mm/init_64.c (ffffffff81068e60)
Location: arch/x86/include/asm/pgalloc.h:112
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In mm/memory.c (ffffffff811beb5b)
Location: arch/x86/include/asm/pgalloc.h:112
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff811de5de)
Location: arch/x86/include/asm/pgalloc.h:112
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8181f408)
Location: arch/x86/include/asm/pgalloc.h:112
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
**Symbols:**

```
ffffffff81068e60-ffffffff81068ed6: pud_populate.constprop.6 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81069010)
Location: arch/x86/include/asm/pgalloc.h:116
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In mm/memory.c (ffffffff811da9bd)
Location: arch/x86/include/asm/pgalloc.h:116
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff811fc9ea)
Location: arch/x86/include/asm/pgalloc.h:116
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81899ae4)
Location: arch/x86/include/asm/pgalloc.h:116
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
**Symbols:**

```
ffffffff81068b60-ffffffff81068bf1: pud_populate.constprop.7 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff8106cc60)
Location: arch/x86/include/asm/pgalloc.h:116
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In mm/memory.c (ffffffff811ea52a)
Location: arch/x86/include/asm/pgalloc.h:116
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff8120d4ce)
Location: arch/x86/include/asm/pgalloc.h:116
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff818ce196)
Location: arch/x86/include/asm/pgalloc.h:116
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
**Symbols:**

```
ffffffff8106c7b0-ffffffff8106c841: pud_populate.constprop.7 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff8106c025)
Location: arch/x86/include/asm/pgalloc.h:118
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In mm/memory.c (ffffffff811f5581)
Location: arch/x86/include/asm/pgalloc.h:118
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff812193a4)
Location: arch/x86/include/asm/pgalloc.h:118
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8190562b)
Location: arch/x86/include/asm/pgalloc.h:118
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
**Symbols:**

```
ffffffff8106bbf0-ffffffff8106bc7c: pud_populate.constprop.15 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81070a65)
Location: arch/x86/include/asm/pgalloc.h:130
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In mm/memory.c (ffffffff8120e460)
Location: arch/x86/include/asm/pgalloc.h:130
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff812343a0)
Location: arch/x86/include/asm/pgalloc.h:130
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8198f68b)
Location: arch/x86/include/asm/pgalloc.h:130
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
**Symbols:**

```
ffffffff81070400-ffffffff81070498: pud_populate.constprop.16 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81073837)
Location: arch/x86/include/asm/pgalloc.h:130
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In mm/memory.c (ffffffff8122ee47)
Location: arch/x86/include/asm/pgalloc.h:130
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff812572f9)
Location: arch/x86/include/asm/pgalloc.h:130
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff819ebefd)
Location: arch/x86/include/asm/pgalloc.h:130
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
**Symbols:**

```
ffffffff81073420-ffffffff810734ad: pud_populate.constprop.16 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81079a87)
Location: arch/x86/include/asm/pgalloc.h:137
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:137
Inline: False
```
```
In mm/memory.c (ffffffff812418d7)
Location: arch/x86/include/asm/pgalloc.h:137
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff8126b971)
Location: arch/x86/include/asm/pgalloc.h:137
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a2716b)
Location: arch/x86/include/asm/pgalloc.h:137
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
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
In arch/x86/mm/init_64.c (ffffffff8107d7a7)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: False
```
```
In mm/memory.c (ffffffff81254256)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff81286c6e)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a97a16)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
**Symbols:**

```
ffffffff8107d040-ffffffff8107d0cd: pud_populate.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff8107e837)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: False
```
```
In mm/memory.c (ffffffff812627b6)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff8129686e)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81acf2e4)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
**Symbols:**

```
ffffffff8107e0d0-ffffffff8107e15d: pud_populate.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81bc4b0c)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: False
```
```
In mm/memory.c (ffffffff812926b6)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff812c9dbe)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7c9f)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
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
In arch/x86/mm/init_64.c (ffffffff81c3da05)
Location: arch/x86/include/asm/pgalloc.h:101
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:101
Inline: False
```
```
In mm/memory.c (ffffffff8129cf9d)
Location: arch/x86/include/asm/pgalloc.h:101
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff812d59fb)
Location: arch/x86/include/asm/pgalloc.h:101
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81c409ca)
Location: arch/x86/include/asm/pgalloc.h:101
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
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
In arch/x86/mm/init_64.c (ffffffff81086e18)
Location: arch/x86/include/asm/pgalloc.h:101
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:101
Inline: False
```
```
In mm/memory.c (ffffffff812a2680)
Location: arch/x86/include/asm/pgalloc.h:101
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff812dc6fc)
Location: arch/x86/include/asm/pgalloc.h:101
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81bdac6c)
Location: arch/x86/include/asm/pgalloc.h:101
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
**Symbols:**

```
ffffffff81bcb01d-ffffffff81bcb0ae: pud_populate.constprop.0 (STB_LOCAL)
ffffffff81bdac6c-ffffffff81bdacfd: pud_populate.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81096128)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: False
```
```
In mm/memory.c (ffffffff812e39f0)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/mremap.c (ffffffff812f1e35)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
```
```
In mm/hugetlb.c (ffffffff813238b4)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81cc0707)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
**Symbols:**

```
ffffffff81ca05b9-ffffffff81ca064a: pud_populate.constprop.0 (STB_LOCAL)
ffffffff81cc0707-ffffffff81cc0798: pud_populate.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff810a89bf)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: False
```
```
In mm/percpu.c (ffffffff81e6c783)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff81344d7d)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/mremap.c (ffffffff81355b83)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
```
```
In mm/hugetlb.c (ffffffff8139142d)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81e72b2d)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
**Symbols:**

```
ffffffff810a82b0-ffffffff810a8358: pud_populate.constprop.0 (STB_LOCAL)
ffffffff81e6c783-ffffffff81e6c82b: pud_populate.constprop.0 (STB_LOCAL)
ffffffff81e72b2d-ffffffff81e72bd5: pud_populate.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff820c68bc)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In mm/percpu.c (ffffffff8139ae70)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff813bcfad)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/mremap.c (ffffffff813d0193)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
```
```
In mm/hugetlb.c (ffffffff8140e450)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8141ba60)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
**Symbols:**

```
ffffffff8139ae70-ffffffff8139af18: pud_populate.constprop.0 (STB_LOCAL)
ffffffff8141ba60-ffffffff8141bb08: pud_populate.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff8214a904)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In mm/percpu.c (ffffffff813cdf30)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff813f1cf3)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/mremap.c (ffffffff81404ef6)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
```
```
In mm/hugetlb.c (ffffffff81441836)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8144f060)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
**Symbols:**

```
ffffffff813cdf30-ffffffff813cdfd8: pud_populate.constprop.0 (STB_LOCAL)
ffffffff8144f060-ffffffff8144f108: pud_populate.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void pud_populate(struct mm_struct *mm, pud_t *pud, pmd_t *pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8222d3b4)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In mm/percpu.c (ffffffff813f88a0)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff81414c00)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: False
Direct callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/mremap.c (ffffffff81431470)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff81474310)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: False
Direct callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81488c20)
Location: arch/x86/include/asm/pgalloc.h:99
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
**Symbols:**

```
ffffffff813f88a0-ffffffff813f8948: pud_populate.constprop.0 (STB_LOCAL)
ffffffff81414c00-ffffffff81414ca0: pud_populate (STB_LOCAL)
ffffffff81431470-ffffffff81431510: pud_populate (STB_LOCAL)
ffffffff81474310-ffffffff814743b0: pud_populate (STB_LOCAL)
ffffffff81488c20-ffffffff81488cc8: pud_populate.constprop.0 (STB_LOCAL)
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
In virt/kvm/arm/mmu.c (ffff8000100cb1f8)
Location: arch/arm64/include/asm/pgalloc.h:52
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:stage2_set_pte
```
```
In mm/memory.c (ffff8000102f9a44)
Location: arch/arm64/include/asm/pgalloc.h:52
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffff800010333794)
Location: arch/arm64/include/asm/pgalloc.h:52
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffff800010da0ef4)
Location: arch/arm64/include/asm/pgalloc.h:52
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000094d8c)
Location: arch/powerpc/include/asm/book3s/64/pgalloc.h:115
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page
```
```
In mm/memory.c (c0000000003c3970)
Location: arch/powerpc/include/asm/book3s/64/pgalloc.h:115
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/sparse-vmemmap.c (c000000000eedde8)
Location: arch/powerpc/include/asm/book3s/64/pgalloc.h:115
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
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
In mm/memory.c (ffffffe00020979a)
Location: arch/riscv/include/asm/pgalloc.h:32
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffe0002310d8)
Location: arch/riscv/include/asm/pgalloc.h:32
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffe0000490a4)
Location: arch/riscv/include/asm/pgalloc.h:32
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
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d837)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: False
```
```
In mm/memory.c (ffffffff8125ae06)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff8128ee4e)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e154)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
**Symbols:**

```
ffffffff8107d0d0-ffffffff8107d15d: pud_populate.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81a26ef5)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
```
```
In mm/memory.c (ffffffff8124d18d)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff81280aa3)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a5e6)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
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
In arch/x86/mm/init_64.c (ffffffff8107d7e7)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: False
```
```
In mm/memory.c (ffffffff81258ba6)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff8128cc5e)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81ada564)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
**Symbols:**

```
ffffffff8107d080-ffffffff8107d10d: pud_populate.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff8107f8d7)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: False
```
```
In mm/memory.c (ffffffff812685a6)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff8129ca2c)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81ae6a1a)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
**Symbols:**

```
ffffffff8107f170-ffffffff8107f1fd: pud_populate.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
