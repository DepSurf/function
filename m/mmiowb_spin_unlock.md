# Function: <code>mmiowb_spin_unlock</code>

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
In init/main.c (c0000000013444f4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In arch/powerpc/kernel/pmc.c (c00000000001ff4c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/kernel/pmc.c:release_pmc_hardware
  - arch/powerpc/kernel/pmc.c:reserve_pmc_hardware
```
```
In arch/powerpc/kernel/rtas.c (c00000000003df7c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In arch/powerpc/kernel/eeh_cache.c (c000000000048160)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh_cache.c:eeh_addr_cache_show
```
```
In arch/powerpc/kernel/iommu.c (c0000000000517f0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/kernel/iommu.c:iommu_release_ownership
  - arch/powerpc/kernel/iommu.c:iommu_take_ownership
  - arch/powerpc/kernel/iommu.c:iommu_range_alloc
  - arch/powerpc/kernel/iommu.c:iommu_range_alloc
```
```
In arch/powerpc/kernel/pci-common.c (c00000000006d204)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-common.c:pci_address_to_pio
  - arch/powerpc/kernel/pci-common.c:pcibios_vaddr_is_ioport
  - arch/powerpc/kernel/pci-common.c:pcibios_free_controller
  - arch/powerpc/kernel/pci-common.c:pcibios_alloc_controller
```
```
In arch/powerpc/kernel/crash.c (c000000000070a9c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/kernel/crash.c:crash_shutdown_unregister
  - arch/powerpc/kernel/crash.c:crash_shutdown_register
```
```
In arch/powerpc/mm/pgtable-frag.c (c00000000008918c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable-frag.c:pte_fragment_alloc
  - arch/powerpc/mm/pgtable-frag.c:pte_fragment_alloc
```
```
In arch/powerpc/mm/book3s64/pgtable.c (c000000000090f80)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/pgtable.c:pmd_fragment_alloc
  - arch/powerpc/mm/book3s64/pgtable.c:pmd_fragment_alloc
```
```
In arch/powerpc/mm/book3s64/hash_native.c (c000000000092a44)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_native.c:native_flush_hash_range
  - arch/powerpc/mm/book3s64/hash_native.c:native_hugepage_invalidate
```
```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000eec014)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable
  - arch/powerpc/mm/book3s64/radix_pgtable.c:stop_machine_change_mapping
```
```
In arch/powerpc/mm/book3s64/subpage_prot.c (c00000000009f9f4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:hpte_flush_range
```
```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a62d8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:follow_huge_pd
  - arch/powerpc/mm/hugetlbpage.c:follow_huge_pd
  - arch/powerpc/mm/hugetlbpage.c:huge_pte_alloc
```
```
In arch/powerpc/sysdev/msi_bitmap.c (c0000000000b7c9c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/sysdev/msi_bitmap.c:msi_bitmap_reserve_dt_hwirqs
```
```
In arch/powerpc/sysdev/i8259.c (c0000000000b94e0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/sysdev/i8259.c:i8259_irq
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000be03c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In arch/powerpc/platforms/pseries/lpar.c (c000000001361920)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lpar.c:pseries_lpar_read_hblkrm_characteristics
```
```
In arch/powerpc/platforms/pseries/setup.c (c0000000000eec9c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/setup.c:pSeries_cmo_feature_init
  - arch/powerpc/platforms/pseries/setup.c:pSeries_cmo_feature_init
```
```
In arch/powerpc/platforms/pseries/iommu.c (c0000000000effa8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/iommu.c:iommu_mem_notifier
  - arch/powerpc/platforms/pseries/iommu.c:enable_ddw
  - arch/powerpc/platforms/pseries/iommu.c:enable_ddw
  - arch/powerpc/platforms/pseries/iommu.c:__machine_initcall_pseries_find_existing_ddw_windows
```
```
In arch/powerpc/platforms/pseries/ras.c (c0000000000f204c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/ras.c:ras_error_interrupt
  - arch/powerpc/platforms/pseries/ras.c:ras_epow_interrupt
  - arch/powerpc/platforms/pseries/ras.c:ras_hotplug_interrupt
```
```
In arch/powerpc/platforms/pseries/dlpar.c (c0000000000f3338)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_configure_connector
```
```
In arch/powerpc/platforms/pseries/mobility.c (c0000000000f4154)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/mobility.c:mobility_rtas_call
```
```
In arch/powerpc/platforms/pseries/pci.c (c0000000000f4db8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/pci.c:pseries_send_map_pe
```
```
In arch/powerpc/platforms/pseries/eeh_pseries.c (c0000000000f6ce0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_send_allow_unfreeze
```
```
In arch/powerpc/platforms/pseries/dtl.c (c0000000000fd1c0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/dtl.c:dtl_file_read
  - arch/powerpc/platforms/pseries/dtl.c:dtl_file_release
  - arch/powerpc/platforms/pseries/dtl.c:dtl_file_open
```
```
In arch/powerpc/platforms/pseries/lparcfg.c (c0000000000fde9c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lparcfg.c:parse_system_parameter_string
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c0000000001201ac)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_rm_h_page_init
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_rm_h_page_init
```
```
In kernel/fork.c (c00000000013bb64)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/panic.c (c00000000013c060)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In kernel/cpu.c (c0000000001407a0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (c000000000142a40)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (c000000000147cfc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In kernel/ptrace.c (c000000000150b1c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/user.c (c0000000001514c4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
```
```
In kernel/signal.c (c00000000015b728)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:__set_current_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_notify
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
```
```
In kernel/sys.c (c00000000015f538)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__se_compat_sys_old_getrlimit
  - kernel/sys.c:__se_sys_old_getrlimit
```
```
In kernel/umh.c (c000000000162824)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In kernel/workqueue.c (c00000000016ca2c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:drain_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/pid.c (c00000000016e7b4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/pid.c:disable_pid_allocation
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
```
```
In kernel/task_work.c (c00000000016ed60)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_run
```
```
In kernel/params.c (c0000000001707a4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/params.c:param_set_charp
  - kernel/params.c:maybe_kfree_parameter
```
```
In kernel/kthread.c (c000000000172144)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/nsproxy.c (c000000000174228)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/async.c (c000000000177dd4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/async.c:async_unregister_domain
```
```
In kernel/ucount.c (c00000000017983c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (c0000000001844b0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/idle.c (c00000000018eac0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sched/idle.c:dequeue_task_idle
```
```
In kernel/sched/fair.c (c00000000019fe68)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:rq_online_fair
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/sched/rt.c (c0000000001a142c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sched/rt.c:tg_set_rt_bandwidth
  - kernel/sched/rt.c:tg_set_rt_bandwidth
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (c0000000001abc88)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:init_dl_bw
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/sched/wait.c (c0000000001ad1a8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
```
```
In kernel/sched/swait.c (c0000000001adc10)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/sched/completion.c (c000000000ee40e4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/sched/completion.c:wait_for_completion
```
```
In kernel/sched/debug.c (c0000000001b9940)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/sched/cpufreq_schedutil.c (c0000000001bd000)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
```
In kernel/sched/psi.c (c0000000001bf8a4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
```
In kernel/locking/mutex.c (c000000000ee6c28)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
```
```
In kernel/locking/semaphore.c (c000000000ee6ef4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
```
```
In kernel/locking/rwsem.c (c0000000001c175c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/spinlock.c (c000000000eea02c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_spin_unlock_bh
```
```
In kernel/locking/rtmutex.c (c0000000001c4068)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/power/suspend.c (c0000000001c8fac)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/wakelock.c (c0000000001c9b58)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/power/wakelock.c:__wakelocks_gc
```
```
In kernel/printk/printk.c (c0000000001caa00)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/printk_safe.c (c0000000001d0a78)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
```
In kernel/irq/irqdesc.c (c0000000001d0d0c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:actions_show
  - kernel/irq/irqdesc.c:name_show
  - kernel/irq/irqdesc.c:wakeup_show
  - kernel/irq/irqdesc.c:type_show
  - kernel/irq/irqdesc.c:hwirq_show
  - kernel/irq/irqdesc.c:chip_name_show
```
```
In kernel/irq/handle.c (c0000000001d2928)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (c0000000001d4158)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/spurious.c (c0000000001d7614)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (c0000000001d96e8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/irq/generic-chip.c (c0000000001dc1b8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
```
```
In kernel/irq/cpuhotplug.c (c0000000001e0e00)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In kernel/rcu/sync.c (c0000000001e3a14)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_enter
```
```
In kernel/rcu/srcutree.c (c0000000001e5b90)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (c0000000001e8e44)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:rcu_iw_handler
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
```
In kernel/livepatch/transition.c (c0000000001f3200)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kcmp.c (c0000000001f7d1c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/freezer.c (c0000000001f8198)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/timer.c (c000000000201360)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:get_next_timer_interrupt
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:add_timer
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (c000000000203dec)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:retrigger_next_event
```
```
In kernel/time/timekeeping.c (c000000000207888)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/posix-timers.c (c000000000210918)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__se_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (c000000000212e5c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
```
```
In kernel/time/itimer.c (c000000000214768)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
```
```
In kernel/time/clockevents.c (c0000000002157fc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:sysfs_show_current_tick_dev
  - kernel/time/clockevents.c:tick_offline_cpu
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/time/tick-common.c (c0000000002176dc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-broadcast.c (c0000000002191cc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_update_freq
```
```
In kernel/time/tick-sched.c (c00000000021a3e8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/futex.c (c00000000022209c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:unqueue_me_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_state
  - kernel/futex.c:attach_to_pi_state
  - kernel/futex.c:put_pi_state
  - kernel/futex.c:put_pi_state
```
```
In kernel/acct.c (c000000000230840)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
  - kernel/acct.c:do_acct_process
```
```
In kernel/cgroup/cgroup.c (c000000000245a2c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:css_task_iter_start
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_task_count
```
```
In kernel/cgroup/rstat.c (c000000000247044)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/namespace.c (c000000000247198)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (c00000000024a210)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
```
In kernel/cgroup/freezer.c (c00000000024b0cc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
```
```
In kernel/cgroup/cpuset.c (c000000000255110)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/utsname.c (c0000000002554e4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (c000000000257bf8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/stop_machine.c (c000000000258d08)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/auditsc.c (c00000000026651c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_getname
```
```
In kernel/audit_tree.c (c00000000026984c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
```
```
In kernel/kprobes.c (c00000000026c808)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/debug/debug_core.c (c00000000027110c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_support.c (c000000000280554)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kmalloc
```
```
In kernel/seccomp.c (c0000000002879c0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/taskstats.c (c00000000028bd84)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/trace/ring_buffer.c (c00000000029b1f4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
```
```
In kernel/trace/blktrace.c (c0000000002c3cb4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_startstop
  - kernel/trace/blktrace.c:__blk_trace_startstop
```
```
In kernel/trace/trace_events.c (c0000000002c8ec0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:remove_event_file_dir
```
```
In kernel/bpf/syscall.c (c00000000030a310)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/bpf/percpu_freelist.c (c000000000325a18)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
```
In kernel/bpf/bpf_lru_list.c (c00000000032643c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/bpf/devmap.c (c000000000332258)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/cpumap.c (c000000000332c58)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (c00000000034d330)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:perf_event_addr_filters_sync
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:perf_ctx_unlock
  - kernel/events/core.c:perf_ctx_unlock
```
```
In kernel/events/uprobes.c (c00000000035bec8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:vma_has_uprobes
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:__uprobe_unregister
  - kernel/events/uprobes.c:find_uprobe
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (c00000000035ca18)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_find_next
  - kernel/padata.c:padata_find_next
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/filemap.c (c000000000366f84)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_check_and_advance_wb_err
```
```
In mm/oom_kill.c (c00000000036f960)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/fadvise.c (c0000000003713b4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
  - mm/fadvise.c:generic_fadvise
  - mm/fadvise.c:generic_fadvise
```
```
In mm/page-writeback.c (c0000000003734ec)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:domain_update_bandwidth
```
```
In mm/truncate.c (c00000000037e494)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_final
```
```
In mm/vmscan.c (c00000000038c4c0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (c00000000038d19c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_free_swap
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_free_inode
  - mm/shmem.c:shmem_reserve_inode
  - mm/shmem.c:shmem_reserve_inode
```
```
In mm/util.c (c000000000398d7c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/util.c:get_cmdline
```
```
In mm/vmstat.c (c000000000399e38)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showfree_print
```
```
In mm/backing-dev.c (c00000000039e8e4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_put
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In mm/mmu_context.c (c00000000039f8cc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/percpu.c (c0000000003a38e8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
```
```
In mm/slab_common.c (c0000000003a7868)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/list_lru.c (c0000000003b438c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (c0000000003b469c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/gup.c (c0000000003b80c8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003c69a0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/mincore.c (c0000000003c8400)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (c0000000003cab88)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_unlock
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:munlock_vma_page
```
```
In mm/mmap.c (c0000000003cf320)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/mprotect.c (c0000000003d225c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d37d8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In mm/page_vma_mapped.c (c0000000003d6234)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In mm/rmap.c (c0000000003da0a8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/vmalloc.c (c0000000003dd350)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/vmalloc.c:s_stop
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:free_vmap_block
  - mm/vmalloc.c:find_vmap_area
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/page_alloc.c (c0000000003ecf18)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/madvise.c (c0000000003f34f8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (c0000000003f6b9c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (c00000000040018c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:has_usable_swap
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:del_from_avail_list
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_discard_work
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
```
```
In mm/swap_slots.c (c000000000400980)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/swap_slots.c:free_swap_slot
  - mm/swap_slots.c:free_swap_slot
```
```
In mm/frontswap.c (c000000000401720)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_curr_pages
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_register_ops
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/zswap.c (c0000000004029fc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_invalidate_area
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_pool_put
```
```
In mm/dmapool.c (c000000000404518)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/dmapool.c:show_pools
```
```
In mm/hugetlb.c (c000000000410c48)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_chg
  - mm/hugetlb.c:region_chg
  - mm/hugetlb.c:region_chg
  - mm/hugetlb.c:region_chg
  - mm/hugetlb.c:region_add
  - mm/hugetlb.c:hugepage_put_subpool
```
```
In mm/mempolicy.c (c000000000416bec)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/mmu_notifier.c (c0000000004183b4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:__mmu_notifier_register
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (c00000000041c2a4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:run_store
  - mm/ksm.c:run_store
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/slub.c (c00000000042b258)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/memory_hotplug.c (c00000000042fbc4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/migrate.c (c000000000434958)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (c000000000442c00)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (c00000000044b228)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (c00000000045b5e0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:mem_cgroup_oom_unregister_event
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
```
```
In mm/vmpressure.c (c00000000045c44c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
  - mm/vmpressure.c:vmpressure
  - mm/vmpressure.c:vmpressure
  - mm/vmpressure.c:vmpressure_work_fn
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In mm/hugetlb_cgroup.c (c00000000045db60)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/zpool.c (c000000000464600)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_get_driver
  - mm/zpool.c:zpool_get_driver
  - mm/zpool.c:zpool_unregister_driver
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zbud.c (c00000000046528c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
  - mm/zbud.c:zbud_alloc
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (c000000000467d14)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/userfaultfd.c (c00000000046ba40)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (c00000000046c080)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (c00000000046fcd4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/memfd.c (c0000000004713c4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/read_write.c (c0000000004756dc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In fs/super.c (c00000000047f640)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/super.c:user_get_super
  - fs/super.c:user_get_super
  - fs/super.c:get_active_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:sget
  - fs/super.c:sget
  - fs/super.c:sget
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/super.c:sget_fc
  - fs/super.c:sget_fc
  - fs/super.c:sget_fc
  - fs/super.c:generic_shutdown_super
  - fs/super.c:grab_super
  - fs/super.c:put_super
```
```
In fs/char_dev.c (c0000000004809ac)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
```
In fs/stat.c (c000000000482d8c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
  - fs/stat.c:inode_sub_bytes
  - fs/stat.c:inode_add_bytes
```
```
In fs/exec.c (c0000000004853dc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/pipe.c (c000000000488da8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:fifo_open
  - fs/pipe.c:fifo_open
  - fs/pipe.c:fifo_open
  - fs/pipe.c:put_pipe_info
```
```
In fs/namei.c (c000000000495e70)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/namei.c:vfs_readlink
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:path_init
  - fs/namei.c:__lookup_slow
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
  - fs/namei.c:set_root
  - fs/namei.c:inode_permission
```
```
In fs/fcntl.c (c000000000497fe8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:setfl
```
```
In fs/ioctl.c (c000000000498d38)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/dcache.c (c0000000004a156c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_rehash
  - fs/dcache.c:d_delete
  - fs/dcache.c:d_delete
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:d_instantiate_new
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_fallthru
  - fs/dcache.c:d_alloc
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:d_find_any_alias
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
  - fs/dcache.c:dentry_unlink_inode
  - fs/dcache.c:dentry_unlink_inode
  - fs/dcache.c:take_dentry_name_snapshot
```
```
In fs/inode.c (c0000000004a6e18)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/inode.c:__wait_on_freeing_inode
  - fs/inode.c:__wait_on_freeing_inode
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iunique
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:new_inode_pseudo
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict
  - fs/inode.c:evict
  - fs/inode.c:clear_inode
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:__insert_inode_hash
  - fs/inode.c:__insert_inode_hash
  - fs/inode.c:inode_sb_list_add
```
```
In fs/file.c (c0000000004acef4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:__fd_install
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:expand_files
```
```
In fs/namespace.c (c0000000004b1344)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/xattr.c (c0000000004be3f0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_list_add
  - fs/xattr.c:simple_xattr_list
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:simple_xattr_get
```
```
In fs/libfs.c (c0000000004c0944)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/libfs.c:simple_pin_fs
  - fs/libfs.c:simple_empty
  - fs/libfs.c:simple_empty
  - fs/libfs.c:simple_empty
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (c0000000004cc124)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:inode_wait_for_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/pnode.c (c0000000004cdcec)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (c0000000004d4a60)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In fs/fs_struct.c (c0000000004d58f0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/fs_pin.c (c0000000004d6d3c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
  - fs/fs_pin.c:pin_kill
  - fs/fs_pin.c:pin_kill
  - fs/fs_pin.c:pin_kill
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/buffer.c (c0000000004deafc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:attach_nobh_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__bforget
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:mark_buffer_dirty_inode
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/block_dev.c (c0000000004e8cbc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:bd_abort_claiming
  - fs/block_dev.c:bd_finish_claiming
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:nr_blockdev_pages
  - fs/block_dev.c:bdget
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/proc_namespace.c (c0000000004ee214)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/fsnotify.c (c0000000004eef44)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/notify/notification.c (c0000000004ef7c4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_add_event
  - fs/notify/notification.c:fsnotify_add_event
  - fs/notify/notification.c:fsnotify_add_event
```
```
In fs/notify/group.c (c0000000004efb58)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_group_stop_queueing
```
```
In fs/notify/mark.c (c0000000004f00fc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
```
```
In fs/notify/dnotify/dnotify.c (c0000000004f28c4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (c0000000004f3950)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify.c (c0000000004f561c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/notify/fanotify/fanotify_user.c (c0000000004f6d9c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_ioctl
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
  - fs/notify/fanotify/fanotify_user.c:finish_permission_event
```
```
In fs/eventpoll.c (c0000000004f99c4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In fs/signalfd.c (c0000000004fbb2c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (c0000000004fd61c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_release
```
```
In fs/eventfd.c (c0000000004fe1a0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_show_fdinfo
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (c000000000500504)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_show_fdinfo
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (c000000000504b80)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_cancel
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:kill_ioctx
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_nr_sub
  - fs/aio.c:free_ioctx_users
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_ring_mremap
  - fs/aio.c:put_aio_ring_file
```
```
In fs/io_uring.c (c00000000050f49c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_send_recvmsg
```
```
In fs/dax.c (c0000000005155d8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
```
```
In fs/crypto/hooks.c (c000000000519a8c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In fs/crypto/keyring.c (c00000000051af7c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
```
```
In fs/crypto/keysetup.c (c00000000051ca04)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/crypto/keysetup_v1.c (c00000000051cedc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (c00000000052462c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/locks.c:locks_stop
  - fs/locks.c:show_fd_locks
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_insert_block
  - fs/locks.c:locks_delete_block
  - fs/locks.c:locks_insert_global_locks
  - fs/locks.c:locks_move_blocks
```
```
In fs/mbcache.c (c000000000534514)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/coredump.c (c000000000538c2c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/drop_caches.c (c00000000053923c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/fhandle.c (c000000000539bfc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/quota/dquot.c (c000000000541350)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:do_get_dqblk
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:unregister_quota_format
  - fs/quota/dquot.c:register_quota_format
```
```
In fs/proc/task_mmu.c (c00000000054d480)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/inode.c (c00000000054f410)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/proc/base.c (c000000000557614)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/generic.c (c000000000559780)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In fs/proc/array.c (c00000000055a178)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (c00000000055cabc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (c00000000055f970)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (c000000000561680)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:sysctl_follow_link
  - fs/proc/proc_sysctl.c:proc_sys_compare
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/proc/proc_sysctl.c:sysctl_head_grab
  - fs/proc/proc_sysctl.c:insert_header
```
```
In fs/proc/proc_net.c (c000000000564608)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/kernfs/dir.c (c00000000056b030)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (c00000000056f0d0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/sysfs/dir.c (c000000000571714)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/sysfs/dir.c:sysfs_remove_dir
```
```
In fs/sysfs/symlink.c (c000000000571cfc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_delete_link
```
```
In fs/sysfs/group.c (c000000000572420)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
```
```
In fs/configfs/inode.c (c000000000573920)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In fs/configfs/dir.c (c0000000005767a0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_lseek
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_undepend_item
  - fs/configfs/dir.c:configfs_do_depend_item
  - fs/configfs/dir.c:configfs_dirent_is_ready
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (c0000000005793f4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/dcookies.c (c00000000057b84c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/dcookies.c:dcookie_unregister
  - fs/dcookies.c:get_dcookie
```
```
In fs/ext4/balloc.c (c00000000057d3e8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (c000000000582320)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (c000000000590180)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/ialloc.c (c00000000059856c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (c0000000005a3d8c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (c0000000005c1850)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/migrate.c (c0000000005c2aa8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (c0000000005e5848)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_journal_commit_callback
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (c000000000606310)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
```
```
In fs/jbd2/commit.c (c000000000606ca4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
```
In fs/jbd2/checkpoint.c (c00000000060b264)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/revoke.c (c00000000060bdf8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/jbd2/journal.c (c000000000612530)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/cache.c (c000000000615104)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_put
  - fs/squashfs/cache.c:squashfs_cache_put
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
```
```
In fs/hugetlbfs/inode.c (c00000000061fd98)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
```
```
In fs/fat/cache.c (c0000000006204c8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fat/dir.c (c000000000624218)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/fat/fatent.c (c0000000006260f8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_get
```
```
In fs/fat/inode.c (c00000000062a0ac)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_iget
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (c00000000062e914)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_dget
```
```
In fs/fat/namei_vfat.c (c00000000062f4cc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/exportfs/expfs.c (c0000000006420fc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:reconnect_path
```
```
In fs/nls/nls_base.c (c000000000643668)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/nls/nls_base.c:find_nls
  - fs/nls/nls_base.c:unregister_nls
  - fs/nls/nls_base.c:unregister_nls
```
```
In fs/fuse/dev.c (c0000000006476c0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_dev_poll
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_queue_forget
  - fs/fuse/dev.c:fuse_dev_wake_and_unlock
```
```
In fs/fuse/dir.c (c00000000064f3d4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_settime
```
```
In fs/fuse/file.c (c000000000657f94)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_notify_poll_wakeup
  - fs/fuse/file.c:fuse_file_poll
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_prepare_release
  - fs/fuse/file.c:fuse_prepare_release
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_link_write_file
```
```
In fs/fuse/inode.c (c000000000659aa4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_dev_install
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/control.c (c00000000065b6bc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_max_background_write
```
```
In fs/fuse/readdir.c (c00000000065dbe0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:fuse_emit
  - fs/fuse/readdir.c:fuse_emit
  - fs/fuse/readdir.c:fuse_emit
```
```
In fs/debugfs/inode.c (c00000000065efcc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In fs/tracefs/inode.c (c00000000066332c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
```
```
In fs/pstore/platform.c (c000000000664c3c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_register
```
```
In ipc/util.c (c000000000666100)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (c000000000669e84)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (c00000000066b104)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (c0000000006731f4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shm_add_rss_swap
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
```
In ipc/mqueue.c (c0000000006755f0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_poll_file
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_get_inode
  - ipc/mqueue.c:mqueue_get_inode
```
```
In ipc/namespace.c (c000000000678978)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/keys/gc.c (c0000000006796c0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (c00000000067b8d0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
  - security/keys/key.c:key_payload_reserve
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
```
```
In security/keys/keyctl.c (c0000000006809d8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/keys/proc.c (c000000000686470)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_stop
  - security/keys/proc.c:proc_keys_stop
```
```
In security/selinux/hooks.c (c0000000006ae78c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/smack/smack_lsm.c (c0000000006d345c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/tomoyo/audit.c (c0000000006e24fc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_read_log
```
```
In security/tomoyo/common.c (c0000000006e9480)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/gc.c (c0000000006f24c4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/apparmorfs.c (c0000000006ff458)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_read
```
```
In security/apparmor/path.c (c000000000705070)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In security/apparmor/secid.c (c000000000718b68)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/apparmor/secid.c:aa_alloc_secid
```
```
In security/apparmor/file.c (c00000000071a774)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
```
```
In security/apparmor/af_unix.c (c000000000726e0c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In security/yama/yama_lsm.c (c000000000727e58)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/integrity/ima/ima_template.c (c0000000007357d4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In crypto/scompress.c (c00000000074e1a0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - crypto/scompress.c:scomp_acomp_comp_decomp
```
```
In crypto/jitterentropy-kcapi.c (c000000000761304)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_kcapi_random
  - crypto/jitterentropy-kcapi.c:jent_kcapi_cleanup
```
```
In block/bio.c (c00000000076cca0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/bio.c:bio_dirty_fn
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/elevator.c (c00000000077158c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elv_register
  - block/elevator.c:elv_register
  - block/elevator.c:elevator_get
  - block/elevator.c:elevator_get
```
```
In block/blk-sysfs.c (c00000000077aed8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_max_sectors_store
```
```
In block/blk-flush.c (c00000000077bc8c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-ioc.c (c00000000077dccc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:ioc_clear_queue
  - block/blk-ioc.c:exit_io_context
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-mq.c (c000000000788fa0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-stat.c (c00000000078c7a4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-stat.c:blk_stat_add_callback
```
```
In block/blk-mq-sched.c (c00000000078f54c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
```
In block/genhd.c (c000000000793878)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:disk_clear_events
  - block/genhd.c:disk_clear_events
  - block/genhd.c:disk_flush_events
```
```
In block/ioprio.c (c000000000797860)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In block/badblocks.c (c000000000798994)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
```
```
In block/bsg.c (c0000000007a6734)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
```
```
In block/blk-cgroup.c (c0000000007a83d0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_conf_finish
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_destroy_all
  - block/blk-cgroup.c:blkg_destroy_all
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (c0000000007b15b4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/blk-iocost.c (c0000000007b5744)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_exit
  - block/blk-iocost.c:ioc_rqos_queue_depth_changed
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
```
```
In block/mq-deadline.c (c0000000007b9390)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_dispatch_stop
  - block/mq-deadline.c:deadline_write_fifo_stop
  - block/mq-deadline.c:deadline_read_fifo_stop
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_bio_merge
  - block/mq-deadline.c:dd_dispatch_request
```
```
In block/blk-mq-debugfs.c (c0000000007c4630)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_stop
  - block/blk-mq-debugfs.c:ctx_read_rq_list_stop
  - block/blk-mq-debugfs.c:ctx_default_rq_list_stop
  - block/blk-mq-debugfs.c:hctx_dispatch_stop
  - block/blk-mq-debugfs.c:queue_requeue_list_stop
```
```
In block/blk-pm.c (c0000000007ca4d4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/lockref.c (c0000000007cafb0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - lib/lockref.c:lockref_get_not_dead
  - lib/lockref.c:lockref_put_or_lock
  - lib/lockref.c:lockref_get_or_lock
  - lib/lockref.c:lockref_put_not_zero
  - lib/lockref.c:lockref_get_not_zero
```
```
In lib/percpu-refcount.c (c0000000007da8d0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In lib/rhashtable.c (c0000000007db488)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_walk_stop
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_exit
  - lib/rhashtable.c:rhashtable_walk_enter
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/refcount.c (c0000000007ddde0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In lib/genalloc.c (c0000000007efe38)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (c000000000810cf8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
  - lib/textsearch.c:textsearch_register
```
```
In lib/percpu_counter.c (c00000000081188c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In drivers/irqchip/irq-al-fic.c (c000000000820610)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type
```
```
In drivers/pinctrl/pinctrl-single.c (c000000000833e64)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_handle
```
```
In drivers/pci/access.c (c000000000853ac8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
  - drivers/pci/access.c:pci_wait_cfg
```
```
In drivers/pci/pci.c (c00000000085d430)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci.c:resource_alignment_show
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
```
```
In drivers/pci/pci-driver.c (c000000000865d04)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:pci_add_dynid
```
```
In drivers/rapidio/rio.c (c000000000894cc8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_get_asm
  - drivers/rapidio/rio.c:rio_get_comptag
  - drivers/rapidio/rio.c:rio_release_inb_pwrite
  - drivers/rapidio/rio.c:rio_request_inb_pwrite
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
```
```
In drivers/video/console/vgacon.c (c00000000089dfe8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In drivers/virtio/virtio.c (c0000000008cb304)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_config_enable
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d76f4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/tty/tty_io.c (c0000000008f162c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:redirected_tty_write
  - drivers/tty/tty_io.c:check_tty_count
  - drivers/tty/tty_io.c:tty_add_file
```
```
In drivers/tty/n_tty.c (c0000000008f866c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (c0000000008fa644)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In drivers/tty/tty_port.c (c0000000008fe538)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
```
```
In drivers/tty/tty_ldsem.c (c000000000ee9768)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/tty/tty_jobctrl.c (c00000000090037c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/pty.c (c0000000009008f0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_set_termios
  - drivers/tty/pty.c:pty_flush_buffer
  - drivers/tty/pty.c:pty_set_pktmode
  - drivers/tty/pty.c:pty_close
```
```
In drivers/tty/sysrq.c (c000000000903310)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
```
```
In drivers/tty/vt/vt_ioctl.c (c000000000905e84)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/vc_screen.c (c0000000009079f8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In drivers/tty/vt/keyboard.c (c00000000090f298)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_reset_keyboard
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:fn_spawn_con
```
```
In drivers/tty/vt/vt.c (c000000000915760)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/tty/serial/serial_core.c (c00000000092a168)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_tiocmget
  - drivers/tty/serial/serial_core.c:uart_change_speed
```
```
In drivers/tty/serial/8250/8250_core.c (c00000000092c2f8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
  - drivers/tty/serial/8250/8250_core.c:serial8250_interrupt
```
```
In drivers/tty/serial/8250/8250_port.c (c000000000930788)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/char/random.c (c000000000943958)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/char/virtio_console.c (c00000000094fe40)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:port_fops_release
```
```
In drivers/char/nvram.c (c0000000009506e8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/char/nvram.c:nvram_misc_release
  - drivers/char/nvram.c:nvram_misc_open
  - drivers/char/nvram.c:nvram_misc_open
```
```
In drivers/char/agp/generic.c (c0000000009559a0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In drivers/char/tpm/tpm_ibmvtpm.c (c00000000096868c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_send
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_recv
```
```
In drivers/iommu/iommu.c (c00000000096e690)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_ops_from_fwnode
  - drivers/iommu/iommu.c:iommu_device_unregister
  - drivers/iommu/iommu.c:iommu_device_register
```
```
In drivers/base/core.c (c00000000097d638)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (c00000000097ecd4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (c000000000982c88)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:driver_detach
```
```
In drivers/base/platform.c (c000000000985bf4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_driver_probe
```
```
In drivers/base/attribute_container.c (c00000000098a530)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/attribute_container.c:attribute_container_unregister
```
```
In drivers/base/swnode.c (c00000000098fec8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_to_swnode
```
```
In drivers/base/devtmpfs.c (c000000000992788)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
```
In drivers/base/power/sysfs.c (c000000000993870)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In drivers/base/power/common.c (c00000000099562c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
  - drivers/base/power/common.c:dev_pm_get_subsys_data
```
```
In drivers/base/power/qos.c (c0000000009972d8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
```
```
In drivers/base/power/runtime.c (c00000000099b6bc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_drop_link
  - drivers/base/power/runtime.c:pm_runtime_new_link
  - drivers/base/power/runtime.c:__pm_runtime_use_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_set_autosuspend_delay
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:pm_runtime_no_callbacks
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_forbid
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_work
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
```
```
In drivers/base/power/main.c (c0000000009a1918)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_check_callbacks
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_propagate_wakeup_to_parent
```
```
In drivers/base/power/wakeup.c (c0000000009a3440)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
```
In drivers/base/power/domain.c (c0000000009aa46c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_free_dev_data
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
```
```
In drivers/base/firmware_loader/main.c (c0000000009acbac)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
  - drivers/base/firmware_loader/main.c:free_fw_priv
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
```
In drivers/base/regmap/regmap.c (c0000000009b41c4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
```
```
In drivers/block/loop.c (c0000000009c610c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/mfd/ezx-pcap.c (c0000000009e9ef0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_irq
  - drivers/mfd/ezx-pcap.c:pcap_adc_irq
```
```
In drivers/mfd/syscon.c (c0000000009fb288)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In drivers/nvdimm/bus.c (c0000000009fdaa8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/nvdimm/region_devs.c (c000000000a03100)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_release_lane
```
```
In drivers/nvdimm/badrange.c (c000000000a12a08)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_forget
  - drivers/nvdimm/badrange.c:badrange_add
  - drivers/nvdimm/badrange.c:badrange_add
```
```
In drivers/dax/super.c (c000000000a196d4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/dma-buf/dma-buf.c (c000000000a1d348)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence.c (c000000000a1e12c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/sw_sync.c (c000000000a241b8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/dma-buf/sync_debug.c (c000000000a24bec)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
```
```
In drivers/scsi/scsi_lib.c (c000000000a335ac)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/scsi_scan.c (c000000000a37f7c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/scsi/scsi_dh.c (c000000000a40dec)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/scsi/scsi_dh.c:__scsi_dh_lookup
```
```
In drivers/scsi/sr.c (c000000000a4d374)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/ata/libata-core.c (c000000000a5bc1c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_finalize_port_ops
```
```
In drivers/ata/libata-scsi.c (c000000000a6a86c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
```
In drivers/ata/libata-sff.c (c000000000a7be84)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
```
```
In drivers/net/tun.c (c000000000a9f118)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa6d98)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_compressor
  - drivers/net/ppp/ppp_generic.c:ppp_register_compressor
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
```
In drivers/vfio/virqfd.c (c000000000ab1c20)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In drivers/usb/core/hub.c (c000000000ad1d50)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (c000000000ad94b8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_synchronize_unlinks
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb_from_ep
  - drivers/usb/core/hcd.c:usb_hcd_link_urb_to_ep
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/urb.c (c000000000adb39c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (c000000000add4b4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/usb/core/driver.c (c000000000ae2c70)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
```
```
In drivers/usb/core/devio.c (c000000000aee328)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/core_intr.c (c000000000afcfe0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/hcd.c (c000000000b066dc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
```
```
In drivers/usb/dwc2/hcd_intr.c (c000000000b119ec)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b245d4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_remove_device
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_silence_controller
  - drivers/usb/host/ehci-hcd.c:ehci_silence_controller
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:fill_bandwidth_buffer
```
```
In drivers/usb/host/ohci-hcd.c (c000000000b3585c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b3c9ec)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
```
```
In drivers/usb/host/xhci.c (c000000000b46ad4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
```
```
In drivers/usb/host/xhci-ring.c (c000000000b545f0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (c000000000b66160)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/usb/host/xhci-dbgtty.c (c000000000b68cfc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
```
In drivers/input/serio/serio.c (c000000000b6ee74)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/i8042.c (c000000000b702b8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_start
```
```
In drivers/input/serio/libps2.c (c000000000b7313c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (c000000000b77674)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/input/input.c:__input_unregister_device
  - drivers/input/input.c:input_dev_poweroff
  - drivers/input/input.c:input_dev_freeze
  - drivers/input/input.c:input_dev_resume
  - drivers/input/input.c:input_dev_suspend
```
```
In drivers/input/ff-core.c (c000000000b7b2e8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/input/ff-core.c:erase_effect
  - drivers/input/ff-core.c:erase_effect
  - drivers/input/ff-core.c:input_ff_upload
```
```
In drivers/input/mousedev.c (c000000000b7c114)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/mousedev.c:mousedev_notify_readers
```
```
In drivers/input/evdev.c (c000000000b7ebc4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_detach_client
  - drivers/input/evdev.c:evdev_pass_values
```
```
In drivers/input/keyboard/atkbd.c (c000000000b83e10)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
```
```
In drivers/input/misc/uinput.c (c000000000b85214)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
```
```
In drivers/rtc/dev.c (c000000000b8d0e0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In drivers/i2c/i2c-dev.c (c000000000b99ef8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:put_i2c_dev
  - drivers/i2c/i2c-dev.c:i2c_dev_get_by_minor
```
```
In drivers/pps/pps.c (c000000000ba77b4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
```
```
In drivers/thermal/thermal_sysfs.c (c000000000bbe3c4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:total_trans_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
```
```
In drivers/watchdog/watchdog_pretimeout.c (c000000000bc953c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_unregister_pretimeout
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_pretimeout
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_unregister_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_get
```
```
In drivers/md/md.c (c0000000013ceaf0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:unregister_md_cluster_operations
  - drivers/md/md.c:register_md_cluster_operations
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:register_md_personality
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_next
  - drivers/md/md.c:md_seq_start
  - drivers/md/md.c:md_seq_start
  - drivers/md/md.c:md_unregister_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_attr_store
  - drivers/md/md.c:md_attr_store
  - drivers/md/md.c:md_attr_show
  - drivers/md/md.c:md_attr_show
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_show
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_show
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:set_in_sync
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
```
```
In drivers/md/md-bitmap.c (c000000000be355c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:behind_writes_used_show
  - drivers/md/md-bitmap.c:can_clear_show
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_destroy
  - drivers/md/md-bitmap.c:md_bitmap_set_memory_bits
  - drivers/md/md-bitmap.c:md_bitmap_set_memory_bits
  - drivers/md/md-bitmap.c:md_bitmap_start_sync
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_checkpage
```
```
In drivers/md/dm.c (c000000000bf06c0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_from_kobject
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:free_minor
  - drivers/md/dm.c:dm_cancel_deferred_remove
  - drivers/md/dm.c:dm_lock_for_deletion
  - drivers/md/dm.c:dm_blk_close
  - drivers/md/dm.c:dm_blk_open
```
```
In drivers/md/dm-kcopyd.c (c000000000bfe07c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/md/dm-stats.c (c000000000bff84c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
  - drivers/md/dm-stats.c:dm_kvzalloc
```
```
In drivers/cpufreq/cpufreq.c (c000000000c114f0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
```
```
In drivers/cpufreq/cpufreq_stats.c (c000000000c178fc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
```
In drivers/cpufreq/powernv-cpufreq.c (c000000000c1c594)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_target_index
  - drivers/cpufreq/powernv-cpufreq.c:gpstate_timer_handler
  - drivers/cpufreq/powernv-cpufreq.c:gpstate_timer_handler
  - drivers/cpufreq/powernv-cpufreq.c:gpstate_timer_handler
```
```
In drivers/cpuidle/driver.c (c000000000c1f100)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
```
```
In drivers/cpuidle/sysfs.c (c000000000c203c4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:show_current_driver
```
```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5b280)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_unlock
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_unlock
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In drivers/vme/vme.c (c000000000c6cc84)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_master_free
  - drivers/vme/vme.c:vme_master_request
  - drivers/vme/vme.c:vme_master_request
  - drivers/vme/vme.c:vme_master_request
```
```
In net/socket.c (c000000000c768a8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/socket.c:sock_unregister
  - net/socket.c:sock_register
```
```
In net/core/sock.c (c000000000c7f1b0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:sk_free_unlock_clone
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/gen_estimator.c (c000000000c98a1c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_fetch_counters
```
```
In net/core/net_namespace.c (c000000000c99d68)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/dev.c (c000000000ca5f80)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:dev_add_pack
```
```
In net/core/dev_addr_lists.c (c000000000cc0f70)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_sync_multiple
  - net/core/dev_addr_lists.c:dev_mc_sync
  - net/core/dev_addr_lists.c:dev_uc_sync_multiple
  - net/core/dev_addr_lists.c:dev_uc_sync
```
```
In net/core/neighbour.c (c000000000cc4d58)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/link_watch.c (c000000000cd8e60)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/net-sysfs.c (c000000000cf467c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_timeout_show
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/core/page_pool.c (c000000000cf81d8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/core/netpoll.c (c000000000cfdc08)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/core/fib_rules.c (c000000000cffb74)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/netprio_cgroup.c (c000000000d0e0e4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (c000000000d0eb10)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_task
  - net/core/netclassid_cgroup.c:update_classid_sock
```
```
In net/core/devlink.c (c000000000d18948)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
```
```
In net/sched/sch_generic.c (c000000000d330e4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/cls_api.c (c000000000d3ce40)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_get_next_proto
```
```
In net/ipv4/route.c (c000000000d5ed2c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_fragment.c (c000000000d62b98)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/inet_hashtables.c (c000000000d708ec)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d70dd4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72f38)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_add
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (c000000000d7d174)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (c000000000d85718)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (c000000000d93e90)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (c000000000d95b18)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (c000000000d975b8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e964)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_cong.c (c000000000da0e34)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_fastopen.c (c000000000da4000)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
```
```
In net/ipv4/tcp_ulp.c (c000000000da55e0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/udp.c (c000000000dab750)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
```
```
In net/ipv4/icmp.c (c000000000db8108)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_global_allow
```
```
In net/ipv4/igmp.c (c000000000dc6304)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_timer_expire
```
```
In net/ipv4/fib_semantics.c (c000000000dcf7cc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:ip_fib_check_default
  - net/ipv4/fib_semantics.c:ip_fib_check_default
```
```
In net/ipv4/sysctl_net_ipv4.c (c000000000de3fec)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/ipv4/ipmr.c (c000000000debe7c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv4/syncookies.c (c000000000df0180)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (c000000000df5324)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (c000000000dfaf94)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_if_register_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_register_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_state.c (c000000000e0533c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
```
In net/xfrm/xfrm_input.c (c000000000e0e7fc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (c000000000e133ec)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
```
In net/unix/af_unix.c (c000000000e13a64)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_stop
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_peer_get
```
```
In net/unix/garbage.c (c000000000e1ae80)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/unix/scm.c (c000000000e1b65c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
```
In net/ipv6/anycast.c (c000000000e1e908)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (c000000000e27368)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (c000000000e36a60)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (c000000000e3ed90)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/icmp.c (c000000000e5dfbc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c000000000e632a0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:igmp6_event_report
```
```
In net/ipv6/reassembly.c (c000000000e67aa8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6cf9c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6_flowlabel.c (c000000000e73e20)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (c000000000e78184)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In net/ipv6/xfrm6_input.c (c000000000e7e418)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
```
In net/ipv6/calipso.c (c000000000e83ad4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8f148)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (c000000000e975c4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:__fanout_set_data_bpf
  - net/packet/af_packet.c:__fanout_link
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
```
In net/netlabel/netlabel_domainhash.c (c000000000ea18a4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (c0000000013c79a0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/rfkill/input.c (c000000000eabe00)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_start
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In lib/dec_and_lock.c (c000000000ec3be0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In lib/klist.c (c000000000ecaf68)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - lib/klist.c:klist_remove
  - lib/klist.c:klist_put
  - lib/klist.c:klist_release
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
```
```
In lib/kobject.c (c000000000ecc000)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - lib/kobject.c:kobj_ns_drop
  - lib/kobject.c:kobj_ns_initial
  - lib/kobject.c:kobj_ns_netlink
  - lib/kobject.c:kobj_ns_grab_current
  - lib/kobject.c:kobj_ns_current_may_mount
  - lib/kobject.c:kobj_ns_type_registered
  - lib/kobject.c:kobj_ns_type_register
  - lib/kobject.c:kset_find_obj
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobj_kset_leave
```
```
In lib/xarray.c (c000000000ee04ac)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - lib/xarray.c:xa_clear_mark
  - lib/xarray.c:xa_set_mark
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store
  - lib/xarray.c:xa_erase
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
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
In init/main.c (ffffffe000000f94)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In arch/riscv/kernel/traps.c (ffffffe0000b6c3e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - arch/riscv/kernel/traps.c:die
```
```
In kernel/fork.c (ffffffe0000c1cc8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_release
  - kernel/fork.c:mm_access
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:mmput_async_fn
```
```
In kernel/panic.c (ffffffe0000c207c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In kernel/exit.c (ffffffe0000c529e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (ffffffe0000c7f80)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In kernel/ptrace.c (ffffffe0000cc62a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_may_access
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/user.c (ffffffe0000ccf2c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
```
```
In kernel/signal.c (ffffffe0000d1af4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/signal.c:__se_sys_rt_sigpending
  - kernel/signal.c:__set_current_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
```
```
In kernel/sys.c (ffffffe0000d2a68)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:do_prlimit
```
```
In kernel/umh.c (ffffffe0000d5798)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In kernel/workqueue.c (ffffffe0000db5a8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:drain_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/pid.c (ffffffe0000dc9d4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/pid.c:disable_pid_allocation
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
```
```
In kernel/task_work.c (ffffffe0000dcdd0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_run
```
```
In kernel/params.c (ffffffe0000de128)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/params.c:maybe_kfree_parameter
```
```
In kernel/kthread.c (ffffffe0000dfb96)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/nsproxy.c (ffffffe0000e0482)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/async.c (ffffffe0000e2a4a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/async.c:async_unregister_domain
```
```
In kernel/ucount.c (ffffffe0000e37dc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffe0000e86d2)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:__se_sys_sched_rr_get_interval
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/idle.c (ffffffe0000edde6)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sched/idle.c:dequeue_task_idle
```
```
In kernel/sched/fair.c (ffffffe0000f6406)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:rq_online_fair
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/rt.c (ffffffe0000f79fc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sched/rt.c:tg_set_rt_bandwidth
  - kernel/sched/rt.c:tg_set_rt_bandwidth
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:do_balance_runtime
  - kernel/sched/rt.c:do_balance_runtime
  - kernel/sched/rt.c:do_balance_runtime
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffffffe0000fe026)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:init_dl_bw
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/sched/wait.c (ffffffe0000fedd2)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
```
```
In kernel/sched/swait.c (ffffffe0000ff5c6)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/sched/completion.c (ffffffe0008c5f24)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/sched/completion.c:wait_for_completion
```
```
In kernel/sched/psi.c (ffffffe000109fa4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
```
In kernel/locking/mutex.c (ffffffe0008c7668)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
```
```
In kernel/locking/semaphore.c (ffffffe0008c78ce)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
```
```
In kernel/locking/rwsem.c (ffffffe00010acd0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/spinlock.c (ffffffe0008c975c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_spin_unlock_bh
```
```
In kernel/locking/rtmutex.c (ffffffe00010c5c8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk.c (ffffffe00010ee7a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/printk/printk_safe.c (ffffffe000112066)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
```
In kernel/irq/irqdesc.c (ffffffe000112236)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:actions_show
  - kernel/irq/irqdesc.c:name_show
  - kernel/irq/irqdesc.c:wakeup_show
  - kernel/irq/irqdesc.c:type_show
  - kernel/irq/irqdesc.c:hwirq_show
  - kernel/irq/irqdesc.c:chip_name_show
```
```
In kernel/irq/handle.c (ffffffe000113366)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffffffe00011448a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/spurious.c (ffffffe000115e72)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (ffffffe0001171a6)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/irq/generic-chip.c (ffffffe000119754)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
```
```
In kernel/rcu/sync.c (ffffffe00011e7ca)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_enter
```
```
In kernel/rcu/srcutree.c (ffffffe00011fdac)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffe000122366)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:rcu_iw_handler
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
```
In kernel/kcmp.c (ffffffe000128ce2)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/freezer.c (ffffffe000128f98)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/timer.c (ffffffe0008c874a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:get_next_timer_interrupt
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (ffffffe00012ecea)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:retrigger_next_event
```
```
In kernel/time/timekeeping.c (ffffffe000131ce4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/posix-timers.c (ffffffe000136960)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__se_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffe000137d12)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
```
```
In kernel/time/itimer.c (ffffffe0001390e4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
```
```
In kernel/time/clockevents.c (ffffffe0001396e0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:sysfs_show_current_tick_dev
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/time/tick-common.c (ffffffe00013a17a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffe00013b0fc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/futex.c (ffffffe00013ca96)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup_begin
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_state
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/acct.c (ffffffe00014811e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
  - kernel/acct.c:do_acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffe000151800)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:css_task_iter_start
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_task_count
```
```
In kernel/cgroup/rstat.c (ffffffe0001526ec)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/namespace.c (ffffffe000152950)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe000154556)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
```
In kernel/cgroup/freezer.c (ffffffe000154dee)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
```
```
In kernel/cgroup/cpuset.c (ffffffe00015ab3c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/utsname.c (ffffffe00015adaa)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffe00015cb24)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/stop_machine.c (ffffffe00015d37c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/auditsc.c (ffffffe0001657c8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_getname
```
```
In kernel/audit_tree.c (ffffffe00016910a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
```
```
In kernel/seccomp.c (ffffffe00016bb2c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/taskstats.c (ffffffe00016eb4e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/trace/ring_buffer.c (ffffffe000177fb8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
```
```
In kernel/trace/blktrace.c (ffffffe00018e818)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_startstop
  - kernel/trace/blktrace.c:__blk_trace_startstop
```
```
In kernel/trace/trace_events.c (ffffffe000191738)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:remove_event_file_dir
```
```
In kernel/bpf/syscall.c (ffffffe0001a10a0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/bpf/percpu_freelist.c (ffffffe0001b3ae0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_push
```
```
In kernel/bpf/bpf_lru_list.c (ffffffe0001b4196)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/bpf/devmap.c (ffffffe0001bbb3a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/cpumap.c (ffffffe0001bc486)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (ffffffe0001d035e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:perf_event_addr_filters_sync
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:perf_ctx_unlock
  - kernel/events/core.c:perf_ctx_unlock
```
```
In kernel/padata.c (ffffffe0001d340e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_find_next
  - kernel/padata.c:padata_find_next
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/filemap.c (ffffffe0001d6ce8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_check_and_advance_wb_err
```
```
In mm/oom_kill.c (ffffffe0001dbd96)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/fadvise.c (ffffffe0001dcd20)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
  - mm/fadvise.c:generic_fadvise
  - mm/fadvise.c:generic_fadvise
```
```
In mm/page-writeback.c (ffffffe0001ddcb4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:domain_update_bandwidth
```
```
In mm/truncate.c (ffffffe0001e4912)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_final
```
```
In mm/vmscan.c (ffffffe0001ec80a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffe0001eeae0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_free_swap
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_free_inode
  - mm/shmem.c:shmem_reserve_inode
  - mm/shmem.c:shmem_reserve_inode
```
```
In mm/util.c (ffffffe0001f35c0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/util.c:get_cmdline
```
```
In mm/vmstat.c (ffffffe0001f43f6)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showfree_print
```
```
In mm/backing-dev.c (ffffffe0001f6d48)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In mm/mmu_context.c (ffffffe0001f7846)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/percpu.c (ffffffe0001f9da2)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
```
```
In mm/slab_common.c (ffffffe0001fc224)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/list_lru.c (ffffffe0002035e2)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffe000203a66)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/gup.c (ffffffe00020463e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In mm/memory.c (ffffffe00020690a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/memory.c:follow_pfn
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/mincore.c (ffffffe00020bbbc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffe00020d086)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_unlock
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:munlock_vma_page
```
```
In mm/mmap.c (ffffffe00020f93c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/mprotect.c (ffffffe0002110f2)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffe000211acc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffe00021289c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In mm/rmap.c (ffffffe000213c88)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/vmalloc.c (ffffffe000215c10)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/vmalloc.c:s_stop
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:find_vmap_area
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/page_alloc.c (ffffffe00021f864)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:build_all_zonelists
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/madvise.c (ffffffe0002206b6)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffe0002228b2)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffe000228aea)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:has_usable_swap
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:del_from_avail_list
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_discard_work
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
```
```
In mm/swap_slots.c (ffffffe000229048)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/swap_slots.c:free_swap_slot
  - mm/swap_slots.c:free_swap_slot
```
```
In mm/frontswap.c (ffffffe00022979e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_curr_pages
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_register_ops
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/zswap.c (ffffffe00022a400)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_invalidate_area
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/dmapool.c (ffffffe00022b41c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/dmapool.c:show_pools
```
```
In mm/hugetlb.c (ffffffe000232306)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_chg
  - mm/hugetlb.c:region_chg
  - mm/hugetlb.c:region_chg
  - mm/hugetlb.c:region_chg
  - mm/hugetlb.c:region_add
  - mm/hugetlb.c:hugepage_put_subpool
```
```
In mm/mmu_notifier.c (ffffffe0002328c0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:__mmu_notifier_register
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffe0002342d8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:run_store
  - mm/ksm.c:run_store
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffe00023cf0a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/migrate.c (ffffffe00023ef1e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/memcontrol.c (ffffffe000248f70)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:mem_cgroup_oom_unregister_event
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
```
```
In mm/vmpressure.c (ffffffe0002495f0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
  - mm/vmpressure.c:vmpressure
  - mm/vmpressure.c:vmpressure
  - mm/vmpressure.c:vmpressure_work_fn
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In mm/hugetlb_cgroup.c (ffffffe00024a67a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/zpool.c (ffffffe00024bab0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_unregister_driver
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zbud.c (ffffffe00024c2da)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
  - mm/zbud.c:zbud_alloc
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffe00024d734)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/userfaultfd.c (ffffffe0002504bc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffe0002509a0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (ffffffe00025229c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/memfd.c (ffffffe00025257e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/read_write.c (ffffffe00025527e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In fs/super.c (ffffffe00025ae00)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/super.c:user_get_super
  - fs/super.c:user_get_super
  - fs/super.c:get_active_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:sget
  - fs/super.c:sget
  - fs/super.c:sget
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/super.c:sget_fc
  - fs/super.c:sget_fc
  - fs/super.c:sget_fc
  - fs/super.c:generic_shutdown_super
  - fs/super.c:grab_super
  - fs/super.c:put_super
```
```
In fs/char_dev.c (ffffffe00025be7e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
```
In fs/stat.c (ffffffe00025cbc2)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
  - fs/stat.c:inode_sub_bytes
  - fs/stat.c:inode_add_bytes
```
```
In fs/exec.c (ffffffe00025e9da)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/pipe.c (ffffffe0002605c8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:fifo_open
  - fs/pipe.c:fifo_open
  - fs/pipe.c:fifo_open
  - fs/pipe.c:put_pipe_info
```
```
In fs/namei.c (ffffffe0002684f4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/namei.c:vfs_readlink
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:path_init
  - fs/namei.c:__lookup_slow
  - fs/namei.c:follow_up
  - fs/namei.c:follow_up
  - fs/namei.c:set_root
  - fs/namei.c:inode_permission
```
```
In fs/fcntl.c (ffffffe0002693ae)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:__se_sys_fcntl
  - fs/fcntl.c:setfl
```
```
In fs/ioctl.c (ffffffe000269dd0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/dcache.c (ffffffe00026d164)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_rehash
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_instantiate_new
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_fallthru
  - fs/dcache.c:d_alloc
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:d_find_any_alias
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:__lock_parent
  - fs/dcache.c:__lock_parent
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
  - fs/dcache.c:dentry_unlink_inode
  - fs/dcache.c:dentry_unlink_inode
  - fs/dcache.c:take_dentry_name_snapshot
```
```
In fs/inode.c (ffffffe00027227a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/inode.c:__wait_on_freeing_inode
  - fs/inode.c:__wait_on_freeing_inode
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:igrab
  - fs/inode.c:igrab
  - fs/inode.c:iunique
  - fs/inode.c:iunique
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:new_inode_pseudo
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict
  - fs/inode.c:evict
  - fs/inode.c:clear_inode
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:__insert_inode_hash
  - fs/inode.c:__insert_inode_hash
  - fs/inode.c:inode_sb_list_add
```
```
In fs/file.c (ffffffe00027590a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:expand_files
```
```
In fs/namespace.c (ffffffe000277f10)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/xattr.c (ffffffe00028026e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_list_add
  - fs/xattr.c:simple_xattr_list
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:simple_xattr_get
```
```
In fs/libfs.c (ffffffe0002816e6)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/libfs.c:simple_pin_fs
  - fs/libfs.c:simple_empty
  - fs/libfs.c:simple_empty
  - fs/libfs.c:simple_empty
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffe0002888fa)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:inode_wait_for_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/pnode.c (ffffffe000289ac2)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffffffe00028d2cc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In fs/fs_struct.c (ffffffe00028ded8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/fs_pin.c (ffffffe00028e778)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
  - fs/fs_pin.c:pin_kill
  - fs/fs_pin.c:pin_kill
  - fs/fs_pin.c:pin_kill
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/buffer.c (ffffffe000292ea6)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__bforget
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/block_dev.c (ffffffe000299126)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:bd_abort_claiming
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
  - fs/block_dev.c:nr_blockdev_pages
  - fs/block_dev.c:bdget
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/proc_namespace.c (ffffffe00029c89e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/fsnotify.c (ffffffe00029d198)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/notify/notification.c (ffffffe00029d800)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_add_event
  - fs/notify/notification.c:fsnotify_add_event
  - fs/notify/notification.c:fsnotify_add_event
```
```
In fs/notify/group.c (ffffffe00029db0e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
```
```
In fs/notify/mark.c (ffffffe00029e036)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_free_mark
  - fs/notify/mark.c:fsnotify_free_mark
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
```
```
In fs/notify/dnotify/dnotify.c (ffffffe00029f954)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffe0002a0ce0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify.c (ffffffe0002a161e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a1ba8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_ioctl
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffe0002a4134)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In fs/signalfd.c (ffffffe0002a5144)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffe0002a628a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/timerfd.c:__se_sys_timerfd_gettime
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_release
```
```
In fs/eventfd.c (ffffffe0002a6862)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_show_fdinfo
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffe0002a7c10)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_show_fdinfo
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffe0002ac3a4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:aio_poll_cancel
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:kill_ioctx
  - fs/aio.c:kill_ioctx
  - fs/aio.c:aio_nr_sub
  - fs/aio.c:free_ioctx_users
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_ring_mremap
  - fs/aio.c:put_aio_ring_file
```
```
In fs/io_uring.c (ffffffe0002b0408)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_send_recvmsg
```
```
In fs/dax.c (ffffffe0002b3514)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_lock_page
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
```
```
In fs/crypto/hooks.c (ffffffe0002b6104)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In fs/crypto/keyring.c (ffffffe0002b6eac)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
```
```
In fs/crypto/keysetup.c (ffffffe0002b7f04)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b82a8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffe0002bd3e2)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/locks.c:locks_stop
  - fs/locks.c:show_fd_locks
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:locks_insert_global_locks
  - fs/locks.c:locks_move_blocks
```
```
In fs/mbcache.c (ffffffe0002c43d0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/coredump.c (ffffffe0002c6bfa)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/drop_caches.c (ffffffe0002c6f7c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/fhandle.c (ffffffe0002c764a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
```
In fs/quota/dquot.c (ffffffe0002cb844)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:do_get_dqblk
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:unregister_quota_format
  - fs/quota/dquot.c:register_quota_format
```
```
In fs/proc/task_mmu.c (ffffffe0002d361c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/inode.c (ffffffe0002d43d8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/proc/base.c (ffffffe0002d8db8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/generic.c (ffffffe0002da1fc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In fs/proc/array.c (ffffffe0002dad00)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (ffffffe0002dc99a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffe0002de8ac)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffe0002e0464)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:sysctl_follow_link
  - fs/proc/proc_sysctl.c:proc_sys_compare
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/proc/proc_sysctl.c:insert_header
```
```
In fs/proc/proc_net.c (ffffffe0002e1d6c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/kernfs/dir.c (ffffffe0002e53d4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffe0002e7212)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/sysfs/dir.c (ffffffe0002e8812)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/sysfs/dir.c:sysfs_remove_dir
```
```
In fs/sysfs/symlink.c (ffffffe0002e8c1c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_delete_link
```
```
In fs/sysfs/group.c (ffffffe0002e9786)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
```
```
In fs/configfs/inode.c (ffffffe0002e9c9e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In fs/configfs/dir.c (ffffffe0002eb652)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_lseek
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_do_depend_item
  - fs/configfs/dir.c:configfs_dirent_is_ready
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffe0002ed738)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/dcookies.c (ffffffe0002eece6)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/dcookies.c:dcookie_unregister
  - fs/dcookies.c:get_dcookie
```
```
In fs/ext4/balloc.c (ffffffe0002f011e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffe0002f30ca)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (ffffffe0002fc5ae)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffe000301dc0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffe000308c86)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffe00031bc08)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/migrate.c (ffffffe00031c6b4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffe000331768)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_journal_commit_callback
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffffffe000345510)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
```
```
In fs/jbd2/commit.c (ffffffe000345c3e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
```
In fs/jbd2/checkpoint.c (ffffffe000348ec4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/revoke.c (ffffffe00034967a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/jbd2/journal.c (ffffffe00034d5ec)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/cache.c (ffffffe00034f4dc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_put
  - fs/squashfs/cache.c:squashfs_cache_put
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
```
```
In fs/hugetlbfs/inode.c (ffffffe000356618)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
```
```
In fs/fat/cache.c (ffffffe000356afc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fat/dir.c (ffffffe000358aa6)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/fat/fatent.c (ffffffe00035a1ae)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_get
```
```
In fs/fat/inode.c (ffffffe00035d36a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffffffe00035f8b0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffe00035fec2)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/exportfs/expfs.c (ffffffe00036cb98)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In fs/nls/nls_base.c (ffffffe00036d4cc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/nls/nls_base.c:find_nls
  - fs/nls/nls_base.c:unregister_nls
  - fs/nls/nls_base.c:unregister_nls
```
```
In fs/fuse/dev.c (ffffffe00036ff02)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_poll
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_queue_forget
  - fs/fuse/dev.c:fuse_dev_wake_and_unlock
```
```
In fs/fuse/dir.c (ffffffe0003751c6)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_settime
```
```
In fs/fuse/file.c (ffffffe00037adac)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_notify_poll_wakeup
  - fs/fuse/file.c:fuse_file_poll
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_prepare_release
  - fs/fuse/file.c:fuse_prepare_release
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_link_write_file
```
```
In fs/fuse/inode.c (ffffffe00037c526)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_dev_install
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/control.c (ffffffe00037d67a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_max_background_write
```
```
In fs/fuse/readdir.c (ffffffe00037ec42)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_emit
  - fs/fuse/readdir.c:fuse_emit
  - fs/fuse/readdir.c:fuse_emit
```
```
In fs/debugfs/inode.c (ffffffe00037fcc4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In fs/tracefs/inode.c (ffffffe000382dd4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
```
```
In fs/pstore/platform.c (ffffffe000383dcc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_register
```
```
In ipc/util.c (ffffffe0003849c6)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (ffffffe000386128)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (ffffffe00038a168)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (ffffffe00038bd84)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shm_add_rss_swap
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
```
```
In ipc/mqueue.c (ffffffe00038cef4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - ipc/mqueue.c:__se_sys_mq_notify
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
  - ipc/mqueue.c:mqueue_poll_file
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_get_inode
  - ipc/mqueue.c:mqueue_get_inode
```
```
In ipc/namespace.c (ffffffe00038e97c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/keys/gc.c (ffffffe00038f15e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffe0003907d0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
  - security/keys/key.c:key_payload_reserve
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
```
```
In security/keys/keyctl.c (ffffffe000393610)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/keys/proc.c (ffffffe000396c5e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_stop
  - security/keys/proc.c:proc_keys_stop
```
```
In security/selinux/hooks.c (ffffffe0003a821e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/smack/smack_lsm.c (ffffffe0003c25f6)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/tomoyo/audit.c (ffffffe0003cad2e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_read_log
```
```
In security/tomoyo/common.c (ffffffe0003ce756)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/gc.c (ffffffe0003d3b20)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/apparmorfs.c (ffffffe0003db3ac)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_read
```
```
In security/apparmor/path.c (ffffffe0003dedc0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In security/apparmor/secid.c (ffffffe0003ea29c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/apparmor/secid.c:aa_alloc_secid
```
```
In security/apparmor/file.c (ffffffe0003eb41c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
```
```
In security/apparmor/af_unix.c (ffffffe0003f2926)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In security/yama/yama_lsm.c (ffffffe0003f3168)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/integrity/ima/ima_template.c (ffffffe0003fa53c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In crypto/scompress.c (ffffffe000409126)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - crypto/scompress.c:scomp_acomp_comp_decomp
```
```
In crypto/jitterentropy-kcapi.c (ffffffe0004182ac)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_kcapi_random
  - crypto/jitterentropy-kcapi.c:jent_kcapi_cleanup
```
```
In block/bio.c (ffffffe00041f482)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/bio.c:bio_dirty_fn
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/elevator.c (ffffffe000421d90)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elv_register
  - block/elevator.c:elevator_get
  - block/elevator.c:elevator_get
```
```
In block/blk-sysfs.c (ffffffe00042773c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_max_sectors_store
```
```
In block/blk-flush.c (ffffffe000428198)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-ioc.c (ffffffe000429914)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:ioc_clear_queue
  - block/blk-ioc.c:exit_io_context
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-mq.c (ffffffe000430808)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-stat.c (ffffffe000432d5c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-stat.c:blk_stat_add_callback
```
```
In block/blk-mq-sched.c (ffffffe000434742)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
```
In block/genhd.c (ffffffe000436d00)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:disk_clear_events
  - block/genhd.c:disk_clear_events
  - block/genhd.c:disk_flush_events
```
```
In block/ioprio.c (ffffffe000439786)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In block/badblocks.c (ffffffe00043a252)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
```
```
In block/bsg.c (ffffffe000443582)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
```
```
In block/blk-cgroup.c (ffffffe0004452e6)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_conf_finish
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_destroy_all
  - block/blk-cgroup.c:blkg_destroy_all
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffe00044a4e0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/blk-iocost.c (ffffffe00044cd3e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_exit
  - block/blk-iocost.c:ioc_rqos_queue_depth_changed
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
```
```
In block/mq-deadline.c (ffffffe00044f560)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_read_fifo_stop
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_bio_merge
  - block/mq-deadline.c:dd_dispatch_request
```
```
In block/blk-mq-debugfs.c (ffffffe0004559a8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:ctx_default_rq_list_stop
  - block/blk-mq-debugfs.c:hctx_dispatch_stop
  - block/blk-mq-debugfs.c:queue_requeue_list_stop
```
```
In block/blk-pm.c (ffffffe000459e50)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/lockref.c (ffffffe00045a306)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - lib/lockref.c:lockref_get_not_dead
  - lib/lockref.c:lockref_put_or_lock
  - lib/lockref.c:lockref_get_or_lock
  - lib/lockref.c:lockref_put_not_zero
  - lib/lockref.c:lockref_get_not_zero
  - lib/lockref.c:lockref_get
```
```
In lib/percpu-refcount.c (ffffffe000462b3c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In lib/rhashtable.c (ffffffe0004638b2)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_walk_stop
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_exit
  - lib/rhashtable.c:rhashtable_walk_enter
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/refcount.c (ffffffe000464d4a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In lib/genalloc.c (ffffffe000470874)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (ffffffe00048c0f2)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
  - lib/textsearch.c:textsearch_register
```
```
In drivers/irqchip/irq-al-fic.c (ffffffe00049532e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type
```
```
In drivers/irqchip/irq-sifive-plic.c (ffffffe000495b94)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/irqchip/irq-sifive-plic.c:plic_set_affinity
  - drivers/irqchip/irq-sifive-plic.c:plic_set_affinity
  - drivers/irqchip/irq-sifive-plic.c:plic_irq_mask
  - drivers/irqchip/irq-sifive-plic.c:plic_irq_unmask
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a1388)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_handle
```
```
In drivers/pci/access.c (ffffffe0004b4494)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
  - drivers/pci/access.c:pci_wait_cfg
```
```
In drivers/pci/pci.c (ffffffe0004bc81a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci.c:resource_alignment_show
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
```
```
In drivers/pci/pci-driver.c (ffffffe0004c1158)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:pci_add_dynid
```
```
In drivers/pci/pcie/pme.c (ffffffe0004d4156)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/rapidio/rio.c (ffffffe0004ed41e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_get_asm
  - drivers/rapidio/rio.c:rio_get_comptag
  - drivers/rapidio/rio.c:rio_release_inb_pwrite
  - drivers/rapidio/rio.c:rio_request_inb_pwrite
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
```
```
In drivers/video/console/vgacon.c (ffffffe0004f1f98)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In drivers/virtio/virtio.c (ffffffe000517cda)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_config_enable
```
```
In drivers/virtio/virtio_balloon.c (ffffffe000520e06)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/tty/tty_io.c (ffffffe00052fa3e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:redirected_tty_write
  - drivers/tty/tty_io.c:check_tty_count
  - drivers/tty/tty_io.c:tty_add_file
```
```
In drivers/tty/n_tty.c (ffffffe000533e80)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffe000534fba)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In drivers/tty/tty_port.c (ffffffe000537282)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
```
```
In drivers/tty/tty_ldsem.c (ffffffe0008c905c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/tty/tty_jobctrl.c (ffffffe000538846)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/pty.c (ffffffe000538f26)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_set_termios
  - drivers/tty/pty.c:pty_flush_buffer
  - drivers/tty/pty.c:pty_set_pktmode
  - drivers/tty/pty.c:pty_close
```
```
In drivers/tty/sysrq.c (ffffffe00053abd0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffe00053c2a8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/vc_screen.c (ffffffe00053d154)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffe000541c58)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_reset_keyboard
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:fn_spawn_con
```
```
In drivers/tty/vt/vt.c (ffffffe000545e96)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054f58a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_tiocmget
  - drivers/tty/serial/serial_core.c:uart_change_speed
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffe0005507be)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
  - drivers/tty/serial/8250/8250_core.c:serial8250_interrupt
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000553390)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/tty/serial/sifive.c (ffffffe00055e088)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/tty/serial/sifive.c:sifive_serial_console_write
  - drivers/tty/serial/sifive.c:sifive_serial_irq
  - drivers/tty/serial/sifive.c:sifive_serial_irq
  - drivers/tty/serial/sifive.c:sifive_serial_irq
```
```
In drivers/char/random.c (ffffffe000561cb8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/char/virtio_console.c (ffffffe000566ef4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:port_fops_release
```
```
In drivers/base/core.c (ffffffe00057bacc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffe00057c95a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffe00057f1ee)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:driver_detach
```
```
In drivers/base/platform.c (ffffffe000580a94)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_driver_probe
```
```
In drivers/base/attribute_container.c (ffffffe0005830f8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/attribute_container.c:attribute_container_unregister
```
```
In drivers/base/swnode.c (ffffffe0005867c6)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_to_swnode
```
```
In drivers/base/devtmpfs.c (ffffffe000587ebc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
```
In drivers/base/power/common.c (ffffffe000588e7a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
  - drivers/base/power/common.c:dev_pm_get_subsys_data
```
```
In drivers/base/power/qos.c (ffffffe000589f84)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
```
```
In drivers/base/power/runtime.c (ffffffe00058ccea)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_drop_link
  - drivers/base/power/runtime.c:pm_runtime_new_link
  - drivers/base/power/runtime.c:__pm_runtime_use_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_set_autosuspend_delay
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:pm_runtime_no_callbacks
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_forbid
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_work
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
```
```
In drivers/base/power/domain.c (ffffffe0005900a4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_free_dev_data
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
```
```
In drivers/base/power/clock_ops.c (ffffffe00059104e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
```
```
In drivers/base/firmware_loader/main.c (ffffffe0005920be)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/base/regmap/regmap.c (ffffffe00059447e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
```
```
In drivers/block/loop.c (ffffffe00059fbd8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/mfd/ezx-pcap.c (ffffffe0005b4d44)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_irq
  - drivers/mfd/ezx-pcap.c:pcap_adc_irq
```
```
In drivers/mfd/syscon.c (ffffffe0005bf846)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:device_node_get_regmap
  - drivers/mfd/syscon.c:of_syscon_register
```
```
In drivers/nvdimm/bus.c (ffffffe0005c1448)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/nvdimm/region_devs.c (ffffffe0005c48b4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_release_lane
```
```
In drivers/nvdimm/badrange.c (ffffffe0005cd990)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_forget
  - drivers/nvdimm/badrange.c:badrange_add
  - drivers/nvdimm/badrange.c:badrange_add
```
```
In drivers/dax/super.c (ffffffe0005d07aa)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/dma-buf/dma-buf.c (ffffffe0005d29ca)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence.c (ffffffe0005d369a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/sw_sync.c (ffffffe0005d68de)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/dma-buf/sync_debug.c (ffffffe0005d6e22)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005e06ae)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/scsi_scan.c (ffffffe0005e3838)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/scsi/scsi_dh.c (ffffffe0005e8f26)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/scsi/scsi_dh.c:__scsi_dh_lookup
```
```
In drivers/scsi/sr.c (ffffffe0005f0d5c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/ata/libata-core.c (ffffffe0005f98ba)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_finalize_port_ops
```
```
In drivers/ata/libata-scsi.c (ffffffe000603cfc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
```
In drivers/ata/libata-sff.c (ffffffe00060fa00)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
```
```
In drivers/net/tun.c (ffffffe000627e00)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062c5ee)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_compressor
  - drivers/net/ppp/ppp_generic.c:ppp_register_compressor
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
```
In drivers/usb/core/hub.c (ffffffe00063d66c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffe000642a18)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_synchronize_unlinks
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb_from_ep
  - drivers/usb/core/hcd.c:usb_hcd_link_urb_to_ep
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/urb.c (ffffffe000643eda)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffe00064554a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/usb/core/driver.c (ffffffe000648ea8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_match_dynamic_id
  - drivers/usb/core/driver.c:usb_match_dynamic_id
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
```
```
In drivers/usb/core/devio.c (ffffffe00064f184)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/core_intr.c (ffffffe0006596ce)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffe0006603e2)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffe000667ea2)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe0006773ca)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_remove_device
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_silence_controller
  - drivers/usb/host/ehci-hcd.c:ehci_silence_controller
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:fill_bandwidth_buffer
```
```
In drivers/usb/host/ohci-hcd.c (ffffffe00067ffce)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe000684878)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
```
```
In drivers/usb/host/xhci.c (ffffffe000689e44)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
```
```
In drivers/usb/host/xhci-ring.c (ffffffe000693eca)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffe00069f716)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffe0006a13f8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
```
In drivers/input/serio/serio.c (ffffffe0006a5240)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (ffffffe0006a64b8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (ffffffe0006a91c8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/input/input.c:__input_unregister_device
```
```
In drivers/input/ff-core.c (ffffffe0006ab814)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/input/ff-core.c:erase_effect
  - drivers/input/ff-core.c:erase_effect
  - drivers/input/ff-core.c:input_ff_upload
```
```
In drivers/input/mousedev.c (ffffffe0006ac74c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/mousedev.c:mousedev_notify_readers
```
```
In drivers/input/evdev.c (ffffffe0006ad7d2)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_pass_values
```
```
In drivers/input/keyboard/atkbd.c (ffffffe0006b0982)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
```
```
In drivers/input/misc/uinput.c (ffffffe0006b2266)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
```
```
In drivers/rtc/dev.c (ffffffe0006b5e54)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In drivers/i2c/i2c-dev.c (ffffffe0006bd164)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:put_i2c_dev
  - drivers/i2c/i2c-dev.c:i2c_dev_get_by_minor
```
```
In drivers/pps/pps.c (ffffffe0006c4df4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
```
```
In drivers/thermal/thermal_sysfs.c (ffffffe0006d244a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:total_trans_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
```
```
In drivers/watchdog/watchdog_pretimeout.c (ffffffe0006d8716)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_unregister_pretimeout
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_pretimeout
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_unregister_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_get
```
```
In drivers/md/md.c (ffffffe0006e4180)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:unregister_md_cluster_operations
  - drivers/md/md.c:register_md_cluster_operations
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:register_md_personality
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_next
  - drivers/md/md.c:md_seq_start
  - drivers/md/md.c:md_seq_start
  - drivers/md/md.c:md_unregister_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_show
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_show
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:set_in_sync
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
```
```
In drivers/md/md-bitmap.c (ffffffe0006e9eac)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:behind_writes_used_show
  - drivers/md/md-bitmap.c:can_clear_show
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_destroy
  - drivers/md/md-bitmap.c:md_bitmap_set_memory_bits
  - drivers/md/md-bitmap.c:md_bitmap_start_sync
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_checkpage
```
```
In drivers/md/dm.c (ffffffe0006f1386)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_from_kobject
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:free_minor
  - drivers/md/dm.c:dm_cancel_deferred_remove
  - drivers/md/dm.c:dm_lock_for_deletion
  - drivers/md/dm.c:dm_blk_close
  - drivers/md/dm.c:dm_blk_open
```
```
In drivers/md/dm-kcopyd.c (ffffffe0006f97a2)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/md/dm-stats.c (ffffffe0006fa6aa)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
  - drivers/md/dm-stats.c:dm_kvzalloc
```
```
In drivers/mmc/core/queue.c (ffffffe000719a32)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/mmc/core/queue.c:mmc_mq_queue_rq
  - drivers/mmc/core/queue.c:mmc_mq_queue_rq
  - drivers/mmc/core/queue.c:mmc_mq_queue_rq
  - drivers/mmc/core/queue.c:mmc_mq_queue_rq
  - drivers/mmc/core/queue.c:mmc_mq_recovery_handler
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072d18c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_unlock
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_unlock
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In drivers/vme/vme.c (ffffffe0007344ac)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_master_free
  - drivers/vme/vme.c:vme_master_request
  - drivers/vme/vme.c:vme_master_request
  - drivers/vme/vme.c:vme_master_request
```
```
In net/socket.c (ffffffe00073a3fa)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/socket.c:sock_register
```
```
In net/core/sock.c (ffffffe00073f3de)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:sk_free_unlock_clone
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/gen_estimator.c (ffffffe00074d0b4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_fetch_counters
```
```
In net/core/net_namespace.c (ffffffe00074e1f4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/dev.c (ffffffe000758cba)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:dev_add_pack
```
```
In net/core/dev_addr_lists.c (ffffffe000766628)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_sync_multiple
  - net/core/dev_addr_lists.c:dev_mc_sync
  - net/core/dev_addr_lists.c:dev_uc_sync_multiple
  - net/core/dev_addr_lists.c:dev_uc_sync
```
```
In net/core/neighbour.c (ffffffe000769422)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/link_watch.c (ffffffe000775236)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/net-sysfs.c (ffffffe00078920a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_timeout_show
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/core/page_pool.c (ffffffe00078a0ce)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/core/netpoll.c (ffffffe00078d500)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/core/fib_rules.c (ffffffe00078f5f2)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/netprio_cgroup.c (ffffffe00079710a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffe000797392)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_task
  - net/core/netclassid_cgroup.c:update_classid_sock
```
```
In net/core/devlink.c (ffffffe00079d034)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
```
```
In net/sched/sch_generic.c (ffffffe0007ab1fe)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/cls_api.c (ffffffe0007b0ede)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_get_next_proto
```
```
In net/ipv4/route.c (ffffffe0007c572e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c7f2a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d10a8)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d14de)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2d46)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_add
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffe0007d8b32)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffe0007de650)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffe0007e8860)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e9b78)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007edd70)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efc44)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_cong.c (ffffffe0007f1240)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f3118)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
```
```
In net/ipv4/tcp_ulp.c (ffffffe0007f40c4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/udp.c (ffffffe0007f9dca)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
```
```
In net/ipv4/icmp.c (ffffffe0007fff60)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_global_allow
```
```
In net/ipv4/igmp.c (ffffffe00080922a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_timer_expire
```
```
In net/ipv4/fib_semantics.c (ffffffe00080e65e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:ip_fib_check_default
  - net/ipv4/fib_semantics.c:ip_fib_check_default
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffe00081b882)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/ipv4/ipmr.c (ffffffe00082100a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_expire_process
```
```
In net/ipv4/syncookies.c (ffffffe000823152)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffe000826716)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082bddc)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_if_register_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_register_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_state.c (ffffffe000831d9c)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
```
In net/xfrm/xfrm_input.c (ffffffe0008386b0)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b8d4)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
```
In net/unix/af_unix.c (ffffffe00083ce88)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_stop
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_peer_get
```
```
In net/unix/garbage.c (ffffffe000840a66)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/unix/scm.c (ffffffe000840f92)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
```
In net/ipv6/anycast.c (ffffffe000843060)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (ffffffe00084a704)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffe000852fda)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffe000858b64)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
```
```
In net/ipv6/icmp.c (ffffffe00086c928)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffe000870580)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:igmp6_event_report
```
```
In net/ipv6/reassembly.c (ffffffe000872e74)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000876b42)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087b552)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (ffffffe00087e85a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffe0008824ac)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
```
In net/ipv6/calipso.c (ffffffe0008874ca)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d932)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffe000891f7e)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:__fanout_set_data_bpf
  - net/packet/af_packet.c:__fanout_link
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
```
In net/netlabel/netlabel_domainhash.c (ffffffe00089953a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089b7f2)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/rfkill/input.c (ffffffe00089fc70)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_start
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In lib/dec_and_lock.c (ffffffe0008aec0a)
Location: include/asm-generic/mmiowb.h:47
Inline: True
```
```
In lib/klist.c (ffffffe0008b39f6)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - lib/klist.c:klist_remove
  - lib/klist.c:klist_put
  - lib/klist.c:klist_release
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
```
```
In lib/kobject.c (ffffffe0008b3eaa)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - lib/kobject.c:kobj_ns_drop
  - lib/kobject.c:kobj_ns_initial
  - lib/kobject.c:kobj_ns_netlink
  - lib/kobject.c:kobj_ns_grab_current
  - lib/kobject.c:kobj_ns_current_may_mount
  - lib/kobject.c:kobj_ns_type_registered
  - lib/kobject.c:kobj_ns_type_register
  - lib/kobject.c:kset_find_obj
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobj_kset_leave
```
```
In lib/xarray.c (ffffffe0008c3520)
Location: include/asm-generic/mmiowb.h:47
Inline: True
Inline callers:
  - lib/xarray.c:xa_clear_mark
  - lib/xarray.c:xa_set_mark
  - lib/xarray.c:xa_store
  - lib/xarray.c:xa_erase
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
```
</details>
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
