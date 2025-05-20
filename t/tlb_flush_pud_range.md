# Function: <code>tlb_flush_pud_range</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812972cf)
Location: include/asm-generic/tlb.h:532
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/hugetlb.c (ffffffff812d4195)
Location: include/asm-generic/tlb.h:532
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff812f7ba2)
Location: include/asm-generic/tlb.h:532
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/memory.c (ffffffff8129d113)
Location: include/asm-generic/tlb.h:534
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/hugetlb.c (ffffffff812db072)
Location: include/asm-generic/tlb.h:534
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff812fe152)
Location: include/asm-generic/tlb.h:534
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/memory.c (ffffffff812de55e)
Location: include/asm-generic/tlb.h:534
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/hugetlb.c (ffffffff813220eb)
Location: include/asm-generic/tlb.h:534
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff81347cf2)
Location: include/asm-generic/tlb.h:534
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/memory.c (ffffffff8133e5fb)
Location: include/asm-generic/tlb.h:538
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/hugetlb.c (ffffffff8138f551)
Location: include/asm-generic/tlb.h:538
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff813be162)
Location: include/asm-generic/tlb.h:538
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/memory.c (ffffffff813b5665)
Location: include/asm-generic/tlb.h:570
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/hugetlb.c (ffffffff8140fd6d)
Location: include/asm-generic/tlb.h:570
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff814409a2)
Location: include/asm-generic/tlb.h:570
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/memory.c (ffffffff813ead25)
Location: include/asm-generic/tlb.h:570
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/hugetlb.c (ffffffff81443134)
Location: include/asm-generic/tlb.h:570
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff81476262)
Location: include/asm-generic/tlb.h:570
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/memory.c (ffffffff81417525)
Location: include/asm-generic/tlb.h:580
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/hugetlb.c (ffffffff8147d34a)
Location: include/asm-generic/tlb.h:580
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffffffff814a5b12)
Location: include/asm-generic/tlb.h:580
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
