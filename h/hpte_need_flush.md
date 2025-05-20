# Function: <code>hpte_need_flush</code>

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
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hpte_need_flush(struct mm_struct *mm, long unsigned int addr, pte_t *ptep, long unsigned int pte, int huge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/hash_tlb.c (c000000000091610)
Location: arch/powerpc/mm/book3s64/hash_tlb.c:41
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/pgtable.c:ptep_modify_prot_start
  - arch/powerpc/mm/book3s64/hash_tlb.c:flush_tlb_pmd_range
  - arch/powerpc/mm/book3s64/hash_tlb.c:__flush_hash_table_range
  - arch/powerpc/mm/book3s64/hash_hugetlbpage.c:huge_ptep_modify_prot_start
  - arch/powerpc/mm/book3s64/subpage_prot.c:hpte_flush_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush_young
  - mm/rmap.c:try_to_unmap_one
  - mm/vmalloc.c:vunmap_page_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
c000000000091610-c000000000091b28: hpte_need_flush (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
