# Function: <code>flush_tlb_mm</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In arch/arm64/mm/hugetlbpage.c (ffff8000100b188c)
Location: arch/arm64/include/asm/tlbflush.h:147
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_clear_flush
  - arch/arm64/mm/hugetlbpage.c:set_huge_pte_at
  - arch/arm64/mm/hugetlbpage.c:get_clear_flush
```
```
In kernel/fork.c (ffff8000100f2c44)
Location: arch/arm64/include/asm/tlbflush.h:147
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/memory.c (ffff8000102f7388)
Location: arch/arm64/include/asm/tlbflush.h:147
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
```
```
In mm/mmu_gather.c (ffff800010304a50)
Location: arch/arm64/include/asm/tlbflush.h:147
Inline: True
```
```
In mm/mprotect.c (ffff8000103056a0)
Location: arch/arm64/include/asm/tlbflush.h:147
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffff80001030655c)
Location: arch/arm64/include/asm/tlbflush.h:147
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffff80001030851c)
Location: arch/arm64/include/asm/tlbflush.h:147
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_clear_flush_young
```
```
In mm/rmap.c (ffff80001030a5c8)
Location: arch/arm64/include/asm/tlbflush.h:147
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffff80001031db6c)
Location: arch/arm64/include/asm/tlbflush.h:147
Inline: True
Inline callers:
  - mm/madvise.c:tlb_flush_mmu_tlbonly
  - mm/madvise.c:tlb_flush_mmu_tlbonly
```
```
In mm/hugetlb.c (ffff800010335c54)
Location: arch/arm64/include/asm/tlbflush.h:147
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/huge_memory.c (ffff80001035811c)
Location: arch/arm64/include/asm/tlbflush.h:147
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void flush_tlb_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/smp_tlb.c (c0314068)
Location: arch/arm/kernel/smp_tlb.c:187
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/memory.c:unmap_page_range
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/madvise.c:tlb_flush_mmu_tlbonly
```
**Symbols:**

```
c0314068-c03140fc: flush_tlb_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c000000000138908)
Location: arch/powerpc/include/asm/book3s/64/tlbflush.h:114
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void flush_tlb_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/tlbflush.c (ffffffe0000ba50e)
Location: arch/riscv/mm/tlbflush.c:42
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffe0000ba50e-ffffffe0000ba544: flush_tlb_mm (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
