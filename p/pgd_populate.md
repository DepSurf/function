# Function: <code>pgd_populate</code>

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
In arch/x86/kernel/espfix_64.c (ffffffff81f672a9)
Location: arch/x86/include/asm/pgalloc.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff8107d541)
Location: arch/x86/include/asm/pgalloc.h:120
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
```
In mm/memory.c (ffffffff811bea05)
Location: arch/x86/include/asm/pgalloc.h:120
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff8181f4b1)
Location: arch/x86/include/asm/pgalloc.h:120
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
**Symbols:**

```
ffffffff8107d541-ffffffff8107d5bb: pgd_populate.constprop.5 (STB_LOCAL)
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
In arch/x86/kernel/espfix_64.c (ffffffff81f8f146)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff8107f019)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:populate_extra_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81fa37c2)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/memory.c (ffffffff811da83f)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81899b9f)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
**Symbols:**

```
ffffffff8107f019-ffffffff8107f0a0: pgd_populate.constprop.6 (STB_LOCAL)
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
In arch/x86/kernel/espfix_64.c (ffffffff81fca4d5)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff810836cf)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:populate_extra_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81fdf10c)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/memory.c (ffffffff811ea3af)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff818ce251)
Location: arch/x86/include/asm/pgalloc.h:124
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
**Symbols:**

```
ffffffff810836cf-ffffffff81083756: pgd_populate.constprop.6 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void pgd_populate(struct mm_struct *mm, pgd_t *pgd, p4d_t *p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81086080)
Location: arch/x86/include/asm/pgalloc.h:174
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:populate_extra_pmd
```
```
In mm/memory.c (ffffffff8128bfa0)
Location: arch/x86/include/asm/pgalloc.h:174
Inline: False
Direct callers:
  - mm/memory.c:__p4d_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff812d177e)
Location: arch/x86/include/asm/pgalloc.h:174
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
**Symbols:**

```
ffffffff81086080-ffffffff81086143: pgd_populate.part.0.constprop.0 (STB_LOCAL)
ffffffff81086143-ffffffff81086154: pgd_populate.constprop.0 (STB_LOCAL)
ffffffff8128bfa0-ffffffff8128c078: pgd_populate (STB_LOCAL)
ffffffff812d177e-ffffffff812d1854: pgd_populate.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void pgd_populate(struct mm_struct *mm, pgd_t *pgd, p4d_t *p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bd89c4)
Location: arch/x86/include/asm/pgalloc.h:136
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:populate_extra_pmd
```
```
In mm/memory.c (ffffffff81296ed0)
Location: arch/x86/include/asm/pgalloc.h:136
Inline: False
Direct callers:
  - mm/memory.c:__p4d_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81be8b69)
Location: arch/x86/include/asm/pgalloc.h:136
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
**Symbols:**

```
ffffffff81bd89c4-ffffffff81bd8a87: pgd_populate.part.0.constprop.0 (STB_LOCAL)
ffffffff81bd8a87-ffffffff81bd8a98: pgd_populate.constprop.0 (STB_LOCAL)
ffffffff81296ed0-ffffffff81296fa8: pgd_populate (STB_LOCAL)
ffffffff81be8b69-ffffffff81be8c3f: pgd_populate.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void pgd_populate(struct mm_struct *mm, pgd_t *pgd, p4d_t *p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bca874)
Location: arch/x86/include/asm/pgalloc.h:136
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:populate_extra_pmd
```
```
In mm/memory.c (ffffffff8129ccb0)
Location: arch/x86/include/asm/pgalloc.h:136
Inline: False
Direct callers:
  - mm/memory.c:__p4d_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81bdab95)
Location: arch/x86/include/asm/pgalloc.h:136
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
**Symbols:**

```
ffffffff81bca874-ffffffff81bca93c: pgd_populate.part.0.constprop.0 (STB_LOCAL)
ffffffff81bca93c-ffffffff81bca94d: pgd_populate.constprop.0 (STB_LOCAL)
ffffffff8129ccb0-ffffffff8129cd9e: pgd_populate (STB_LOCAL)
ffffffff81bdab95-ffffffff81bdac6c: pgd_populate.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void pgd_populate(struct mm_struct *mm, pgd_t *pgd, p4d_t *p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c9fd5c)
Location: arch/x86/include/asm/pgalloc.h:134
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:populate_extra_pmd
```
```
In mm/memory.c (ffffffff812dda90)
Location: arch/x86/include/asm/pgalloc.h:134
Inline: False
Direct callers:
  - mm/memory.c:__p4d_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81cc0630)
Location: arch/x86/include/asm/pgalloc.h:134
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
**Symbols:**

```
ffffffff81c9fd5c-ffffffff81c9fe24: pgd_populate.part.0.constprop.0 (STB_LOCAL)
ffffffff81c9fe24-ffffffff81c9fe35: pgd_populate.constprop.0 (STB_LOCAL)
ffffffff812dda90-ffffffff812ddb7e: pgd_populate (STB_LOCAL)
ffffffff81cc0630-ffffffff81cc0707: pgd_populate.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void pgd_populate(struct mm_struct *mm, pgd_t *pgd, p4d_t *p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81e4f475)
Location: arch/x86/include/asm/pgalloc.h:134
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:populate_extra_pmd
```
```
In mm/percpu.c (ffffffff81e6c694)
Location: arch/x86/include/asm/pgalloc.h:134
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff8133d5d0)
Location: arch/x86/include/asm/pgalloc.h:134
Inline: False
Direct callers:
  - mm/memory.c:__p4d_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81e72a3e)
Location: arch/x86/include/asm/pgalloc.h:134
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
**Symbols:**

```
ffffffff81e4f475-ffffffff81e4f547: pgd_populate.part.0.constprop.0 (STB_LOCAL)
ffffffff81e4f547-ffffffff81e4f568: pgd_populate.constprop.0 (STB_LOCAL)
ffffffff81e6c694-ffffffff81e6c783: pgd_populate.constprop.0 (STB_LOCAL)
ffffffff8133d5d0-ffffffff8133d6e1: pgd_populate (STB_LOCAL)
ffffffff81e72a3e-ffffffff81e72b2d: pgd_populate.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void pgd_populate(struct mm_struct *mm, pgd_t *pgd, p4d_t *p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff820c7209)
Location: arch/x86/include/asm/pgalloc.h:134
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:populate_extra_pmd
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:populate_extra_pmd
```
```
In mm/percpu.c (ffffffff8139d370)
Location: arch/x86/include/asm/pgalloc.h:134
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff813b5280)
Location: arch/x86/include/asm/pgalloc.h:134
Inline: False
Direct callers:
  - mm/memory.c:__p4d_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff8141bc60)
Location: arch/x86/include/asm/pgalloc.h:134
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
**Symbols:**

```
ffffffff810c1c50-ffffffff810c1d63: pgd_populate.part.0.constprop.0 (STB_LOCAL)
ffffffff8139d370-ffffffff8139d4a3: pgd_populate.constprop.0 (STB_LOCAL)
ffffffff813b5280-ffffffff813b53ac: pgd_populate (STB_LOCAL)
ffffffff8141bc60-ffffffff8141bd93: pgd_populate.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void pgd_populate(struct mm_struct *mm, pgd_t *pgd, p4d_t *p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8214b293)
Location: arch/x86/include/asm/pgalloc.h:134
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:populate_extra_pmd
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:populate_extra_pmd
```
```
In mm/percpu.c (ffffffff813d04a0)
Location: arch/x86/include/asm/pgalloc.h:134
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff813ea020)
Location: arch/x86/include/asm/pgalloc.h:134
Inline: False
Direct callers:
  - mm/memory.c:__p4d_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff8144f260)
Location: arch/x86/include/asm/pgalloc.h:134
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
**Symbols:**

```
ffffffff810c5330-ffffffff810c5443: pgd_populate.part.0.constprop.0 (STB_LOCAL)
ffffffff813d04a0-ffffffff813d05d3: pgd_populate.constprop.0 (STB_LOCAL)
ffffffff813ea020-ffffffff813ea14c: pgd_populate (STB_LOCAL)
ffffffff8144f260-ffffffff8144f393: pgd_populate.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void pgd_populate(struct mm_struct *mm, pgd_t *pgd, p4d_t *p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8222dd43)
Location: arch/x86/include/asm/pgalloc.h:134
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:populate_extra_pmd
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:populate_extra_pmd
```
```
In mm/percpu.c (ffffffff813fae60)
Location: arch/x86/include/asm/pgalloc.h:134
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff81415d30)
Location: arch/x86/include/asm/pgalloc.h:134
Inline: False
Direct callers:
  - mm/memory.c:__p4d_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81488ee0)
Location: arch/x86/include/asm/pgalloc.h:134
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
**Symbols:**

```
ffffffff810cd610-ffffffff810cd723: pgd_populate.part.0.constprop.0 (STB_LOCAL)
ffffffff813fae60-ffffffff813faf93: pgd_populate.constprop.0 (STB_LOCAL)
ffffffff81415d30-ffffffff81415e5c: pgd_populate (STB_LOCAL)
ffffffff81488ee0-ffffffff81489013: pgd_populate.constprop.0 (STB_LOCAL)
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
In virt/kvm/arm/mmu.c (ffff8000100ca168)
Location: arch/arm64/include/asm/pgalloc.h:81
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:stage2_get_pud
```
```
In mm/memory.c (ffff8000102f9890)
Location: arch/arm64/include/asm/pgalloc.h:81
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffff800010da0f8c)
Location: arch/arm64/include/asm/pgalloc.h:81
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
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
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000094d0c)
Location: arch/powerpc/include/asm/book3s/64/pgalloc.h:88
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page
```
```
In mm/memory.c (c0000000003c3828)
Location: arch/powerpc/include/asm/book3s/64/pgalloc.h:88
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (c000000000eeded0)
Location: arch/powerpc/include/asm/book3s/64/pgalloc.h:88
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
