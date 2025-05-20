# Function: <code>tlb_flush_pte_range</code>

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
In mm/memory.c (ffffffff8129a096)
Location: include/asm-generic/tlb.h:518
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff812c2e2e)
Location: include/asm-generic/tlb.h:518
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
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
In mm/memory.c (ffffffff8129f2ba)
Location: include/asm-generic/tlb.h:520
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff812c9ca7)
Location: include/asm-generic/tlb.h:520
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
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
In mm/memory.c (ffffffff812e051f)
Location: include/asm-generic/tlb.h:520
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff8130ecc7)
Location: include/asm-generic/tlb.h:520
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
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
In mm/memory.c (ffffffff81340b9e)
Location: include/asm-generic/tlb.h:524
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff81353f82)
Location: include/asm-generic/tlb.h:524
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/madvise.c (ffffffff81376da5)
Location: include/asm-generic/tlb.h:524
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8138f6c3)
Location: include/asm-generic/tlb.h:524
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
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
In mm/memory.c (ffffffff813b8b3c)
Location: include/asm-generic/tlb.h:556
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff813ce3a8)
Location: include/asm-generic/tlb.h:556
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/madvise.c (ffffffff813f4429)
Location: include/asm-generic/tlb.h:556
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8140fe50)
Location: include/asm-generic/tlb.h:556
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
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
In mm/memory.c (ffffffff813ed776)
Location: include/asm-generic/tlb.h:556
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff81402b20)
Location: include/asm-generic/tlb.h:556
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/madvise.c (ffffffff8142792e)
Location: include/asm-generic/tlb.h:556
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff81443217)
Location: include/asm-generic/tlb.h:556
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
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
In mm/memory.c (ffffffff81418d5b)
Location: include/asm-generic/tlb.h:566
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff8142f174)
Location: include/asm-generic/tlb.h:566
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/madvise.c (ffffffff8146113f)
Location: include/asm-generic/tlb.h:566
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8147d46b)
Location: include/asm-generic/tlb.h:566
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
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
