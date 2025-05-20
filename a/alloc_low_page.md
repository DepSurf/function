# Function: <code>alloc_low_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8181bd9d)
Location: arch/x86/mm/mm_internal.h:5
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff81896a47)
Location: arch/x86/mm/mm_internal.h:5
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/kaslr.c (ffffffff81896e49)
Location: arch/x86/mm/mm_internal.h:5
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
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
In arch/x86/mm/init_64.c (ffffffff818cb134)
Location: arch/x86/mm/mm_internal.h:5
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/kaslr.c (ffffffff818cb532)
Location: arch/x86/mm/mm_internal.h:5
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
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
In arch/x86/mm/init_64.c (ffffffff81902710)
Location: arch/x86/mm/mm_internal.h:5
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/kaslr.c (ffffffff81902b1d)
Location: arch/x86/mm/mm_internal.h:5
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
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
In arch/x86/mm/init_64.c (ffffffff8198c686)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/kaslr.c (ffffffff8198ca51)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
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
In arch/x86/mm/init_64.c (ffffffff819e8f55)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/kaslr.c (ffffffff819e9369)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
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
In arch/x86/mm/init_64.c (ffffffff81a247d8)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/kaslr.c (ffffffff81a24caf)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
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
In arch/x86/mm/init_64.c (ffffffff81a94b29)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/kaslr.c (ffffffff81a9507c)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
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
In arch/x86/mm/init_64.c (ffffffff81acc409)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/kaslr.c (ffffffff81acc95c)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
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
In arch/x86/mm/init_64.c (ffffffff81bc4f56)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/kaslr.c (ffffffff81bc5182)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
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
In arch/x86/mm/init_64.c (ffffffff81c3de2e)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/kaslr.c (ffffffff81c3e055)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
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
In arch/x86/mm/init_64.c (ffffffff81c30174)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/kaslr.c (ffffffff81c3039e)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
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
In arch/x86/mm/init_64.c (ffffffff81d4e900)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/kaslr.c (ffffffff81d4eb3c)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
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
In arch/x86/mm/init_64.c (ffffffff81f1e6dc)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/kaslr.c (ffffffff81f1ea35)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
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
In arch/x86/mm/init_64.c (ffffffff820c6f1e)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/kaslr.c (ffffffff820c7856)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
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
In arch/x86/mm/init_64.c (ffffffff8214af8e)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/kaslr.c (ffffffff8214b8e6)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
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
In arch/x86/mm/init_64.c (ffffffff8222da3e)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/kaslr.c (ffffffff8222e396)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
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
In arch/x86/mm/init_64.c (ffffffff81a6b279)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/kaslr.c (ffffffff81a6b7cc)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
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
In arch/x86/mm/init_64.c (ffffffff81a27846)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/kaslr.c (ffffffff81a27d1b)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
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
In arch/x86/mm/init_64.c (ffffffff81ad7689)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/kaslr.c (ffffffff81ad7bdc)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
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
In arch/x86/mm/init_64.c (ffffffff81ae3b49)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/kaslr.c (ffffffff81ae409c)
Location: arch/x86/mm/mm_internal.h:6
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
</details>
</li>
</ul>

## Differences
