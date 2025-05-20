# Function: <code>might_resched</code>

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
In arch/x86/hyperv/hv_init.c (ffffffff83454d7c)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107d03a)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81081ee2)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In arch/x86/mm/fault.c (ffffffff810aac2f)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810b8362)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810bee96)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
```
```
In kernel/fork.c (ffffffff810cb881)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:mmput
```
```
In kernel/cpu.c (ffffffff810cf1f5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/exit.c (ffffffff810d2ddf)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff810d438d)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/ptrace.c (ffffffff810db709)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/signal.c (ffffffff810e050a)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
```
In kernel/umh.c (ffffffff810ee265)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/workqueue.c (ffffffff810f306f)
Location: include/linux/kernel.h:108
Inline: True
```
```
In kernel/kthread.c (ffffffff810fab36)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/nsproxy.c (ffffffff810ffae6)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/async.c (ffffffff811034e1)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
```
```
In kernel/smpboot.c (ffffffff8110467e)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/kmod.c (ffffffff81105c6e)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff8111428b)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/build_utility.c (ffffffff81143bb2)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffffffff8114dcfe)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
```
```
In kernel/locking/semaphore.c (ffffffff8114df75)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:down_timeout
  - kernel/locking/semaphore.c:down_killable
  - kernel/locking/semaphore.c:down_interruptible
  - kernel/locking/semaphore.c:down
```
```
In kernel/locking/rwsem.c (ffffffff81f25c35)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
```
```
In kernel/locking/percpu-rwsem.c (ffffffff81f25dc5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f27947)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_killable
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex_api.c:rt_mutex_lock
```
```
In kernel/power/swap.c (ffffffff81e5b4ad)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
```
```
In kernel/printk/printk.c (ffffffff8115d382)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/printk/printk.c:__pr_flush
  - kernel/printk/printk.c:__pr_flush
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/irq/manage.c (ffffffff8116308e)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:synchronize_irq
```
```
In kernel/irq/chip.c (ffffffff811669f8)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/rcu/update.c (ffffffff81174606)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/sync.c (ffffffff811753a6)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/rcu/sync.c:rcu_sync_enter
```
```
In kernel/rcu/srcutree.c (ffffffff81177063)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__synchronize_srcu
```
```
In kernel/rcu/tree.c (ffffffff8117ef23)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/module/main.c (ffffffff8118dab8)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/module/main.c:add_unformed_module
  - kernel/module/main.c:simplify_symbols
```
```
In kernel/freezer.c (ffffffff81193815)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (ffffffff81f28583)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex/core.c (ffffffff811b270a)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/futex/waitwake.c (ffffffff811b7433)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wait_multiple
  - kernel/futex/waitwake.c:futex_wait_queue
```
```
In kernel/kexec_core.c (ffffffff811bc418)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
```
```
In kernel/cgroup/cgroup.c (ffffffff811ccf23)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In kernel/cgroup/rstat.c (ffffffff811ce436)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
```
```
In kernel/cgroup/cpuset.c (ffffffff811d8193)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/audit.c (ffffffff811df0de)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
```
In kernel/irq_work.c (ffffffff81269340)
Location: include/linux/kernel.h:108
Inline: True
```
```
In kernel/events/core.c (ffffffff812e208c)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
```
```
In kernel/events/uprobes.c (ffffffff812e8624)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812f1b21)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/mempool.c (ffffffff812f76dc)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
```
```
In mm/oom_kill.c (ffffffff812fb347)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/page-writeback.c (ffffffff812fc5df)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff81307627)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81312954)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff813185e2)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_undo_range
```
```
In mm/backing-dev.c (ffffffff81324075)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/compaction.c (ffffffff8133321e)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
```
```
In mm/gup.c (ffffffff813375f1)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/memory.c (ffffffff81348ac6)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mmap.c (ffffffff8134d783)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/mmap.c:remove_vma
```
```
In mm/mprotect.c (ffffffff813545cf)
Location: include/linux/kernel.h:108
Inline: True
```
```
In mm/mremap.c (ffffffff813562bc)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8135f622)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/vmalloc.c (ffffffff813667a5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/page_alloc.c (ffffffff813702a0)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/memory_hotplug.c (ffffffff81373aa5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In mm/madvise.c (ffffffff81375b24)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff813825ab)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/dmapool.c (ffffffff81386e51)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In mm/hugetlb.c (ffffffff81394a00)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mmu_notifier.c (ffffffff8139cdc3)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
```
```
In mm/ksm.c (ffffffff8139e4ce)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff813aaa35)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/migrate.c (ffffffff813b5221)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:writeout
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:putback_movable_pages
```
```
In mm/migrate_device.c (ffffffff813b847f)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_pages
  - mm/migrate_device.c:migrate_vma_setup
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff813c0ba4)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff813c8496)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memory-failure.c (ffffffff813da091)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
```
In mm/userfaultfd.c (ffffffff813e5692)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9b03)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/open.c (ffffffff813ec249)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff813f30d4)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/file_table.c (ffffffff813f3732)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff813fbda9)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/pipe.c (ffffffff813ff54d)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/dcache.c (ffffffff814138ec)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
```
In fs/inode.c (ffffffff81418b13)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
```
```
In fs/file.c (ffffffff8141b14b)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
```
In fs/namespace.c (ffffffff81420e33)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/fs-writeback.c (ffffffff81433d62)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
```
In fs/splice.c (ffffffff814392e1)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff81442612)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/buffer.c (ffffffff814447c9)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/buffer.c:bh_submit_read
  - fs/buffer.c:bh_submit_read
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/notify/fsnotify.c (ffffffff8144e1e3)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/notify/group.c (ffffffff8144ed57)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81452e1b)
Location: include/linux/kernel.h:108
Inline: True
```
```
In fs/aio.c (ffffffff81461235)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/aio.c:aio_write
  - fs/aio.c:read_events
  - fs/aio.c:aio_read_events_ring
```
```
In fs/verity/read_metadata.c (ffffffff8147401a)
Location: include/linux/kernel.h:108
Inline: True
```
```
In fs/locks.c (ffffffff8147b46c)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/mbcache.c (ffffffff81481714)
Location: include/linux/kernel.h:108
Inline: True
```
```
In fs/coredump.c (ffffffff81485ec4)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:coredump_wait
```
```
In fs/iomap/buffered-io.c (ffffffff81488acb)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/quota/dquot.c (ffffffff81490903)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/quota/quota.c (ffffffff814946aa)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/quota/quota.c:quotactl_block
```
```
In fs/proc/task_mmu.c (ffffffff81498e2c)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/proc_sysctl.c (ffffffff814adba6)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
```
In fs/kernfs/dir.c (ffffffff814b3cf0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff814bffd6)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff814c2fe5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/extents.c (ffffffff814c48c7)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff814d101a)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff814d53d7)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff814d8719)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff814dbc56)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff814ebf80)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff814eec92)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff814fb704)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/mmp.c (ffffffff814fd8a8)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff815031d9)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/resize.c (ffffffff8150b541)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff81526b86)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_read_bh
```
```
In fs/ext4/xattr.c (ffffffff81534a3a)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/fast_commit.c (ffffffff81535b96)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff8153a39e)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/crypto.c (ffffffff8153cd36)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
```
```
In fs/jbd2/transaction.c (ffffffff8153fdcf)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff81540eb5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff815430e3)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff81543c93)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/revoke.c (ffffffff815448e0)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff81549d38)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/squashfs/cache.c (ffffffff8154cecd)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
```
```
In fs/hugetlbfs/inode.c (ffffffff815556dc)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff8155930a)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8155be1f)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/fat/misc.c (ffffffff8156273f)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff81569322)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/ecryptfs/read_write.c (ffffffff81569ceb)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff8156b0a4)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/ecryptfs/kthread.c (ffffffff8156ff16)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In fs/ecryptfs/miscdev.c (ffffffff81571138)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/fuse/dev.c (ffffffff81578558)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/dir.c (ffffffff8157bbe0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In fs/fuse/file.c (ffffffff8157f173)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_launder_folio
  - fs/fuse/file.c:fuse_launder_folio
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/inode.c (ffffffff81584baa)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In fs/fuse/readdir.c (ffffffff8158931b)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In fs/fuse/dax.c (ffffffff8158ab02)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
```
```
In security/keys/gc.c (ffffffff815a40ee)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/process_keys.c (ffffffff815ab535)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff815ac7a2)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/selinux/hooks.c (ffffffff815cd2ff)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
```
```
In security/tomoyo/common.c (ffffffff815fcba9)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_supervisor
```
```
In security/apparmor/apparmorfs.c (ffffffff81609b58)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/domain.c (ffffffff81614978)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/lsm.c (ffffffff81626e95)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/apparmor/lsm.c:aa_get_buffer
  - security/apparmor/lsm.c:begin_current_label_crit_section
```
```
In security/apparmor/net.c (ffffffff81631a9e)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81632c06)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/landlock/object.c (ffffffff81638515)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/landlock/object.c:landlock_put_object
```
```
In security/landlock/ruleset.c (ffffffff81638df5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:free_ruleset
  - security/landlock/ruleset.c:free_ruleset
  - security/landlock/ruleset.c:inherit_ruleset
  - security/landlock/ruleset.c:merge_ruleset
  - security/landlock/ruleset.c:insert_rule
  - security/landlock/ruleset.c:insert_rule
```
```
In security/landlock/fs.c (ffffffff81639514)
Location: include/linux/kernel.h:108
Inline: True
```
```
In crypto/skcipher.c (ffffffff81650c5c)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff8166c855)
Location: include/linux/kernel.h:108
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff8166cacc)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
```
```
In block/blk-core.c (ffffffff81679384)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_cleanup_queue
```
```
In block/blk-sysfs.c (ffffffff8167a2d2)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_release_queue
```
```
In block/blk-mq.c (ffffffff816880ea)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-mq-sched.c (ffffffff8168fc2d)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/genhd.c (ffffffff81692851)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - block/genhd.c:disk_release
  - block/genhd.c:del_gendisk
```
```
In block/blk-cgroup.c (ffffffff816a4655)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In block/blk-crypto-profile.c (ffffffff816c26ab)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/io_uring.c (ffffffff816d7668)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_write
```
```
In lib/scatterlist.c (ffffffff816df472)
Location: include/linux/kernel.h:108
Inline: True
```
```
In lib/iov_iter.c (ffffffff816e5350)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
```
```
In lib/percpu-refcount.c (ffffffff816e8f7d)
Location: include/linux/kernel.h:108
Inline: True
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8178e8d5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In drivers/gpio/gpiolib.c (ffffffff817a40f5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
```
```
In drivers/pwm/core.c (ffffffff817b5565)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_apply_state
```
```
In drivers/pwm/pwm-lpss.c (ffffffff817b74fe)
Location: include/linux/kernel.h:108
Inline: True
```
```
In drivers/pci/access.c (ffffffff817b86a5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/access.c:pci_wait_cfg
```
```
In drivers/pci/pci.c (ffffffff817c6e0f)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_init_reset_methods
  - drivers/pci/pci.c:__pci_reset_function_locked
```
```
In drivers/pci/pcie/dpc.c (ffffffff817dccf2)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff817e97f2)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817e9d67)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff817edc6f)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/iov.c (ffffffff817f2765)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8180f397)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/osl.c (ffffffff81f1c471)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/ec.c (ffffffff81833558)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81899c40)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/acpi/acpi_dbg.c (ffffffff8189a3e4)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
```
In drivers/dma/dmaengine.c (ffffffff818b7ccf)
Location: include/linux/kernel.h:108
Inline: True
```
```
In drivers/virtio/virtio.c (ffffffff818bc9e5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c5b52)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_oom_notify
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
```
```
In drivers/xen/balloon.c (ffffffff818ca527)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff818d4906)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff818d4ed7)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff818d8b09)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81ebe518)
Location: include/linux/kernel.h:108
Inline: True
```
```
In drivers/tty/tty_ioctl.c (ffffffff818f9262)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
```
```
In drivers/tty/tty_ldsem.c (ffffffff81f28dc5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81902dc6)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
```
```
In drivers/tty/vt/vt.c (ffffffff81911636)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_blank_screen
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81915286)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_write
```
```
In drivers/tty/serial/serial_core.c (ffffffff8191862f)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81925c6a)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/char/random.c (ffffffff81ec2dba)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/char/random.c:wait_for_random_bytes
```
```
In drivers/char/virtio_console.c (ffffffff81939a79)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8194a380)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/iommu/intel/pasid.c (ffffffff8195eaf5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/iommu.c (ffffffff81966cb5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81970792)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/dd.c (ffffffff8197cac8)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/base/dd.c:wait_for_device_probe
```
```
In drivers/base/power/runtime.c (ffffffff81991298)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
```
```
In drivers/base/power/main.c (ffffffff819966b8)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
```
```
In drivers/base/power/clock_ops.c (ffffffff81ecca82)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_op_lock
```
```
In drivers/base/firmware_loader/main.c (ffffffff8199ff77)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff819a129e)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_rw
```
```
In drivers/base/regmap/regmap.c (ffffffff819a7b8d)
Location: include/linux/kernel.h:108
Inline: True
```
```
In drivers/block/loop.c (ffffffff819b6d69)
Location: include/linux/kernel.h:108
Inline: True
```
```
In drivers/misc/sram.c (ffffffff819bf50f)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/nvdimm/bus.c (ffffffff819d6444)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/nvdimm/claim.c (ffffffff819e45db)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In drivers/dma-buf/dma-buf.c (ffffffff819ed775)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
```
```
In drivers/dma-buf/dma-fence.c (ffffffff819eeeb0)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
```
```
In drivers/scsi/scsi_error.c (ffffffff819fad70)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/sg.c (ffffffff81a1dbac)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
```
```
In drivers/spi/spi.c (ffffffff81a4cfc5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_delay_exec
```
```
In drivers/spi/spi-mem.c (ffffffff81a5103b)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
```
```
In drivers/net/phy/phy_device.c (ffffffff81a58025)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
```
```
In drivers/net/phy/bcm84881.c (ffffffff81a5e42d)
Location: include/linux/kernel.h:108
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6f118)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
```
```
In drivers/net/xen-netfront.c (ffffffff81a7033f)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
```
```
In drivers/usb/core/hcd.c (ffffffff81a9bee5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/urb.c (ffffffff81a9c781)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/devio.c (ffffffff81aac53c)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae275a)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
```
```
In drivers/usb/host/xhci.c (ffffffff81aeed2c)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
```
```
In drivers/input/serio/libps2.c (ffffffff81b13362)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/mousedev.c (ffffffff81b1b978)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_read
```
```
In drivers/input/evdev.c (ffffffff81b1d221)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_read
```
```
In drivers/input/misc/uinput.c (ffffffff81b23d65)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81b37e57)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b38a67)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/i2c/busses/i2c-designware-amdpsp.c (ffffffff81b3a30d)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req
```
```
In drivers/pps/pps.c (ffffffff81b3a9d4)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81b3d4ff)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81b3f080)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81b3fa05)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81b5d2ea)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
```
```
In drivers/md/md-bitmap.c (ffffffff81b6c2b7)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm-zone.c (ffffffff81b6dc6b)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/md/dm.c (ffffffff81b73fb7)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_destroy
```
```
In drivers/md/dm-kcopyd.c (ffffffff81b7d474)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b8e8a3)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
```
```
In drivers/mmc/core/core.c (ffffffff81ba4830)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In net/core/sock.c (ffffffff81bf0a15)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock_fast
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
```
```
In net/core/skbuff.c (ffffffff81bf9411)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff81bfffe0)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff81c1739c)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:dev_remove_pack
```
```
In net/core/filter.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/core/netpoll.c (ffffffff81c5b555)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
```
```
In net/core/selftests.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81caf7f5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/netlink/genetlink.c (ffffffff81cb20a1)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81cdc98e)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp_output.c (ffffffff81d0010d)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_cong.c (ffffffff81d0fc95)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
```
```
In net/ipv4/arp.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81d7d2b8)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
```
```
In net/unix/garbage.c (ffffffff81d83741)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/unix/garbage.c:wait_for_unix_gc
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/strparser/strparser.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/wireless/wext-proc.c (ffffffff81dfbc65)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/rfkill/core.c (ffffffff81e04f91)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_read
```
```
In net/mptcp/protocol.c (ffffffff81e1d262)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:mptcp_worker
```
```
In virt/lib/irqbypass.c (ffffffff81e3bf40)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - virt/lib/irqbypass.c:irq_bypass_register_consumer
  - virt/lib/irqbypass.c:irq_bypass_register_producer
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108e490)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81090bb8)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81092961)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810947c3)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In arch/x86/mm/fault.c (ffffffff810c491f)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d3bb2)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810daac6)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
```
```
In kernel/fork.c (ffffffff810e740e)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/fork.c:mm_access
```
```
In kernel/cpu.c (ffffffff810ed665)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/softirq.c (ffffffff810f3024)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_unlock_wait
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/ptrace.c (ffffffff810fb7c9)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/signal.c (ffffffff811050d5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
```
```
In kernel/umh.c (ffffffff8110f775)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/workqueue.c (ffffffff8111334f)
Location: include/linux/kernel.h:108
Inline: True
```
```
In kernel/kthread.c (ffffffff8111d9a6)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/nsproxy.c (ffffffff81124846)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/async.c (ffffffff81128b81)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
```
```
In kernel/smpboot.c (ffffffff81129ed3)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/kmod.c (ffffffff8112b78a)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff8113b5cb)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/build_utility.c (ffffffff8116f520)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
  - kernel/sched/build_utility.c:wait_for_completion_io_timeout
  - kernel/sched/build_utility.c:wait_for_completion_io
  - kernel/sched/build_utility.c:wait_for_completion_timeout
  - kernel/sched/build_utility.c:wait_for_completion
```
```
In kernel/locking/mutex.c (ffffffff8117cebe)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
```
```
In kernel/locking/semaphore.c (ffffffff820d0825)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:down_timeout
  - kernel/locking/semaphore.c:down_killable
  - kernel/locking/semaphore.c:down_interruptible
  - kernel/locking/semaphore.c:down
```
```
In kernel/locking/rwsem.c (ffffffff820d1655)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
```
```
In kernel/locking/percpu-rwsem.c (ffffffff820d1835)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
```
```
In kernel/locking/rtmutex_api.c (ffffffff820d3437)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_killable
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex_api.c:rt_mutex_lock
```
```
In kernel/power/swap.c (ffffffff811893d3)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
```
```
In kernel/printk/printk.c (ffffffff811907c7)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:suspend_console
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/irq/manage.c (ffffffff81196248)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/irq/manage.c:wake_up_and_wait_for_irq_thread_ready
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:synchronize_irq
```
```
In kernel/irq/chip.c (ffffffff8119acd8)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/irq/msi.c (ffffffff811a4181)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_insert_desc
  - kernel/irq/msi.c:msi_insert_desc
```
```
In kernel/rcu/update.c (ffffffff811a948d)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/sync.c (ffffffff811ac496)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/rcu/sync.c:rcu_sync_enter
```
```
In kernel/rcu/srcutree.c (ffffffff811ae623)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__synchronize_srcu
```
```
In kernel/rcu/tree.c (ffffffff811b61fb)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/module/main.c (ffffffff811ca5cd)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/module/main.c:add_unformed_module
  - kernel/module/main.c:simplify_symbols
```
```
In kernel/freezer.c (ffffffff811d11b5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
```
```
In kernel/futex/core.c (ffffffff811f35aa)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/cgroup/cgroup.c (ffffffff812104e3)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In kernel/cgroup/rstat.c (ffffffff81211c30)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
```
```
In kernel/cgroup/cpuset.c (ffffffff8121d0f5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/audit.c (ffffffff81224d15)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In kernel/irq_work.c (ffffffff812be180)
Location: include/linux/kernel.h:108
Inline: True
```
```
In kernel/events/core.c (ffffffff8134a5b8)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134ce83)
Location: include/linux/kernel.h:108
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813522c1)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8135cbdb)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/mempool.c (ffffffff8136102c)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
```
```
In mm/oom_kill.c (ffffffff81365387)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/page-writeback.c (ffffffff813668ef)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff81371745)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81385d97)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:try_to_inc_max_seq
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8138c4d6)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_undo_range
```
```
In mm/backing-dev.c (ffffffff81398945)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/compaction.c (ffffffff813a9bd2)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/gup.c (ffffffff813ae71b)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/memory.c (ffffffff813c0f43)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mmap.c (ffffffff813c66c5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/mmap.c:remove_vma
```
```
In mm/mprotect.c (ffffffff813ceae9)
Location: include/linux/kernel.h:108
Inline: True
```
```
In mm/mremap.c (ffffffff813d08ea)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff813da482)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/vmalloc.c (ffffffff813e2405)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/page_alloc.c (ffffffff813ec940)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/memory_hotplug.c (ffffffff813f11d5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In mm/madvise.c (ffffffff813f30c1)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff813fc511)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/dmapool.c (ffffffff81404d1f)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In mm/hugetlb.c (ffffffff8140dd26)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mmu_notifier.c (ffffffff8141c1f3)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
```
```
In mm/ksm.c (ffffffff8141dbfe)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8142cd4a)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/migrate.c (ffffffff81435276)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:writeout
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:putback_movable_pages
```
```
In mm/migrate_device.c (ffffffff8143a424)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_setup
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff81442a04)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8144c656)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memory-failure.c (ffffffff81461833)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
```
In mm/memremap.c (ffffffff8146f851)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471b3d)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/open.c (ffffffff81474719)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff8147bdc2)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/file_table.c (ffffffff8147c502)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff81484e59)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/pipe.c (ffffffff8148930d)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/dcache.c (ffffffff8149ecec)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
```
In fs/inode.c (ffffffff814a4433)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
```
```
In fs/file.c (ffffffff814a71db)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
```
In fs/namespace.c (ffffffff814ad453)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/fs-writeback.c (ffffffff814c1cf2)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
```
In fs/splice.c (ffffffff814c75d1)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff814d1302)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/buffer.c (ffffffff814d33cc)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__bh_read
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/notify/fsnotify.c (ffffffff814dc8d3)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/notify/group.c (ffffffff814dd517)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e1bae)
Location: include/linux/kernel.h:108
Inline: True
```
```
In fs/aio.c (ffffffff814f11c5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/aio.c:aio_write
  - fs/aio.c:read_events
  - fs/aio.c:aio_read_events_ring
```
```
In fs/locks.c (ffffffff8150dffc)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/mbcache.c (ffffffff81514734)
Location: include/linux/kernel.h:108
Inline: True
```
```
In fs/coredump.c (ffffffff81519753)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8151c79b)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/quota/dquot.c (ffffffff815244a3)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/quota/quota.c (ffffffff8152852a)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/quota/quota.c:quotactl_block
```
```
In fs/proc/task_mmu.c (ffffffff8152d194)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/proc_sysctl.c (ffffffff815440a6)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
```
In fs/kernfs/dir.c (ffffffff8154a1e7)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_drain
```
```
In fs/ext4/balloc.c (ffffffff81557285)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8155b375)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/extents.c (ffffffff8155ce07)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff81569a5e)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff8156e335)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81571501)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff81574bb6)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81585ced)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff81588d56)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff81595ed4)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/mmp.c (ffffffff81598088)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8159dd19)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/resize.c (ffffffff815a61e4)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff815c4466)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_read_bh
```
```
In fs/ext4/xattr.c (ffffffff815d2f67)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:__ext4_xattr_check_block
```
```
In fs/ext4/fast_commit.c (ffffffff815d4046)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff815d890e)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/crypto.c (ffffffff815db4fb)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
```
```
In fs/jbd2/transaction.c (ffffffff815de965)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff815e0008)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff815e1f3b)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff815e2c03)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/revoke.c (ffffffff815e3990)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff815ea5d8)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/squashfs/cache.c (ffffffff815ecdeb)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
```
```
In fs/squashfs/decompressor_multi.c (ffffffff815f2c25)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi.c:squashfs_decompress
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6b26)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff815fc40f)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff815fdd1a)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/fat/misc.c (ffffffff8160511d)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff8160ceb2)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/ecryptfs/read_write.c (ffffffff8160d99b)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff8160ef64)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/ecryptfs/kthread.c (ffffffff81614cf7)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In fs/ecryptfs/miscdev.c (ffffffff816163a8)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/fuse/dev.c (ffffffff8161daa8)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/dir.c (ffffffff816215c0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In fs/fuse/file.c (ffffffff81624e40)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_launder_folio
  - fs/fuse/file.c:fuse_launder_folio
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/inode.c (ffffffff8162ad1a)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In fs/fuse/dax.c (ffffffff8163125f)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
```
```
In security/keys/gc.c (ffffffff8164ddce)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/process_keys.c (ffffffff81655955)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff81656c87)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/selinux/hooks.c (ffffffff8167aa0f)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_remove_acl
  - security/selinux/hooks.c:selinux_inode_get_acl
  - security/selinux/hooks.c:selinux_inode_set_acl
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
```
```
In security/tomoyo/common.c (ffffffff816ad92d)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_supervisor
```
```
In security/apparmor/apparmorfs.c (ffffffff816bb698)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/domain.c (ffffffff816c7695)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/lsm.c (ffffffff816dad43)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/apparmor/lsm.c:aa_get_buffer
  - security/apparmor/lsm.c:begin_current_label_crit_section
```
```
In security/apparmor/net.c (ffffffff816e67fe)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff816e7a56)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/landlock/object.c (ffffffff816ef985)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/landlock/object.c:landlock_put_object
```
```
In security/landlock/ruleset.c (ffffffff816f0315)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:free_ruleset
  - security/landlock/ruleset.c:free_ruleset
  - security/landlock/ruleset.c:inherit_ruleset
  - security/landlock/ruleset.c:merge_ruleset
  - security/landlock/ruleset.c:insert_rule
  - security/landlock/ruleset.c:insert_rule
```
```
In security/landlock/fs.c (ffffffff816f0b84)
Location: include/linux/kernel.h:108
Inline: True
```
```
In crypto/skcipher.c (ffffffff8170a43c)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff817277e5)
Location: include/linux/kernel.h:108
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81727a78)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
```
```
In block/blk-core.c (ffffffff81735804)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8174a55f)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_destroy_queue
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/blk-mq-sched.c (ffffffff8174e74a)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/genhd.c (ffffffff817528a5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/genhd.c:del_gendisk
```
```
In block/partitions/core.c (ffffffff817547e8)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
```
```
In block/blk-cgroup.c (ffffffff81763385)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In block/blk-crypto-profile.c (ffffffff81783a0b)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/io_uring.c (ffffffff8178c3cf)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
```
```
In io_uring/rw.c (ffffffff817a4ac3)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
```
```
In lib/scatterlist.c (ffffffff817cf6a2)
Location: include/linux/kernel.h:108
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff817d905d)
Location: include/linux/kernel.h:108
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff818bbb75)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
```
```
In drivers/pwm/core.c (ffffffff818cf8c5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_apply_state
```
```
In drivers/pwm/pwm-lpss.c (ffffffff818d1bc1)
Location: include/linux/kernel.h:108
Inline: True
```
```
In drivers/pci/access.c (ffffffff818d3055)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/access.c:pci_wait_cfg
```
```
In drivers/pci/pci.c (ffffffff818e42af)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_init_reset_methods
  - drivers/pci/pci.c:__pci_reset_function_locked
```
```
In drivers/pci/pcie/dpc.c (ffffffff818ff08b)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8190f7df)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8190fdcb)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81914fef)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/iov.c (ffffffff8191ada5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
```
```
In drivers/pci/doe.c (ffffffff819205b8)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/pci/doe.c:pcim_doe_create_mb
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8193e137)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/osl.c (ffffffff820c44a1)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/ec.c (ffffffff81967062)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/acpi/cppc_acpi.c (ffffffff819e2010)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/acpi/acpi_dbg.c (ffffffff819e2a14)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
```
In drivers/dma/dmaengine.c (ffffffff81a04f6f)
Location: include/linux/kernel.h:108
Inline: True
```
```
In drivers/virtio/virtio.c (ffffffff81a0b705)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a16252)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_oom_notify
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
```
```
In drivers/xen/balloon.c (ffffffff81a1ba67)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81a26b96)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a27167)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a2b2c9)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81a2d2c0)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
```
```
In drivers/tty/tty_ioctl.c (ffffffff81a52112)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
```
```
In drivers/tty/tty_ldsem.c (ffffffff820d4a55)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81a5cd96)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
```
```
In drivers/tty/vt/vt.c (ffffffff81a6c576)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_blank_screen
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81a70526)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_write
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a74065)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81a826aa)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/char/random.c (ffffffff81a94fc2)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/char/random.c:wait_for_random_bytes
```
```
In drivers/char/virtio_console.c (ffffffff81a99bae)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aada21)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In drivers/iommu/intel/pasid.c (ffffffff81ac6585)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81acf34d)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/ioasid.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81adb5b2)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/dd.c (ffffffff81ae9cb8)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/base/dd.c:wait_for_device_probe
```
```
In drivers/base/power/runtime.c (ffffffff81b01608)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
```
```
In drivers/base/power/main.c (ffffffff81b073bf)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
```
```
In drivers/base/power/clock_ops.c (ffffffff81b0f0d8)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_op_lock
```
```
In drivers/base/memory.c (ffffffff81b1602d)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register
```
```
In drivers/base/regmap/regmap.c (ffffffff81b1ac6d)
Location: include/linux/kernel.h:108
Inline: True
```
```
In drivers/block/loop.c (ffffffff81b2bfc5)
Location: include/linux/kernel.h:108
Inline: True
```
```
In drivers/misc/sram.c (ffffffff81b34caf)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/nvdimm/bus.c (ffffffff81b510d4)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/nvdimm/claim.c (ffffffff81b6031b)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In drivers/dax/super.c (ffffffff81b65a82)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_add_host
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81b69535)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment_unlocked
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81b6c3b2)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
```
```
In drivers/dma-buf/dma-heap.c (ffffffff81b6f954)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/dma-heap.c:dma_heap_add
```
```
In drivers/scsi/scsi_error.c (ffffffff81b78de0)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81b86895)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
```
```
In drivers/scsi/sg.c (ffffffff81b9eebc)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
```
```
In drivers/spi/spi.c (ffffffff81bd5965)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_delay_exec
```
```
In drivers/spi/spi-mem.c (ffffffff81bda23b)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
```
```
In drivers/net/phy/phy_device.c (ffffffff81be1dc1)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
```
```
In drivers/net/phy/bcm84881.c (ffffffff81be916d)
Location: include/linux/kernel.h:108
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c030e8)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
```
```
In drivers/net/xen-netfront.c (ffffffff81c035ef)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
```
```
In drivers/usb/core/hcd.c (ffffffff81c20d75)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/urb.c (ffffffff81c21721)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/devio.c (ffffffff81c33c16)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c6e18a)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
```
```
In drivers/usb/host/xhci.c (ffffffff81c7bd5e)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
```
```
In drivers/input/serio/libps2.c (ffffffff81ca4292)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/mousedev.c (ffffffff81cad768)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_read
```
```
In drivers/input/evdev.c (ffffffff81caf1c1)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_read
```
```
In drivers/input/misc/uinput.c (ffffffff81cb6ff5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81ccd497)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81cce377)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/i2c/busses/i2c-designware-amdpsp.c (ffffffff81ccfd4d)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req
```
```
In drivers/pps/pps.c (ffffffff81cd0614)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81cd354f)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81cd5460)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81cd5f75)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81cf496a)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
```
```
In drivers/md/md-bitmap.c (ffffffff81d08327)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm-zone.c (ffffffff81d0a156)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/md/dm.c (ffffffff81d10f57)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_destroy
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d1b394)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
```
```
In drivers/opp/core.c (ffffffff81d29bb6)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_config
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d2ec03)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
```
```
In drivers/mmc/core/core.c (ffffffff81d46a50)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In net/core/sock.c (ffffffff81d9cff5)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock_fast
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
  - net/core/sock.c:sock_bindtoindex
```
```
In net/core/skbuff.c (ffffffff81da8240)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff81daf3d0)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff81dc839c)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:dev_remove_pack
```
```
In net/core/filter.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/core/netpoll.c (ffffffff81e11845)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
```
```
In net/core/selftests.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/core/devlink.c (ffffffff81e2f486)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_region_snapshot_id_get
  - net/core/devlink.c:devl_port_register
  - net/core/devlink.c:devlink_alloc_ns
  - net/core/devlink.c:devlink_nl_cmd_region_new
```
```
In net/netlink/af_netlink.c (ffffffff83f0dd37)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/netlink/genetlink.c (ffffffff81e702a3)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81e9d3ee)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp_output.c (ffffffff81ec51dd)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_cong.c (ffffffff81ed5915)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
```
```
In net/ipv4/arp.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/unix/garbage.c (ffffffff81f50ed1)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/unix/garbage.c:wait_for_unix_gc
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/strparser/strparser.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/wireless/wext-proc.c (ffffffff81fd0565)
Location: include/linux/kernel.h:108
Inline: True
```
```
In net/rfkill/core.c (ffffffff81fda1e1)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_read
```
```
In net/mptcp/protocol.c (ffffffff81ff47f2)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:mptcp_worker
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8204c205)
Location: include/linux/kernel.h:108
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81091340)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81093ae8)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81095894)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81097763)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d6f92)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810e6056)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
```
```
In kernel/fork.c (ffffffff810f2f24)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/fork.c:mm_access
```
```
In kernel/cpu.c (ffffffff810f91f5)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/softirq.c (ffffffff810ff364)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_unlock_wait
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/ptrace.c (ffffffff81107869)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/signal.c (ffffffff81111355)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
```
```
In kernel/umh.c (ffffffff8111bc15)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/workqueue.c (ffffffff8111f94f)
Location: include/linux/kernel.h:109
Inline: True
```
```
In kernel/kthread.c (ffffffff8112ab96)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/nsproxy.c (ffffffff81131b46)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/async.c (ffffffff81136031)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
```
```
In kernel/sched/core.c (ffffffff8114ea11)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/build_utility.c (ffffffff81180e8c)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_rtpoll_worker
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
  - kernel/sched/build_utility.c:wait_for_completion_io_timeout
  - kernel/sched/build_utility.c:wait_for_completion_io
  - kernel/sched/build_utility.c:wait_for_completion_timeout
  - kernel/sched/build_utility.c:wait_for_completion
```
```
In kernel/locking/mutex.c (ffffffff8118db6e)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
```
```
In kernel/locking/semaphore.c (ffffffff82154bb5)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:down_timeout
  - kernel/locking/semaphore.c:down_killable
  - kernel/locking/semaphore.c:down_interruptible
  - kernel/locking/semaphore.c:down
```
```
In kernel/locking/rwsem.c (ffffffff821559c5)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
```
```
In kernel/locking/percpu-rwsem.c (ffffffff82155ba5)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
```
```
In kernel/locking/rtmutex_api.c (ffffffff8215771f)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_killable
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex_api.c:rt_mutex_lock
```
```
In kernel/power/swap.c (ffffffff8119a8ef)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
```
```
In kernel/printk/printk.c (ffffffff811a20da)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:suspend_console
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/irq/manage.c (ffffffff811a7c08)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/irq/manage.c:wake_up_and_wait_for_irq_thread_ready
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:synchronize_irq
```
```
In kernel/irq/chip.c (ffffffff811aca38)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/irq/msi.c (ffffffff811b63f7)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_insert_desc
  - kernel/irq/msi.c:msi_insert_desc
```
```
In kernel/rcu/update.c (ffffffff811bb20b)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/sync.c (ffffffff811be3b6)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/rcu/sync.c:rcu_sync_enter
```
```
In kernel/rcu/srcutree.c (ffffffff811c0603)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__synchronize_srcu
```
```
In kernel/rcu/tree.c (ffffffff811c8a0f)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:synchronize_rcu
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/module/main.c (ffffffff811dd178)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/module/main.c:simplify_symbols
```
```
In kernel/freezer.c (ffffffff811e5425)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
```
```
In kernel/futex/core.c (ffffffff81207d60)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/cgroup/cgroup.c (ffffffff81225ef3)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In kernel/cgroup/rstat.c (ffffffff81227590)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
```
```
In kernel/cgroup/cpuset.c (ffffffff81233533)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
```
```
In kernel/audit.c (ffffffff8123b2ea)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In kernel/trace/trace_events_user.c (ffffffff812c7240)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_mm_remove
```
```
In kernel/irq_work.c (ffffffff812e4d40)
Location: include/linux/kernel.h:109
Inline: True
```
```
In kernel/events/core.c (ffffffff8137b5f8)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137dcd3)
Location: include/linux/kernel.h:109
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813834d1)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8138ec0e)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/mempool.c (ffffffff813933ec)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
```
```
In mm/oom_kill.c (ffffffff81397847)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/page-writeback.c (ffffffff81398f5f)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff813a3855)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813b905b)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff813bf843)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_get_partial_folio
```
```
In mm/backing-dev.c (ffffffff813cb8a5)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/compaction.c (ffffffff813dce88)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/gup.c (ffffffff813e301b)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/memory.c (ffffffff813f5a73)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mmap.c (ffffffff813fade5)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/mmap.c:remove_vma
```
```
In mm/mprotect.c (ffffffff81403433)
Location: include/linux/kernel.h:109
Inline: True
```
```
In mm/mremap.c (ffffffff8140530a)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8140ebc2)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/vmalloc.c (ffffffff81416c85)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/page_alloc.c (ffffffff814218b2)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/memory_hotplug.c (ffffffff81424c15)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In mm/madvise.c (ffffffff81426b20)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8142f820)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/dmapool.c (ffffffff8143817d)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In mm/hugetlb.c (ffffffff81441100)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mmu_notifier.c (ffffffff8144f7a3)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
```
```
In mm/ksm.c (ffffffff8145253e)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8146235c)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/migrate.c (ffffffff8146a7e4)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:writeout
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:putback_movable_pages
```
```
In mm/migrate_device.c (ffffffff8146fd74)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_setup
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff81478339)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81481f06)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memory-failure.c (ffffffff81497052)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:try_to_split_thp_page
```
```
In mm/memremap.c (ffffffff814a4031)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a6498)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/open.c (ffffffff814a90f6)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff814b0989)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/file_table.c (ffffffff814b108b)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/exec.c (ffffffff814b9dd9)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/pipe.c (ffffffff814be23d)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/dcache.c (ffffffff814d400c)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
```
In fs/inode.c (ffffffff814d95aa)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
```
```
In fs/file.c (ffffffff814dc1c2)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
```
In fs/namespace.c (ffffffff814e2233)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/fs-writeback.c (ffffffff814f7082)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
```
In fs/splice.c (ffffffff814fd4e7)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff815075f8)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/buffer.c (ffffffff8150a65c)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__bh_read
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/notify/fsnotify.c (ffffffff81513123)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/notify/group.c (ffffffff81513d77)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
```
```
In fs/notify/fanotify/fanotify.c (ffffffff815184be)
Location: include/linux/kernel.h:109
Inline: True
```
```
In fs/aio.c (ffffffff8152853e)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/aio.c:aio_write
  - fs/aio.c:read_events
```
```
In fs/locks.c (ffffffff815457cf)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/mbcache.c (ffffffff8154c144)
Location: include/linux/kernel.h:109
Inline: True
```
```
In fs/coredump.c (ffffffff8155102b)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8155499b)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/quota/dquot.c (ffffffff8155c8dc)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/quota/quota.c (ffffffff81560949)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/quota/quota.c:quotactl_block
```
```
In fs/proc/task_mmu.c (ffffffff81564ec2)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/proc_sysctl.c (ffffffff8157a915)
Location: include/linux/kernel.h:109
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff81581e17)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_drain
```
```
In fs/ext4/balloc.c (ffffffff8158f105)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81593195)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/extents.c (ffffffff81594c27)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff815a184e)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff815a61f5)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815a9268)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff815aca86)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff815bc5a4)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff815bf5cb)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_getuuid
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff815cc8fe)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/mmp.c (ffffffff815ceb38)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block_thawed
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/namei.c (ffffffff815d457d)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/resize.c (ffffffff815dca54)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff815fbb47)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_read_bh
```
```
In fs/ext4/xattr.c (ffffffff8160aab5)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:check_xattrs
```
```
In fs/ext4/fast_commit.c (ffffffff8160bc26)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff816104af)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/crypto.c (ffffffff81612fab)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
```
```
In fs/jbd2/transaction.c (ffffffff816163c5)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff81617324)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81619757)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff8161a51d)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/revoke.c (ffffffff8161b145)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff81620de1)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/squashfs/cache.c (ffffffff81624d2b)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
```
```
In fs/squashfs/decompressor_multi.c (ffffffff8162ad15)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi.c:squashfs_decompress
```
```
In fs/hugetlbfs/inode.c (ffffffff8162ebe1)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff8163439f)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81635ccb)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/fat/misc.c (ffffffff8163d02d)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff81644d62)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/ecryptfs/read_write.c (ffffffff8164584b)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
```
```
In fs/ecryptfs/crypto.c (ffffffff81646df4)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/ecryptfs/kthread.c (ffffffff8164cd77)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In fs/ecryptfs/miscdev.c (ffffffff8164e428)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/fuse/dev.c (ffffffff81655bd8)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/dir.c (ffffffff81659a10)
Location: include/linux/kernel.h:109
Inline: True
```
```
In fs/fuse/file.c (ffffffff8165d1c6)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_launder_folio
  - fs/fuse/file.c:fuse_launder_folio
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/inode.c (ffffffff81662f3a)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In fs/fuse/dax.c (ffffffff81669495)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
```
```
In security/keys/gc.c (ffffffff8168658e)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/process_keys.c (ffffffff8168e185)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff8168f507)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/selinux/hooks.c (ffffffff816b263f)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_remove_acl
  - security/selinux/hooks.c:selinux_inode_get_acl
  - security/selinux/hooks.c:selinux_inode_set_acl
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
```
```
In security/tomoyo/common.c (ffffffff816e62bf)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_supervisor
```
```
In security/apparmor/apparmorfs.c (ffffffff816f3dc8)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/domain.c (ffffffff816ffc68)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/lsm.c (ffffffff81714478)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - security/apparmor/lsm.c:aa_get_buffer
  - security/apparmor/lsm.c:begin_current_label_crit_section
```
```
In security/apparmor/net.c (ffffffff8171ff2e)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff817211d6)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/landlock/object.c (ffffffff81729e35)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - security/landlock/object.c:landlock_put_object
```
```
In security/landlock/ruleset.c (ffffffff8172a6db)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:free_ruleset
  - security/landlock/ruleset.c:free_ruleset
  - security/landlock/ruleset.c:inherit_ruleset
  - security/landlock/ruleset.c:insert_rule
  - security/landlock/ruleset.c:insert_rule
```
```
In security/landlock/fs.c (ffffffff8172b024)
Location: include/linux/kernel.h:109
Inline: True
```
```
In crypto/skcipher.c (ffffffff81743c8c)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/jitterentropy-testing.c (ffffffff8175e480)
Location: include/linux/kernel.h:109
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff81763bd5)
Location: include/linux/kernel.h:109
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81763ec8)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
```
```
In block/blk-core.c (ffffffff81771db1)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff81786c42)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_destroy_queue
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/genhd.c (ffffffff8178ea65)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/genhd.c:del_gendisk
```
```
In block/partitions/core.c (ffffffff817908ea)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
```
```
In block/blk-cgroup.c (ffffffff817a24d5)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In block/blk-crypto-profile.c (ffffffff817c3cfb)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/io_uring.c (ffffffff817cd5e3)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
```
```
In io_uring/rw.c (ffffffff817e5ac6)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
```
```
In lib/scatterlist.c (ffffffff8180db52)
Location: include/linux/kernel.h:109
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff8181826d)
Location: include/linux/kernel.h:109
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff818ff0b5)
Location: include/linux/kernel.h:109
Inline: True
```
```
In drivers/pwm/core.c (ffffffff81912905)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_apply_state
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81914bb1)
Location: include/linux/kernel.h:109
Inline: True
```
```
In drivers/pci/access.c (ffffffff81916055)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/access.c:pci_wait_cfg
```
```
In drivers/pci/pci.c (ffffffff81924be5)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_init_reset_methods
  - drivers/pci/pci.c:__pci_reset_function_locked
```
```
In drivers/pci/pcie/dpc.c (ffffffff8194261b)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81952ef7)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819534eb)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81958606)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/iov.c (ffffffff8195e3b5)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
```
```
In drivers/pci/doe.c (ffffffff81963e3e)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/pci/doe.c:pci_doe_init
  - drivers/pci/doe.c:pci_doe_create_mb
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81982637)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/osl.c (ffffffff82148281)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/ec.c (ffffffff819ad632)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a2a63a)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/acpi/acpi_dbg.c (ffffffff81a2b014)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
```
In drivers/dma/dmaengine.c (ffffffff81a4ddcf)
Location: include/linux/kernel.h:109
Inline: True
```
```
In drivers/virtio/virtio.c (ffffffff81a54595)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5f302)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_oom_notify
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
```
```
In drivers/xen/balloon.c (ffffffff81a64c07)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81a70206)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a707d7)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a74a76)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81a76a1b)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
```
```
In drivers/tty/tty_ioctl.c (ffffffff81a9ce43)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
```
```
In drivers/tty/tty_ldsem.c (ffffffff82158c65)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81aa71b3)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
```
```
In drivers/tty/vt/vt.c (ffffffff81ab6c96)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_blank_screen
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81abace6)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_write
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abe6e9)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81acdcc0)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/char/random.c (ffffffff81ae07e2)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/char/random.c:wait_for_random_bytes
```
```
In drivers/char/virtio_console.c (ffffffff81ae541e)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81af92c7)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/kernel.h:109
Inline: True
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b13175)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/kernel.h:109
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81b1dfdd)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/iommu.c:iommu_create_device_direct_mappings
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b29872)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/dd.c (ffffffff81b37f68)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/base/dd.c:wait_for_device_probe
```
```
In drivers/base/power/runtime.c (ffffffff81b4f738)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
```
```
In drivers/base/power/main.c (ffffffff81b5540f)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
```
```
In drivers/base/power/clock_ops.c (ffffffff81b5d19e)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_op_lock
```
```
In drivers/base/memory.c (ffffffff81b64d9d)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register
```
```
In drivers/base/regmap/regmap.c (ffffffff81b6986d)
Location: include/linux/kernel.h:109
Inline: True
```
```
In drivers/block/loop.c (ffffffff81b7c297)
Location: include/linux/kernel.h:109
Inline: True
```
```
In drivers/block/virtio_blk.c (ffffffff81b80c7a)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:cache_type_store
  - drivers/block/virtio_blk.c:virtblk_get_cache_mode
  - drivers/block/virtio_blk.c:init_vq
  - drivers/block/virtio_blk.c:virtblk_config_changed_work
  - drivers/block/virtio_blk.c:virtblk_update_capacity
  - drivers/block/virtio_blk.c:virtblk_update_capacity
  - drivers/block/virtio_blk.c:virtblk_getgeo
  - drivers/block/virtio_blk.c:virtblk_getgeo
  - drivers/block/virtio_blk.c:virtblk_getgeo
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
```
```
In drivers/misc/sram.c (ffffffff81b8818f)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/nvdimm/bus.c (ffffffff81ba4574)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/nvdimm/claim.c (ffffffff81bb3875)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In drivers/dax/super.c (ffffffff81bb90a2)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_add_host
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81bbc975)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment_unlocked
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81bbfe32)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
```
```
In drivers/dma-buf/dma-heap.c (ffffffff81bc3284)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/dma-buf/dma-heap.c:dma_heap_add
```
```
In drivers/scsi/scsi_error.c (ffffffff81bcca70)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81bda665)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81be33be)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_init
  - drivers/scsi/virtio_scsi.c:virtscsi_init
```
```
In drivers/scsi/sg.c (ffffffff81bf4ecf)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
```
```
In drivers/spi/spi.c (ffffffff81c2c695)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_delay_exec
```
```
In drivers/spi/spi-mem.c (ffffffff81c30cd7)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
```
```
In drivers/net/phy/phy_device.c (ffffffff81c396b5)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
```
```
In drivers/net/phy/bcm84881.c (ffffffff81c4159d)
Location: include/linux/kernel.h:109
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81c51e20)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_set_mac_address
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:109
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c687b2)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_write
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
```
```
In drivers/net/xen-netfront.c (ffffffff81c68c7f)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
```
```
In drivers/usb/core/hcd.c (ffffffff81c87cf5)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/urb.c (ffffffff81c886a1)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/devio.c (ffffffff81c9ae67)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd578a)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
```
```
In drivers/usb/host/xhci.c (ffffffff81ce2fcd)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
```
```
In drivers/input/serio/libps2.c (ffffffff81d0b9a3)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/mousedev.c (ffffffff81d14d48)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_read
```
```
In drivers/input/evdev.c (ffffffff81d167c3)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_read
```
```
In drivers/input/misc/uinput.c (ffffffff81d1e695)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81d35207)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d36c19)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/pps/pps.c (ffffffff81d38054)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81d3b0ff)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81d3d0f0)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81d3df75)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81d5c77a)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
```
```
In drivers/md/md-bitmap.c (ffffffff81d714b7)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm-zone.c (ffffffff81d7328f)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/md/dm.c (ffffffff81d7a3e7)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_destroy
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d84504)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
```
```
In drivers/opp/core.c (ffffffff81d92dcd)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_config
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d97d33)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
```
```
In drivers/mmc/core/core.c (ffffffff81db1220)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In net/core/sock.c (ffffffff81e0b845)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock_fast
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
  - net/core/sock.c:sock_bindtoindex
```
```
In net/core/skbuff.c (ffffffff81e16d6c)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff81e1f5d3)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff81e38751)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:dev_remove_pack
```
```
In net/core/filter.c (0)
Location: include/linux/kernel.h:109
Inline: True
```
```
In net/core/netpoll.c (ffffffff81e85155)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
```
```
In net/core/selftests.c (0)
Location: include/linux/kernel.h:109
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81eb66e0)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_init_ex
```
```
In net/netlink/af_netlink.c (ffffffff83734347)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/netlink/genetlink.c (ffffffff81ecc3b3)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/kernel.h:109
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/kernel.h:109
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81f23b01)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_cong.c (ffffffff81f34855)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
```
```
In net/ipv4/arp.c (0)
Location: include/linux/kernel.h:109
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/kernel.h:109
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/kernel.h:109
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/kernel.h:109
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/kernel.h:109
Inline: True
```
```
In net/unix/garbage.c (ffffffff81fb0831)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - net/unix/garbage.c:wait_for_unix_gc
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/kernel.h:109
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/kernel.h:109
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/kernel.h:109
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:109
Inline: True
```
```
In net/devlink/leftover.c (ffffffff82032f76)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_region_snapshot_id_get
  - net/devlink/leftover.c:devl_params_register
  - net/devlink/leftover.c:devl_port_register_with_ops
  - net/devlink/leftover.c:devlink_nl_cmd_region_new
```
```
In net/devlink/core.c (ffffffff82041f6d)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_alloc_ns
```
```
In net/strparser/strparser.c (0)
Location: include/linux/kernel.h:109
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/kernel.h:109
Inline: True
```
```
In net/wireless/wext-proc.c (ffffffff8204c025)
Location: include/linux/kernel.h:109
Inline: True
```
```
In net/rfkill/core.c (ffffffff82055ea1)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_read
```
```
In net/mptcp/protocol.c (ffffffff82070d12)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:mptcp_worker
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff820cab05)
Location: include/linux/kernel.h:109
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81098722)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109afa0)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109cdd4)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109ecd3)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810df7f2)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810ee446)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
```
```
In kernel/fork.c (ffffffff810fc2d4)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/fork.c:mm_access
```
```
In kernel/cpu.c (ffffffff81102605)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
```
In kernel/softirq.c (ffffffff81108a14)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_unlock_wait
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/ptrace.c (ffffffff811111c7)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/signal.c (ffffffff8111ace5)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
```
```
In kernel/umh.c (ffffffff81125735)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/workqueue.c (ffffffff81129e9f)
Location: include/linux/kernel.h:105
Inline: True
```
```
In kernel/kthread.c (ffffffff811352b6)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/nsproxy.c (ffffffff8113ce86)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/nsproxy.c:exec_task_namespaces
  - kernel/nsproxy.c:exit_task_namespaces
```
```
In kernel/async.c (ffffffff811411e1)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
```
```
In kernel/sched/core.c (ffffffff8115a888)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/build_utility.c (ffffffff8118ebdc)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_rtpoll_worker
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
  - kernel/sched/build_utility.c:wait_for_completion_io_timeout
  - kernel/sched/build_utility.c:wait_for_completion_io
  - kernel/sched/build_utility.c:wait_for_completion_timeout
  - kernel/sched/build_utility.c:wait_for_completion
```
```
In kernel/locking/mutex.c (ffffffff8119c51e)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
```
```
In kernel/locking/semaphore.c (ffffffff822379f5)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:down_timeout
  - kernel/locking/semaphore.c:down_killable
  - kernel/locking/semaphore.c:down_interruptible
  - kernel/locking/semaphore.c:down
```
```
In kernel/locking/rwsem.c (ffffffff82238805)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
```
```
In kernel/locking/percpu-rwsem.c (ffffffff822389e5)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
```
```
In kernel/locking/rtmutex_api.c (ffffffff8223a56f)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_killable
  - kernel/locking/rtmutex_api.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex_api.c:rt_mutex_lock
```
```
In kernel/power/swap.c (ffffffff811a9a55)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
```
```
In kernel/printk/printk.c (ffffffff811b2ccf)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/irq/manage.c (ffffffff811b7768)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/irq/manage.c:wake_up_and_wait_for_irq_thread_ready
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/irq/chip.c (ffffffff811bc636)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/irq/msi.c (ffffffff811c62a7)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_insert_desc
  - kernel/irq/msi.c:msi_insert_desc
```
```
In kernel/rcu/update.c (ffffffff811cb1cb)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/sync.c (ffffffff811ce8d6)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/rcu/sync.c:rcu_sync_enter
```
```
In kernel/rcu/srcutree.c (ffffffff811d0ae3)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__synchronize_srcu
```
```
In kernel/rcu/tree.c (ffffffff811daa7f)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:synchronize_rcu
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/module/main.c (ffffffff811f2e78)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/module/main.c:simplify_symbols
```
```
In kernel/freezer.c (ffffffff811fb1d5)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
```
```
In kernel/futex/core.c (ffffffff8121ef0a)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/cgroup/cgroup.c (ffffffff8123db83)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In kernel/cgroup/rstat.c (ffffffff8123f3a0)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
```
```
In kernel/cgroup/cpuset.c (ffffffff8124d365)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
```
```
In kernel/audit.c (ffffffff812551aa)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In kernel/trace/trace_events_user.c (ffffffff812e3c00)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_mm_remove
```
```
In kernel/irq_work.c (ffffffff81302df0)
Location: include/linux/kernel.h:105
Inline: True
```
```
In kernel/events/core.c (ffffffff813a47f8)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a6f33)
Location: include/linux/kernel.h:105
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813ac8eb)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff813b7ffe)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/mempool.c (ffffffff813bd09c)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
```
```
In mm/oom_kill.c (ffffffff813c1677)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/page-writeback.c (ffffffff813c2d5f)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff813cd3ba)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813e205b)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff813ea85c)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_get_partial_folio
  - mm/shmem.c:shmem_inode_unacct_blocks
  - mm/shmem.c:shmem_inode_acct_blocks
```
```
In mm/backing-dev.c (ffffffff813f61e4)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/compaction.c (ffffffff81406de8)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/gup.c (ffffffff8140d852)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/memory.c (ffffffff81421750)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mmap.c (ffffffff81426a35)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/mmap.c:remove_vma
```
```
In mm/mprotect.c (ffffffff8142f9c3)
Location: include/linux/kernel.h:105
Inline: True
```
```
In mm/mremap.c (ffffffff81431815)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8143b582)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/vmalloc.c (ffffffff81444329)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:delayed_vfree_work
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/page_alloc.c (ffffffff8144e6e2)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/memory_hotplug.c (ffffffff81451f55)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In mm/slub.c (ffffffff8145e83f)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmalloc_node_trace
  - mm/slub.c:kmalloc_trace
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/madvise.c (ffffffff81460760)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff814693f4)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/dmapool.c (ffffffff81471add)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In mm/hugetlb.c (ffffffff8147b232)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mmu_notifier.c (ffffffff81489483)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
```
```
In mm/ksm.c (ffffffff8148cbce)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff814997c4)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:writeout
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:putback_movable_pages
```
```
In mm/migrate_device.c (ffffffff8149eff1)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_setup
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff814a7a69)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff814ab874)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memory-failure.c (ffffffff814c63fd)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:try_to_split_thp_page
```
```
In mm/userfaultfd.c (ffffffff814d2e2d)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
```
```
In mm/memremap.c (ffffffff814d4ee1)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d73e8)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/open.c (ffffffff814da148)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff814e214a)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:vfs_write
```
```
In fs/file_table.c (ffffffff814e28bb)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/super.c (ffffffff814e4fdc)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/super.c:grab_super
  - fs/super.c:super_lock
```
```
In fs/exec.c (ffffffff814ec355)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/pipe.c (ffffffff814f06bd)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/dcache.c (ffffffff815066ea)
Location: include/linux/kernel.h:105
Inline: True
```
```
In fs/inode.c (ffffffff8150bd5a)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In fs/file.c (ffffffff8150e4e2)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
```
In fs/namespace.c (ffffffff81512f13)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/libfs.c (ffffffff8152369c)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/libfs.c:simple_offset_add
```
```
In fs/fs-writeback.c (ffffffff8152b7c2)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
```
In fs/splice.c (ffffffff8153213a)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff8153c82a)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/buffer.c (ffffffff8153f60c)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__bh_read
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/notify/fsnotify.c (ffffffff815475d3)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/notify/group.c (ffffffff81548247)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154c89e)
Location: include/linux/kernel.h:105
Inline: True
```
```
In fs/aio.c (ffffffff8155d5be)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/locks.c (ffffffff8157ad2f)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:locks_lock_inode_wait
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
```
In fs/backing-file.c (ffffffff81581b31)
Location: include/linux/kernel.h:105
Inline: True
```
```
In fs/mbcache.c (ffffffff81581f44)
Location: include/linux/kernel.h:105
Inline: True
```
```
In fs/coredump.c (ffffffff81586ebc)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8158ab8b)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/quota/dquot.c (ffffffff81593099)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/quota/quota.c (ffffffff81597039)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/quota/quota.c:quotactl_block
```
```
In fs/proc/task_mmu.c (ffffffff8159bdf2)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:do_pagemap_scan
  - fs/proc/task_mmu.c:do_pagemap_scan
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/proc_sysctl.c (ffffffff815b31f5)
Location: include/linux/kernel.h:105
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff815ba8b7)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_drain
```
```
In fs/ext4/balloc.c (ffffffff815c7e15)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff815cbe85)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
```
```
In fs/ext4/extents.c (ffffffff815cd8d7)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff815da5fe)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/ialloc.c (ffffffff815df074)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815e1e77)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff815e5825)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff815f5384)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff815f8371)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_getuuid
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff816053e8)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/mmp.c (ffffffff816073b8)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block_thawed
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/namei.c (ffffffff8160cc2d)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/resize.c (ffffffff8161533a)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff816346e7)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_read_bh
```
```
In fs/ext4/xattr.c (ffffffff81643865)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:check_xattrs
```
```
In fs/ext4/fast_commit.c (ffffffff816449e6)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff8164926f)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/crypto.c (ffffffff8164bdab)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
```
```
In fs/jbd2/transaction.c (ffffffff8164f1e7)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffffffff8165013e)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff8165267c)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/checkpoint.c (ffffffff81653457)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/revoke.c (ffffffff81654065)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
```
In fs/jbd2/journal.c (ffffffff81659a21)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/squashfs/cache.c (ffffffff8165ddbb)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
```
```
In fs/squashfs/decompressor_multi.c (ffffffff81664094)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi.c:squashfs_decompress
```
```
In fs/hugetlbfs/inode.c (ffffffff816680a8)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff8166d87e)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8166f1ba)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/fat/misc.c (ffffffff8167659d)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e282)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/ecryptfs/kthread.c (ffffffff816862a7)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In fs/ecryptfs/miscdev.c (ffffffff81687988)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/fuse/dev.c (ffffffff8168f338)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/dir.c (ffffffff81693680)
Location: include/linux/kernel.h:105
Inline: True
```
```
In fs/fuse/file.c (ffffffff81696f26)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_launder_folio
  - fs/fuse/file.c:fuse_launder_folio
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/inode.c (ffffffff8169caa9)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In fs/fuse/dax.c (ffffffff816a3795)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:fuse_setup_new_dax_mapping
```
```
In security/keys/gc.c (ffffffff816c29fe)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/process_keys.c (ffffffff816ca6d5)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff816cba97)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/selinux/hooks.c (ffffffff816efc7f)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_remove_acl
  - security/selinux/hooks.c:selinux_inode_get_acl
  - security/selinux/hooks.c:selinux_inode_set_acl
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
```
```
In security/tomoyo/common.c (ffffffff81722f6f)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_supervisor
```
```
In security/apparmor/apparmorfs.c (ffffffff81730b58)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/domain.c (ffffffff8173d244)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/lsm.c (ffffffff81752ee4)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - security/apparmor/lsm.c:aa_get_buffer
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_inode_create
```
```
In security/apparmor/net.c (ffffffff8175e961)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8175fcf9)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/apparmor/af_inet.c (ffffffff81762399)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - security/apparmor/af_inet.c:begin_current_label_crit_section
```
```
In security/landlock/object.c (ffffffff8176b1a5)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - security/landlock/object.c:landlock_put_object
```
```
In security/landlock/ruleset.c (ffffffff8176bd65)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:free_ruleset
  - security/landlock/ruleset.c:free_ruleset
  - security/landlock/ruleset.c:free_ruleset
  - security/landlock/ruleset.c:inherit_ruleset
  - security/landlock/ruleset.c:inherit_tree
  - security/landlock/ruleset.c:merge_tree
  - security/landlock/ruleset.c:insert_rule
  - security/landlock/ruleset.c:insert_rule
```
```
In security/landlock/fs.c (ffffffff8176cb44)
Location: include/linux/kernel.h:105
Inline: True
```
```
In crypto/skcipher.c (ffffffff8178602b)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff817a57f5)
Location: include/linux/kernel.h:105
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff817a5ae8)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
```
```
In block/bio.c (ffffffff817abafb)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:__bio_release_pages
```
```
In block/blk-core.c (ffffffff817b40f1)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff817c931f)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_destroy_queue
  - block/blk-mq.c:blk_mq_init_hctx
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
```
```
In block/genhd.c (ffffffff817d1354)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/genhd.c:del_gendisk
```
```
In block/partitions/core.c (ffffffff817d4154)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
```
```
In block/blk-cgroup.c (ffffffff817e6015)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In block/blk-crypto-profile.c (ffffffff8180898b)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/rw.c (ffffffff81829d80)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
```
```
In io_uring/register.c (ffffffff8182bbb0)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - io_uring/register.c:__io_uring_register
```
```
In lib/scatterlist.c (ffffffff81853802)
Location: include/linux/kernel.h:105
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff8185d56d)
Location: include/linux/kernel.h:105
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff81949119)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_find
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpio_device_find_by_fwnode
```
```
In drivers/pwm/core.c (ffffffff8195a814)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8195cb21)
Location: include/linux/kernel.h:105
Inline: True
```
```
In drivers/pci/access.c (ffffffff8195dfc5)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/access.c:pci_wait_cfg
```
```
In drivers/pci/pci.c (ffffffff8196d2b5)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_init_reset_methods
  - drivers/pci/pci.c:__pci_reset_function_locked
```
```
In drivers/pci/pcie/dpc.c (ffffffff8198b8ab)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8199c387)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199c97b)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff819a1b76)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/iov.c (ffffffff819a7a15)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
```
```
In drivers/pci/doe.c (ffffffff819ad4ee)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/pci/doe.c:pci_doe_init
  - drivers/pci/doe.c:pci_doe_create_mb
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b4b14)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_suspend_noirq
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c9db7)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/osl.c (ffffffff8222ac10)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/ec.c (ffffffff819f7ab2)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a7580a)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/acpi/acpi_dbg.c (ffffffff81a761e4)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
```
In drivers/dma/dmaengine.c (ffffffff81a99a6f)
Location: include/linux/kernel.h:105
Inline: True
```
```
In drivers/virtio/virtio.c (ffffffff81aa5235)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab2712)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_oom_notify
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
```
```
In drivers/xen/balloon.c (ffffffff81ab7467)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81ac2306)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81ac28d7)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81ac6bd6)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81ac8c0b)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
```
```
In drivers/tty/tty_ioctl.c (ffffffff81aef913)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
```
```
In drivers/tty/tty_ldsem.c (ffffffff8223c4e5)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81af9c43)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
```
```
In drivers/tty/vt/vt.c (ffffffff81b09996)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_blank_screen
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0da56)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:hvc_write
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b11469)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81b20d90)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/char/random.c (ffffffff81b33be2)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/char/random.c:wait_for_random_bytes
```
```
In drivers/char/virtio_console.c (ffffffff81b38817)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4c8e7)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/kernel.h:105
Inline: True
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b67d75)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/svm.c (0)
Location: include/linux/kernel.h:105
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81b73f8a)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/iommu.c:iommu_map
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b80862)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/dd.c (ffffffff81b8fa08)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/base/dd.c:wait_for_device_probe
```
```
In drivers/base/power/runtime.c (ffffffff81ba7cb8)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
```
```
In drivers/base/power/main.c (ffffffff81bad9cf)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
```
```
In drivers/base/power/clock_ops.c (ffffffff81bb0a4e)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_op_lock
```
```
In drivers/base/memory.c (ffffffff81bb8afc)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbd52d)
Location: include/linux/kernel.h:105
Inline: True
```
```
In drivers/block/virtio_blk.c (ffffffff81bd4ad9)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:cache_type_store
  - drivers/block/virtio_blk.c:virtblk_get_cache_mode
  - drivers/block/virtio_blk.c:init_vq
  - drivers/block/virtio_blk.c:virtblk_update_capacity
  - drivers/block/virtio_blk.c:virtblk_update_capacity
  - drivers/block/virtio_blk.c:virtblk_getgeo
  - drivers/block/virtio_blk.c:virtblk_getgeo
  - drivers/block/virtio_blk.c:virtblk_getgeo
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
```
```
In drivers/misc/sram.c (ffffffff81bdc03f)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/nvdimm/bus.c (ffffffff81bf8794)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/nvdimm/claim.c (ffffffff81c07dc5)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In drivers/dax/super.c (ffffffff81c0d702)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_add_host
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81c110c5)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment_unlocked
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c145b2)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
```
```
In drivers/dma-buf/dma-heap.c (ffffffff81c17a23)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/dma-buf/dma-heap.c:dma_heap_add
```
```
In drivers/scsi/scsi_error.c (ffffffff81c216a0)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81c2f395)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81c3881e)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_init
  - drivers/scsi/virtio_scsi.c:virtscsi_init
```
```
In drivers/scsi/sg.c (ffffffff81c4a80f)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c96b19)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_read
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb0bfe)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb6ebc)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_wait_vblank_ioctl
  - drivers/gpu/drm/drm_vblank.c:drm_wait_one_vblank
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc1767)
Location: include/linux/kernel.h:105
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81cdefb5)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_delay_exec
```
```
In drivers/spi/spi-mem.c (ffffffff81ce3b67)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
```
```
In drivers/net/phy/phy_device.c (ffffffff81ceea45)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
```
```
In drivers/net/phy/bcm84881.c (ffffffff81cf6c2d)
Location: include/linux/kernel.h:105
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81d080a0)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_set_mac_address
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/linux/kernel.h:105
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81d1d6af)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
```
```
In drivers/usb/core/hcd.c (ffffffff81d3c745)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/urb.c (ffffffff81d3d0f1)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/devio.c (ffffffff81d4fa28)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8a76a)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
```
```
In drivers/usb/host/xhci.c (ffffffff81d9811f)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
```
```
In drivers/input/serio/libps2.c (ffffffff81dc1633)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/mousedev.c (ffffffff81dca968)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_read
```
```
In drivers/input/evdev.c (ffffffff81dcc443)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_read
```
```
In drivers/input/misc/uinput.c (ffffffff81dd4395)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81deb397)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81dec9d9)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/pps/pps.c (ffffffff81dee2d4)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81df1a58)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81df3a40)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81df48c5)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_put
```
```
In drivers/md/md.c (ffffffff81e13dca)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:stop_sync_thread
  - drivers/md/md.c:md_super_wait
  - drivers/md/md.c:mddev_suspend
  - drivers/md/md.c:mddev_suspend
```
```
In drivers/md/md-bitmap.c (ffffffff81e28567)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:write_file_page
```
```
In drivers/md/dm-zone.c (ffffffff81e2a3d2)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/md/dm.c (ffffffff81e31587)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_destroy
```
```
In drivers/md/dm-kcopyd.c (ffffffff81e3bcc4)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
```
```
In drivers/opp/core.c (ffffffff81e4a747)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_config
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e4f9b3)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
```
```
In drivers/mmc/core/core.c (ffffffff81e695b0)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81e93815)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
```
```
In drivers/dpll/dpll_core.c (ffffffff81eb6bd6)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - drivers/dpll/dpll_core.c:dpll_pin_get
  - drivers/dpll/dpll_core.c:dpll_device_get
  - drivers/dpll/dpll_core.c:dpll_xa_ref_dpll_add
  - drivers/dpll/dpll_core.c:dpll_xa_ref_pin_add
```
```
In net/core/sock.c (ffffffff81ec8235)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock_fast
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
  - net/core/sock.c:sock_bindtoindex
```
```
In net/core/skbuff.c (ffffffff81ed417c)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/datagram.c (ffffffff81edcc83)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff81ef6865)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:dev_remove_pack
```
```
In net/core/filter.c (0)
Location: include/linux/kernel.h:105
Inline: True
```
```
In net/core/page_pool_user.c (ffffffff81f460cb)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_list
```
```
In net/core/netpoll.c (ffffffff81f47145)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
```
```
In net/core/selftests.c (0)
Location: include/linux/kernel.h:105
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81f794fe)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_init_ex
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/netlink/af_netlink.c (ffffffff839688e5)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/netlink/genetlink.c (ffffffff81f8f8df)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
  - net/netlink/genetlink.c:genl_sk_priv_get
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/kernel.h:105
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/kernel.h:105
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81fe826a)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_cong.c (ffffffff81ffa9d5)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
```
```
In net/ipv4/arp.c (0)
Location: include/linux/kernel.h:105
Inline: True
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/linux/kernel.h:105
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/kernel.h:105
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/kernel.h:105
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/kernel.h:105
Inline: True
```
```
In net/unix/garbage.c (ffffffff8207dec1)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - net/unix/garbage.c:wait_for_unix_gc
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/kernel.h:105
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/linux/kernel.h:105
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/kernel.h:105
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:105
Inline: True
```
```
In net/devlink/core.c (ffffffff820fea8d)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_alloc_ns
  - net/devlink/core.c:devlink_rel_nested_in_add
```
```
In net/devlink/dev.c (ffffffff821021a7)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - net/devlink/dev.c:devl_nested_devlink_set
```
```
In net/devlink/port.c (ffffffff82107238)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - net/devlink/port.c:devl_port_register_with_ops
```
```
In net/devlink/param.c (ffffffff8210eb63)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - net/devlink/param.c:devl_params_register
```
```
In net/devlink/region.c (ffffffff8210f566)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_region_snapshot_id_get
  - net/devlink/region.c:devlink_nl_region_new_doit
```
```
In net/strparser/strparser.c (0)
Location: include/linux/kernel.h:105
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/linux/kernel.h:105
Inline: True
```
```
In net/wireless/wext-proc.c (ffffffff8211e4b5)
Location: include/linux/kernel.h:105
Inline: True
```
```
In net/rfkill/core.c (ffffffff82128721)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_read
```
```
In net/mptcp/protocol.c (ffffffff82145252)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:mptcp_worker
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff821a5345)
Location: include/linux/kernel.h:105
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
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
