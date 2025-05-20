# Function: <code>mm_dec_nr_ptes</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81209ba9)
Location: include/linux/mm.h:1719
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/huge_memory.c (ffffffff81251d16)
Location: include/linux/mm.h:1719
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81257962)
Location: include/linux/mm.h:1719
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/memory.c (ffffffff8122a9b0)
Location: include/linux/mm.h:1806
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/huge_memory.c (ffffffff8127627b)
Location: include/linux/mm.h:1806
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8127bb92)
Location: include/linux/mm.h:1806
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/memory.c (ffffffff8123dd65)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/huge_memory.c (ffffffff8128af53)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8128fed4)
Location: include/linux/mm.h:1884
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/memory.c (ffffffff8124e445)
Location: include/linux/mm.h:1879
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/huge_memory.c (ffffffff812a5af6)
Location: include/linux/mm.h:1879
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812ab0be)
Location: include/linux/mm.h:1879
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/memory.c (ffffffff8125c9b5)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/huge_memory.c (ffffffff812b6fb6)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812bca57)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
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
In mm/memory.c (ffffffff8128c2a5)
Location: include/linux/mm.h:2083
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/huge_memory.c (ffffffff812ec198)
Location: include/linux/mm.h:2083
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812f11f3)
Location: include/linux/mm.h:2083
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
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
In mm/memory.c (ffffffff81297219)
Location: include/linux/mm.h:2128
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/huge_memory.c (ffffffff812f722a)
Location: include/linux/mm.h:2128
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812fc8fa)
Location: include/linux/mm.h:2128
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
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
In mm/memory.c (ffffffff8129d054)
Location: include/linux/mm.h:2136
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/huge_memory.c (ffffffff812fd6c0)
Location: include/linux/mm.h:2136
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81303665)
Location: include/linux/mm.h:2136
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
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
In mm/memory.c (ffffffff812de49f)
Location: include/linux/mm.h:2165
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/huge_memory.c (ffffffff813472f5)
Location: include/linux/mm.h:2165
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8134d3cf)
Location: include/linux/mm.h:2165
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
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
In mm/memory.c (ffffffff8133e56d)
Location: include/linux/mm.h:2243
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/huge_memory.c (ffffffff813bd5a6)
Location: include/linux/mm.h:2243
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813c3b5b)
Location: include/linux/mm.h:2243
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
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
In mm/memory.c (ffffffff813b55d9)
Location: include/linux/mm.h:2407
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/huge_memory.c (ffffffff8143fd3e)
Location: include/linux/mm.h:2407
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8144733a)
Location: include/linux/mm.h:2407
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
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
In mm/memory.c (ffffffff813eac94)
Location: include/linux/mm.h:2727
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/huge_memory.c (ffffffff81475566)
Location: include/linux/mm.h:2727
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8147ca11)
Location: include/linux/mm.h:2727
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
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
In mm/memory.c (ffffffff81417494)
Location: include/linux/mm.h:2768
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/huge_memory.c (ffffffff814a4f5e)
Location: include/linux/mm.h:2768
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814acd26)
Location: include/linux/mm.h:2768
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
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
In mm/memory.c (ffff8000102f5584)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/huge_memory.c (ffff800010357d0c)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffff80001035dca4)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
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
In arch/arm/mm/pgd.c (c031f9c4)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - arch/arm/mm/pgd.c:pgd_free
```
```
In mm/memory.c (c0517608)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
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
In mm/memory.c (c0000000003bc790)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/huge_memory.c (c00000000043c140)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (c000000000449348)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000206b26)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
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
In mm/memory.c (ffffffff81255005)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/huge_memory.c (ffffffff812af596)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812b5037)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
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
In mm/memory.c (ffffffff81248c52)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/huge_memory.c (ffffffff812a0b87)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812a6065)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
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
In mm/memory.c (ffffffff81252da5)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/huge_memory.c (ffffffff812ad3a6)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812b2e47)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
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
In mm/memory.c (ffffffff81262705)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/huge_memory.c (ffffffff812bd727)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812c3282)
Location: include/linux/mm.h:1851
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
</details>
</li>
</ul>

## Differences
