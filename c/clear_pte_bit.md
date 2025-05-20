# Function: <code>clear_pte_bit</code>

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
In arch/arm64/mm/pageattr.c (ffff8000100b0138)
Location: arch/arm64/include/asm/pgtable.h:126
Inline: True
Inline callers:
  - arch/arm64/mm/pageattr.c:change_page_range
```
```
In arch/arm64/mm/hugetlbpage.c (ffff8000100b16f4)
Location: arch/arm64/include/asm/pgtable.h:126
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_set_wrprotect
```
```
In virt/kvm/arm/mmu.c (ffff8000100ca3cc)
Location: arch/arm64/include/asm/pgtable.h:126
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:kvm_age_hva_handler
  - virt/kvm/arm/mmu.c:kvm_age_hva_handler
  - virt/kvm/arm/mmu.c:kvm_age_hva_handler
```
```
In mm/shmem.c (ffff8000102d3124)
Location: arch/arm64/include/asm/pgtable.h:126
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (0)
Location: arch/arm64/include/asm/pgtable.h:126
Inline: True
```
```
In mm/memory.c (ffff8000102f8ec0)
Location: arch/arm64/include/asm/pgtable.h:126
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffff800010305584)
Location: arch/arm64/include/asm/pgtable.h:126
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/pgtable-generic.c (ffff8000103080c0)
Location: arch/arm64/include/asm/pgtable.h:126
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_clear_flush_young
```
```
In mm/rmap.c (ffff800010309d34)
Location: arch/arm64/include/asm/pgtable.h:126
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (ffff80001031ec4c)
Location: arch/arm64/include/asm/pgtable.h:126
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffff80001032612c)
Location: arch/arm64/include/asm/pgtable.h:126
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffff800010334378)
Location: arch/arm64/include/asm/pgtable.h:126
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:make_huge_pte
```
```
In mm/ksm.c (0)
Location: arch/arm64/include/asm/pgtable.h:126
Inline: True
```
```
In mm/migrate.c (ffff80001034efc8)
Location: arch/arm64/include/asm/pgtable.h:126
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffff800010355f20)
Location: arch/arm64/include/asm/pgtable.h:126
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (0)
Location: arch/arm64/include/asm/pgtable.h:126
Inline: True
```
```
In mm/userfaultfd.c (ffff800010378064)
Location: arch/arm64/include/asm/pgtable.h:126
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/page_idle.c (ffff8000103795e0)
Location: arch/arm64/include/asm/pgtable.h:126
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/dax.c (ffff8000104077b4)
Location: arch/arm64/include/asm/pgtable.h:126
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffff80001043aa18)
Location: arch/arm64/include/asm/pgtable.h:126
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/arm/mm/pageattr.c (c031fc04)
Location: arch/arm/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - arch/arm/mm/pageattr.c:change_page_range
```
```
In mm/shmem.c (c04fb06c)
Location: arch/arm/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (c051b374)
Location: arch/arm/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (c05233b4)
Location: arch/arm/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/pgtable-generic.c (c0525554)
Location: arch/arm/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush_young
```
```
In mm/rmap.c (c0525ba8)
Location: arch/arm/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (c0537868)
Location: arch/arm/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (c053d970)
Location: arch/arm/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/ksm.c (c0544a34)
Location: arch/arm/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (c0551730)
Location: arch/arm/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/userfaultfd.c (c0563878)
Location: arch/arm/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (c0564494)
Location: arch/arm/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/proc/task_mmu.c (c06004a4)
Location: arch/arm/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
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
