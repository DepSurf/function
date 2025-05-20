# Function: <code>folio_ref_count</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81e6b4a1)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/truncate.c (ffffffff81307eff)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/truncate.c:mapping_evict_folio
```
```
In mm/vmscan.c (ffffffff8130e94a)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/compaction.c (ffffffff8133115b)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81338425)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_get_folio
```
```
In mm/memory.c (ffffffff81344203)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:insert_pages
  - mm/memory.c:copy_present_pte
```
```
In mm/mprotect.c (ffffffff81353fc3)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8135e7b1)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff8137293b)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/memory_hotplug.c (ffffffff81f1bd23)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/hugetlb.c (ffffffff8138ee45)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/ksm.c (ffffffff813a06fe)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff813b3957)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/migrate_device.c (ffffffff813b68f0)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c1c3f)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813c5f5e)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memory-failure.c (ffffffff813da519)
Location: include/linux/page_ref.h:87
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
In mm/page_isolation.c (ffffffff813deb3a)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/memfd.c (ffffffff813e9682)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff813fe32a)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff8146372c)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff8149a907)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff814b1589)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In drivers/xen/grant-table.c (ffffffff818c7ec7)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In net/socket.c (ffffffff81be78ed)
Location: include/linux/page_ref.h:87
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
In mm/filemap.c (ffffffff81359a43)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/truncate.c (ffffffff813712ec)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/truncate.c:mapping_evict_folio
```
```
In mm/vmscan.c (ffffffff813808ae)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
```
```
In mm/compaction.c (ffffffff813a7e17)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813afc1a)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff813bbfd0)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:insert_pages
  - mm/memory.c:copy_present_pte
```
```
In mm/mprotect.c (ffffffff813ce407)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff813d99d3)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff813f00ab)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/memory_hotplug.c (ffffffff820c3b05)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/hugetlb.c (ffffffff8140d92e)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/mempolicy.c (ffffffff81417bcb)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff8141fee5)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff814347c5)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/migrate_device.c (ffffffff8143826a)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81443de4)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8144aaac)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memory-failure.c (ffffffff81461c8f)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_swapcache_clean
```
```
In mm/page_isolation.c (ffffffff814657fa)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/memfd.c (ffffffff81471654)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff81487f9a)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff814f281c)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff8152ee27)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81547f1b)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In drivers/xen/grant-table.c (ffffffff81a19487)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In net/socket.c (ffffffff81d940fd)
Location: include/linux/page_ref.h:87
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
In mm/filemap.c (ffffffff8138b390)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/truncate.c (ffffffff813a34bc)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/truncate.c:mapping_evict_folio
```
```
In mm/vmscan.c (ffffffff813b1955)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
```
```
In mm/compaction.c (ffffffff813db203)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813e7e23)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/gup.c:folio_add_pin
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff813f0a01)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:copy_present_pte
```
```
In mm/mprotect.c (ffffffff81402cb5)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8140dea9)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff81423c28)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/memory_hotplug.c (ffffffff82147a8a)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/hugetlb.c (ffffffff81440ce1)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/mempolicy.c (ffffffff8144b163)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/ksm.c (ffffffff81454afc)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff81469fd5)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/migrate_device.c (ffffffff8146df3a)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8147932c)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81480ba2)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memory-failure.c (ffffffff81497422)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_swapcache_clean
```
```
In mm/page_isolation.c (ffffffff8149b1f3)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/memfd.c (ffffffff814a5b95)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff814bce8a)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff8152943f)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff81567137)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8157fb1d)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/ext4/inode.c (ffffffff815b04ea)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
```
```
In drivers/xen/grant-table.c (ffffffff81a623a7)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In net/core/skbuff.c (ffffffff81e14c20)
Location: include/linux/page_ref.h:87
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
In mm/filemap.c (ffffffff813b4eb7)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/truncate.c (ffffffff813ce72c)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/truncate.c:mapping_evict_folio
```
```
In mm/vmscan.c (ffffffff813daec1)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
```
```
In mm/compaction.c (ffffffff814052be)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81412a90)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/gup.c:folio_add_pin
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff81420273)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:copy_present_pte
```
```
In mm/mprotect.c (ffffffff8142f41d)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8143a55b)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff81450b65)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
```
```
In mm/memory_hotplug.c (ffffffff8222a13e)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/hugetlb.c (ffffffff8147ae11)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/mempolicy.c (ffffffff81484b15)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/ksm.c (ffffffff8148fce8)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff81498fa5)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/migrate_device.c (ffffffff8149e901)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a8892)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814aeb7f)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memory-failure.c (ffffffff814c671d)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:has_extra_refcount
```
```
In mm/page_isolation.c (ffffffff814ca8d3)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/userfaultfd.c (ffffffff814cff0f)
Location: include/linux/page_ref.h:87
Inline: True
```
```
In mm/memfd.c (ffffffff814d6b42)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/pipe.c (ffffffff814ef32a)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/aio.c (ffffffff8155e313)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/proc/task_mmu.c (ffffffff8159ccc7)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff815b852d)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/ext4/inode.c (ffffffff815e92d7)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
```
```
In drivers/xen/grant-table.c (ffffffff81ab4bd7)
Location: include/linux/page_ref.h:87
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In net/core/skbuff.c (ffffffff81ed2219)
Location: include/linux/page_ref.h:87
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
