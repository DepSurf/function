# Function: <code>tlb_start_vma</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813419c5)
Location: include/asm-generic/tlb.h:489
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mprotect.c (ffffffff813547fb)
Location: include/asm-generic/tlb.h:489
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff81375b3e)
Location: include/asm-generic/tlb.h:489
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/madvise.c:madvise_cold
```
```
In mm/hugetlb.c (ffffffff8138f216)
Location: include/asm-generic/tlb.h:489
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
In mm/memory.c (ffffffff813b98f5)
Location: include/asm-generic/tlb.h:521
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mprotect.c (ffffffff813ced23)
Location: include/asm-generic/tlb.h:521
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff813f30db)
Location: include/asm-generic/tlb.h:521
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/madvise.c:madvise_cold
```
```
In mm/hugetlb.c (ffffffff8140f9bc)
Location: include/asm-generic/tlb.h:521
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
In mm/memory.c (ffffffff813ee615)
Location: include/asm-generic/tlb.h:521
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mprotect.c (ffffffff8140397f)
Location: include/asm-generic/tlb.h:521
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff81426b3a)
Location: include/asm-generic/tlb.h:521
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/madvise.c:madvise_cold
```
```
In mm/hugetlb.c (ffffffff81442d80)
Location: include/asm-generic/tlb.h:521
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
In mm/memory.c (ffffffff8141a0f5)
Location: include/asm-generic/tlb.h:531
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mprotect.c (ffffffff8142feff)
Location: include/asm-generic/tlb.h:531
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff8146077a)
Location: include/asm-generic/tlb.h:531
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/madvise.c:madvise_cold
```
```
In mm/hugetlb.c (ffffffff8147cf80)
Location: include/asm-generic/tlb.h:531
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/asm-generic/tlb.h:472
Inline: True
```
```
In mm/madvise.c (0)
Location: include/asm-generic/tlb.h:472
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/tlb.h:472
Inline: True
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
In mm/memory.c (c0518ce4)
Location: include/asm-generic/tlb.h:472
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/madvise.c (c0538080)
Location: include/asm-generic/tlb.h:472
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
```
</details>
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
Location: include/asm-generic/tlb.h:472
Inline: True
```
```
In mm/madvise.c (0)
Location: include/asm-generic/tlb.h:472
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/tlb.h:472
Inline: True
```
</details>
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
