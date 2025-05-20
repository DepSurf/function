# Function: <code>pte_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101deea)
Location: arch/x86/include/asm/paravirt.h:379
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:__ptep_modify_prot_start
```
```
In arch/x86/kernel/paravirt.c (ffffffff810646ba)
Location: arch/x86/include/asm/paravirt.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In arch/x86/mm/pgtable.c (ffffffff81070fe9)
Location: arch/x86/include/asm/paravirt.h:379
Inline: True
```
```
In mm/memory.c (ffffffff811bdb2e)
Location: arch/x86/include/asm/paravirt.h:379
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff811c9708)
Location: arch/x86/include/asm/paravirt.h:379
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811cb432)
Location: arch/x86/include/asm/paravirt.h:379
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff811ce4d6)
Location: arch/x86/include/asm/paravirt.h:379
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff811d0460)
Location: arch/x86/include/asm/paravirt.h:379
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/hugetlb.c (ffffffff811dd9bf)
Location: arch/x86/include/asm/paravirt.h:379
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101d2da)
Location: arch/x86/include/asm/paravirt.h:369
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:__ptep_modify_prot_start
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106430a)
Location: arch/x86/include/asm/paravirt.h:369
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In arch/x86/mm/pgtable.c (ffffffff81070eaf)
Location: arch/x86/include/asm/paravirt.h:369
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_set_access_flags
```
```
In mm/memory.c (ffffffff811d93f1)
Location: arch/x86/include/asm/paravirt.h:369
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff811e5abb)
Location: arch/x86/include/asm/paravirt.h:369
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811e85c0)
Location: arch/x86/include/asm/paravirt.h:369
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff811eb088)
Location: arch/x86/include/asm/paravirt.h:369
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff811ed610)
Location: arch/x86/include/asm/paravirt.h:369
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/madvise.c (ffffffff811eee33)
Location: arch/x86/include/asm/paravirt.h:369
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff811fc4df)
Location: arch/x86/include/asm/paravirt.h:369
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101d9fa)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:__ptep_modify_prot_start
```
```
In arch/x86/kernel/paravirt.c (ffffffff810677da)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In arch/x86/mm/pgtable.c (ffffffff81074a2f)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_set_access_flags
```
```
In mm/memory.c (ffffffff811e880a)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff811f5d1e)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff811f7a00)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff811f98d2)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff811fc2e8)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
```
```
In mm/madvise.c (ffffffff811ff7dd)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff8120cfcf)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8101fcda)
Location: arch/x86/include/asm/paravirt.h:368
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_start
```
```
In arch/x86/kernel/paravirt.c (ffffffff81066aaa)
Location: arch/x86/include/asm/paravirt.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In arch/x86/mm/pgtable.c (ffffffff81073f7f)
Location: arch/x86/include/asm/paravirt.h:368
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_set_access_flags
```
```
In mm/memory.c (ffffffff811f77cd)
Location: arch/x86/include/asm/paravirt.h:368
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/mremap.c (ffffffff81200b0c)
Location: arch/x86/include/asm/paravirt.h:368
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81202b90)
Location: arch/x86/include/asm/paravirt.h:368
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff812044b3)
Location: arch/x86/include/asm/paravirt.h:368
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81206fae)
Location: arch/x86/include/asm/paravirt.h:368
Inline: True
```
```
In mm/madvise.c (ffffffff8120a368)
Location: arch/x86/include/asm/paravirt.h:368
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff81218ed5)
Location: arch/x86/include/asm/paravirt.h:368
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
</details>
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
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/powerpc/mm/book3s64/pgtable.c (c000000000091378)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:353
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/pgtable.c:ptep_modify_prot_start
```
```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000095cac)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:353
Inline: True
Direct callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable
  - arch/powerpc/mm/book3s64/radix_pgtable.c:split_kernel_mapping
  - arch/powerpc/mm/book3s64/radix_pgtable.c:stop_machine_change_mapping
```
```
In arch/powerpc/mm/book3s64/hash_hugetlbpage.c (c00000000009e788)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:353
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_hugetlbpage.c:huge_ptep_modify_prot_start
```
```
In arch/powerpc/mm/book3s64/subpage_prot.c (c00000000009f9c0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:353
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:hpte_flush_range
```
```
In mm/memory.c (c0000000003bee50)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:353
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mremap.c (c0000000003d3724)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:353
Inline: True
```
```
In mm/pgtable-generic.c (c0000000003d71d8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:353
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush_young
```
```
In mm/rmap.c (c0000000003d9e00)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:353
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (c0000000003dcd70)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:353
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_page_range
```
```
In mm/madvise.c (c0000000003f32c0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:353
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (c00000000040cf28)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:353
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (c000000000434cc4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:353
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (c000000000446178)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:353
Inline: True
```
```
In mm/page_idle.c (c00000000046c414)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:353
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/proc/task_mmu.c (c00000000054e6ec)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:353
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
c000000000095cac-c000000000095d98: pte_update.constprop.0 (STB_LOCAL)
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
