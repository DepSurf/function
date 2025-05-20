# Function: <code>protval_4k_2_large</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff82ce5a82)
Location: arch/x86/include/asm/pgtable_types.h:487
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a1ea)
Location: arch/x86/include/asm/pgtable_types.h:487
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c4f5)
Location: arch/x86/include/asm/pgtable_types.h:487
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
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
In arch/x86/mm/init_64.c (ffffffff82fd340d)
Location: arch/x86/include/asm/pgtable_types.h:488
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a467)
Location: arch/x86/include/asm/pgtable_types.h:488
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c795)
Location: arch/x86/include/asm/pgtable_types.h:488
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
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
In arch/x86/mm/init_64.c (ffffffff831ddf04)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pgtable.c (ffffffff8108b0c7)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d1c7)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
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
In arch/x86/mm/init_64.c (ffffffff832c116c)
Location: arch/x86/include/asm/pgtable_types.h:484
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a667)
Location: arch/x86/include/asm/pgtable_types.h:484
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109ca4a)
Location: arch/x86/include/asm/pgtable_types.h:484
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
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
In arch/x86/mm/init_64.c (ffffffff834737b9)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pgtable.c (ffffffff810ad8e4)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b0254)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
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
In arch/x86/mm/init_64.c (ffffffff83e9b3ab)
Location: arch/x86/include/asm/pgtable_types.h:465
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7a94)
Location: arch/x86/include/asm/pgtable_types.h:465
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ca8ef)
Location: arch/x86/include/asm/pgtable_types.h:465
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
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
In arch/x86/mm/init_64.c (ffffffff836bee4b)
Location: arch/x86/include/asm/pgtable_types.h:466
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pgtable.c (ffffffff810cb1e7)
Location: arch/x86/include/asm/pgtable_types.h:466
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cdf2f)
Location: arch/x86/include/asm/pgtable_types.h:466
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
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
In arch/x86/mm/init_64.c (ffffffff838ef8eb)
Location: arch/x86/include/asm/pgtable_types.h:494
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pgtable.c (ffffffff810d3737)
Location: arch/x86/include/asm/pgtable_types.h:494
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d660f)
Location: arch/x86/include/asm/pgtable_types.h:494
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
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
