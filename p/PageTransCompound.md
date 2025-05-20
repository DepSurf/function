# Function: <code>PageTransCompound</code>

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
In mm/ksm.c (ffffffff811e46e5)
Location: include/linux/page-flags.h:472
Inline: True
Inline callers:
  - mm/ksm.c:page_trans_compound_anon
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In fs/proc/page.c (ffffffff81288242)
Location: include/linux/page-flags.h:472
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/shmem.c (ffffffff811c0053)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/gup.c (ffffffff811d49bd)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811da20f)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff811df238)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (ffffffff811e821a)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff811eec68)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/mempolicy.c (ffffffff811fee96)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81203ee8)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff81210040)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81216966)
Location: include/linux/page-flags.h:530
Inline: True
```
```
In mm/khugepaged.c (ffffffff8121c6dc)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff81221241)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In fs/proc/page.c (ffffffff812b5691)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/shmem.c (ffffffff811d0223)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/gup.c (ffffffff811e4a27)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811e9d3f)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff811ef04c)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (ffffffff811f9599)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff811ff598)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/mempolicy.c (ffffffff812106d0)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81215ed7)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81222169)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81228f26)
Location: include/linux/page-flags.h:546
Inline: True
```
```
In mm/khugepaged.c (ffffffff8122e100)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff81233985)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In fs/proc/page.c (ffffffff812caf18)
Location: include/linux/page-flags.h:546
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/shmem.c (ffffffff811d8cc9)
Location: include/linux/page-flags.h:549
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/gup.c (ffffffff811ef03f)
Location: include/linux/page-flags.h:549
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f4e3c)
Location: include/linux/page-flags.h:549
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff811f9fe9)
Location: include/linux/page-flags.h:549
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (ffffffff81204714)
Location: include/linux/page-flags.h:549
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff8120a250)
Location: include/linux/page-flags.h:549
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swap_state.c (ffffffff8120c43f)
Location: include/linux/page-flags.h:549
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/mempolicy.c (ffffffff8121c0cd)
Location: include/linux/page-flags.h:549
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff812215e7)
Location: include/linux/page-flags.h:549
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8122dfe4)
Location: include/linux/page-flags.h:549
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81234c06)
Location: include/linux/page-flags.h:549
Inline: True
```
```
In mm/khugepaged.c (ffffffff8123a3da)
Location: include/linux/page-flags.h:549
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff8123f233)
Location: include/linux/page-flags.h:549
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In fs/proc/page.c (ffffffff812d83b5)
Location: include/linux/page-flags.h:549
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/shmem.c (ffffffff811edf0e)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/gup.c (ffffffff8120610a)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8120cf3c)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff8121247e)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (ffffffff8121d66e)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff812234b2)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swap_state.c (ffffffff812261e3)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap_state.c:do_swap_page_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81229bb9)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/mempolicy.c (ffffffff81237504)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff8123c8f7)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8124b4b6)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81254626)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
```
```
In mm/khugepaged.c (ffffffff812590fa)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff8125ef93)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/page.c (ffffffff812fcab5)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/shmem.c (ffffffff8120f3ac)
Location: include/linux/page-flags.h:557
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/gup.c (ffffffff8122641f)
Location: include/linux/page-flags.h:557
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8122dafc)
Location: include/linux/page-flags.h:557
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff812331d8)
Location: include/linux/page-flags.h:557
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (ffffffff8123f498)
Location: include/linux/page-flags.h:557
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff81246326)
Location: include/linux/page-flags.h:557
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swap_state.c (ffffffff81247c65)
Location: include/linux/page-flags.h:557
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8124ae72)
Location: include/linux/page-flags.h:557
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff81261cdb)
Location: include/linux/page-flags.h:557
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8126e03a)
Location: include/linux/page-flags.h:557
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81278475)
Location: include/linux/page-flags.h:557
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
```
```
In mm/khugepaged.c (ffffffff8127d4ad)
Location: include/linux/page-flags.h:557
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff8128310c)
Location: include/linux/page-flags.h:557
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/page.c (ffffffff8132a6d4)
Location: include/linux/page-flags.h:557
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/shmem.c (ffffffff81221bdc)
Location: include/linux/page-flags.h:574
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/gup.c (ffffffff8123a77b)
Location: include/linux/page-flags.h:574
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81241275)
Location: include/linux/page-flags.h:574
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff812469a6)
Location: include/linux/page-flags.h:574
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (ffffffff81253bde)
Location: include/linux/page-flags.h:574
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff8125a746)
Location: include/linux/page-flags.h:574
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swap_state.c (ffffffff8125c23a)
Location: include/linux/page-flags.h:574
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8126088c)
Location: include/linux/page-flags.h:574
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff81276574)
Location: include/linux/page-flags.h:574
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81282eaa)
Location: include/linux/page-flags.h:574
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8128cac5)
Location: include/linux/page-flags.h:574
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
```
```
In mm/khugepaged.c (ffffffff8129213e)
Location: include/linux/page-flags.h:574
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8129915c)
Location: include/linux/page-flags.h:574
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/page.c (ffffffff81341a2f)
Location: include/linux/page-flags.h:574
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/shmem.c (ffffffff81231449)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/gup.c (ffffffff8124ba91)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81253579)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff81258c32)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (ffffffff81265fbf)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff81275826)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swap_state.c (ffffffff8127741a)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8127a17e)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff812916e6)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8129de1c)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a77c5)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
```
```
In mm/khugepaged.c (ffffffff812acb4d)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff812b4531)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/page.c (ffffffff81369e55)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/shmem.c (ffffffff8123f509)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/gup.c (ffffffff81259f81)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81261ad9)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff81267102)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (ffffffff812748ec)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff812847f6)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff81286efa)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81289c5e)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff812a1466)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812ae968)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b8c65)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
```
```
In mm/khugepaged.c (ffffffff812be437)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812c5e51)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/page.c (ffffffff81382075)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/shmem.c (ffffffff8126cd4c)
Location: include/linux/page-flags.h:623
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/gup.c (ffffffff812884a1)
Location: include/linux/page-flags.h:623
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81291d0e)
Location: include/linux/page-flags.h:623
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff81296ab6)
Location: include/linux/page-flags.h:623
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
```
```
In mm/page_vma_mapped.c (ffffffff812a1a18)
Location: include/linux/page-flags.h:623
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812a5c6e)
Location: include/linux/page-flags.h:623
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (ffffffff812b4087)
Location: include/linux/page-flags.h:623
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/madvise.c (ffffffff812b69a1)
Location: include/linux/page-flags.h:623
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff812b947a)
Location: include/linux/page-flags.h:623
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff812bcb92)
Location: include/linux/page-flags.h:623
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/ksm.c (ffffffff812d6377)
Location: include/linux/page-flags.h:623
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812e40a2)
Location: include/linux/page-flags.h:623
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ed815)
Location: include/linux/page-flags.h:623
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
```
```
In mm/khugepaged.c (ffffffff812f2387)
Location: include/linux/page-flags.h:623
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812fbb39)
Location: include/linux/page-flags.h:623
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/page.c (ffffffff813cc6a5)
Location: include/linux/page-flags.h:623
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/shmem.c (ffffffff812777f1)
Location: include/linux/page-flags.h:627
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/gup.c (ffffffff8129218a)
Location: include/linux/page-flags.h:627
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129c5d5)
Location: include/linux/page-flags.h:627
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff812a1926)
Location: include/linux/page-flags.h:627
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
```
```
In mm/page_vma_mapped.c (ffffffff812ad2d5)
Location: include/linux/page-flags.h:627
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812b10f5)
Location: include/linux/page-flags.h:627
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (ffffffff812bfb14)
Location: include/linux/page-flags.h:627
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/madvise.c (ffffffff812c2bf1)
Location: include/linux/page-flags.h:627
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff812c4e13)
Location: include/linux/page-flags.h:627
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff812c86c2)
Location: include/linux/page-flags.h:627
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/ksm.c (ffffffff812e1e8c)
Location: include/linux/page-flags.h:627
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812efd35)
Location: include/linux/page-flags.h:627
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812f8e95)
Location: include/linux/page-flags.h:627
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
```
```
In mm/khugepaged.c (ffffffff812fe83f)
Location: include/linux/page-flags.h:627
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff81307789)
Location: include/linux/page-flags.h:627
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/page.c (ffffffff813de307)
Location: include/linux/page-flags.h:627
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/shmem.c (ffffffff8127c651)
Location: include/linux/page-flags.h:621
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff81297ed6)
Location: include/linux/page-flags.h:621
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812a1b06)
Location: include/linux/page-flags.h:621
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:finish_fault
```
```
In mm/mlock.c (ffffffff812a70e6)
Location: include/linux/page-flags.h:621
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
```
```
In mm/page_vma_mapped.c (ffffffff812b2506)
Location: include/linux/page-flags.h:621
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812b66bd)
Location: include/linux/page-flags.h:621
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (ffffffff812c5274)
Location: include/linux/page-flags.h:621
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/madvise.c (ffffffff812c9a6d)
Location: include/linux/page-flags.h:621
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff812cbaa7)
Location: include/linux/page-flags.h:621
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff812cf072)
Location: include/linux/page-flags.h:621
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/ksm.c (ffffffff812e9629)
Location: include/linux/page-flags.h:621
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812f56ba)
Location: include/linux/page-flags.h:621
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ff4d5)
Location: include/linux/page-flags.h:621
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
```
```
In mm/khugepaged.c (ffffffff813054bf)
Location: include/linux/page-flags.h:621
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8130df0a)
Location: include/linux/page-flags.h:621
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/page.c (ffffffff813e50ec)
Location: include/linux/page-flags.h:621
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/shmem.c (ffffffff812bf1d1)
Location: include/linux/page-flags.h:641
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff812d8916)
Location: include/linux/page-flags.h:641
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812e2ad6)
Location: include/linux/page-flags.h:641
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:finish_fault
```
```
In mm/mlock.c (ffffffff812e85e1)
Location: include/linux/page-flags.h:641
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
```
```
In mm/page_vma_mapped.c (ffffffff812f40f6)
Location: include/linux/page-flags.h:641
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812f9917)
Location: include/linux/page-flags.h:641
Inline: True
Inline callers:
  - mm/rmap.c:page_mlock
  - mm/rmap.c:page_mlock
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (ffffffff813097c1)
Location: include/linux/page-flags.h:641
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/madvise.c (ffffffff8130ea8d)
Location: include/linux/page-flags.h:641
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff81310b9e)
Location: include/linux/page-flags.h:641
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81314612)
Location: include/linux/page-flags.h:641
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/ksm.c (ffffffff81331565)
Location: include/linux/page-flags.h:641
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff8133fcbb)
Location: include/linux/page-flags.h:641
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff813490e5)
Location: include/linux/page-flags.h:641
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
```
```
In mm/khugepaged.c (ffffffff8134f2fa)
Location: include/linux/page-flags.h:641
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff81358d69)
Location: include/linux/page-flags.h:641
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/page.c (ffffffff81436cbc)
Location: include/linux/page-flags.h:641
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/shmem.c (ffffffff8131ae8e)
Location: include/linux/page-flags.h:864
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff813433f8)
Location: include/linux/page-flags.h:864
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
```
```
In mm/mlock.c (ffffffff8134c6e3)
Location: include/linux/page-flags.h:864
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/rmap.c (ffffffff8135d459)
Location: include/linux/page-flags.h:864
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff813768bf)
Location: include/linux/page-flags.h:864
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8137b956)
Location: include/linux/page-flags.h:864
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8137faa2)
Location: include/linux/page-flags.h:864
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_free_swap
```
```
In mm/ksm.c (ffffffff813a23ca)
Location: include/linux/page-flags.h:864
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff813b731d)
Location: include/linux/page-flags.h:864
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (0)
Location: include/linux/page-flags.h:864
Inline: True
```
```
In mm/khugepaged.c (ffffffff813c5e9c)
Location: include/linux/page-flags.h:864
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff813d2f87)
Location: include/linux/page-flags.h:864
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/page_isolation.c (ffffffff813ddced)
Location: include/linux/page-flags.h:864
Inline: True
```
```
In fs/proc/page.c (ffffffff814b151c)
Location: include/linux/page-flags.h:864
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/shmem.c (ffffffff8138ccd1)
Location: include/linux/page-flags.h:861
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/memory.c (ffffffff813bb438)
Location: include/linux/page-flags.h:861
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
```
```
In mm/mlock.c (ffffffff813c527a)
Location: include/linux/page-flags.h:861
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/rmap.c (ffffffff813d8024)
Location: include/linux/page-flags.h:861
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
```
```
In mm/madvise.c (ffffffff813f4b2d)
Location: include/linux/page-flags.h:861
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/ksm.c (ffffffff81422026)
Location: include/linux/page-flags.h:861
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff81438e26)
Location: include/linux/page-flags.h:861
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8144aa33)
Location: include/linux/page-flags.h:861
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff814587b0)
Location: include/linux/page-flags.h:861
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/page_isolation.c (ffffffff8146497d)
Location: include/linux/page-flags.h:861
Inline: True
```
```
In fs/proc/page.c (ffffffff81547ec5)
Location: include/linux/page-flags.h:861
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/memory.c (ffffffff813eff67)
Location: include/linux/page-flags.h:845
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
```
```
In mm/ksm.c (ffffffff81456d10)
Location: include/linux/page-flags.h:845
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8146f669)
Location: include/linux/page-flags.h:845
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff81480b29)
Location: include/linux/page-flags.h:845
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8148e375)
Location: include/linux/page-flags.h:845
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/page_isolation.c (ffffffff8149a47d)
Location: include/linux/page-flags.h:845
Inline: True
```
```
In fs/proc/page.c (ffffffff8157fac7)
Location: include/linux/page-flags.h:845
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/memory.c (ffffffff8141b5c7)
Location: include/linux/page-flags.h:875
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
```
```
In mm/ksm.c (ffffffff81491817)
Location: include/linux/page-flags.h:875
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8149e177)
Location: include/linux/page-flags.h:875
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff814aeb09)
Location: include/linux/page-flags.h:875
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff814bdbe5)
Location: include/linux/page-flags.h:875
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/page_isolation.c (ffffffff814c9bfb)
Location: include/linux/page-flags.h:875
Inline: True
```
```
In fs/proc/page.c (ffffffff815b84da)
Location: include/linux/page-flags.h:875
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In virt/kvm/arm/mmu.c (ffff8000100cad28)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
```
```
In mm/shmem.c (ffff8000102d0d14)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/gup.c (ffff8000102f1a4c)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102f8c28)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffff8000102fe364)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (ffff80001030a470)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffff80001031eb38)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffff800010321910)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffff800010324cd4)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffff800010340d70)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffff80001034f034)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffff80001035933c)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
```
```
In mm/khugepaged.c (ffff80001035fdbc)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffff800010368b5c)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/page.c (ffff8000104501d4)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/shmem.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/page-flags.h:702
Inline: True
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
In mm/shmem.c (c000000000390f04)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/gup.c (c0000000003b6034)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003c2450)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (c0000000003c9b3c)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (c0000000003da020)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (c0000000003f334c)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (c0000000003f7094)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (c0000000003fadd8)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (c00000000041e5c0)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (c00000000043452c)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (c000000000442780)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
```
```
In mm/khugepaged.c (c00000000044ab50)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (c000000000456f90)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/page.c (c0000000005681d0)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/shmem.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/page-flags.h:702
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/page-flags.h:702
Inline: True
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
In mm/shmem.c (ffffffff81237b59)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/gup.c (ffffffff812525d1)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125a129)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff8125f752)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (ffffffff8126cf3c)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff8127ce46)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8127f54a)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8128223e)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff81299a46)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812a6f48)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b1245)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
```
```
In mm/khugepaged.c (ffffffff812b6a17)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812be431)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/page.c (ffffffff8137a655)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/shmem.c (ffffffff8122ab99)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/gup.c (ffffffff81245368)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124c537)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff81251b72)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (ffffffff8125ef91)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff8126ecf0)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8127136a)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81273d5e)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff8128b606)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81298985)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a2615)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
```
```
In mm/khugepaged.c (ffffffff812a7be7)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812af4f5)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/page.c (ffffffff8136b125)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/shmem.c (ffffffff812358f9)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/gup.c (ffffffff81250371)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81257ec9)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff8125d4f2)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (ffffffff8126acdc)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff8127abe6)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8127d2ea)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8128004e)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff81297856)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812a4d58)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812af055)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
```
```
In mm/khugepaged.c (ffffffff812b4827)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812bc241)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/page.c (ffffffff81378125)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/shmem.c (ffffffff81245ba9)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/gup.c (ffffffff8125fcfc)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812678b5)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff8126ced8)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (ffffffff8127a65b)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff8128a7c7)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8128ceb3)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8128fd3e)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (ffffffff812a7632)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812b58b4)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812bf3a5)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
```
```
In mm/khugepaged.c (ffffffff812c51fa)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812cca12)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/page.c (ffffffff8138bbd5)
Location: include/linux/page-flags.h:607
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
</ul>

## Differences
