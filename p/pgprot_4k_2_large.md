# Function: <code>pgprot_4k_2_large</code>

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
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable_types.h:364
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff8106ca2c)
Location: arch/x86/include/asm/pgtable_types.h:364
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable_types.h:364
Inline: True
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
In arch/x86/mm/init_64.c (ffffffff81fa0051)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff8106d7eb)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8107119d)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
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
In arch/x86/mm/init_64.c (ffffffff81fdb5bb)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81071477)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff81074d1d)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
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
In arch/x86/mm/init_64.c (ffffffff820bc5d9)
Location: arch/x86/include/asm/pgtable_types.h:439
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81070999)
Location: arch/x86/include/asm/pgtable_types.h:439
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810742d0)
Location: arch/x86/include/asm/pgtable_types.h:439
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
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
In arch/x86/mm/init_64.c (ffffffff826c3013)
Location: arch/x86/include/asm/pgtable_types.h:464
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff810761a2)
Location: arch/x86/include/asm/pgtable_types.h:464
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff81079d60)
Location: arch/x86/include/asm/pgtable_types.h:464
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
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
In arch/x86/mm/init_64.c (ffffffff826ed27f)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81078c85)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8107c9ca)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
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
In arch/x86/mm/init_64.c (ffffffff828a3e11)
Location: arch/x86/include/asm/pgtable_types.h:487
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff8107f5e5)
Location: arch/x86/include/asm/pgtable_types.h:487
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810833fa)
Location: arch/x86/include/asm/pgtable_types.h:487
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
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
In arch/x86/mm/init_64.c (ffffffff828bc2b8)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81083081)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8108705a)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
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
In arch/x86/mm/init_64.c (ffffffff828c275f)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81084151)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff81087d4a)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c4f5)
Location: arch/x86/include/asm/pgtable_types.h:492
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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c795)
Location: arch/x86/include/asm/pgtable_types.h:493
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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d1c7)
Location: arch/x86/include/asm/pgtable_types.h:491
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
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109ca4a)
Location: arch/x86/include/asm/pgtable_types.h:489
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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b0254)
Location: arch/x86/include/asm/pgtable_types.h:491
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
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810ca8ef)
Location: arch/x86/include/asm/pgtable_types.h:470
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
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cdf2f)
Location: arch/x86/include/asm/pgtable_types.h:471
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
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d660f)
Location: arch/x86/include/asm/pgtable_types.h:499
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff828ad735)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81083151)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff81086d4a)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
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
In arch/x86/mm/init_64.c (ffffffff828a59f6)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81071da6)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810759b6)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
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
In arch/x86/mm/init_64.c (ffffffff828c0634)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81083101)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff81086cfa)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
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
In arch/x86/mm/init_64.c (ffffffff828c377f)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81085236)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff81088e2a)
Location: arch/x86/include/asm/pgtable_types.h:486
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
```
</details>
</li>
</ul>

## Differences
