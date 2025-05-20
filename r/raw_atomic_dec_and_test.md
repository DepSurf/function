# Function: <code>raw_atomic_dec_and_test</code>

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
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff83682838)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/events/core.c (ffffffff8100670f)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8105ac42)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108bc19)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092008)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81094832)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109f1f3)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In kernel/fork.c (ffffffff810f5667)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:mm_access
  - kernel/fork.c:__mmput
  - kernel/fork.c:__put_task_struct
```
```
In kernel/cpu.c (ffffffff810f7339)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/cpu.c:finish_cpu
```
```
In kernel/exit.c (ffffffff810fd87d)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff81107f21)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/umh.c (ffffffff8111b6fe)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff8111c831)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
```
In kernel/kthread.c (ffffffff8112a8f2)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/nsproxy.c (ffffffff811317af)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:put_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/cred.c (ffffffff8113417b)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/reboot.c (ffffffff81134efb)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
```
```
In kernel/groups.c (ffffffff81138e0d)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:__do_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffffffff81143575)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff8117c95c)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:destroy_sched_domain
  - kernel/sched/build_utility.c:sched_put_rd
  - kernel/sched/build_utility.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffffffff8118db86)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/power/swap.c (ffffffff81199a21)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/irq/manage.c (ffffffff811a8ae0)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
```
In kernel/rcu/update.c (ffffffff811bb069)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic_cb
```
```
In kernel/rcu/srcutree.c (ffffffff811c0923)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffffffff811c2bf5)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
```
```
In kernel/futex/core.c (ffffffff81207dde)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/uid16.c (ffffffff8120fb15)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
```
In kernel/cgroup/cgroup.c (ffffffff8121ac20)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81228301)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
```
```
In kernel/user_namespace.c (ffffffff81237ff5)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/stop_machine.c (ffffffff81239bc9)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/trace/trace_events_user.c (ffffffff812c337a)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_set_call_visible
  - kernel/trace/trace_events_user.c:user_event_mm_destroy
```
```
In kernel/bpf/cpumap.c (ffffffff8134f613)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
```
```
In kernel/events/core.c (ffffffff8136de57)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/uprobes.c (ffffffff813814c3)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/jump_label.c (ffffffff813867d9)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
```
```
In kernel/watch_queue.c (ffffffff81389060)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - kernel/watch_queue.c:free_watch
```
```
In mm/filemap.c (ffffffff813910f4)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_get_entry
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:folio_end_private_2
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:replace_page_cache_folio
```
```
In mm/oom_kill.c (ffffffff81396939)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/readahead.c (ffffffff8139e2f7)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff813a15e3)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff813a41b1)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813b2494)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:reclaim_folio_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff813c0324)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_get_partial_folio
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff813db19c)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813e35ee)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff813f52f9)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff813f5de5)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/rmap.c (ffffffff8140ebe7)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff8142410e)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:__free_pages
```
```
In mm/memory_hotplug.c (ffffffff814258e8)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/madvise.c (ffffffff81427b73)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:shmem_swapin_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8142c858)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8142fc9b)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff814375cf)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81446691)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/hugetlb.c:folio_putback_active_hugetlb
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:add_hugetlb_folio
```
```
In mm/mempolicy.c (ffffffff8144dcf5)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:vma_replace_policy
  - mm/mempolicy.c:vma_replace_policy
```
```
In mm/mmu_notifier.c (ffffffff8144f8bf)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff81457f8f)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:replace_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff8146bd4a)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:migrate_folio_undo_src
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8146e59d)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814790a9)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:mm_put_huge_zero_page
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff81482510)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff8148e3ed)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81499bdd)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:try_to_split_thp_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/zsmalloc.c (ffffffff8149e3d9)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/secretmem.c (ffffffff814a02a2)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff814a1f9c)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/page_idle.c (ffffffff814a2c43)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_folio
```
```
In fs/open.c (ffffffff814a7a81)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff814b0f5d)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/file_table.c:init_file
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (ffffffff814b3063)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffffffff814ba3a1)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff814bcf5d)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff814c0a4d)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffffffff814d1c3e)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/dcache.c:copy_name
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (ffffffff814dcca5)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
```
```
In fs/libfs.c (ffffffff814eefbe)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffffffff814f4f8d)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
```
```
In fs/splice.c (ffffffff814fb3a8)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (ffffffff81503f6d)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/remap_range.c (ffffffff815070f7)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
```
```
In fs/buffer.c (ffffffff8150c25d)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/mpage.c (ffffffff8150e1af)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/direct-io.c (ffffffff81510496)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/notify/mark.c (ffffffff815145e5)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81523b24)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/userfaultfd.c:new_userfaultfd
```
```
In fs/aio.c (ffffffff8152b422)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migrate_folio
  - fs/aio.c:aio_migrate_folio
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/read_metadata.c (ffffffff8153d5fd)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
```
```
In fs/verity/verify.c (ffffffff8153df03)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
```
```
In fs/coredump.c (ffffffff81551215)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff815542a0)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (ffffffff81558bcf)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (ffffffff815648e1)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff8156bb01)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/proc/base.c:mem_release
```
```
In fs/proc/array.c (ffffffff815733f0)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/kernfs/dir.c (ffffffff81582857)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_destroy_root
```
```
In fs/configfs/inode.c (ffffffff81588b6e)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff8158c399)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff8158d069)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/ext4/inline.c (ffffffff815ae0dc)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff815b1e89)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff815c6383)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_pa_put_free
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff815d0735)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815da7c6)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (ffffffff815db6a9)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/fast_commit.c (ffffffff8160dc4e)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_stop_update
```
```
In fs/ext4/verity.c (ffffffff81611da4)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff8161366e)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
```
```
In fs/jbd2/commit.c (ffffffff8161813b)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/block.c (ffffffff816241b6)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/squashfs/file.c (ffffffff81626dd4)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8162a454)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff8162f5b6)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8164509e)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff816453f2)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81652c33)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8165d897)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/inode.c (ffffffff81662f4c)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In fs/fuse/readdir.c (ffffffff81667982)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/keys/keyctl.c (ffffffff8168d043)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff8168f05d)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8168f955)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81690728)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
```
```
In security/tomoyo/common.c (ffffffff816e6e04)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffffffff816ea338)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/audit.c (ffffffff816fa0aa)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
```
```
In security/apparmor/domain.c (ffffffff8170477d)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/apparmor/lsm.c (ffffffff81714075)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/safesetid/lsm.c (ffffffff81726ff7)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
```
```
In block/bdev.c (ffffffff81766405)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_put_whole
```
```
In block/fops.c (ffffffff81767693)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
  - block/fops.c:blkdev_bio_end_io
```
```
In block/bio.c (ffffffff8176a300)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_put
```
```
In block/blk-flush.c (ffffffff81774fd9)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff817772aa)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff8178258a)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/partitions/amiga.c (ffffffff817917d6)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8179256d)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff81792edf)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:read_lba
```
```
In block/partitions/mac.c (ffffffff81794761)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81796fd2)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff81798b1c)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/osf.c (ffffffff81799498)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8179982c)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81799c7f)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8179a074)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8179a713)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff8179b862)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8179bb53)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In io_uring/io_uring.c (ffffffff817cd716)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:io_eventfd_ops
  - io_uring/io_uring.c:io_clean_op
```
```
In io_uring/timeout.c (ffffffff817daf29)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_req_task_link_timeout
```
```
In io_uring/kbuf.c (ffffffff817e010e)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
```
```
In io_uring/io-wq.c (ffffffff817e8b5d)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_wq_dec_running
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In drivers/pci/p2pdma.c (ffffffff8195f4f6)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5fd3b)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81a62c9a)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abfde9)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffffffff81ae2199)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81aea3fb)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81b1d43c)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_domain_free
```
```
In drivers/base/power/domain.c (ffffffff81b5bcca)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b6025d)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/block/loop.c (ffffffff81b7a1f5)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff81ba51c0)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81bc0536)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81bc6d6c)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff81bcc593)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff81c4a25e)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/virtio_net.c (ffffffff81c541d1)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_rq_free_unused_buf
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:mergeable_buf_free
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:page_to_skb
```
```
In drivers/usb/core/devio.c (ffffffff81c99696)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff81d5eeb9)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff81d6de4d)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (ffffffff81d77f8e)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_poll_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (ffffffff81d83470)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d84fff)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de5ba2)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In net/core/sock.c (ffffffff81e07826)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
```
```
In net/core/skbuff.c (ffffffff81e1eac2)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81e41463)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
```
```
In net/core/dst.c (ffffffff81e450fc)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (ffffffff81e70e2c)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81e79616)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81e7b776)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/page_pool.c (ffffffff81e8272a)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/core/skmsg.c (ffffffff81ea2dcc)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/netlink/af_netlink.c (ffffffff81ec551b)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/tcp.c (ffffffff81f10646)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81f22d55)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/fib_semantics.c (ffffffff81f5faf4)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ping.c (ffffffff81f6b027)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f8618d)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81f98a72)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81fa7f4d)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/unix/af_unix.c (ffffffff81faebff)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/route.c (ffffffff81fd6f85)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff82004b76)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/dns_resolver/dns_key.c (ffffffff83af63ec)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
```
In net/mptcp/protocol.c (ffffffff820716e9)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - net/mptcp/protocol.c:dfrag_clear
```
```
In lib/buildid.c (ffffffff8209f0a0)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In lib/dec_and_lock.c (ffffffff8209fbae)
Location: include/linux/atomic/atomic-arch-fallback.h:2258
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
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
In init/do_mounts.c (ffffffff838b18d8)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/events/core.c (ffffffff8100be0f)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff81061f02)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108f2a5)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099378)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109bd12)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a6673)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In kernel/fork.c (ffffffff810fc2d9)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - kernel/fork.c:mm_access
  - kernel/fork.c:__mmput
  - kernel/fork.c:__put_task_struct
```
```
In kernel/cpu.c (ffffffff811006e9)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - kernel/cpu.c:finish_cpu
```
```
In kernel/exit.c (ffffffff811066ed)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/umh.c (ffffffff811251ee)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff811261c1)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
```
In kernel/kthread.c (ffffffff81134f82)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/reboot.c (ffffffff811403f0)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
```
```
In kernel/sched/core.c (ffffffff8114ea4f)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff8118a68c)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:destroy_sched_domain
  - kernel/sched/build_utility.c:sched_put_rd
  - kernel/sched/build_utility.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffffffff8119c536)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/power/swap.c (ffffffff811a8a81)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/irq/manage.c (ffffffff811b8640)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
```
In kernel/rcu/update.c (ffffffff811cb029)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic_cb
```
```
In kernel/rcu/srcutree.c (ffffffff811d0e03)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffffffff811d2df5)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
```
```
In kernel/futex/core.c (ffffffff8121ef39)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/cgroup/cgroup.c (ffffffff81232990)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
```
```
In kernel/stop_machine.c (ffffffff81253899)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/trace/trace_events.c (ffffffff812c311b)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_file_put
```
```
In kernel/trace/trace_events_user.c (ffffffff812e1a5d)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_mm_destroy
```
```
In kernel/events/core.c (ffffffff81396f87)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_sched_delayed
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/uprobes.c (ffffffff813aa872)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/jump_label.c (ffffffff813afc99)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
```
```
In mm/filemap.c (ffffffff813bae94)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_get_entry
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:folio_end_private_2
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:replace_page_cache_folio
```
```
In mm/oom_kill.c (ffffffff813c0249)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/readahead.c (ffffffff813c7f98)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff813cb266)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff813cdd01)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813dba45)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:reclaim_folio_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff813eb392)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_alloc_and_add_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_get_partial_folio
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff81404e88)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8140de0b)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff81415906)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff81421ab5)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/rmap.c (ffffffff8143b5a7)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff81450f56)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:__free_pages
```
```
In mm/memory_hotplug.c (ffffffff81452b3a)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/slub.c (ffffffff81454cc8)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/slub.c:free_large_kmalloc
```
```
In mm/madvise.c (ffffffff81461388)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:shmem_swapin_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81465f9b)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81469784)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff814700ab)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8148012f)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/hugetlb.c:folio_putback_active_hugetlb
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:add_hugetlb_folio
```
```
In mm/mempolicy.c (ffffffff81487bbb)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
```
```
In mm/mmu_notifier.c (ffffffff8148959f)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffff814928ee)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:replace_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff8149adc2)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:migrate_folio_undo_src
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8149ef2a)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a86a7)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:mm_put_huge_zero_page
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff814b1899)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff814bdc5a)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814c93cc)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:try_to_split_thp_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/zsmalloc.c (ffffffff814cd50a)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/secretmem.c (ffffffff814cf914)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff814d2ca7)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/page_idle.c (ffffffff814d3ad3)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_folio
```
```
In fs/super.c (ffffffff814e4ac3)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffffffff814ec921)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff814ef3fd)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff814f3099)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffffffff8150460e)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/dcache.c:copy_name
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (ffffffff8150f465)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
```
```
In fs/libfs.c (ffffffff81522c29)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffffffff8152969d)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
```
```
In fs/splice.c (ffffffff8153009a)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/remap_range.c (ffffffff8153c415)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
```
```
In fs/buffer.c (ffffffff81540e4f)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/mpage.c (ffffffff81542c8c)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/direct-io.c (ffffffff81544936)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/notify/mark.c (ffffffff81548ab5)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
```
```
In fs/userfaultfd.c (ffffffff815580a4)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/userfaultfd.c:new_userfaultfd
```
```
In fs/aio.c (ffffffff8155c639)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migrate_folio
  - fs/aio.c:aio_migrate_folio
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/read_metadata.c (ffffffff81572a5d)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
```
```
In fs/verity/verify.c (ffffffff815734a0)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
```
```
In fs/coredump.c (ffffffff815870f2)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff8158a4bb)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:ifs_free
```
```
In fs/iomap/direct-io.c (ffffffff8158f30a)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (ffffffff8159b2c1)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/base.c (ffffffff815a4271)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/proc/base.c:mem_release
```
```
In fs/kernfs/dir.c (ffffffff815bb487)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_destroy_root
```
```
In fs/configfs/inode.c (ffffffff815c1741)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff815c507a)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff815c5daf)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/ext4/inline.c (ffffffff815e6e9c)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff815eacb7)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff81601cd1)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_pa_put_free
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff81608f66)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff81612f86)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (ffffffff81613f76)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/fast_commit.c (ffffffff81646a0e)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_stop_update
```
```
In fs/ext4/verity.c (ffffffff8164ab52)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff8164c46e)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
```
```
In fs/jbd2/commit.c (ffffffff81651072)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/block.c (ffffffff8165d256)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/squashfs/file.c (ffffffff8165ff35)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8166377e)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff81668ad4)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e5ce)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8167e913)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8168c243)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff816975d7)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/inode.c (ffffffff8169cabb)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In fs/fuse/readdir.c (ffffffff816a1cc6)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/common.c (ffffffff81723b14)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffffffff81727048)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bdev.c (ffffffff817a7f02)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - block/bdev.c:bdev_release
  - block/bdev.c:blkdev_put_whole
```
```
In block/fops.c (ffffffff817a9483)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
  - block/fops.c:blkdev_bio_end_io
```
```
In block/bio.c (ffffffff817ac760)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_put
```
```
In block/blk-flush.c (ffffffff817b72ff)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff817b94ca)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
```
```
In block/blk-mq.c (ffffffff817c492a)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/partitions/amiga.c (ffffffff817d50e6)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff817d5e7d)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff817d67ef)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:read_lba
```
```
In block/partitions/mac.c (ffffffff817d80c1)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff817da9d2)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff817dc54c)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/osf.c (ffffffff817dcec8)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff817dd25c)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff817dd6af)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff817ddaa4)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff817de143)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff817df2c2)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff817df5b3)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In io_uring/io_uring.c (ffffffff81811370)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:io_eventfd_ops
```
```
In io_uring/timeout.c (ffffffff8181f219)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_req_task_link_timeout
```
```
In io_uring/io-wq.c (ffffffff8182e90d)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_wq_dec_running
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
```
```
In drivers/pci/p2pdma.c (ffffffff819a8b56)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/pmdomain/core.c (ffffffff81aa37ca)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:genpd_power_on
  - drivers/pmdomain/core.c:genpd_power_on
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab254b)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81ab52ca)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b12c69)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffffffff81b35589)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81b3d88b)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81b739c1)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_domain_free
```
```
In drivers/block/loop.c (ffffffff81bce155)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff81bf9440)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81c14cb6)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81c1b8db)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff81c211c3)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c97e37)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_release
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb5f28)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_put
```
```
In drivers/net/tun.c (ffffffff81cffbea)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/virtio_net.c (ffffffff81d078ce)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:free_receive_page_frags
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:mergeable_buf_free
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:virtnet_rq_unmap
  - drivers/net/virtio_net.c:page_to_skb
```
```
In drivers/md/md.c (ffffffff81e16129)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff81e2544d)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_sb_page
```
```
In drivers/md/dm.c (ffffffff81e2f1be)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_poll_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (ffffffff81e3ab30)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffffffff81e3c77f)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9bd82)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In net/core/sock.c (ffffffff81ec4266)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81edc122)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81effdcd)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
```
```
In net/core/dst.c (ffffffff81f03d7c)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (ffffffff81f30503)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81f396b0)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81f3ba06)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/page_pool.c (ffffffff81f436bd)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
```
In net/core/skmsg.c (ffffffff81f650fc)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/netlink/af_netlink.c (ffffffff81f8890c)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/tcp.c (ffffffff81fd4835)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81fe7be5)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/fib_semantics.c (ffffffff820260c4)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204d76d)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff82065de2)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff8207520d)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/ipv6/route.c (ffffffff820a4905)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d3946)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/mptcp/protocol.c (ffffffff82145869)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - net/mptcp/protocol.c:dfrag_clear
```
```
In lib/buildid.c (ffffffff821770a0)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In lib/dec_and_lock.c (ffffffff82177b7e)
Location: include/linux/atomic/atomic-arch-fallback.h:2267
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
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
