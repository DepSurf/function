# Function: <code>radix__pte_update</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/pgtable.c (c00000000009137c)
Location: arch/powerpc/include/asm/book3s/64/radix.h:150
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/pgtable.c:ptep_modify_prot_start
```
```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c0000000000954e4)
Location: arch/powerpc/include/asm/book3s/64/radix.h:150
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix__pmdp_huge_get_and_clear
```
```
In arch/powerpc/mm/book3s64/hash_hugetlbpage.c (c00000000009e78c)
Location: arch/powerpc/include/asm/book3s/64/radix.h:150
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_hugetlbpage.c:huge_ptep_modify_prot_start
```
```
In arch/powerpc/mm/book3s64/subpage_prot.c (c00000000009f9c4)
Location: arch/powerpc/include/asm/book3s/64/radix.h:150
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:hpte_flush_range
```
```
In mm/memory.c (c0000000003bee54)
Location: arch/powerpc/include/asm/book3s/64/radix.h:150
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mremap.c (c0000000003d3728)
Location: arch/powerpc/include/asm/book3s/64/radix.h:150
Inline: True
```
```
In mm/pgtable-generic.c (c0000000003d71e0)
Location: arch/powerpc/include/asm/book3s/64/radix.h:150
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush_young
```
```
In mm/rmap.c (c0000000003d9e04)
Location: arch/powerpc/include/asm/book3s/64/radix.h:150
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (c0000000003dcd74)
Location: arch/powerpc/include/asm/book3s/64/radix.h:150
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_page_range
```
```
In mm/madvise.c (c0000000003f32c4)
Location: arch/powerpc/include/asm/book3s/64/radix.h:150
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (c00000000040cf2c)
Location: arch/powerpc/include/asm/book3s/64/radix.h:150
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (c000000000434cc8)
Location: arch/powerpc/include/asm/book3s/64/radix.h:150
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (c00000000044617c)
Location: arch/powerpc/include/asm/book3s/64/radix.h:150
Inline: True
```
```
In mm/page_idle.c (c00000000046c418)
Location: arch/powerpc/include/asm/book3s/64/radix.h:150
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/proc/task_mmu.c (c00000000054e6f0)
Location: arch/powerpc/include/asm/book3s/64/radix.h:150
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
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
