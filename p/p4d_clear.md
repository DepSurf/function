# Function: <code>p4d_clear</code>

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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f2afc)
Location: arch/x86/include/asm/paravirt.h:621
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81202ab5)
Location: arch/x86/include/asm/paravirt.h:621
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
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
In mm/memory.c (ffffffff81209d94)
Location: arch/x86/include/asm/paravirt.h:585
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8121b825)
Location: arch/x86/include/asm/paravirt.h:585
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
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
In mm/memory.c (ffffffff8122abc5)
Location: arch/x86/include/asm/paravirt.h:590
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8123d605)
Location: arch/x86/include/asm/paravirt.h:590
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
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
In mm/memory.c (ffffffff8123df84)
Location: arch/x86/include/asm/paravirt.h:569
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81251b55)
Location: arch/x86/include/asm/paravirt.h:569
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
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
In mm/memory.c (ffffffff8124e63d)
Location: arch/x86/include/asm/paravirt.h:570
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81263e26)
Location: arch/x86/include/asm/paravirt.h:570
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
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
In mm/memory.c (ffffffff8125cbad)
Location: arch/x86/include/asm/paravirt.h:558
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81272696)
Location: arch/x86/include/asm/paravirt.h:558
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
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
In arch/x86/mm/init_64.c (ffffffff81bc3cba)
Location: arch/x86/include/asm/paravirt.h:572
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pud_table
```
```
In mm/memory.c (ffffffff8128c4b6)
Location: arch/x86/include/asm/paravirt.h:572
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff812a3426)
Location: arch/x86/include/asm/paravirt.h:572
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
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
In arch/x86/mm/init_64.c (ffffffff81c3cbd6)
Location: arch/x86/include/asm/paravirt.h:494
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pud_table
```
```
In mm/memory.c (ffffffff81297424)
Location: arch/x86/include/asm/paravirt.h:494
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff812aed36)
Location: arch/x86/include/asm/paravirt.h:494
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
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
In arch/x86/mm/init_64.c (ffffffff81c2f673)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
```
```
In mm/memory.c (ffffffff8129d285)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff812b4266)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
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
In arch/x86/mm/init_64.c (ffffffff81d4dd74)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
```
```
In mm/memory.c (ffffffff812de6ae)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff812f5e46)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
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
In arch/x86/mm/init_64.c (ffffffff81f1daf1)
Location: arch/x86/include/asm/paravirt.h:531
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
```
```
In mm/memory.c (ffffffff8133e773)
Location: arch/x86/include/asm/paravirt.h:531
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81359da4)
Location: arch/x86/include/asm/paravirt.h:531
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
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
In arch/x86/mm/init_64.c (ffffffff820c5f14)
Location: arch/x86/include/asm/paravirt.h:531
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
```
```
In mm/memory.c (ffffffff813b57de)
Location: arch/x86/include/asm/paravirt.h:531
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff813d47a4)
Location: arch/x86/include/asm/paravirt.h:531
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
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
In arch/x86/mm/init_64.c (ffffffff82149f74)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
```
```
In mm/memory.c (ffffffff813eae84)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81409174)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
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
In arch/x86/mm/init_64.c (ffffffff8222ca24)
Location: arch/x86/include/asm/paravirt.h:524
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
```
```
In mm/memory.c (ffffffff81417684)
Location: arch/x86/include/asm/paravirt.h:524
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81435964)
Location: arch/x86/include/asm/paravirt.h:524
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
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
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nopud.h:34
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/asm-generic/pgtable-nopud.h:34
Inline: True
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
In mm/memory.c (ffffffff812551fd)
Location: arch/x86/include/asm/paravirt.h:558
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff8126ace6)
Location: arch/x86/include/asm/paravirt.h:558
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
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
In mm/memory.c (ffffffff81252f9d)
Location: arch/x86/include/asm/paravirt.h:558
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81268a86)
Location: arch/x86/include/asm/paravirt.h:558
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
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
In mm/memory.c (ffffffff812628fd)
Location: arch/x86/include/asm/paravirt.h:558
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81278416)
Location: arch/x86/include/asm/paravirt.h:558
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
</details>
</li>
</ul>

## Differences
