# Function: <code>paravirt_alloc_pud</code>

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
In arch/x86/kernel/espfix_64.c (ffffffff81f672b3)
Location: arch/x86/include/asm/paravirt.h:370
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff8107d56d)
Location: arch/x86/include/asm/paravirt.h:370
Inline: True
```
```
In mm/memory.c (ffffffff811bea22)
Location: arch/x86/include/asm/paravirt.h:370
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff8181f4ce)
Location: arch/x86/include/asm/paravirt.h:370
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
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
In arch/x86/kernel/espfix_64.c (ffffffff81f8f169)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff8107f052)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81fa37e2)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/memory.c (ffffffff811da850)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81899bbf)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
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
In arch/x86/kernel/espfix_64.c (ffffffff81fca4f8)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff81083708)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81fdf12c)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/memory.c (ffffffff811ea3c0)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff818ce271)
Location: arch/x86/include/asm/paravirt.h:351
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
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
In arch/x86/kernel/espfix_64.c (ffffffff820aac9e)
Location: arch/x86/include/asm/paravirt.h:349
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff8106beee)
Location: arch/x86/include/asm/paravirt.h:349
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff811f5440)
Location: arch/x86/include/asm/paravirt.h:349
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff819056fa)
Location: arch/x86/include/asm/paravirt.h:349
Inline: True
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
In arch/x86/kernel/espfix_64.c (ffffffff826b1416)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff8107090e)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff8120e309)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff8198f764)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
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
In arch/x86/kernel/espfix_64.c (ffffffff826daacf)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff81073709)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff8122ed06)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff819ebfd0)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
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
In arch/x86/kernel/espfix_64.c (ffffffff82890eb1)
Location: arch/x86/include/asm/paravirt.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff81a24869)
Location: arch/x86/include/asm/paravirt.h:355
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff81241796)
Location: arch/x86/include/asm/paravirt.h:355
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81a2723e)
Location: arch/x86/include/asm/paravirt.h:355
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
In arch/x86/kernel/espfix_64.c (ffffffff828a841c)
Location: arch/x86/include/asm/paravirt.h:355
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff81a94bc7)
Location: arch/x86/include/asm/paravirt.h:355
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff81254116)
Location: arch/x86/include/asm/paravirt.h:355
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81a97aec)
Location: arch/x86/include/asm/paravirt.h:355
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
In arch/x86/kernel/espfix_64.c (ffffffff828ab47c)
Location: arch/x86/include/asm/paravirt.h:343
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff81acc4a7)
Location: arch/x86/include/asm/paravirt.h:343
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff81262676)
Location: arch/x86/include/asm/paravirt.h:343
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81acf3ba)
Location: arch/x86/include/asm/paravirt.h:343
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
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
In arch/x86/kernel/espfix_64.c (ffffffff82cd078d)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff81084cc9)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff81292576)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7db9)
Location: arch/x86/include/asm/paravirt.h:357
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
**Symbols:**

```
ffffffff81086280-ffffffff81086297: paravirt_alloc_pud.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/espfix_64.c (ffffffff82fbc5cd)
Location: arch/x86/include/asm/paravirt.h:353
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff810861d9)
Location: arch/x86/include/asm/paravirt.h:353
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff8129ce26)
Location: arch/x86/include/asm/paravirt.h:353
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81c40ae4)
Location: arch/x86/include/asm/paravirt.h:353
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
**Symbols:**

```
ffffffff81bd8bc4-ffffffff81bd8bdb: paravirt_alloc_pud.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/espfix_64.c (ffffffff81bc6064)
Location: arch/x86/include/asm/paravirt.h:370
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81086ce9)
Location: arch/x86/include/asm/paravirt.h:370
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff812a2506)
Location: arch/x86/include/asm/paravirt.h:370
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81c32a46)
Location: arch/x86/include/asm/paravirt.h:370
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
**Symbols:**

```
ffffffff81bcaa7a-ffffffff81bcaa91: paravirt_alloc_pud.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/espfix_64.c (ffffffff81c99035)
Location: arch/x86/include/asm/paravirt.h:370
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81095ff9)
Location: arch/x86/include/asm/paravirt.h:370
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff812e3876)
Location: arch/x86/include/asm/paravirt.h:370
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81d51416)
Location: arch/x86/include/asm/paravirt.h:370
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
**Symbols:**

```
ffffffff81c9ff62-ffffffff81c9ff79: paravirt_alloc_pud.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/espfix_64.c (ffffffff81e48602)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff810a8880)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/percpu.c (ffffffff8348b923)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff81344c18)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81f216aa)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
**Symbols:**

```
ffffffff810a7f80-ffffffff810a7fb0: paravirt_alloc_pud.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/espfix_64.c (ffffffff810566a9)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff820c7126)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/percpu.c (ffffffff83ebc829)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff813bce38)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff820cb842)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
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
In arch/x86/kernel/espfix_64.c (ffffffff81057679)
Location: arch/x86/include/asm/paravirt.h:371
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff8214b198)
Location: arch/x86/include/asm/paravirt.h:371
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/percpu.c (ffffffff836e4ea9)
Location: arch/x86/include/asm/paravirt.h:371
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff813f1b6e)
Location: arch/x86/include/asm/paravirt.h:371
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff8214fad2)
Location: arch/x86/include/asm/paravirt.h:371
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
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
In arch/x86/kernel/espfix_64.c (ffffffff838c6e5f)
Location: arch/x86/include/asm/paravirt.h:373
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff8222dc48)
Location: arch/x86/include/asm/paravirt.h:373
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/percpu.c (ffffffff813f90e8)
Location: arch/x86/include/asm/paravirt.h:373
Inline: True
```
```
In mm/memory.c (ffffffff814150d8)
Location: arch/x86/include/asm/paravirt.h:373
Inline: True
Inline callers:
  - mm/memory.c:p4d_populate
```
```
In mm/sparse-vmemmap.c (ffffffff81488e58)
Location: arch/x86/include/asm/paravirt.h:373
Inline: True
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
In arch/x86/kernel/espfix_64.c (ffffffff8289948e)
Location: arch/x86/include/asm/paravirt.h:343
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff81a6b317)
Location: arch/x86/include/asm/paravirt.h:343
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff8125acc6)
Location: arch/x86/include/asm/paravirt.h:343
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e22a)
Location: arch/x86/include/asm/paravirt.h:343
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
In arch/x86/kernel/espfix_64.c (0)
Location: arch/x86/include/asm/pgalloc.h:23
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgalloc.h:23
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgalloc.h:23
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/x86/include/asm/pgalloc.h:23
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
In arch/x86/kernel/espfix_64.c (ffffffff828ac46e)
Location: arch/x86/include/asm/paravirt.h:343
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff81ad7727)
Location: arch/x86/include/asm/paravirt.h:343
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff81258a66)
Location: arch/x86/include/asm/paravirt.h:343
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81ada63a)
Location: arch/x86/include/asm/paravirt.h:343
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
In arch/x86/kernel/espfix_64.c (ffffffff828ac48c)
Location: arch/x86/include/asm/paravirt.h:343
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/mm/init_64.c (ffffffff81ae3be7)
Location: arch/x86/include/asm/paravirt.h:343
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
```
```
In mm/memory.c (ffffffff81268466)
Location: arch/x86/include/asm/paravirt.h:343
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81ae6af0)
Location: arch/x86/include/asm/paravirt.h:343
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
</details>
</li>
</ul>

## Differences
