# Function: <code>mmu_notifier_range_blockable</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8128e677)
Location: include/linux/mmu_notifier.h:266
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
```
In mm/hmm.c (ffffffff812c3a6a)
Location: include/linux/mmu_notifier.h:266
Inline: True
Inline callers:
  - mm/hmm.c:hmm_invalidate_range_start
  - mm/hmm.c:hmm_invalidate_range_start
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
In kernel/events/uprobes.c (ffffffff8121a2ba)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff8122a346)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff8125d0ce)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff8126e87b)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126fb32)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812742d1)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8128375f)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8129636b)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mmu_notifier.c (ffffffff8129e45f)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
```
In mm/ksm.c (ffffffff8129f5da)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812afee6)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff812b4511)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812bd171)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff812d4fbd)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/hmm.c:hmm_invalidate_range_start
  - mm/hmm.c:hmm_invalidate_range_start
```
```
In fs/dax.c (ffffffff81347563)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8136efb2)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff81246c3f)
Location: include/linux/mmu_notifier.h:395
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81257116)
Location: include/linux/mmu_notifier.h:395
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff8128d6f2)
Location: include/linux/mmu_notifier.h:395
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff8129ed5f)
Location: include/linux/mmu_notifier.h:395
Inline: True
```
```
In mm/mremap.c (ffffffff812a05ae)
Location: include/linux/mmu_notifier.h:395
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812a556b)
Location: include/linux/mmu_notifier.h:395
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812b55c2)
Location: include/linux/mmu_notifier.h:395
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff812c98ec)
Location: include/linux/mmu_notifier.h:395
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mmu_notifier.c (ffffffff812d2a68)
Location: include/linux/mmu_notifier.h:395
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mn_hlist_invalidate_range_start
  - mm/mmu_notifier.c:mn_hlist_invalidate_range_start
  - mm/mmu_notifier.c:mn_itree_invalidate
```
```
In mm/ksm.c (ffffffff812d3c28)
Location: include/linux/mmu_notifier.h:395
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812e2240)
Location: include/linux/mmu_notifier.h:395
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect
```
```
In mm/khugepaged.c (ffffffff812f2886)
Location: include/linux/mmu_notifier.h:395
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c3b7)
Location: include/linux/mmu_notifier.h:395
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/dax.c (ffffffff8138d946)
Location: include/linux/mmu_notifier.h:395
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813b72f7)
Location: include/linux/mmu_notifier.h:395
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff812512af)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81261cf6)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff8129fba3)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff812aa128)
Location: include/linux/mmu_notifier.h:401
Inline: True
```
```
In mm/mremap.c (ffffffff812aba8f)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812b09f9)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812c0882)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff812d547a)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mmu_notifier.c (ffffffff81be8c68)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mn_hlist_invalidate_range_start
  - mm/mmu_notifier.c:mn_hlist_invalidate_range_start
  - mm/mmu_notifier.c:mn_itree_invalidate
```
```
In mm/ksm.c (ffffffff812df622)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812ed546)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect
```
```
In mm/khugepaged.c (ffffffff812fceaf)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff813182f7)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/dax.c (ffffffff8139f3c6)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813c8baa)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff812553a9)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff812667b8)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff812a5433)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff812af5a7)
Location: include/linux/mmu_notifier.h:401
Inline: True
```
```
In mm/mremap.c (ffffffff812b0e8b)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812b602b)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812c780b)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff812de9d9)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mmu_notifier.c (ffffffff812e5a6a)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:mn_hlist_invalidate_range_start
  - mm/mmu_notifier.c:mn_hlist_invalidate_range_start
```
```
In mm/ksm.c (ffffffff812e7f5e)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812f52bc)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/khugepaged.c (ffffffff81303c24)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e4e7)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/dax.c (ffffffff813a6133)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813cfbe9)
Location: include/linux/mmu_notifier.h:401
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff81290de8)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff812a2d88)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff812dee81)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff812f0dd6)
Location: include/linux/mmu_notifier.h:407
Inline: True
```
```
In mm/mremap.c (ffffffff812f2960)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812f8d0d)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8130c5cb)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff81325dbe)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mmu_notifier.c (ffffffff8132d87f)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
```
In mm/ksm.c (ffffffff8132fe6c)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff8133f8bc)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/khugepaged.c (ffffffff8134d95f)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136b8c7)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/dax.c (ffffffff813f5ba3)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81420fc6)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff812e60c7)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff812fabc6)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff8133ee44)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff8135472f)
Location: include/linux/mmu_notifier.h:407
Inline: True
```
```
In mm/mremap.c (ffffffff8135659c)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8135f2ee)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81375bc4)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff81394b29)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mmu_notifier.c (ffffffff8139da87)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
```
In mm/ksm.c (ffffffff813a023d)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff813b6d1c)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/khugepaged.c (ffffffff813c6bc6)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9a4b)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff81498e5c)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff8134fd1b)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81362cfd)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff813b612a)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff813cec51)
Location: include/linux/mmu_notifier.h:407
Inline: True
```
```
In mm/mremap.c (ffffffff813d0bc6)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff813da1a9)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff813f3152)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8140de89)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mmu_notifier.c (ffffffff8141cf9e)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
```
In mm/ksm.c (ffffffff8141f12b)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8143871e)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/khugepaged.c (ffffffff8144731e)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471a8b)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff8152d1c9)
Location: include/linux/mmu_notifier.h:407
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff81380eb4)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81395131)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff813ea9ae)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff8140353e)
Location: include/linux/mmu_notifier.h:406
Inline: True
```
```
In mm/mremap.c (ffffffff81405602)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8140e8e9)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81426ba7)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff81441269)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mmu_notifier.c (ffffffff8145055d)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
```
In mm/ksm.c (ffffffff81453c82)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8146e40f)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/khugepaged.c (ffffffff8147c9f5)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a63db)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff81564ef7)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff813aa280)
Location: include/linux/mmu_notifier.h:405
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff813beef0)
Location: include/linux/mmu_notifier.h:405
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff814170d8)
Location: include/linux/mmu_notifier.h:405
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff8142face)
Location: include/linux/mmu_notifier.h:405
Inline: True
```
```
In mm/mremap.c (ffffffff81431b27)
Location: include/linux/mmu_notifier.h:405
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8143b10d)
Location: include/linux/mmu_notifier.h:405
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff814607ea)
Location: include/linux/mmu_notifier.h:405
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8147b368)
Location: include/linux/mmu_notifier.h:405
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mmu_notifier.c (ffffffff8148a28d)
Location: include/linux/mmu_notifier.h:405
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
```
In mm/ksm.c (ffffffff8148e539)
Location: include/linux/mmu_notifier.h:405
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8149d994)
Location: include/linux/mmu_notifier.h:405
Inline: True
Inline callers:
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff814a5e65)
Location: include/linux/mmu_notifier.h:405
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:move_pages_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814acd01)
Location: include/linux/mmu_notifier.h:405
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff814d2d0e)
Location: include/linux/mmu_notifier.h:405
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d732b)
Location: include/linux/mmu_notifier.h:405
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff8159bf3a)
Location: include/linux/mmu_notifier.h:405
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:do_pagemap_scan
  - fs/proc/task_mmu.c:clear_refs_write
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
In virt/kvm/kvm_main.c (ffff8000100bb494)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_invalidate_range_start
```
```
In kernel/events/uprobes.c (ffff8000102a56cc)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffff8000102b8300)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffff8000102f457c)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffff80001030552c)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffff800010305fd4)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffff800010309ef8)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffff80001031def4)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffff800010335a70)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mmu_notifier.c (ffff80001033d7c0)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
```
In mm/ksm.c (ffff80001033ec54)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffff800010355adc)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffff80001035e48c)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffff80001037af18)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/hmm.c:hmm_invalidate_range_start
  - mm/hmm.c:hmm_invalidate_range_start
```
```
In fs/dax.c (ffff8000104076fc)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffff80001043939c)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (c04d4b50)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (c04e4ab0)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (c051971c)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (c0523578)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c052409c)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (c0526740)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (c0537580)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/mmu_notifier.c (c0543e24)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
```
In mm/ksm.c (c0545094)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/hmm.c (c056572c)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/hmm.c:hmm_invalidate_range_start
  - mm/hmm.c:hmm_invalidate_range_start
```
```
In fs/proc/task_mmu.c (c0600310)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (c00000000035844c)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (c0000000003703d8)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (c0000000003bb0ec)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (c0000000003d2a90)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d3e60)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (c0000000003d98c8)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (c0000000003f1ac8)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (c00000000040fdf8)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mmu_notifier.c (c000000000418f60)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
```
In mm/ksm.c (c00000000041ae08)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (c000000000435e8c)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (c00000000043d30c)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (c000000000447958)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (c00000000046eaa0)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/hmm.c:hmm_invalidate_range_start
  - mm/hmm.c:hmm_invalidate_range_start
```
```
In fs/dax.c (c0000000005126f8)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (c00000000054c204)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In mm/oom_kill.c (ffffffe0001dc0f8)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffe0002066f0)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffe0002114b0)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffe000211cfa)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffe000213e58)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffe000220ef4)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffe000230da4)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mmu_notifier.c (ffffffe000232e80)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
```
In mm/ksm.c (ffffffe000234a34)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/hmm.c (ffffffe00025177e)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/hmm.c:hmm_invalidate_range_start
  - mm/hmm.c:hmm_invalidate_range_start
```
```
In fs/dax.c (ffffffe0002b2d30)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffe0002d30da)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff8121290a)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81222996)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff8125571e)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff81266ecb)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81268182)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8126c921)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8127bdaf)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8128e94b)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mmu_notifier.c (ffffffff81296a3f)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
```
In mm/ksm.c (ffffffff81297bba)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a84c6)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff812acaf1)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b5751)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff812cd59d)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/hmm.c:hmm_invalidate_range_start
  - mm/hmm.c:hmm_invalidate_range_start
```
```
In fs/dax.c (ffffffff8133fb43)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81367592)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff81205672)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81215b46)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff81247e12)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff8125925a)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8125a3a9)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8125e973)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8126dc8f)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff812806f8)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mmu_notifier.c (ffffffff8128864f)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
```
In mm/ksm.c (ffffffff81289743)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81299e86)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff8129eb3a)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812a6797)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff812be40d)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/hmm.c:hmm_invalidate_range_start
  - mm/hmm.c:hmm_invalidate_range_start
```
```
In fs/dax.c (ffffffff81330755)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81358232)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff812106aa)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81220736)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff812534be)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff81264c6b)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81265f22)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8126a6c1)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff81279b4f)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8128c75b)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mmu_notifier.c (ffffffff8129484f)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
```
In mm/ksm.c (ffffffff812959ca)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a62d6)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff812aa901)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b3561)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff812cb3ad)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/hmm.c:hmm_invalidate_range_start
  - mm/hmm.c:hmm_invalidate_range_start
```
```
In fs/dax.c (ffffffff8133d613)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81365062)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (0)
Location: include/linux/mmu_notifier.h:299
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/mmu_notifier.h:299
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mmu_notifier.h:299
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mmu_notifier.h:299
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/mmu_notifier.h:299
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/mmu_notifier.h:299
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/mmu_notifier.h:299
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/mmu_notifier.h:299
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff812a46bf)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
```
In mm/ksm.c (0)
Location: include/linux/mmu_notifier.h:299
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/mmu_notifier.h:299
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/mmu_notifier.h:299
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/mmu_notifier.h:299
Inline: True
```
```
In mm/hmm.c (ffffffff812dc10d)
Location: include/linux/mmu_notifier.h:299
Inline: True
Inline callers:
  - mm/hmm.c:hmm_invalidate_range_start
  - mm/hmm.c:hmm_invalidate_range_start
```
```
In fs/dax.c (0)
Location: include/linux/mmu_notifier.h:299
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mmu_notifier.h:299
Inline: True
```
</details>
</li>
</ul>

## Differences
