# Function: <code>ptep_get_and_clear</code>

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
In arch/x86/xen/mmu.c (ffffffff8101dee5)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:__ptep_modify_prot_start
```
```
In arch/x86/kernel/paravirt.c (ffffffff810646b5)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In mm/memory.c (ffffffff811bdb25)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mremap.c (ffffffff811c9703)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811cb429)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff811ce4d0)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff811d0452)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/hugetlb.c (ffffffff811dd9b9)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:hugetlb_change_protection
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
In arch/x86/xen/mmu.c (ffffffff8101d2d5)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:__ptep_modify_prot_start
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064305)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In mm/memory.c (ffffffff811d93e7)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mremap.c (ffffffff811e5ab6)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811e85b8)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff811eb082)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff811ed602)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/madvise.c (ffffffff811eee2c)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff811fc4d5)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
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
In arch/x86/xen/mmu.c (ffffffff8101d9f5)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:__ptep_modify_prot_start
```
```
In arch/x86/kernel/paravirt.c (ffffffff810677d5)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In mm/memory.c (ffffffff811e8801)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mremap.c (ffffffff811f5d19)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff811f79f2)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff811f98c6)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff811fc2e2)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
```
```
In mm/madvise.c (ffffffff811ff7d7)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff8120cfc5)
Location: arch/x86/include/asm/pgtable.h:822
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
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
In arch/x86/xen/mmu_pv.c (ffffffff8101fcd5)
Location: arch/x86/include/asm/pgtable.h:1016
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_start
```
```
In arch/x86/kernel/paravirt.c (ffffffff81066aa5)
Location: arch/x86/include/asm/pgtable.h:1016
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In mm/memory.c (ffffffff811f39cd)
Location: arch/x86/include/asm/pgtable.h:1016
Inline: True
```
```
In mm/mremap.c (ffffffff81200b07)
Location: arch/x86/include/asm/pgtable.h:1016
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81202b82)
Location: arch/x86/include/asm/pgtable.h:1016
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff812044aa)
Location: arch/x86/include/asm/pgtable.h:1016
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81206fa8)
Location: arch/x86/include/asm/pgtable.h:1016
Inline: True
```
```
In mm/madvise.c (ffffffff8120a361)
Location: arch/x86/include/asm/pgtable.h:1016
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff81218ecf)
Location: arch/x86/include/asm/pgtable.h:1016
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81020941)
Location: arch/x86/include/asm/pgtable.h:1024
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_start
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106ac31)
Location: arch/x86/include/asm/pgtable.h:1024
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In mm/memory.c (ffffffff8120b35e)
Location: arch/x86/include/asm/pgtable.h:1024
Inline: True
```
```
In mm/mremap.c (ffffffff81219544)
Location: arch/x86/include/asm/pgtable.h:1024
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff8121b8ee)
Location: arch/x86/include/asm/pgtable.h:1024
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff8121d52d)
Location: arch/x86/include/asm/pgtable.h:1024
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8121ff92)
Location: arch/x86/include/asm/pgtable.h:1024
Inline: True
```
```
In mm/madvise.c (ffffffff8122395e)
Location: arch/x86/include/asm/pgtable.h:1024
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff81233e6d)
Location: arch/x86/include/asm/pgtable.h:1024
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/migrate.c (ffffffff8124b6f1)
Location: arch/x86/include/asm/pgtable.h:1024
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810213f0)
Location: arch/x86/include/asm/pgtable.h:1075
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_start
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106d8f0)
Location: arch/x86/include/asm/pgtable.h:1075
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In mm/memory.c (ffffffff8122c152)
Location: arch/x86/include/asm/pgtable.h:1075
Inline: True
```
```
In mm/mremap.c (ffffffff8123ade4)
Location: arch/x86/include/asm/pgtable.h:1075
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff8123d6ce)
Location: arch/x86/include/asm/pgtable.h:1075
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff8123f512)
Location: arch/x86/include/asm/pgtable.h:1075
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812412c2)
Location: arch/x86/include/asm/pgtable.h:1075
Inline: True
```
```
In mm/madvise.c (ffffffff812466d6)
Location: arch/x86/include/asm/pgtable.h:1075
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff81256ddb)
Location: arch/x86/include/asm/pgtable.h:1075
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/migrate.c (ffffffff8126e3cc)
Location: arch/x86/include/asm/pgtable.h:1075
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81020c60)
Location: arch/x86/include/asm/pgtable.h:1100
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_start
```
```
In arch/x86/kernel/paravirt.c (ffffffff81073a90)
Location: arch/x86/include/asm/pgtable.h:1100
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In mm/memory.c (ffffffff8123f6eb)
Location: arch/x86/include/asm/pgtable.h:1100
Inline: True
```
```
In mm/mremap.c (ffffffff8124efe4)
Location: arch/x86/include/asm/pgtable.h:1100
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81251c1e)
Location: arch/x86/include/asm/pgtable.h:1100
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff81253c13)
Location: arch/x86/include/asm/pgtable.h:1100
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812559a6)
Location: arch/x86/include/asm/pgtable.h:1100
Inline: True
```
```
In mm/madvise.c (ffffffff8125aaf9)
Location: arch/x86/include/asm/pgtable.h:1100
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff8126b392)
Location: arch/x86/include/asm/pgtable.h:1100
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/migrate.c (ffffffff8128325a)
Location: arch/x86/include/asm/pgtable.h:1100
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810227a0)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_start
```
```
In arch/x86/kernel/paravirt.c (ffffffff810775f0)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In mm/memory.c (ffffffff81250e9e)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
```
```
In mm/mremap.c (ffffffff81261346)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81263eef)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff81265e3b)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81267d24)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
```
```
In mm/madvise.c (ffffffff81275b2c)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff81286666)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810230e0)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_start
```
```
In arch/x86/kernel/paravirt.c (ffffffff81078660)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In mm/memory.c (ffffffff8125f43a)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
```
```
In mm/mremap.c (ffffffff8126fae9)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff8127275f)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff81274768)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8127665c)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
```
```
In mm/madvise.c (ffffffff81284afc)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8129624b)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/migrate.c (ffffffff812ae9bb)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025950)
Location: arch/x86/include/asm/pgtable.h:1080
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_start
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107fa60)
Location: arch/x86/include/asm/pgtable.h:1080
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In mm/memory.c (ffffffff8128f801)
Location: arch/x86/include/asm/pgtable.h:1080
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mremap.c (ffffffff812a0115)
Location: arch/x86/include/asm/pgtable.h:1080
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812a351f)
Location: arch/x86/include/asm/pgtable.h:1080
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff812a5ac2)
Location: arch/x86/include/asm/pgtable.h:1080
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812a7be8)
Location: arch/x86/include/asm/pgtable.h:1080
Inline: True
```
```
In mm/madvise.c (ffffffff812b6d28)
Location: arch/x86/include/asm/pgtable.h:1080
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff812c97ce)
Location: arch/x86/include/asm/pgtable.h:1080
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/migrate.c (ffffffff812e40f3)
Location: arch/x86/include/asm/pgtable.h:1080
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81026070)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_start
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107f680)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In mm/memory.c (ffffffff8129a2cc)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mremap.c (ffffffff812ab571)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812aedff)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff812b0f3d)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812b2cb8)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
```
```
In mm/madvise.c (ffffffff812c2f6d)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff812d5539)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/migrate.c (ffffffff812f0129)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
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
In arch/x86/xen/mmu_pv.c (ffffffff81027fb0)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_start
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080780)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In mm/memory.c (ffffffff8129f4bd)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mremap.c (ffffffff812b0974)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812b432f)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff812b6505)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812b888b)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
```
```
In mm/madvise.c (ffffffff812c9dce)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff812dc1b3)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/migrate.c (ffffffff812f5806)
Location: arch/x86/include/asm/pgtable.h:1076
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff8108f6a0)
Location: arch/x86/include/asm/pgtable.h:1047
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In mm/memory.c (ffffffff812e0774)
Location: arch/x86/include/asm/pgtable.h:1047
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mremap.c (ffffffff812f2304)
Location: arch/x86/include/asm/pgtable.h:1047
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812f5f0f)
Location: arch/x86/include/asm/pgtable.h:1047
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff812f7c7c)
Location: arch/x86/include/asm/pgtable.h:1047
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812fec97)
Location: arch/x86/include/asm/pgtable.h:1047
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_range_noflush
```
```
In mm/madvise.c (ffffffff8130edee)
Location: arch/x86/include/asm/pgtable.h:1047
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff81323349)
Location: arch/x86/include/asm/pgtable.h:1047
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/migrate.c (ffffffff8133fe09)
Location: arch/x86/include/asm/pgtable.h:1047
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff810a0420)
Location: arch/x86/include/asm/pgtable.h:1048
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In mm/memory.c (ffffffff81340f2f)
Location: arch/x86/include/asm/pgtable.h:1048
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mremap.c (ffffffff813560a8)
Location: arch/x86/include/asm/pgtable.h:1048
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81359e9e)
Location: arch/x86/include/asm/pgtable.h:1048
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff8135daab)
Location: arch/x86/include/asm/pgtable.h:1048
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff813614a9)
Location: arch/x86/include/asm/pgtable.h:1048
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/madvise.c (ffffffff81376d92)
Location: arch/x86/include/asm/pgtable.h:1048
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff81390c35)
Location: arch/x86/include/asm/pgtable.h:1048
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
```
```
In mm/migrate_device.c (ffffffff813b73a6)
Location: arch/x86/include/asm/pgtable.h:1048
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff813c3fbe)
Location: arch/x86/include/asm/pgtable.h:1048
Inline: True
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
In arch/x86/kernel/paravirt.c (ffffffff810b7fb0)
Location: arch/x86/include/asm/pgtable.h:1066
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In mm/memory.c (ffffffff813b8faa)
Location: arch/x86/include/asm/pgtable.h:1066
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mremap.c (ffffffff813d06eb)
Location: arch/x86/include/asm/pgtable.h:1066
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff813d48ce)
Location: arch/x86/include/asm/pgtable.h:1066
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff813d8934)
Location: arch/x86/include/asm/pgtable.h:1066
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff813dce43)
Location: arch/x86/include/asm/pgtable.h:1066
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/madvise.c (ffffffff813f465f)
Location: arch/x86/include/asm/pgtable.h:1066
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8141253c)
Location: arch/x86/include/asm/pgtable.h:1066
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
```
```
In mm/migrate_device.c (ffffffff81438eb7)
Location: arch/x86/include/asm/pgtable.h:1066
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff81447763)
Location: arch/x86/include/asm/pgtable.h:1066
Inline: True
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
In arch/x86/kernel/paravirt.c (ffffffff810bb160)
Location: arch/x86/include/asm/pgtable.h:1067
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In mm/memory.c (ffffffff813edb39)
Location: arch/x86/include/asm/pgtable.h:1067
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mremap.c (ffffffff81404bcb)
Location: arch/x86/include/asm/pgtable.h:1067
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff8140929e)
Location: arch/x86/include/asm/pgtable.h:1067
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff8140dd16)
Location: arch/x86/include/asm/pgtable.h:1067
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff814116b3)
Location: arch/x86/include/asm/pgtable.h:1067
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/madvise.c (ffffffff8142791c)
Location: arch/x86/include/asm/pgtable.h:1067
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff81445b12)
Location: arch/x86/include/asm/pgtable.h:1067
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
```
```
In mm/migrate_device.c (ffffffff8146f6f4)
Location: arch/x86/include/asm/pgtable.h:1067
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8147ce69)
Location: arch/x86/include/asm/pgtable.h:1067
Inline: True
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
In arch/x86/kernel/paravirt.c (ffffffff810c25b0)
Location: arch/x86/include/asm/pgtable.h:1282
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In mm/memory.c (ffffffff8141913f)
Location: arch/x86/include/asm/pgtable.h:1282
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mremap.c (ffffffff814311af)
Location: arch/x86/include/asm/pgtable.h:1282
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81435a8e)
Location: arch/x86/include/asm/pgtable.h:1282
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff8143a95f)
Location: arch/x86/include/asm/pgtable.h:1282
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8143dea3)
Location: arch/x86/include/asm/pgtable.h:1282
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/madvise.c (ffffffff81461114)
Location: arch/x86/include/asm/pgtable.h:1282
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8147f4d5)
Location: arch/x86/include/asm/pgtable.h:1282
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
```
```
In mm/migrate_device.c (ffffffff8149e32f)
Location: arch/x86/include/asm/pgtable.h:1282
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff814b07f5)
Location: arch/x86/include/asm/pgtable.h:1282
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/userfaultfd.c (ffffffff814d2fb0)
Location: arch/x86/include/asm/pgtable.h:1282
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
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
In arch/arm64/mm/hugetlbpage.c (ffff8000100b1318)
Location: arch/arm64/include/asm/pgtable.h:757
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_get_and_clear
  - arch/arm64/mm/hugetlbpage.c:get_clear_flush
```
```
In mm/memory.c (ffff8000102fa044)
Location: arch/arm64/include/asm/pgtable.h:757
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
```
```
In mm/mprotect.c (ffff80001030524c)
Location: arch/arm64/include/asm/pgtable.h:757
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffff80001030618c)
Location: arch/arm64/include/asm/pgtable.h:757
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffff800010308214)
Location: arch/arm64/include/asm/pgtable.h:757
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (0)
Location: arch/arm64/include/asm/pgtable.h:757
Inline: True
```
```
In mm/vmalloc.c (ffff80001030c7c0)
Location: arch/arm64/include/asm/pgtable.h:757
Inline: True
```
```
In mm/madvise.c (ffff80001031ec38)
Location: arch/arm64/include/asm/pgtable.h:757
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffff800010357f90)
Location: arch/arm64/include/asm/pgtable.h:757
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In mm/memory.c (c0518ecc)
Location: include/asm-generic/pgtable.h:125
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mprotect.c (c0523374)
Location: include/asm-generic/pgtable.h:125
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0523f88)
Location: include/asm-generic/pgtable.h:125
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (c05255c0)
Location: include/asm-generic/pgtable.h:125
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable.h:125
Inline: True
```
```
In mm/vmalloc.c (c05282e4)
Location: include/asm-generic/pgtable.h:125
Inline: True
```
```
In mm/madvise.c (c0537848)
Location: include/asm-generic/pgtable.h:125
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
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
In mm/memory.c (c0000000003bee50)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:451
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mremap.c (c0000000003d3724)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:451
Inline: True
```
```
In mm/pgtable-generic.c (c0000000003d71d8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:451
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (c0000000003d9e00)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:451
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (c0000000003dcd70)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:451
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_page_range
```
```
In mm/madvise.c (c0000000003f38e0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:451
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (c000000000434cc4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:451
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe0002076a6)
Location: arch/riscv/include/asm/pgtable.h:363
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mprotect.c (ffffffe000211204)
Location: arch/riscv/include/asm/pgtable.h:363
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffe000211c38)
Location: arch/riscv/include/asm/pgtable.h:363
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffe000212d54)
Location: arch/riscv/include/asm/pgtable.h:363
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (0)
Location: arch/riscv/include/asm/pgtable.h:363
Inline: True
```
```
In mm/vmalloc.c (ffffffe00021561e)
Location: arch/riscv/include/asm/pgtable.h:363
Inline: True
```
```
In mm/madvise.c (ffffffe000220648)
Location: arch/riscv/include/asm/pgtable.h:363
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffe000230dde)
Location: arch/riscv/include/asm/pgtable.h:363
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023240)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_start
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077660)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In mm/memory.c (ffffffff81257a8a)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
```
```
In mm/mremap.c (ffffffff81268139)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff8126adaf)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff8126cdb8)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8126ecac)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
```
```
In mm/madvise.c (ffffffff8127d14c)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8128e82b)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/migrate.c (ffffffff812a6f9b)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124da0f)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff81258d40)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8125a365)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff8125cddf)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff8125edf1)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff812605cc)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
```
```
In mm/madvise.c (ffffffff8126efbc)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff812805ec)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/migrate.c (ffffffff812989d7)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8135a1e0)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810230a0)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_start
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077610)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In mm/memory.c (ffffffff8125582a)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
```
```
In mm/mremap.c (ffffffff81265ed9)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81268b4f)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff8126ab58)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8126ca4c)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
```
```
In mm/madvise.c (ffffffff8127aeec)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8128c63b)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/migrate.c (ffffffff812a4dab)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023510)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_start
```
```
In arch/x86/kernel/paravirt.c (ffffffff810796b0)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_start
```
```
In mm/memory.c (ffffffff812652e1)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
```
```
In mm/mremap.c (ffffffff8127587b)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff812784df)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffffffff8127a4c1)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8127c58c)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
```
```
In mm/madvise.c (ffffffff8128aab8)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8129c423)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/migrate.c (ffffffff812b5907)
Location: arch/x86/include/asm/pgtable.h:1120
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
</details>
</li>
</ul>

## Differences
