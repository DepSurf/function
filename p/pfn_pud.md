# Function: <code>pfn_pud</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8123152c)
Location: arch/x86/include/asm/pgtable.h:526
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8124f6f0)
Location: arch/x86/include/asm/pgtable.h:541
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In arch/x86/mm/pageattr.c (ffffffff81077e45)
Location: arch/x86/include/asm/pgtable.h:562
Inline: True
```
```
In mm/huge_memory.c (ffffffff8127373d)
Location: arch/x86/include/asm/pgtable.h:562
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In arch/x86/mm/pageattr.c (ffffffff8107e5f5)
Location: arch/x86/include/asm/pgtable.h:564
Inline: True
```
```
In mm/huge_memory.c (ffffffff81287ac9)
Location: arch/x86/include/asm/pgtable.h:564
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In arch/x86/mm/pageattr.c (ffffffff81081ef0)
Location: arch/x86/include/asm/pgtable.h:581
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a222d)
Location: arch/x86/include/asm/pgtable.h:581
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In arch/x86/mm/pageattr.c (ffffffff81082fb0)
Location: arch/x86/include/asm/pgtable.h:581
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b35dd)
Location: arch/x86/include/asm/pgtable.h:581
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108c57f)
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
```
In mm/huge_memory.c (ffffffff812e8f1b)
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108c81f)
Location: arch/x86/include/asm/pgtable.h:619
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
```
In mm/huge_memory.c (ffffffff812f438b)
Location: arch/x86/include/asm/pgtable.h:619
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108d252)
Location: arch/x86/include/asm/pgtable.h:619
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
```
In mm/huge_memory.c (ffffffff812fa5cb)
Location: arch/x86/include/asm/pgtable.h:619
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
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
In arch/x86/mm/pat/set_memory.c (ffffffff8109cad5)
Location: arch/x86/include/asm/pgtable.h:590
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
```
In mm/huge_memory.c (ffffffff8134442b)
Location: arch/x86/include/asm/pgtable.h:590
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
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
In arch/x86/mm/pat/set_memory.c (ffffffff810b02d4)
Location: arch/x86/include/asm/pgtable.h:593
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
```
In mm/huge_memory.c (ffffffff813b9941)
Location: arch/x86/include/asm/pgtable.h:593
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
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
In arch/x86/mm/init_64.c (ffffffff820c6925)
Location: arch/x86/include/asm/pgtable.h:610
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ca95e)
Location: arch/x86/include/asm/pgtable.h:610
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
```
In mm/huge_memory.c (ffffffff8143be28)
Location: arch/x86/include/asm/pgtable.h:610
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
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
In arch/x86/mm/init_64.c (ffffffff8214a968)
Location: arch/x86/include/asm/pgtable.h:611
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cdf9c)
Location: arch/x86/include/asm/pgtable.h:611
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
```
In mm/huge_memory.c (ffffffff8147193b)
Location: arch/x86/include/asm/pgtable.h:611
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
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
In arch/x86/mm/init_64.c (ffffffff8222d418)
Location: arch/x86/include/asm/pgtable.h:780
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d667c)
Location: arch/x86/include/asm/pgtable.h:780
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
```
In mm/huge_memory.c (ffffffff814a10eb)
Location: arch/x86/include/asm/pgtable.h:780
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
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
In arch/x86/mm/pageattr.c (ffffffff81081fb0)
Location: arch/x86/include/asm/pgtable.h:581
Inline: True
```
```
In mm/huge_memory.c (ffffffff812abbbd)
Location: arch/x86/include/asm/pgtable.h:581
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In arch/x86/mm/pageattr.c (ffffffff81070cce)
Location: arch/x86/include/asm/pgtable.h:581
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pgd
```
```
In mm/huge_memory.c (ffffffff8129d4a8)
Location: arch/x86/include/asm/pgtable.h:581
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In arch/x86/mm/pageattr.c (ffffffff81081f60)
Location: arch/x86/include/asm/pgtable.h:581
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a99cd)
Location: arch/x86/include/asm/pgtable.h:581
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In arch/x86/mm/pageattr.c (ffffffff81084080)
Location: arch/x86/include/asm/pgtable.h:581
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b981f)
Location: arch/x86/include/asm/pgtable.h:581
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
</details>
</li>
</ul>

## Differences
