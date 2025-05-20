# Function: <code>__flush_tlb_range</code>

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
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm64/mm/hugetlbpage.c (ffff8000100b17c4)
Location: arch/arm64/include/asm/tlbflush.h:180
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_clear_flush
  - arch/arm64/mm/hugetlbpage.c:set_huge_pte_at
  - arch/arm64/mm/hugetlbpage.c:get_clear_flush
```
```
In mm/memory.c (ffff8000102f71a0)
Location: arch/arm64/include/asm/tlbflush.h:180
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mmu_gather.c (ffff8000103048b4)
Location: arch/arm64/include/asm/tlbflush.h:180
Inline: True
```
```
In mm/mprotect.c (ffff8000103055ec)
Location: arch/arm64/include/asm/tlbflush.h:180
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffff800010306314)
Location: arch/arm64/include/asm/tlbflush.h:180
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffff80001030847c)
Location: arch/arm64/include/asm/tlbflush.h:180
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_clear_flush_young
```
```
In mm/rmap.c (ffff800010309fd4)
Location: arch/arm64/include/asm/tlbflush.h:180
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffff80001031d9d8)
Location: arch/arm64/include/asm/tlbflush.h:180
Inline: True
Inline callers:
  - mm/madvise.c:tlb_flush_mmu_tlbonly
```
```
In mm/hugetlb.c (ffff8000103359f4)
Location: arch/arm64/include/asm/tlbflush.h:180
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
Direct callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffff800010357fe0)
Location: arch/arm64/include/asm/tlbflush.h:180
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffff80001032ec30-ffff80001032ed50: __flush_tlb_range.isra.0 (STB_LOCAL)
```
</details>
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
