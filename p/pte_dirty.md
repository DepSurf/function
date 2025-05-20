# Function: <code>pte_dirty</code>

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
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:100
Inline: True
```
```
In mm/memory.c (ffffffff811bdb44)
Location: arch/x86/include/asm/pgtable.h:100
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mprotect.c (ffffffff811c88e5)
Location: arch/x86/include/asm/pgtable.h:100
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff811cb1ce)
Location: arch/x86/include/asm/pgtable.h:100
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable.h:100
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:100
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81278957)
Location: arch/x86/include/asm/pgtable.h:100
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:97
Inline: True
```
```
In mm/memory.c (ffffffff811d91b7)
Location: arch/x86/include/asm/pgtable.h:97
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mprotect.c (ffffffff811e4ba3)
Location: arch/x86/include/asm/pgtable.h:97
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff811e8288)
Location: arch/x86/include/asm/pgtable.h:97
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:97
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable.h:97
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:97
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812a47fd)
Location: arch/x86/include/asm/pgtable.h:97
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
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
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:97
Inline: True
```
```
In mm/memory.c (ffffffff811e8639)
Location: arch/x86/include/asm/pgtable.h:97
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mprotect.c (ffffffff811f4bcc)
Location: arch/x86/include/asm/pgtable.h:97
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable.h:97
Inline: True
```
```
In mm/rmap.c (ffffffff811f96b1)
Location: arch/x86/include/asm/pgtable.h:97
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:97
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable.h:97
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:97
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:97
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812ba184)
Location: arch/x86/include/asm/pgtable.h:97
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
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
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:109
Inline: True
```
```
In mm/memory.c (ffffffff811f3765)
Location: arch/x86/include/asm/pgtable.h:109
Inline: True
```
```
In mm/mprotect.c (ffffffff811ffa8b)
Location: arch/x86/include/asm/pgtable.h:109
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable.h:109
Inline: True
```
```
In mm/rmap.c (ffffffff812042eb)
Location: arch/x86/include/asm/pgtable.h:109
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:109
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable.h:109
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:109
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:109
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812c78db)
Location: arch/x86/include/asm/pgtable.h:109
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
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
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:119
Inline: True
```
```
In mm/memory.c (ffffffff8120b0c1)
Location: arch/x86/include/asm/pgtable.h:119
Inline: True
```
```
In mm/mprotect.c (ffffffff812181c0)
Location: arch/x86/include/asm/pgtable.h:119
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable.h:119
Inline: True
```
```
In mm/rmap.c (ffffffff8121d0b3)
Location: arch/x86/include/asm/pgtable.h:119
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:119
Inline: True
```
```
In mm/hugetlb.c (ffffffff81232f33)
Location: arch/x86/include/asm/pgtable.h:119
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:119
Inline: True
```
```
In fs/dax.c (ffffffff812ce223)
Location: arch/x86/include/asm/pgtable.h:119
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff812eb4f9)
Location: arch/x86/include/asm/pgtable.h:119
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/gup.c (ffffffff812266d2)
Location: arch/x86/include/asm/pgtable.h:119
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8122bebf)
Location: arch/x86/include/asm/pgtable.h:119
Inline: True
```
```
In mm/mprotect.c (ffffffff812392f8)
Location: arch/x86/include/asm/pgtable.h:119
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8123ad9d)
Location: arch/x86/include/asm/pgtable.h:119
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8123efb6)
Location: arch/x86/include/asm/pgtable.h:119
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:119
Inline: True
```
```
In mm/hugetlb.c (ffffffff81255ef4)
Location: arch/x86/include/asm/pgtable.h:119
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/ksm.c (ffffffff8126075a)
Location: arch/x86/include/asm/pgtable.h:119
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In fs/dax.c (ffffffff812f87f3)
Location: arch/x86/include/asm/pgtable.h:119
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff8131881a)
Location: arch/x86/include/asm/pgtable.h:119
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/gup.c (ffffffff8123aa12)
Location: arch/x86/include/asm/pgtable.h:121
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8123f2db)
Location: arch/x86/include/asm/pgtable.h:121
Inline: True
```
```
In mm/mprotect.c (ffffffff8124d897)
Location: arch/x86/include/asm/pgtable.h:121
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff812535cf)
Location: arch/x86/include/asm/pgtable.h:121
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:121
Inline: True
```
```
In mm/hugetlb.c (ffffffff8126a37b)
Location: arch/x86/include/asm/pgtable.h:121
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/ksm.c (ffffffff81274e9e)
Location: arch/x86/include/asm/pgtable.h:121
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In fs/dax.c (ffffffff8130c4ec)
Location: arch/x86/include/asm/pgtable.h:121
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8132fa7a)
Location: arch/x86/include/asm/pgtable.h:121
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/gup.c (ffffffff8124bcc5)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81250c1a)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
```
```
In mm/mprotect.c (ffffffff8125f899)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81265839)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
```
```
In mm/hugetlb.c (ffffffff812854a0)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/ksm.c (ffffffff8128efcd)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
```
```
In fs/dax.c (ffffffff81333a2b)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813578da)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/gup.c (ffffffff8125a1b5)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125f1fa)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
```
```
In mm/mprotect.c (ffffffff8126e0a9)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8127414e)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
```
```
In mm/hugetlb.c (ffffffff81295045)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/ksm.c (ffffffff8129ed3c)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
```
```
In fs/dax.c (ffffffff813475f1)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8136fb0a)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/gup.c (ffffffff81288464)
Location: arch/x86/include/asm/pgtable.h:125
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8128f5cd)
Location: arch/x86/include/asm/pgtable.h:125
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff8129e6ca)
Location: arch/x86/include/asm/pgtable.h:125
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812a53ce)
Location: arch/x86/include/asm/pgtable.h:125
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:125
Inline: True
```
```
In mm/hugetlb.c (ffffffff812c8631)
Location: arch/x86/include/asm/pgtable.h:125
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/ksm.c (ffffffff812d3830)
Location: arch/x86/include/asm/pgtable.h:125
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c6a5)
Location: arch/x86/include/asm/pgtable.h:125
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In fs/dax.c (ffffffff8138d9f8)
Location: arch/x86/include/asm/pgtable.h:125
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813b6faa)
Location: arch/x86/include/asm/pgtable.h:125
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
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
In mm/gup.c (ffffffff81292159)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129a0da)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff812a9a8a)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812b0862)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
```
```
In mm/hugetlb.c (ffffffff812d41bd)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/ksm.c (ffffffff812df245)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff813185e5)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In fs/dax.c (ffffffff8139f478)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813c864a)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
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
In mm/gup.c (ffffffff81297dc3)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129f2fc)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff812aef15)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812b5e8d)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
```
```
In mm/hugetlb.c (ffffffff812db09b)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/ksm.c (ffffffff812e6a1e)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e7d5)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In fs/dax.c (ffffffff813a61e2)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813cf687)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
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
In mm/gup.c (ffffffff812d8803)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812e0561)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff812f0705)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812f8c68)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
```
```
In mm/hugetlb.c (ffffffff81322115)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/ksm.c (ffffffff8132e93e)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bbb5)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In fs/dax.c (ffffffff813f5c52)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81420a67)
Location: arch/x86/include/asm/pgtable.h:124
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
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
In mm/gup.c (ffffffff813387c7)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81340c43)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff81353d15)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8135f24d)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
```
```
In mm/hugetlb.c (ffffffff8138f3e5)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/ksm.c (ffffffff813a0716)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9d65)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In fs/proc/task_mmu.c (ffffffff8149993e)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/vmscan.c (ffffffff813873f8)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
```
```
In mm/gup.c (ffffffff813aff80)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813b8bda)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
```
```
In mm/rmap.c (ffffffff813da105)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
```
```
In mm/hugetlb.c (ffffffff8140fb7a)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/ksm.c (ffffffff8141fef9)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff81438ecc)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471de5)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In fs/proc/task_mmu.c (ffffffff8152db55)
Location: arch/x86/include/asm/pgtable.h:127
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/vmscan.c (ffffffff813b7917)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
```
```
In mm/gup.c (ffffffff813e45d2)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813ed818)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
```
```
In mm/rmap.c (ffffffff8140e84b)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:set_tlb_ubc_flush_pending
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
```
```
In mm/hugetlb.c (ffffffff81442f3f)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/ksm.c (ffffffff81454b10)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8146f70a)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a6738)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In fs/proc/task_mmu.c (ffffffff81565f85)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/vmscan.c (ffffffff813e0730)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
```
```
In mm/gup.c (ffffffff8140ed6a)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81416856)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff8142ed8d)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
Inline callers:
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/rmap.c (ffffffff8143b061)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
```
```
In mm/hugetlb.c (ffffffff8147d13c)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/ksm.c (ffffffff8148fcfc)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate_device.c (ffffffff8149e344)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff814ac5dc)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d779f)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In fs/proc/task_mmu.c (ffffffff8159df55)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_entry
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/xmon/xmon.c (c00000000010ae4c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:480
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:format_pte
```
```
In mm/gup.c (c0000000003b6590)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:480
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003beb68)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:480
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (c0000000003d221c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:480
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (c0000000003d9728)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:480
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (c0000000003f3464)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:480
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (c00000000040c838)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:480
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/ksm.c (c000000000419f0c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:480
Inline: True
```
```
In mm/huge_memory.c (c000000000444180)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:480
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In fs/dax.c (c000000000512684)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:480
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (c00000000054c828)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:480
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/gup.c (ffffffe0002047a4)
Location: arch/riscv/include/asm/pgtable.h:230
Inline: True
```
```
In mm/memory.c (ffffffe0002076ec)
Location: arch/riscv/include/asm/pgtable.h:230
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mprotect.c (ffffffe00021121e)
Location: arch/riscv/include/asm/pgtable.h:230
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffe000213d3c)
Location: arch/riscv/include/asm/pgtable.h:230
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (0)
Location: arch/riscv/include/asm/pgtable.h:230
Inline: True
```
```
In mm/hugetlb.c (ffffffe00022fdde)
Location: arch/riscv/include/asm/pgtable.h:230
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/ksm.c (ffffffe0002346ee)
Location: arch/riscv/include/asm/pgtable.h:230
Inline: True
```
```
In fs/dax.c (0)
Location: arch/riscv/include/asm/pgtable.h:230
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffe0002d3212)
Location: arch/riscv/include/asm/pgtable.h:230
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/gup.c (ffffffff81252805)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125784a)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
```
```
In mm/mprotect.c (ffffffff812666f9)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8126c79e)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128d625)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/ksm.c (ffffffff8129731c)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
```
```
In fs/dax.c (ffffffff8133fbd1)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813680ea)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/gup.c (ffffffff8124566b)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124a1d1)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff81258dcb)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff8125e7f6)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
```
```
In mm/hugetlb.c (ffffffff8127f3c8)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/ksm.c (ffffffff81288f1e)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
```
```
In fs/dax.c (ffffffff8133086f)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813589e2)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/gup.c (ffffffff812505a5)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812555ea)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
```
```
In mm/mprotect.c (ffffffff81264499)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8126a53e)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128b435)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/ksm.c (ffffffff8129512c)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
```
```
In fs/dax.c (ffffffff8133d6a1)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81365bba)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/gup.c (ffffffff8125ff25)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81265092)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
```
```
In mm/mprotect.c (ffffffff81273e59)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81279ec2)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129b250)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/ksm.c (ffffffff812a4f9b)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
```
```
In fs/dax.c (ffffffff813505b4)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8137924a)
Location: arch/x86/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
</details>
</li>
</ul>

## Differences
