# Function: <code>flush_tlb_range</code>

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
In arch/arm64/mm/hugetlbpage.c (ffff8000100b17c4)
Location: arch/arm64/include/asm/tlbflush.h:214
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_clear_flush
  - arch/arm64/mm/hugetlbpage.c:set_huge_pte_at
  - arch/arm64/mm/hugetlbpage.c:get_clear_flush
```
```
In mm/mprotect.c (ffff8000103055ec)
Location: arch/arm64/include/asm/tlbflush.h:214
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffff800010306314)
Location: arch/arm64/include/asm/tlbflush.h:214
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffff80001030847c)
Location: arch/arm64/include/asm/tlbflush.h:214
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_clear_flush_young
```
```
In mm/rmap.c (ffff800010309fd4)
Location: arch/arm64/include/asm/tlbflush.h:214
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffff8000103359f4)
Location: arch/arm64/include/asm/tlbflush.h:214
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/huge_memory.c (ffff800010357fe0)
Location: arch/arm64/include/asm/tlbflush.h:214
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
void flush_tlb_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/smp_tlb.c (c03142c4)
Location: arch/arm/kernel/smp_tlb.c:220
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:tlb_flush
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:tlb_flush_mmu_tlbonly
```
**Symbols:**

```
c03142c4-c0314394: flush_tlb_range (STB_GLOBAL)
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
In mm/mprotect.c (c0000000003d2bc0)
Location: arch/powerpc/include/asm/book3s/64/tlbflush.h:68
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d3970)
Location: arch/powerpc/include/asm/book3s/64/tlbflush.h:68
Inline: True
```
```
In mm/rmap.c (c0000000003d9b24)
Location: arch/powerpc/include/asm/book3s/64/tlbflush.h:68
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (c000000000434c84)
Location: arch/powerpc/include/asm/book3s/64/tlbflush.h:68
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (c0000000004407b8)
Location: arch/powerpc/include/asm/book3s/64/tlbflush.h:68
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void flush_tlb_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/tlbflush.c (ffffffe0000ba582)
Location: arch/riscv/mm/tlbflush.c:52
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
```
**Symbols:**

```
ffffffe0000ba582-ffffffe0000ba5c8: flush_tlb_range (STB_GLOBAL)
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
