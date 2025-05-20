# Function: <code>p4d_populate</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff820aac7b)
Location: arch/x86/include/asm/pgalloc.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff8106bed1)
Location: arch/x86/include/asm/pgalloc.h:126
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
```
In mm/memory.c (ffffffff811f542f)
Location: arch/x86/include/asm/pgalloc.h:126
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff819056da)
Location: arch/x86/include/asm/pgalloc.h:126
Inline: True
```
**Symbols:**

```
ffffffff8106bb60-ffffffff8106bbec: p4d_populate.constprop.14 (STB_LOCAL)
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
In arch/x86/kernel/espfix_64.c (ffffffff826b13f3)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff810708f1)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
```
In mm/memory.c (ffffffff8120e2f8)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff8198f744)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
```
**Symbols:**

```
ffffffff81070360-ffffffff810703f8: p4d_populate.constprop.15 (STB_LOCAL)
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
In arch/x86/kernel/espfix_64.c (ffffffff826daa9a)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff810736f2)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
```
In mm/memory.c (ffffffff8122ece7)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff819ebfaa)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
**Symbols:**

```
ffffffff81073390-ffffffff8107341d: p4d_populate.constprop.15 (STB_LOCAL)
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
In arch/x86/kernel/espfix_64.c (ffffffff82890e7c)
Location: arch/x86/include/asm/pgalloc.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff81079762)
Location: arch/x86/include/asm/pgalloc.h:151
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff81241777)
Location: arch/x86/include/asm/pgalloc.h:151
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81a27218)
Location: arch/x86/include/asm/pgalloc.h:151
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
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
In arch/x86/kernel/espfix_64.c (ffffffff828a83e7)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff81a94c36)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff812540f7)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81a97ac6)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
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
In arch/x86/kernel/espfix_64.c (ffffffff828ab447)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff81acc516)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff81262657)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81acf394)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
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
In arch/x86/kernel/espfix_64.c (ffffffff82cd0760)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff81084cb2)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff81292557)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7d93)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
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
In arch/x86/kernel/espfix_64.c (ffffffff82fbc5a0)
Location: arch/x86/include/asm/pgalloc.h:115
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff810861c2)
Location: arch/x86/include/asm/pgalloc.h:115
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff8129ce07)
Location: arch/x86/include/asm/pgalloc.h:115
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81c40abe)
Location: arch/x86/include/asm/pgalloc.h:115
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
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
In arch/x86/kernel/espfix_64.c (ffffffff81bc602b)
Location: arch/x86/include/asm/pgalloc.h:115
Inline: True
Direct callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff81086cd2)
Location: arch/x86/include/asm/pgalloc.h:115
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff812a24e7)
Location: arch/x86/include/asm/pgalloc.h:115
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81c32a20)
Location: arch/x86/include/asm/pgalloc.h:115
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
**Symbols:**

```
ffffffff81bc602b-ffffffff81bc60bd: p4d_populate.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/espfix_64.c (ffffffff81c98ffc)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Direct callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff81095fe2)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff812e3857)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81d513f0)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
**Symbols:**

```
ffffffff81c98ffc-ffffffff81c9908e: p4d_populate.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/espfix_64.c (ffffffff81e485c9)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Direct callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff810a8869)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/percpu.c (ffffffff8348b8f6)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff81344bf9)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81f2167d)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
**Symbols:**

```
ffffffff81e485c9-ffffffff81e48672: p4d_populate.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/espfix_64.c (ffffffff81056670)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Direct callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff820c71d6)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/percpu.c (ffffffff83ebc807)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff813bce19)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff820cb81c)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
**Symbols:**

```
ffffffff81056670-ffffffff81056719: p4d_populate.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/espfix_64.c (ffffffff81057640)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Direct callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff8214b242)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/percpu.c (ffffffff836e4e87)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff813f1b4f)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff8214faac)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
**Symbols:**

```
ffffffff81057640-ffffffff810576e9: p4d_populate.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void p4d_populate(struct mm_struct *mm, p4d_t *p4d, pud_t *pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff838c6e3c)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff8222dcf2)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/percpu.c (ffffffff813f90b0)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff814150a0)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: False
Direct callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81488e20)
Location: arch/x86/include/asm/pgalloc.h:113
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
**Symbols:**

```
ffffffff813f90b0-ffffffff813f9158: p4d_populate.constprop.0 (STB_LOCAL)
ffffffff814150a0-ffffffff81415140: p4d_populate (STB_LOCAL)
ffffffff81488e20-ffffffff81488ec8: p4d_populate.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/espfix_64.c (ffffffff82899459)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff81a6b386)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff8125aca7)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e204)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
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
In arch/x86/kernel/espfix_64.c (ffffffff82891754)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff81a27906)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff8124d09d)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a641)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
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
In arch/x86/kernel/espfix_64.c (ffffffff828ac439)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff81ad7796)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff81258a47)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81ada614)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
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
In arch/x86/kernel/espfix_64.c (ffffffff828ac457)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff81ae3c56)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff81268447)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81ae6aca)
Location: arch/x86/include/asm/pgalloc.h:138
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
