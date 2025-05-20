# Function: <code>page_count</code>

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
In mm/page_alloc.c (ffffffff811976e0)
Location: include/linux/mm.h:449
Inline: True
Inline callers:
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In mm/vmscan.c (ffffffff811a0951)
Location: include/linux/mm.h:449
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811a882e)
Location: include/linux/mm.h:449
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
```
```
In mm/compaction.c (ffffffff811b623a)
Location: include/linux/mm.h:449
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff811c1941)
Location: include/linux/mm.h:449
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In mm/hugetlb.c (ffffffff811db7cb)
Location: include/linux/mm.h:449
Inline: True
Inline callers:
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
```
```
In mm/ksm.c (ffffffff811e555c)
Location: include/linux/mm.h:449
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff8181a6c9)
Location: include/linux/mm.h:449
Inline: True
```
```
In mm/migrate.c (ffffffff811f1011)
Location: include/linux/mm.h:449
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f4c9f)
Location: include/linux/mm.h:449
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff81201b8f)
Location: include/linux/mm.h:449
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:soft_offline_page
```
```
In fs/pipe.c (ffffffff81214a8d)
Location: include/linux/mm.h:449
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff8125b899)
Location: include/linux/mm.h:449
Inline: True
Inline callers:
  - fs/aio.c:aio_free_ring
  - fs/aio.c:SyS_io_setup
```
```
In fs/fuse/dev.c (ffffffff8130e9fc)
Location: include/linux/mm.h:449
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffffffff814c5e34)
Location: include/linux/mm.h:449
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
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
In mm/filemap.c (ffffffff811a202e)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff811acbc7)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/vmscan.c (ffffffff811b9d71)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811bf652)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
```
```
In mm/compaction.c (ffffffff811d01e0)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff811dd411)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In mm/hugetlb.c (ffffffff811fe0ab)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:dissolve_free_huge_pages
```
```
In mm/ksm.c (ffffffff81204025)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff81894268)
Location: include/linux/page_ref.h:69
Inline: True
```
```
In mm/migrate.c (ffffffff81213167)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812178c6)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8121c013)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memory-failure.c (ffffffff812281ae)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In fs/pipe.c (ffffffff8123b821)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff81284f2b)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff812a454b)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812b54dc)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/fuse/dev.c (ffffffff81342da8)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffffffff815164c4)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
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
In mm/filemap.c (ffffffff811b1e90)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff811bd186)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/vmscan.c (ffffffff811ca3f9)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811cfcfd)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
```
```
In mm/compaction.c (ffffffff811e020e)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff811ecf01)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In mm/hugetlb.c (ffffffff8120eb7b)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dissolve_free_huge_pages
```
```
In mm/ksm.c (ffffffff8121624d)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/memory_hotplug.c (ffffffff818c896a)
Location: include/linux/page_ref.h:69
Inline: True
```
```
In mm/migrate.c (ffffffff812254d3)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81229e76)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8122e66f)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memory-failure.c (ffffffff8123a76e)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In fs/pipe.c (ffffffff8124e5c1)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff81299134)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff812b9eab)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812cad3d)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/fuse/dev.c (ffffffff81358bc7)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffffffff81542934)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
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
In mm/filemap.c (ffffffff811b8b52)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff811c53e0)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/vmscan.c (ffffffff811d2dde)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811d943e)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
```
```
In mm/compaction.c (ffffffff811e9edc)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff811f7e41)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In mm/hugetlb.c (ffffffff81217cfb)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/ksm.c (ffffffff8122178d)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/memory_hotplug.c (ffffffff818fff0f)
Location: include/linux/page_ref.h:69
Inline: True
```
```
In mm/migrate.c (ffffffff8122f8f9)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81235ccf)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffffffff8123a0af)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memory-failure.c (ffffffff81246275)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:identify_page_state
```
```
In fs/pipe.c (ffffffff8125a581)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff812a6807)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff812c75be)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812d81cd)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/fuse/dev.c (ffffffff8136d437)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffffffff815567f6)
Location: include/linux/page_ref.h:69
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
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
In mm/filemap.c (ffffffff811ca242)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff811da1ae)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/vmscan.c (ffffffff811e845b)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811ee713)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
```
```
In mm/compaction.c (ffffffff81200237)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff8120ffb1)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In mm/hugetlb.c (ffffffff81232a5b)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/ksm.c (ffffffff8123caa2)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/memory_hotplug.c (ffffffff8198a052)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff8124d3f5)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81254a34)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffffffff81259785)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memory-failure.c (ffffffff81266384)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:identify_page_state
```
```
In fs/pipe.c (ffffffff8127c881)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff812c9d3b)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff812eae9f)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812fc8cd)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/fuse/dev.c (ffffffff81391ec0)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffffffff815ba303)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
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
In mm/filemap.c (ffffffff811f0c7f)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff811faa1e)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/vmscan.c (ffffffff8120992c)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/compaction.c (ffffffff81221665)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff8122f681)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In mm/hugetlb.c (ffffffff81255acb)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/ksm.c (ffffffff81260371)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/memory_hotplug.c (ffffffff819e63df)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff81270d81)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8127884a)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffffffff8127d536)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memory-failure.c (ffffffff8128ac8f)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:identify_page_state
```
```
In mm/memfd.c (ffffffff81294470)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/pipe.c (ffffffff812a37d1)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff812f302c)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff81318503)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8132a4d4)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/fuse/dev.c (ffffffff813c0eed)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffffffff815f2153)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
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
In mm/filemap.c (ffffffff81202adb)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff8120d19e)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/vmscan.c (ffffffff8121c60c)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/compaction.c (ffffffff812346b7)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff81244071)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In mm/hugetlb.c (ffffffff81269f1b)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/ksm.c (ffffffff81274abc)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81285393)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8128cf00)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffffffff81291cf6)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memory-failure.c (ffffffff8129fba8)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:identify_page_state
```
```
In mm/memfd.c (ffffffff812a8ec9)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/pipe.c (ffffffff812b8921)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff81307d4f)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff8132f3d7)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff813417f7)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/fuse/dev.c (ffffffff813da24f)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/grant-table.c (ffffffff8160d0b3)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
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
In mm/filemap.c (ffffffff81219f0b)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff8122c1b1)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/compaction.c (ffffffff81244475)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff812523cd)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/page_alloc.c (ffffffff812735cb)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/hugetlb.c (ffffffff8128504e)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/ksm.c (ffffffff8128ef2f)
Location: include/linux/page_ref.h:70
Inline: True
```
```
In mm/migrate.c (ffffffff8129fa0f)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a7b90)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffffffff812acbf9)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffffffff812ba39d)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:identify_page_state
```
```
In mm/memfd.c (ffffffff812c54d1)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff812d54f2)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff8132c542)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff81356e8d)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81369c15)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/fuse/dev.c (ffffffff81405e92)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In drivers/xen/grant-table.c (ffffffff81640859)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
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
In mm/filemap.c (ffffffff8122787b)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff8123a05d)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/compaction.c (ffffffff81252935)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff812609ad)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/page_alloc.c (ffffffff8128243b)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/hugetlb.c (ffffffff81294bee)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/ksm.c (ffffffff8129ecab)
Location: include/linux/page_ref.h:70
Inline: True
```
```
In mm/migrate.c (ffffffff812b0daf)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b9060)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffffffff812be4c7)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffffffff812cbacd)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:identify_page_state
```
```
In mm/memfd.c (ffffffff812d6edf)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff812e7062)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff8133f392)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff8136f45d)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81381e35)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/fuse/dev.c (ffffffff814209f2)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In drivers/xen/grant-table.c (ffffffff81663219)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
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
In mm/filemap.c (ffffffff812541ba)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff81266762)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/compaction.c (ffffffff81282d7c)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff81290fc6)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/page_alloc.c (ffffffff812b4589)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:pfn_range_valid_contig
```
```
In mm/hugetlb.c (ffffffff812c81e4)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:gather_bootmem_prealloc
```
```
In mm/ksm.c (ffffffff812d3819)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/memory_hotplug.c (ffffffff812e0e1f)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory_hotplug.c:scan_movable_pages
```
```
In mm/migrate.c (ffffffff812e6485)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812edc31)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffffffff812f23e9)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memory-failure.c (ffffffff813024f0)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:identify_page_state
```
```
In mm/page_isolation.c (ffffffff81303ff4)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/memfd.c (ffffffff8130c010)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff8131e842)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff813779a2)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff813b6b2d)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff813cc465)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In drivers/xen/grant-table.c (ffffffff817126d1)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
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
In mm/filemap.c (ffffffff81be6a5a)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff812710d0)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/compaction.c (ffffffff8128cd74)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff8129ba5d)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/page_alloc.c (ffffffff812c021e)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:pfn_range_valid_contig
```
```
In mm/hugetlb.c (ffffffff812d3dc1)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/ksm.c (ffffffff812df22e)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/memory_hotplug.c (ffffffff812ebc1f)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory_hotplug.c:scan_movable_pages
```
```
In mm/migrate.c (ffffffff812f12b4)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812f92ee)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffffffff812fe8a1)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memory-failure.c (ffffffff81bea16d)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:identify_page_state
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_isolation.c (ffffffff8130febf)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/memfd.c (ffffffff81317ed0)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff81329da2)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff813852f6)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff813c81ca)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff813de0ab)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In drivers/xen/grant-table.c (ffffffff8172f461)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In net/socket.c (ffffffff819de96c)
Location: include/linux/page_ref.h:70
Inline: True
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
In mm/filemap.c (ffffffff81bd87f0)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff81275c2a)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/compaction.c (ffffffff81291fe1)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff812a0b41)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/page_alloc.c (ffffffff812c5995)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/memory_hotplug.c (ffffffff81c2d831)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/hugetlb.c (ffffffff812daccc)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/ksm.c (ffffffff812e6a08)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812f75b4)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812ff603)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffffffff81305564)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memory-failure.c (ffffffff81bdc0f0)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:identify_page_state
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_isolation.c (ffffffff81315f9c)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/memfd.c (ffffffff8131e0c0)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff8132fd62)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff8138c0a3)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff813cf30d)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff813e4e97)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In drivers/xen/grant-table.c (ffffffff81712eb1)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In net/socket.c (ffffffff819c48f9)
Location: include/linux/page_ref.h:70
Inline: True
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
In mm/filemap.c (ffffffff81cb9e4a)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff812b3930)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/compaction.c (ffffffff812d16f7)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff812e1c61)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff812f0887)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_alloc.c (ffffffff8130a0b1)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/memory_hotplug.c (ffffffff81d4c118)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/hugetlb.c (ffffffff81321ced)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/ksm.c (ffffffff8132e928)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff81341c21)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81349213)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffffffff8134f39e)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memory-failure.c (ffffffff8135f233)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:identify_page_state
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_isolation.c (ffffffff813620a2)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/memfd.c (ffffffff8136b5e2)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff8137d522)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff813d9656)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff814206d0)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81436a67)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In drivers/xen/grant-table.c (ffffffff8178f971)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In net/socket.c (ffffffff81a73d95)
Location: include/linux/page_ref.h:70
Inline: True
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
In mm/compaction.c (ffffffff81331147)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff813441fb)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:insert_pages
```
```
In mm/mprotect.c (ffffffff81353fae)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_alloc.c (ffffffff8137292a)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/memory_hotplug.c (ffffffff81f1bd12)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/hugetlb.c (ffffffff8138ee33)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/ksm.c (ffffffff813a06ed)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff813b3942)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__buffer_migrate_page
```
```
In mm/migrate_device.c (ffffffff813b68dc)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_unmap
```
```
In mm/huge_memory.c (ffffffff813bed5d)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff813c5f4a)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memory-failure.c (ffffffff813da511)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_swapcache_clean
```
```
In mm/page_isolation.c (ffffffff813deb2f)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/memfd.c (ffffffff813e9671)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff813fe31d)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff8146371a)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff81499d1d)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff814b1574)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In drivers/xen/grant-table.c (ffffffff818c7ee2)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In net/socket.c (ffffffff81be78e0)
Location: include/linux/page_ref.h:92
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
In mm/compaction.c (ffffffff813a7e03)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff813bd414)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
  - mm/memory.c:insert_pages
```
```
In mm/mprotect.c (ffffffff813ce3f3)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_alloc.c (ffffffff813f009a)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/memory_hotplug.c (ffffffff820c3af1)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/hugetlb.c (ffffffff8140d91c)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81417bbd)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff8141fed1)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff81438256)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
```
```
In mm/khugepaged.c (ffffffff8144aa98)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memory-failure.c (ffffffff81461c82)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_swapcache_clean
```
```
In mm/page_isolation.c (ffffffff814657ef)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/memfd.c (ffffffff81471647)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff81487f8d)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff814f280a)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff8152fa44)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81547f06)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In drivers/xen/grant-table.c (ffffffff81a194a2)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In net/socket.c (ffffffff81d940f0)
Location: include/linux/page_ref.h:92
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
In mm/memory.c (ffffffff813f20c4)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In mm/mprotect.c (ffffffff81402ca1)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_alloc.c (ffffffff81423c17)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/memory_hotplug.c (ffffffff82147a79)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/hugetlb.c (ffffffff81440ccf)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8144b154)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/ksm.c (ffffffff81454ae8)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8146df26)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
```
```
In mm/khugepaged.c (ffffffff81480b8e)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memory-failure.c (ffffffff81497415)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_swapcache_clean
```
```
In mm/page_isolation.c (ffffffff8149b1e4)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/memfd.c (ffffffff814a5b84)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff814bce7d)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff8152942d)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff8156826f)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8157fb08)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In drivers/xen/grant-table.c (ffffffff81a623c2)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In net/core/skbuff.c (ffffffff81e14c0b)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_splice_from_iter
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
In mm/memory.c (ffffffff8141cd44)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In mm/page_alloc.c (ffffffff81450b54)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/memory_hotplug.c (ffffffff8222a12a)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/hugetlb.c (ffffffff8147adff)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81484b06)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/ksm.c (ffffffff8148fcd7)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8149e8ed)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
```
```
In mm/khugepaged.c (ffffffff814aeb6b)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff814c6713)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:has_extra_refcount
```
```
In mm/page_isolation.c (ffffffff814ca8c4)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/memfd.c (ffffffff814d6b31)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff814ef31d)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff8155e301)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff8159f0d8)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff815b8518)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In drivers/xen/grant-table.c (ffffffff81ab4bee)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In net/core/skbuff.c (ffffffff81ed2204)
Location: include/linux/page_ref.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_splice_from_iter
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
In virt/kvm/kvm_main.c (ffff8000100b699c)
Location: include/linux/page_ref.h:70
Inline: True
```
```
In virt/kvm/arm/mmu.c (ffff8000100c9554)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
```
```
In mm/filemap.c (ffff8000102aeeac)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffff8000102caf10)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/compaction.c (ffff8000102eb5e8)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffff8000102f7e30)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/page_alloc.c (ffff80001031a564)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:free_contig_range
```
```
In mm/hugetlb.c (ffff800010333964)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_gigantic_page
```
```
In mm/ksm.c (ffff80001033e418)
Location: include/linux/page_ref.h:70
Inline: True
```
```
In mm/migrate.c (ffff8000103512dc)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffff8000103597f8)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffff80001035fe34)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffff800010370830)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:identify_page_state
```
```
In mm/memfd.c (ffff80001037be60)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffff80001038fbf8)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffff8000103fb36c)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffff800010438b38)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffff800010450030)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/fuse/dev.c (ffff8000105035ec)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In drivers/xen/grant-table.c (ffff80001082c6b8)
Location: include/linux/page_ref.h:70
Inline: True
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
In mm/filemap.c (c04daae0)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (c04f4cb0)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/compaction.c (c050eac4)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (c051a524)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/page_alloc.c (c0534b10)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:free_contig_range
```
```
In mm/ksm.c (c0544a14)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (c055285c)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memfd.c (c0566c10)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (c0576a04)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (c05d0598)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (c0600b04)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/proc/page.c (c06132d4)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/fuse/dev.c (c06bfc74)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (c000000000362404)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (c000000000387cf0)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/compaction.c (c0000000003ac9c0)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (c0000000003c0b2c)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/page_alloc.c (c0000000003ee054)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/hugetlb.c (c00000000040f5b4)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/ksm.c (c000000000419ef4)
Location: include/linux/page_ref.h:70
Inline: True
```
```
In mm/migrate.c (c00000000043760c)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (c000000000442d3c)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (c00000000044abd0)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (c0000000004609d0)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:identify_page_state
```
```
In mm/memfd.c (c000000000471360)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (c000000000487360)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (c0000000005082f0)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (c00000000054c340)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (c000000000568044)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/fuse/dev.c (c000000000648154)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffe0001d4410)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffe0001e9e86)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/compaction.c (ffffffe0001ff88e)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffe0002082a0)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/page_alloc.c (ffffffe00021fd54)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:free_contig_range
```
```
In mm/hugetlb.c (ffffffe00022fae6)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/ksm.c (ffffffe000234654)
Location: include/linux/page_ref.h:70
Inline: True
```
```
In mm/migrate.c (ffffffe00023fc36)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memfd.c (ffffffe00025261c)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffe00025f694)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffe0002aab06)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffe0002d3294)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/page.c (ffffffe0002e322a)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/fuse/dev.c (ffffffe000370414)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff8121fecb)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff812326ad)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/compaction.c (ffffffff8124af85)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff81258ffd)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/page_alloc.c (ffffffff8127aa8b)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/hugetlb.c (ffffffff8128d1ce)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/ksm.c (ffffffff8129728b)
Location: include/linux/page_ref.h:70
Inline: True
```
```
In mm/migrate.c (ffffffff812a938f)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b1640)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffffffff812b6aa7)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffffffff812c40ad)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:identify_page_state
```
```
In mm/memfd.c (ffffffff812cf4bf)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff812df642)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff81337972)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff81367a3d)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8137a415)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/fuse/dev.c (ffffffff81418fd2)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In drivers/xen/grant-table.c (ffffffff81629089)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
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
In mm/filemap.c (ffffffff8121307b)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff81225759)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/compaction.c (ffffffff8123df25)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff8124b4a1)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/page_alloc.c (ffffffff8126c96b)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/hugetlb.c (ffffffff8127efb5)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/ksm.c (ffffffff81288e9b)
Location: include/linux/page_ref.h:70
Inline: True
```
```
In mm/migrate.c (ffffffff8129acef)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a2a10)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffffffff812a7c77)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffffffff812b50ed)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:identify_page_state
```
```
In mm/memfd.c (ffffffff812c0143)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff812d0282)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff813286a2)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff813586dd)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8136aee5)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/fuse/dev.c (ffffffff81409a52)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff8121dc6b)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff8123044d)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/compaction.c (ffffffff81248d25)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff81256d9d)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/page_alloc.c (ffffffff8127882b)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/hugetlb.c (ffffffff8128afde)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/ksm.c (ffffffff8129509b)
Location: include/linux/page_ref.h:70
Inline: True
```
```
In mm/migrate.c (ffffffff812a719f)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812af450)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffffffff812b48b7)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffffffff812c1ebd)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:identify_page_state
```
```
In mm/memfd.c (ffffffff812cd2cf)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff812dd452)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff81335442)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff8136550d)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81377ee5)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/fuse/dev.c (ffffffff81415172)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In drivers/xen/grant-table.c (ffffffff81657059)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
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
In mm/filemap.c (ffffffff8122ccdb)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff8123f896)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/compaction.c (ffffffff81258554)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff812667fb)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/page_alloc.c (ffffffff8128841b)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/hugetlb.c (ffffffff8129adfe)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/ksm.c (ffffffff812a4eff)
Location: include/linux/page_ref.h:70
Inline: True
```
```
In mm/migrate.c (ffffffff812b74aa)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812bf7a0)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffffffff812c52a8)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffffffff812d295d)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:identify_page_state
```
```
In mm/memfd.c (ffffffff812de055)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff812ee3d8)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff81348446)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff81378bed)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8138b995)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/fuse/dev.c (ffffffff8142bee7)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In drivers/xen/grant-table.c (ffffffff81671659)
Location: include/linux/page_ref.h:70
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
</details>
</li>
</ul>

## Differences
