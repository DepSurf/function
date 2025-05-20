# Function: <code>__ll_sc_atomic_sub_return</code>

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
In init/do_mounts.c (ffff800011431894)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In virt/kvm/kvm_main.c (ffff8000100bc018)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:__gfn_to_pfn_memslot
  - virt/kvm/kvm_main.c:kvm_put_kvm
  - virt/kvm/kvm_main.c:kvm_create_vm
```
```
In virt/kvm/arm/mmu.c (ffff8000100ca9ac)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
```
```
In kernel/fork.c (ffff8000100f58dc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmput
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffff8000100fa700)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In kernel/ptrace.c (ffff800010108634)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffff80001010b54c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/umh.c (ffff80001011ad7c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffff80001011cdf8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/nsproxy.c (ffff80001012b70c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/cred.c (ffff80001012d13c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/groups.c (ffff80001013136c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/groups.c:__arm64_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffff80001013d124)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/topology.c (ffff80001015adb8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/sched/topology.c:destroy_sched_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffff8000101688dc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In kernel/irq/manage.c (ffff800010179384)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In kernel/rcu/srcutree.c (ffff80001018a714)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffff80001018c230)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In kernel/futex.c (ffff8000101b7c5c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/uid16.c (ffff8000101be2d4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/uid16.c:__arm64_sys_setgroups16
  - kernel/uid16.c:__arm64_sys_setgroups16
```
```
In kernel/module.c (ffff8000101c34e8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/module.c:__arm64_sys_delete_module
```
```
In kernel/cgroup/cgroup.c (ffff8000101d07f4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffff8000101da0b4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101db5b8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In kernel/utsname.c (ffff8000101e5230)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffff8000101e67e4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/pid_namespace.c (ffff8000101e755c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/stop_machine.c (ffff8000101e8698)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_signal_done
```
```
In kernel/trace/trace_events.c (ffff80001023b3d8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffff8000102429a4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In kernel/bpf/syscall.c (ffff80001025fe98)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_put_uref
```
```
In kernel/bpf/cpumap.c (ffff800010287e3c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In kernel/bpf/stackmap.c (ffff80001028bcbc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffff80001029a9b8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/uprobes.c (ffff8000102a5b44)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/events/uprobes.c:is_trap_at_addr
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (ffff8000102a9340)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
```
```
In kernel/jump_label.c (ffff8000102ab3c0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In mm/filemap.c (ffff8000102b1800)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/oom_kill.c (ffff8000102b7a58)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/page-writeback.c (ffff8000102bd2b4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffff8000102bf1f8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffff8000102c19f0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffff8000102c40fc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffff8000102cb650)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffff8000102d59d8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mmu_context.c (ffff8000102e00bc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/gup.c (ffff8000102f12d8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102fba84)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (ffff8000102fcd4c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffff8000102fe3e4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffff80001030a6f8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/process_vm_access.c (ffff800010312474)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In mm/page_alloc.c (ffff800010317294)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/madvise.c (ffff80001031e71c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffff8000103224a8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffff800010327b60)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffff80001032c7fc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffff8000103361f8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffff800010339ba8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/mmu_notifier.c (ffff80001033cd4c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffff80001033fc30)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffff80001034e16c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffff800010353328)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffff800010359d5c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035fd2c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffff800010368d04)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffff8000103706dc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffff800010375e58)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffff8000103785e8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/page_idle.c (ffff8000103793ac)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffff800010379db0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/open.c (ffff80001037e528)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/read_write.c (ffff80001038049c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In fs/file_table.c (ffff8000103851e8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (ffff800010386ac4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffff80001038ce84)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/pipe.c (ffff80001038fce8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffff80001039337c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffff8000103a8658)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (ffff8000103b1df0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In fs/namespace.c (ffff8000103b4b28)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/libfs.c (ffff8000103c0abc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffff8000103c3e50)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In fs/splice.c (ffff8000103ce4a0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (ffff8000103d59ac)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/buffer.c (ffff8000103dd060)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffff8000103e0b04)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
```
```
In fs/direct-io.c (ffff8000103e5420)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (ffff8000103e6f80)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/notify/mark.c (ffff8000103e9dc8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In fs/userfaultfd.c (ffff8000103f6e48)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/userfaultfd.c:__arm64_sys_userfaultfd
```
```
In fs/aio.c (ffff8000103ff858)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffff80001040346c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_mem_free
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/verity/enable.c (ffff800010411280)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffff800010413514)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffff80001042123c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffff800010424af0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/mbcache.c (ffff800010424f70)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:__entry_find
```
```
In fs/coredump.c (ffff800010428470)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffff80001042bc98)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (ffff80001042d3f8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (ffff800010439808)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/inode.c (ffff80001043b3b0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/root.c (ffff80001043c9f0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffff80001043e780)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
```
In fs/proc/array.c (ffff8000104451e8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/kernfs/dir.c (ffff8000104521c4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In fs/kernfs/file.c (ffff800010454d84)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In fs/sysfs/mount.c (ffff800010457ac8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/inode.c (ffff800010458d44)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffff80001045af84)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffff80001045d8f4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/ext4/inline.c (ffff80001047b350)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffff800010489044)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_end_io_dio
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffff8000104926c4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffff80001049a7fc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffff8000104a3bf8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (ffff8000104a4ef0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffff8000104c0fa8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In fs/ext4/xattr.c (ffff8000104c4bbc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/verity.c (ffff8000104c8388)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In fs/jbd2/transaction.c (ffff8000104ca750)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
```
In fs/jbd2/commit.c (ffff8000104cf450)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffff8000104dbd30)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffff8000104de26c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffff8000104e2668)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffff8000104f62c4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffff8000104f6778)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffff800010503208)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffff80001050e66c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
```
```
In fs/fuse/inode.c (ffff800010512188)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In fs/fuse/readdir.c (ffff800010515704)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In ipc/mqueue.c (ffff800010529dec)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffff80001052cdd4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/keyctl.c (ffff800010533cd4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffff8000105352d8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffff800010535984)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffff800010536394)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In security/tomoyo/common.c (ffff80001057d8f4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffff8000105802d8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/domain.c (ffff800010595004)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffff80001059da50)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In block/bio.c (ffff8000105dbcec)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-core.c (ffff8000105e0da4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In block/blk-ioc.c (ffff8000105e8a34)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In block/partition-generic.c (ffff8000105fd138)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffff8000105ff5a0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffff8000106000bc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffff800010600858)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffff80001060129c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffff800010603254)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
```
```
In block/partitions/msdos.c (ffff800010604ba0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffff8000106052a8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffff800010605568)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffff800010605984)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffff800010605b0c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffff80001060609c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffff800010606d10)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffff800010607088)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In block/blk-wbt.c (ffff8000106210a4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffff80001066a344)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffff8000106e6b54)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffff8000107434fc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In drivers/dma/dmaengine.c (ffff8000107fd0e0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:chan_dev_release
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082b284)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffff80001082e26c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/reset/core.c (ffff80001084d10c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffff80001085d67c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/serial/serial_core.c (ffff80001087dcc8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
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
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffff8000108b38ac)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In drivers/base/power/runtime.c (ffff8000108fd778)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
```
```
In drivers/base/power/domain.c (ffff80001090889c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_sd_counter_dec
```
```
In drivers/block/loop.c (ffff8000109239b4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/mfd/mfd-core.c (ffff800010940918)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In drivers/nvdimm/bus.c (ffff800010952ef4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (ffff80001096807c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (ffff80001096cc44)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffff800010970d68)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/scsi/scsi_lib.c (ffff800010978ed8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffff800010987cb8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/net/tun.c (ffff8000109e1924)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e2bcc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_cleanup
```
```
In drivers/usb/core/devio.c (ffff800010a2d35c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acc684)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/md.c (ffff800010ae9b58)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (ffff800010af7f70)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (ffff800010afe608)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (ffff800010b0a060)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffff800010b0bbe4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/edac/edac_pci_sysfs.c (ffff800010b13ce0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b81234)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In drivers/devfreq/devfreq.c (ffff800010b86510)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In net/core/sock.c (ffff800010bacad0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffff800010bb3dfc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/net_namespace.c (ffff800010bc11c8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffff800010bced64)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/dst.c (ffff800010be0ec4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (ffff800010bfdc38)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffff800010c06e48)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffff800010c0cb9c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffff800010c0e7a8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/netlink/af_netlink.c (ffff800010c4dee8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/ip_input.c (ffff800010c5ebb8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffff800010c624b4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp.c (ffff800010c761e0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffff800010c82000)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8f328)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffff800010c98888)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9f62c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/fib_semantics.c (ffff800010cb6994)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ping.c (ffff800010cc0e50)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ipmr.c (ffff800010ccfd14)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd3670)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0d50)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_state.c (ffff800010ce3670)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffff800010ceb404)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010cec538)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/unix/af_unix.c (ffff800010cf419c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/ip6_output.c (ffff800010cf855c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffff800010cfda80)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffff800010d15950)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/raw.c (ffff800010d2b08c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3f150)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/packet/af_packet.c (ffff800010d5b944)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/rfkill/core.c (ffff800010d6bb58)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In net/dns_resolver/dns_key.c (ffff800010d72f08)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
```
In lib/dec_and_lock.c (ffff800010d847e4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:112
Inline: True
```
</details>
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
