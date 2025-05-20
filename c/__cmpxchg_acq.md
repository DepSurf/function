# Function: <code>__cmpxchg_acq</code>

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
In init/main.c (ffff8000114311f8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In arch/arm64/kernel/debug-monitors.c (ffff800010086aa8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - arch/arm64/kernel/debug-monitors.c:register_kernel_break_hook
  - arch/arm64/kernel/debug-monitors.c:register_user_break_hook
  - arch/arm64/kernel/debug-monitors.c:register_kernel_step_hook
  - arch/arm64/kernel/debug-monitors.c:register_user_step_hook
  - arch/arm64/kernel/debug-monitors.c:unregister_debug_hook
```
```
In arch/arm64/kernel/traps.c (ffff800010094510)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:call_undef_hook
  - arch/arm64/kernel/traps.c:unregister_undef_hook
  - arch/arm64/kernel/traps.c:register_undef_hook
  - arch/arm64/kernel/traps.c:die
```
```
In arch/arm64/kernel/insn.c (ffff800010da75ec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - arch/arm64/kernel/insn.c:__aarch64_insn_write
```
```
In arch/arm64/kernel/cpu_errata.c (ffff800010098888)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In arch/arm64/kernel/cpufeature.c (ffff800010099cbc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In arch/arm64/kernel/perf_event.c (ffff8000100a460c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_event.c:armv8pmu_stop
  - arch/arm64/kernel/perf_event.c:armv8pmu_start
  - arch/arm64/kernel/perf_event.c:armv8pmu_disable_event
  - arch/arm64/kernel/perf_event.c:armv8pmu_enable_event
```
```
In arch/arm64/kernel/armv8_deprecated.c (ffff8000100a85f8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - arch/arm64/kernel/armv8_deprecated.c:run_all_insn_set_hw_mode
```
```
In arch/arm64/mm/mmu.c (ffff8000100ae6d0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:set_swapper_pgd
```
```
In arch/arm64/mm/context.c (ffff8000100afae0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In virt/kvm/kvm_main.c (ffff8000100b8414)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:hardware_disable_all
  - virt/kvm/kvm_main.c:kvm_dying_cpu
  - virt/kvm/kvm_main.c:kvm_starting_cpu
  - virt/kvm/kvm_main.c:kvm_clear_dirty_log_protect
  - virt/kvm/kvm_main.c:kvm_get_dirty_log_protect
  - virt/kvm/kvm_main.c:kvm_create_vm
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_test_young
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_clear_young
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_clear_flush_young
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_invalidate_range_start
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_change_pte
```
```
In virt/kvm/coalesced_mmio.c (ffff8000100bfef8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - virt/kvm/coalesced_mmio.c:coalesced_mmio_write
```
```
In virt/kvm/eventfd.c (ffff8000100c1944)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:kvm_irq_routing_update
  - virt/kvm/eventfd.c:kvm_irqfd_release
  - virt/kvm/eventfd.c:kvm_irqfd
  - virt/kvm/eventfd.c:kvm_irqfd_assign
  - virt/kvm/eventfd.c:irqfd_wakeup
```
```
In virt/kvm/arm/arm.c (ffff8000100c6cec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
```
```
In virt/kvm/arm/mmu.c (ffff8000100cd13c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:kvm_arch_flush_shadow_memslot
  - virt/kvm/arm/mmu.c:kvm_arch_prepare_memory_region
  - virt/kvm/arm/mmu.c:kvm_handle_guest_abort
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:kvm_mmu_wp_memory_region
  - virt/kvm/arm/mmu.c:kvm_phys_addr_ioremap
  - virt/kvm/arm/mmu.c:kvm_free_stage2_pgd
  - virt/kvm/arm/mmu.c:stage2_unmap_vm
  - virt/kvm/arm/mmu.c:stage2_flush_vm
```
```
In virt/kvm/arm/vgic/vgic.c (ffff8000100dd560)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_map_is_active
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_flush_hwstate
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_flush_hwstate
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_flush_hwstate
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_sync_hwstate
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_sync_hwstate
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_sync_hwstate
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_sync_hwstate
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_sync_hwstate
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_set_owner
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_unmap_phys_irq
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_reset_mapped_irq
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_map_phys_irq
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_inject_irq
  - virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock
  - virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock
  - virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock
  - virt/kvm/arm/vgic/vgic.c:vgic_irq_cmp
  - virt/kvm/arm/vgic/vgic.c:vgic_irq_cmp
  - virt/kvm/arm/vgic/vgic.c:vgic_flush_pending_lpis
  - virt/kvm/arm/vgic/vgic.c:vgic_flush_pending_lpis
```
```
In virt/kvm/arm/vgic/vgic-v2.c (ffff8000100de978)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_fold_lr_state
```
```
In virt/kvm/arm/vgic/vgic-v3.c (ffff8000100dfab8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_lpi_sync_pending_status
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_fold_lr_state
```
```
In virt/kvm/arm/vgic/vgic-mmio.c (ffff8000100e249c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_write_irq_line_level_info
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_config
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_priority
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_cpending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_spending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_read_pending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_cenable
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_senable
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_group
```
```
In virt/kvm/arm/vgic/vgic-mmio-v2.c (ffff8000100e35e0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgipends
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgipendc
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_target
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgir
```
```
In virt/kvm/arm/vgic/vgic-mmio-v3.c (ffff8000100e4ee0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_dispatch_sgi
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_uaccess_write_pending
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_mmio_write_irouter
```
```
In virt/kvm/arm/vgic/vgic-its.c (ffff8000100eadd0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-its.c:vgic_enable_lpis
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_inject_cached_translation
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_inject_cached_translation
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_trigger_msi
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_resolve_lpi
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_invalidate_cache
  - virt/kvm/arm/vgic/vgic-its.c:vgic_copy_lpi_list
  - virt/kvm/arm/vgic/vgic-its.c:update_lpi_config
```
```
In virt/kvm/arm/vgic/vgic-debug.c (ffff8000100eb6a0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-debug.c:vgic_debug_show
```
```
In arch/arm/xen/p2m.c (ffff8000100f0570)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - arch/arm/xen/p2m.c:__set_phys_to_machine_multi
  - arch/arm/xen/p2m.c:__set_phys_to_machine_multi
```
```
In kernel/fork.c (ffff8000100f5994)
Location: arch/arm64/include/asm/cmpxchg.h:173
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
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
```
```
In kernel/panic.c (ffff8000100f622c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In kernel/exit.c (ffff8000100fb5ec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (ffff800010100af4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:adjust_resource
  - kernel/resource.c:remove_resource
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:release_resource
  - kernel/resource.c:request_resource_conflict
  - kernel/resource.c:release_child_resources
```
```
In kernel/ptrace.c (ffff80001010953c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_resume
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/user.c (ffff80001010a4b8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:find_user
```
```
In kernel/signal.c (ffff800010113a80)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:__set_current_blocked
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:force_sigsegv
  - kernel/signal.c:__lock_task_sighand
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:flush_itimer_signals
  - kernel/signal.c:flush_signals
  - kernel/signal.c:calculate_sigpending
```
```
In kernel/sys.c (ffff800010115e8c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__arm64_sys_setpgid
```
```
In kernel/umh.c (ffff80001011b134)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In kernel/workqueue.c (ffff800010122ca4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:pwq_adjust_max_active
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
In kernel/pid.c (ffff8000101249f8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/pid.c:disable_pid_allocation
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
```
```
In kernel/task_work.c (ffff800010124e28)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_run
  - kernel/task_work.c:task_work_cancel
```
```
In kernel/params.c (ffff800010126828)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/params.c:param_set_charp
  - kernel/params.c:maybe_kfree_parameter
```
```
In kernel/kthread.c (ffff800010128c00)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_queue_work
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kthread.c:__kthread_parkme
```
```
In kernel/nsproxy.c (ffff80001012b684)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/notifier.c (ffff80001012c1b4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/notifier.c:atomic_notifier_chain_register
```
```
In kernel/async.c (ffff80001012e4a0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/async.c:async_unregister_domain
  - kernel/async.c:async_schedule_node_domain
  - kernel/async.c:async_schedule_node_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:lowest_in_progress
```
```
In kernel/ucount.c (ffff800010130058)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
  - kernel/ucount.c:get_ucounts
  - kernel/ucount.c:get_ucounts
```
```
In kernel/sched/core.c (ffff8000101387b0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:__balance_callback
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/core.c:task_rq_lock
```
```
In kernel/sched/cputime.c (ffff80001013f4ac)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/sched/cputime.c:cputime_adjust
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/idle.c (ffff80001013fa0c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/sched/idle.c:dequeue_task_idle
```
```
In kernel/sched/fair.c (ffff80001014d628)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:rq_online_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/sched/rt.c (ffff80001014f0ec)
Location: arch/arm64/include/asm/cmpxchg.h:173
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
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:rto_push_irq_work_func
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
In kernel/sched/deadline.c (ffff8000101578f0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:dl_clear_root_domain
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:init_dl_bw
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/sched/wait.c (ffff800010158c94)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:__wake_up_common_lock
  - kernel/sched/wait.c:remove_wait_queue
  - kernel/sched/wait.c:add_wait_queue_exclusive
  - kernel/sched/wait.c:add_wait_queue
```
```
In kernel/sched/swait.c (ffff800010159824)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_exclusive
  - kernel/sched/swait.c:swake_up_all
  - kernel/sched/swait.c:swake_up_all
  - kernel/sched/swait.c:swake_up_one
```
```
In kernel/sched/completion.c (ffff800010da2844)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/sched/completion.c:__wait_for_common
  - kernel/sched/completion.c:__wait_for_common
  - kernel/sched/completion.c:complete_all
  - kernel/sched/completion.c:complete
```
```
In kernel/sched/cpudeadline.c (ffff80001015a690)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_clear
```
```
In kernel/sched/topology.c (ffff80001015b224)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/sched/debug.c (ffff800010163110)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cfs_rq
```
```
In kernel/sched/cpufreq_schedutil.c (ffff800010165404)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_work
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
```
In kernel/sched/psi.c (ffff800010167868)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
```
In kernel/locking/mutex.c (ffff800010da4214)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
```
In kernel/locking/semaphore.c (ffff800010da4918)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
  - kernel/locking/semaphore.c:up
  - kernel/locking/semaphore.c:down_timeout
  - kernel/locking/semaphore.c:down_trylock
  - kernel/locking/semaphore.c:down_killable
  - kernel/locking/semaphore.c:down_interruptible
  - kernel/locking/semaphore.c:down
```
```
In kernel/locking/rwsem.c (ffff8000101696f4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/locking/spinlock.c (ffff800010da73c8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_trylock
```
```
In kernel/locking/osq_lock.c (ffff80001016a838)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffff80001016a978)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex.c (ffff80001016c458)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_timed_lock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
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
```
```
In kernel/locking/qrwlock.c (ffff80001016c880)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/qos.c (ffff80001016cd7c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In kernel/power/suspend.c (ffff8000101704f0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/power/suspend.c:s2idle_wake
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/power/wakelock.c (ffff8000101716d4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/power/wakelock.c:__wakelocks_gc
```
```
In kernel/printk/printk.c (ffff800010172fc4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/printk/printk.c:kmsg_dump_register
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/printk/printk_safe.c (ffff800010177054)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/irq/irqdesc.c (ffff800010177de4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:actions_show
  - kernel/irq/irqdesc.c:name_show
  - kernel/irq/irqdesc.c:wakeup_show
  - kernel/irq/irqdesc.c:type_show
  - kernel/irq/irqdesc.c:hwirq_show
  - kernel/irq/irqdesc.c:chip_name_show
```
```
In kernel/irq/handle.c (ffff800010178a00)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (ffff80001017c628)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffff80001017d3ec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/irq/spurious.c:__report_bad_irq
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (ffff80001017ec48)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_fasteoi_mask_irq
  - kernel/irq/chip.c:handle_fasteoi_ack_irq
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/irq/generic-chip.c (ffff800010181968)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
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
In kernel/irq/autoprobe.c (ffff800010182364)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
```
In kernel/irq/proc.c (ffff800010185f8c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/cpuhotplug.c (ffff80001018659c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In kernel/irq/pm.c (ffff80001018674c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In kernel/rcu/update.c (ffff800010188c0c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/sync.c (ffff800010189600)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/sync.c:rcu_sync_func
```
```
In kernel/rcu/srcutree.c (ffff80001018aa3c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffff80001018fd20)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:sync_rcu_preempt_exp_done_unlocked
  - kernel/rcu/tree.c:rcu_iw_handler
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcutree_offline_cpu
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
```
In kernel/dma/coherent.c (ffff8000101959d8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/dma/coherent.c:__dma_release_from_coherent
  - kernel/dma/coherent.c:__dma_alloc_from_coherent
```
```
In kernel/dma/swiotlb.c (ffff800010196c60)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In kernel/kcmp.c (ffff800010197aa0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/freezer.c (ffff800010198238)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/timer.c (ffff8000101a02a8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:get_next_timer_interrupt
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffff8000101a27a8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/hrtimer.c:lock_hrtimer_base
```
```
In kernel/time/timekeeping.c (ffff8000101a5934)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
```
```
In kernel/time/timer_list.c (ffff8000101a7bb4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_active_timers
```
```
In kernel/time/alarmtimer.c (ffff8000101a9978)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_handle_timer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/alarmtimer.c:alarmtimer_get_rtcdev
```
```
In kernel/time/posix-timers.c (ffff8000101aca64)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__arm64_sys_timer_delete
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/time/posix-timers.c:posix_timer_fn
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ae85c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
```
```
In kernel/time/itimer.c (ffff8000101afde0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
```
```
In kernel/time/clockevents.c (ffff8000101b09e4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:sysfs_show_current_tick_dev
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:tick_offline_cpu
  - kernel/time/clockevents.c:clockevents_register_device
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/time/tick-common.c (ffff8000101b221c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-broadcast.c (ffff8000101b3d78)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_switch_to_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_update_freq
```
```
In kernel/time/tick-sched.c (ffff8000101b4b64)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/futex.c (ffff8000101b6c4c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup_begin
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/acct.c (ffff8000101c80f4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
  - kernel/acct.c:do_acct_process
```
```
In kernel/cgroup/cgroup.c (ffff8000101d88b8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_task_count
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/cgroup/rstat.c (ffff8000101d9ad4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/cgroup/namespace.c (ffff8000101d9f8c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dc550)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
```
In kernel/cgroup/freezer.c (ffff8000101ddb04)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4908)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
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
In kernel/utsname.c (ffff8000101e511c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffff8000101e75ac)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/stop_machine.c (ffff8000101e7ff0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_should_run
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/audit.c (ffff8000101e9b10)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_get_tty
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/auditsc.c (ffff8000101f1fac)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_getname
```
```
In kernel/audit_tree.c (ffff8000101f6110)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
```
```
In kernel/kprobes.c (ffff8000101f8448)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/debug/debug_core.c (ffff8000101fa244)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_support.c (ffff800010203e28)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In kernel/seccomp.c (ffff8000102098cc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/delayacct.c (ffff80001020cc40)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:delayacct_end
```
```
In kernel/taskstats.c (ffff80001020da58)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/trace/trace_clock.c (ffff80001020efc8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffff800010218e00)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/trace/trace.c (ffff800010228eec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffff800010230718)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffff800010232334)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/blktrace.c (ffff8000102372ec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_events.c (ffff80001023a9a0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:remove_event_file_dir
```
```
In kernel/trace/trace_uprobe.c (ffff8000102594b4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In kernel/bpf/core.c (ffff80001025e1e4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffff80001026550c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_id
```
```
In kernel/bpf/helpers.c (ffff8000102769e4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/hashtab.c (ffff800010279098)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
```
```
In kernel/bpf/percpu_freelist.c (ffff80001027c130)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_push
```
```
In kernel/bpf/bpf_lru_list.c (ffff80001027ced0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
```
In kernel/bpf/lpm_trie.c (ffff80001027df00)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
```
In kernel/bpf/local_storage.c (ffff80001027f51c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/queue_stack_maps.c (ffff80001027f8d8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_push_elem
  - kernel/bpf/queue_stack_maps.c:__stack_map_get
  - kernel/bpf/queue_stack_maps.c:__queue_map_get
```
```
In kernel/bpf/btf.c (ffff800010285628)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/devmap.c (ffff8000102871ec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/cpumap.c (ffff800010288490)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/xskmap.c (ffff80001028962c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
```
```
In kernel/bpf/reuseport_array.c (ffff800010290818)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
```
```
In kernel/events/core.c (ffff8000102a10e4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:perf_unpin_context
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:event_function_call
```
```
In kernel/events/uprobes.c (ffff8000102a7ff4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:vma_has_uprobes
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:__uprobe_unregister
  - kernel/events/uprobes.c:find_uprobe
```
```
In kernel/padata.c (ffff8000102a9f0c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_find_next
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/filemap.c (ffff8000102aef6c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_fdatawrite_range
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/mempool.c (ffff8000102b57fc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/mempool.c:mempool_free
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/mempool.c:mempool_resize
  - mm/mempool.c:mempool_resize
  - mm/mempool.c:mempool_resize
```
```
In mm/oom_kill.c (ffff8000102b7b28)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/fadvise.c (ffff8000102b9074)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
  - mm/fadvise.c:generic_fadvise
  - mm/fadvise.c:generic_fadvise
```
```
In mm/page-writeback.c (ffff8000102bc02c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:domain_update_bandwidth
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/swap.c (ffff8000102c1810)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffff8000102c3f1c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_final
```
```
In mm/vmscan.c (ffff8000102ce65c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffff8000102d0f7c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_lock
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
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_free_swap
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_free_inode
  - mm/shmem.c:shmem_reserve_inode
```
```
In mm/util.c (ffff8000102d91a4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/util.c:get_cmdline
```
```
In mm/vmstat.c (ffff8000102da654)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showfree_print
```
```
In mm/backing-dev.c (ffff8000102def40)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_put
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In mm/mmu_context.c (ffff8000102dfe6c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/percpu.c (ffff8000102e2d20)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffff8000102e5824)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_cache_shutdown
```
```
In mm/compaction.c (ffff8000102ec674)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/list_lru.c (ffff8000102efa9c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffff8000102f001c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/gup.c (ffff8000102f1fe4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102f4600)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/mincore.c (ffff8000102fcff4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffff8000102fee08)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_unlock
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
```
```
In mm/mmap.c (ffff800010302a30)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/mprotect.c (ffff800010305114)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffff8000103060c8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffff800010307314)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffff80001030a3f0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/vmalloc.c (ffff80001030cb58)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/vmalloc.c:s_start
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:find_vmap_area
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/page_alloc.c (ffff80001031ac24)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/shuffle.c (ffff80001031b30c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In mm/madvise.c (ffff80001031ea84)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffff80001032153c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffff800010328cc4)
Location: arch/arm64/include/asm/cmpxchg.h:173
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
  - mm/swapfile.c:enable_swap_info
  - mm/swapfile.c:enable_swap_info
  - mm/swapfile.c:enable_swap_info
  - mm/swapfile.c:enable_swap_info
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
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
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_discard_work
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
```
```
In mm/swap_slots.c (ffff800010329cb0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/swap_slots.c:free_swap_slot
```
```
In mm/frontswap.c (ffff80001032a21c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_curr_pages
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_register_ops
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/zswap.c (ffff80001032b748)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_invalidate_area
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_pool_put
```
```
In mm/dmapool.c (ffff80001032d160)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
  - mm/dmapool.c:dma_pool_alloc
  - mm/dmapool.c:dma_pool_alloc
  - mm/dmapool.c:show_pools
```
```
In mm/hugetlb.c (ffff800010336334)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:alloc_gigantic_page
  - mm/hugetlb.c:alloc_gigantic_page
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:region_chg
  - mm/hugetlb.c:region_chg
  - mm/hugetlb.c:region_add
  - mm/hugetlb.c:hugepage_put_subpool
```
```
In mm/mempolicy.c (ffff80001033be34)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/mmu_notifier.c (ffff80001033cef4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:__mmu_notifier_register
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffff80001033fa44)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:run_store
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffff8000103496c8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:count_partial
  - mm/slub.c:free_debug_processing
```
```
In mm/memory_hotplug.c (ffff800010d9d064)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/migrate.c (ffff800010352ed4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffff800010359ad8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035f860)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffff800010365e78)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_oom_unregister_event
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
```
```
In mm/vmpressure.c (ffff80001036c5fc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
  - mm/vmpressure.c:vmpressure
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In mm/swap_cgroup.c (ffff80001036cc38)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/hugetlb_cgroup.c (ffff80001036d944)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffff800010370924)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_work_func
  - mm/memory-failure.c:memory_failure_queue
```
```
In mm/page_isolation.c (ffff800010372074)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zpool.c (ffff80001037294c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_get_driver
  - mm/zpool.c:zpool_unregister_driver
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zbud.c (ffff800010373418)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
  - mm/zbud.c:zbud_alloc
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffff8000103747e8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffff800010377690)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_putback
  - mm/balloon_compaction.c:balloon_page_isolate
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
```
```
In mm/userfaultfd.c (ffff800010378c60)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/page_idle.c (ffff800010379174)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (ffff80001037aff8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_unregister
  - mm/hmm.c:hmm_range_register
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_invalidate_range_start
  - mm/hmm.c:notifiers_decrement
```
```
In mm/memfd.c (ffff80001037bec8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/read_write.c (ffff80001037f9f4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In fs/super.c (ffff8000103887d4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/super.c:user_get_super
  - fs/super.c:user_get_super
  - fs/super.c:get_active_super
  - fs/super.c:__get_super_thawed
  - fs/super.c:get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/super.c:generic_shutdown_super
  - fs/super.c:put_super
```
```
In fs/char_dev.c (ffff800010389d08)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
```
In fs/stat.c (ffff80001038a9e4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
  - fs/stat.c:inode_sub_bytes
  - fs/stat.c:inode_add_bytes
```
```
In fs/exec.c (ffff80001038c4e4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/pipe.c (ffff800010390e34)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:fifo_open
  - fs/pipe.c:put_pipe_info
```
```
In fs/namei.c (ffff80001039af78)
Location: arch/arm64/include/asm/cmpxchg.h:173
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
  - fs/namei.c:set_root
  - fs/namei.c:inode_permission
```
```
In fs/fcntl.c (ffff80001039d1f0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_modown
  - fs/fcntl.c:setfl
```
```
In fs/ioctl.c (ffff80001039e8ec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/dcache.c (ffff8000103a7070)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_rehash
  - fs/dcache.c:__d_lookup
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
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:d_find_any_alias
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:__lock_parent
  - fs/dcache.c:__lock_parent
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
  - fs/dcache.c:take_dentry_name_snapshot
```
```
In fs/inode.c (ffff8000103ad520)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/inode.c:__wait_on_freeing_inode
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:new_inode_pseudo
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
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
In fs/file.c (ffff8000103b17e4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
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
In fs/filesystems.c (ffff8000103b2ef4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/filesystems.c:unregister_filesystem
  - fs/filesystems.c:register_filesystem
```
```
In fs/namespace.c (ffff8000103b4dac)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:__arm64_sys_open_tree
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
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/xattr.c (ffff8000103bf960)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_list_add
  - fs/xattr.c:simple_xattr_list
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:simple_xattr_get
```
```
In fs/libfs.c (ffff8000103c1854)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/libfs.c:simple_pin_fs
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
In fs/fs-writeback.c (ffff8000103ca6b8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:inode_wait_for_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In fs/pnode.c (ffff8000103cc554)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (ffff8000103d1cd0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
```
```
In fs/fs_struct.c (ffff8000103d2c9c)
Location: arch/arm64/include/asm/cmpxchg.h:173
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
In fs/fs_pin.c (ffff8000103d4150)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
  - fs/fs_pin.c:pin_kill
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/buffer.c (ffff8000103d87f0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__bforget
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/block_dev.c (ffff8000103e2cd8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:bd_abort_claiming
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:nr_blockdev_pages
  - fs/block_dev.c:bdget
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/direct-io.c (ffff8000103e54d4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/proc_namespace.c (ffff8000103e79e0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/fsnotify.c (ffff8000103e8498)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/notify/notification.c (ffff8000103e8c4c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_add_event
```
```
In fs/notify/group.c (ffff8000103e9068)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
```
```
In fs/notify/mark.c (ffff8000103e95b4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_free_mark
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
```
```
In fs/notify/dnotify/dnotify.c (ffff8000103eb4ec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (ffff8000103ec684)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify.c (ffff8000103edcb0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffff8000103ee730)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_ioctl
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffff8000103f22d8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_remove
  - fs/eventpoll.c:ep_remove
```
```
In fs/signalfd.c (ffff8000103f3f58)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffff8000103f4950)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_poll
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_release
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_triggered
```
```
In fs/eventfd.c (ffff8000103f5f4c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_show_fdinfo
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/userfaultfd.c (ffff8000103f6f70)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_show_fdinfo
  - fs/userfaultfd.c:__wake_userfault
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
In fs/aio.c (ffff8000103fc18c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/aio.c:__arm64_sys_io_cancel
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_complete
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_nr_sub
  - fs/aio.c:free_ioctx_users
  - fs/aio.c:kiocb_set_cancel_fn
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_ring_mremap
```
```
In fs/io_uring.c (ffff800010402b7c)
Location: arch/arm64/include/asm/cmpxchg.h:173
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
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_send_recvmsg
  - fs/io_uring.c:io_cqring_add_event
```
```
In fs/dax.c (ffff800010409194)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
```
```
In fs/crypto/crypto.c (ffff80001040ab80)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In fs/crypto/hooks.c (ffff80001040cb70)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In fs/crypto/keyring.c (ffff80001040db50)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
```
```
In fs/crypto/keysetup.c (ffff80001040f178)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/crypto/keysetup_v1.c (ffff80001040f790)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffff8000104162e0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/locks.c:locks_start
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
In fs/mbcache.c (ffff800010425208)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/coredump.c (ffff800010428a08)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/drop_caches.c (ffff800010428f14)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/fhandle.c (ffff800010429648)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In fs/quota/dquot.c (ffff80001042f6c0)
Location: arch/arm64/include/asm/cmpxchg.h:173
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
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:unregister_quota_format
  - fs/quota/dquot.c:register_quota_format
```
```
In fs/proc/task_mmu.c (ffff800010439bc8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/inode.c (ffff80001043b71c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_entry_rundown
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/proc/base.c (ffff8000104420a4)
Location: arch/arm64/include/asm/cmpxchg.h:173
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
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/generic.c (ffff800010444508)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_register
```
```
In fs/proc/array.c (ffff800010444d38)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (ffff800010446a28)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffff800010449098)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffff80001044ad6c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
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
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/proc/proc_sysctl.c:insert_header
```
```
In fs/proc/proc_net.c (ffff80001044d058)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/kernfs/dir.c (ffff8000104529c8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_path_from_node
  - fs/kernfs/dir.c:kernfs_name
```
```
In fs/kernfs/file.c (ffff800010455280)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/sysfs/dir.c (ffff8000104572d8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/sysfs/dir.c:sysfs_remove_dir
```
```
In fs/sysfs/symlink.c (ffff80001045781c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_delete_link
```
```
In fs/sysfs/group.c (ffff8000104586c8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
```
```
In fs/configfs/inode.c (ffff800010458c88)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In fs/configfs/dir.c (ffff80001045ad34)
Location: arch/arm64/include/asm/cmpxchg.h:173
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
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_do_depend_item
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffff80001045d6f8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/dcookies.c (ffff80001045f2c0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/dcookies.c:dcookie_unregister
  - fs/dcookies.c:get_dcookie
```
```
In fs/ext4/balloc.c (ffff8000104609f8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffff800010464a20)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (ffff8000104702e0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/ialloc.c (ffff800010473d84)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In fs/ext4/inode.c (ffff80001047fb4c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffff80001048f7e4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/migrate.c (ffff80001049837c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
```
```
In fs/ext4/page-io.c (ffff8000104a36ec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/super.c (ffff8000104b843c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_init_journal_params
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_journal_commit_callback
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (ffff8000104ccc40)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_unlock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
```
```
In fs/jbd2/commit.c (ffff8000104ce0dc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
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
In fs/jbd2/checkpoint.c (ffff8000104d1c40)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/revoke.c (ffff8000104d2604)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/jbd2/journal.c (ffff8000104d5414)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_ack_err
  - fs/jbd2/journal.c:jbd2_journal_clear_err
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_log_start_commit
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/squashfs/cache.c (ffff8000104da4f0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_put
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
```
```
In fs/hugetlbfs/inode.c (ffff8000104e2b40)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
```
```
In fs/fat/cache.c (ffff8000104e3264)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fat/dir.c (ffff8000104e623c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/fat/fatent.c (ffff8000104e9088)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_get
```
```
In fs/fat/inode.c (ffff8000104ecc74)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (ffff8000104efa48)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In fs/fat/namei_vfat.c (ffff8000104f020c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/exportfs/expfs.c (ffff8000104fece8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In fs/nls/nls_base.c (ffff8000104ff73c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/nls/nls_base.c:find_nls
  - fs/nls/nls_base.c:unregister_nls
```
```
In fs/fuse/dev.c (ffff800010503128)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_dev_poll
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:flush_bg_queue
  - fs/fuse/dev.c:fuse_queue_forget
```
```
In fs/fuse/dir.c (ffff8000105095b8)
Location: arch/arm64/include/asm/cmpxchg.h:173
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
In fs/fuse/file.c (ffff8000105105c0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_notify_poll_wakeup
  - fs/fuse/file.c:fuse_file_poll
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
In fs/fuse/inode.c (ffff8000105124b0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_dev_install
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/control.c (ffff800010513924)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_max_background_write
```
```
In fs/fuse/readdir.c (ffff8000105152b8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:fuse_emit
  - fs/fuse/readdir.c:fuse_emit
```
```
In fs/debugfs/inode.c (ffff800010516618)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In fs/tracefs/inode.c (ffff800010519b58)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
```
```
In fs/pstore/inode.c (ffff80001051a458)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
```
In fs/pstore/platform.c (ffff80001051ad58)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
```
```
In ipc/util.c (ffff80001051dcbc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (ffff80001051f948)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
```
```
In ipc/sem.c (ffff800010525858)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
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
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_down
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:freeary
```
```
In ipc/shm.c (ffff8000105286a4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:shmctl_down
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffff80001052a8b4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
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
```
```
In ipc/namespace.c (ffff80001052ca0c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:free_ipcs
```
```
In security/keys/gc.c (ffff80001052d454)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffff80001052eef4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
  - security/keys/key.c:key_payload_reserve
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/keys/keyring.c (ffff8000105302c0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/keys/keyctl.c (ffff800010533ad8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/keys/proc.c (ffff80001053787c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_start
```
```
In security/selinux/avc.c (ffff800010546f00)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_ss_reset
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
```
```
In security/selinux/hooks.c (ffff80001054e6e8)
Location: arch/arm64/include/asm/cmpxchg.h:173
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
In security/selinux/netif.c (ffff800010557e4c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffff8000105586b8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffff800010558ac8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ibpkey.c (ffff800010558eb8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/selinux/ss/sidtab.c (ffff80001055b2c8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In security/selinux/ss/services.c (ffff800010567014)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/smack/smack_lsm.c (ffff80001056f440)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/tomoyo/audit.c (ffff80001057889c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_read_log
  - security/tomoyo/audit.c:tomoyo_write_log2
```
```
In security/tomoyo/common.c (ffff80001057d758)
Location: arch/arm64/include/asm/cmpxchg.h:173
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
In security/tomoyo/gc.c (ffff8000105836b0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/apparmorfs.c (ffff80001058d170)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_read
```
```
In security/apparmor/path.c (ffff800010591408)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In security/apparmor/secid.c (ffff80001059eeac)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/apparmor/secid.c:aa_alloc_secid
```
```
In security/apparmor/file.c (ffff8000105a0438)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
```
```
In security/apparmor/policy_ns.c (ffff8000105a10d4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In security/apparmor/label.c (ffff8000105a2b5c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_remove
```
```
In security/apparmor/af_unix.c (ffff8000105a97b0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In security/yama/yama_lsm.c (ffff8000105aaa64)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/integrity/iint.c (ffff8000105ac8b8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
```
```
In security/integrity/ima/ima_template.c (ffff8000105b3108)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In crypto/scompress.c (ffff8000105c5154)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - crypto/scompress.c:scomp_acomp_comp_decomp
```
```
In crypto/jitterentropy-kcapi.c (ffff8000105d3d58)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_kcapi_random
  - crypto/jitterentropy-kcapi.c:jent_kcapi_cleanup
```
```
In block/bio.c (ffff8000105dd7a4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/elevator.c (ffff8000105df2e0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elv_register
```
```
In block/blk-sysfs.c (ffff8000105e6954)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_max_sectors_store
```
```
In block/blk-flush.c (ffff8000105e7310)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffff8000105e8fb4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:ioc_clear_queue
  - block/blk-ioc.c:ioc_clear_queue
  - block/blk-ioc.c:exit_io_context
  - block/blk-ioc.c:ioc_release_fn
  - block/blk-ioc.c:ioc_release_fn
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-mq.c (ffff8000105f1eb4)
Location: arch/arm64/include/asm/cmpxchg.h:173
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
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-stat.c (ffff8000105f4f68)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-stat.c:blk_stat_add_callback
```
```
In block/blk-mq-sched.c (ffff8000105f700c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
```
In block/genhd.c (ffff8000105fa8ec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:disk_clear_events
  - block/genhd.c:disk_clear_events
  - block/genhd.c:disk_flush_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:disk_block_events
  - block/genhd.c:get_gendisk
```
```
In block/ioprio.c (ffff8000105fdd5c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In block/badblocks.c (ffff8000105fee7c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
  - block/badblocks.c:badblocks_set
```
```
In block/bsg.c (ffff80001060a51c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
```
```
In block/blk-cgroup.c (ffff80001060e714)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkcg_can_attach
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_destroy_all
  - block/blk-cgroup.c:blkg_destroy_all
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffff800010612ff0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/blk-iocost.c (ffff8000106161f8)
Location: arch/arm64/include/asm/cmpxchg.h:173
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
  - block/blk-iocost.c:ioc_pd_init
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
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
```
In block/mq-deadline.c (ffff8000106196e4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_dispatch_start
  - block/mq-deadline.c:deadline_write_fifo_start
  - block/mq-deadline.c:deadline_read_fifo_start
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_bio_merge
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-mq-debugfs.c (ffff800010623a30)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:ctx_poll_rq_list_start
  - block/blk-mq-debugfs.c:ctx_read_rq_list_start
  - block/blk-mq-debugfs.c:ctx_default_rq_list_start
  - block/blk-mq-debugfs.c:hctx_dispatch_start
  - block/blk-mq-debugfs.c:queue_requeue_list_start
```
```
In block/blk-pm.c (ffff800010628974)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/lockref.c (ffff800010629100)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In lib/random32.c (ffff80001062a400)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - lib/random32.c:__prandom_reseed
```
```
In lib/percpu-refcount.c (ffff8000106355f8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In lib/rhashtable.c (ffff8000106366bc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_walk_stop
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_exit
  - lib/rhashtable.c:rhashtable_walk_enter
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/once.c (ffff80001063761c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - lib/once.c:__do_once_start
```
```
In lib/refcount.c (ffff8000106379e0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In lib/genalloc.c (ffff8000106448d4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (ffff80001065e6c8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
  - lib/textsearch.c:textsearch_register
```
```
In lib/percpu_counter.c (ffff80001065ea20)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
  - lib/percpu_counter.c:percpu_counter_cpu_dead
  - lib/percpu_counter.c:__percpu_counter_init
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_add_batch
  - lib/percpu_counter.c:percpu_counter_set
```
```
In lib/sbitmap.c (ffff800010669c34)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In drivers/irqchip/irq-al-fic.c (ffff80001066a718)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (ffff80001066b0b0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_resume
```
```
In drivers/irqchip/irq-sunxi-nmi.c (ffff80001066b508)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_set_type
```
```
In drivers/irqchip/irq-gic-common.c (ffff80001066cf28)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-common.c:gic_configure_irq
```
```
In drivers/irqchip/irq-gic-v2m.c (ffff80001066d4d4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010674ae8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_save_disable
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_send_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_msi_prepare
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_vcommand
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_command
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff800010676e0c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_set_affinity
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_mask
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_unmask
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_irq_handle
```
```
In drivers/irqchip/irq-brcmstb-l2.c (ffff80001067752c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_resume
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_suspend
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_irq_handle
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_mask_and_ack
```
```
In drivers/irqchip/irq-mtk-sysirq.c (ffff800010677d38)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_set_type
```
```
In drivers/irqchip/irq-imx-gpcv2.c (ffff80001067894c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_mask
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_unmask
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_set_wake
```
```
In drivers/irqchip/irq-mvebu-gicp.c (ffff800010678e60)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-gicp.c:gicp_irq_domain_free
  - drivers/irqchip/irq-mvebu-gicp.c:gicp_irq_domain_alloc
  - drivers/irqchip/irq-mvebu-gicp.c:gicp_irq_domain_alloc
```
```
In drivers/irqchip/irq-mvebu-odmi.c (ffff8000106799c8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-odmi.c:odmi_irq_domain_free
  - drivers/irqchip/irq-mvebu-odmi.c:odmi_irq_domain_alloc
  - drivers/irqchip/irq-mvebu-odmi.c:odmi_irq_domain_alloc
```
```
In drivers/irqchip/irq-mvebu-sei.c (ffff80001067ae20)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_unmask_irq
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_mask_irq
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067b8d0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_domain_irq_free
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_domain_irq_alloc
```
```
In drivers/irqchip/irq-meson-gpio.c (ffff80001067c918)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc
```
```
In drivers/irqchip/qcom-pdc.c (ffff80001067d278)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In drivers/irqchip/irq-imx-irqsteer.c (ffff80001067dbac)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_mask
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_unmask
```
```
In drivers/bus/hisi_lpc.c (ffff80001067f888)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/bus/hisi_lpc.c:hisi_lpc_target_out
  - drivers/bus/hisi_lpc.c:hisi_lpc_target_in
```
```
In drivers/bus/fsl-mc/mc-sys.c (ffff800010681338)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/mc-sys.c:mc_send_command
```
```
In drivers/pinctrl/pinctrl-amd.c (ffff800010693e70)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff80001069b238)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set_config
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set
  - drivers/pinctrl/pinctrl-rockchip.c:_rockchip_pmx_gpio_set_direction
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069db20)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_handle
  - drivers/pinctrl/pinctrl-single.c:pcs_set_mux
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (ffff8000106a1df8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_ack
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_unmask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask
  - drivers/pinctrl/actions/pinctrl-owl.c:irq_set_type
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_input
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_get
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_free
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_request
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_set_mux
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (ffff8000106a3ef4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_disable
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_enable
```
```
In drivers/pinctrl/bcm/pinctrl-iproc-gpio.c (ffff8000106a6108)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_pin_config_set
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_pin_config_get
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_get_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_direction_output
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_direction_input
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_unmask
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_mask
```
```
In drivers/pinctrl/bcm/pinctrl-ns2-mux.c (ffff8000106a7408)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_get_pull
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_set_pull
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_enable
```
```
In drivers/pinctrl/mvebu/pinctrl-armada-37xx.c (ffff8000106ac310)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_set_type
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_set_wake
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_unmask
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_mask
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_ack
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106add3c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_wake
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_ack
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_clear_unmask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_mask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_output
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_input
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_set_mux
```
```
In drivers/pinctrl/sh-pfc/pinctrl.c (ffff8000106b13ec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_set_direction
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_disable_free
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_request_enable
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_func_set_mux
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b56a0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_unmask
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_mask
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_set_type
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_gpio_set
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_request
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_set
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pconf_set
```
```
In drivers/gpio/gpiolib.c (ffff8000106bff74)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_next
  - drivers/gpio/gpiolib.c:gpiolib_seq_start
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_find
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-sysfs.c (ffff8000106c9854)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
```
In drivers/gpio/gpio-mmio.c (ffff8000106cd270)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_dir_out
  - drivers/gpio/gpio-mmio.c:bgpio_dir_in
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_single_reg
  - drivers/gpio/gpio-mmio.c:bgpio_set_set
  - drivers/gpio/gpio-mmio.c:bgpio_set
```
```
In drivers/gpio/gpio-davinci.c (ffff8000106ce4b8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/gpio/gpio-davinci.c:davinci_direction_out
  - drivers/gpio/gpio-davinci.c:davinci_direction_in
```
```
In drivers/gpio/gpio-mpc8xxx.c (ffff8000106cf9bc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/gpio/gpio-mpc8xxx.c:mpc512x_irq_set_type
  - drivers/gpio/gpio-mpc8xxx.c:mpc512x_irq_set_type
  - drivers/gpio/gpio-mpc8xxx.c:mpc512x_irq_set_type
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_irq_set_type
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_irq_set_type
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_irq_mask
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_irq_unmask
  - drivers/gpio/gpio-mpc8xxx.c:ls1028a_gpio_dir_in_init
```
```
In drivers/gpio/gpio-mvebu.c (ffff8000106d144c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_apply
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_get_state
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_free
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_request
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_level_irq_unmask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_level_irq_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_edge_irq_unmask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_edge_irq_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_ack
```
```
In drivers/gpio/gpio-pl061.c (ffff8000106d3338)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_irq_ack
  - drivers/gpio/gpio-pl061.c:pl061_irq_unmask
  - drivers/gpio/gpio-pl061.c:pl061_irq_mask
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_direction_output
  - drivers/gpio/gpio-pl061.c:pl061_direction_input
```
```
In drivers/gpio/gpio-xgene.c (ffff8000106d6954)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/gpio/gpio-xgene.c:xgene_gpio_dir_out
  - drivers/gpio/gpio-xgene.c:xgene_gpio_dir_in
  - drivers/gpio/gpio-xgene.c:xgene_gpio_set
```
```
In drivers/gpio/gpio-xilinx.c (ffff8000106d73a0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_out
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_in
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set
```
```
In drivers/pci/access.c (ffff8000106db908)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_cfg_access_unlock
  - drivers/pci/access.c:pci_cfg_access_trylock
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
  - drivers/pci/access.c:pci_wait_cfg
  - drivers/pci/access.c:pci_bus_set_ops
  - drivers/pci/access.c:pci_bus_write_config_dword
  - drivers/pci/access.c:pci_bus_write_config_word
  - drivers/pci/access.c:pci_bus_write_config_byte
  - drivers/pci/access.c:pci_bus_read_config_dword
  - drivers/pci/access.c:pci_bus_read_config_word
  - drivers/pci/access.c:pci_bus_read_config_byte
```
```
In drivers/pci/pci.c (ffff8000106e55b8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci.c:resource_alignment_show
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
```
```
In drivers/pci/pci-driver.c (ffff8000106ebf68)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:pci_add_dynid
```
```
In drivers/pci/pcie/aer.c (ffff80001070482c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffff800010706014)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_irq
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffff80001071b510)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_linkup
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/pcie-xilinx-nwl.c (ffff800010724508)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_unmask_leg_irq
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_mask_leg_irq
```
```
In drivers/pci/controller/pcie-mobiveil.c (ffff80001072c060)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_unmask_intx_irq
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_mask_intx_irq
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072e960)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff800010732a5c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_unmask
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_mask
```
```
In drivers/rapidio/rio.c (ffff80001073d6fc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_get_asm
  - drivers/rapidio/rio.c:rio_get_comptag
  - drivers/rapidio/rio.c:rio_map_outb_region
  - drivers/rapidio/rio.c:rio_map_inb_region
  - drivers/rapidio/rio.c:rio_release_inb_pwrite
  - drivers/rapidio/rio.c:rio_request_inb_pwrite
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
```
```
In drivers/video/fbdev/mx3fb.c (ffff8000107609d4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_disable_channel
  - drivers/video/fbdev/mx3fb.c:sdc_enable_channel
```
```
In drivers/acpi/osl.c (ffff80001076436c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_acquire_lock
```
```
In drivers/acpi/ec.c (ffff800010770a58)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_enter_noirq
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_stopped
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/ec.c:ec_transaction_completed
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/acpi/apei/erst.c (ffff8000107addec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
```
In drivers/acpi/apei/ghes.c (ffff8000107b065c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_sdei_critical_callback
  - drivers/acpi/apei/ghes.c:ghes_sdei_normal_callback
  - drivers/acpi/apei/ghes.c:ghes_notify_sea
  - drivers/acpi/apei/ghes.c:ghes_notify_hed
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
```
In drivers/acpi/arm64/iort.c (ffff8000107b2518)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/acpi/arm64/iort.c:iort_iommu_msi_get_resv_regions
  - drivers/acpi/arm64/iort.c:iort_iommu_msi_get_resv_regions
  - drivers/acpi/arm64/iort.c:iort_find_domain_token
  - drivers/acpi/arm64/iort.c:iort_deregister_domain_token
  - drivers/acpi/arm64/iort.c:iort_register_domain_token
```
```
In drivers/clk/clk.c (ffff8000107bf9f4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_enable_lock
  - drivers/clk/clk.c:clk_enable_lock
```
```
In drivers/clk/clk-divider.c (ffff8000107c4718)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_set_rate
```
```
In drivers/clk/clk-gate.c (ffff8000107c5724)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/clk-gate.c:clk_gate_endisable
```
```
In drivers/clk/clk-multiplier.c (ffff8000107c5ae8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
```
```
In drivers/clk/clk-mux.c (ffff8000107c62e0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
```
In drivers/clk/clk-fractional-divider.c (ffff8000107c7118)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
```
```
In drivers/clk/clk-xgene.c (ffff8000107c94ec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/clk-xgene.c:xgene_clk_set_rate
  - drivers/clk/clk-xgene.c:xgene_clk_disable
  - drivers/clk/clk-xgene.c:xgene_clk_enable
  - drivers/clk/clk-xgene.c:xgene_clk_pmd_set_rate
  - drivers/clk/clk-xgene.c:xgene_clk_pmd_recalc_rate
```
```
In drivers/clk/bcm/clk-bcm2835.c (ffff8000107ce09c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_set_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_off
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_off
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_set_rate
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_off
```
```
In drivers/clk/berlin/berlin2-div.c (ffff8000107cf5e4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_recalc_rate
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_get_parent
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_set_parent
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_disable
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_enable
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_is_enabled
```
```
In drivers/clk/hisilicon/clkgate-separated.c (ffff8000107d0200)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_disable
  - drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_enable
```
```
In drivers/clk/hisilicon/clkdivider-hi6220.c (ffff8000107d05f0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clkdivider-hi6220.c:hi6220_clkdiv_set_rate
```
```
In drivers/clk/hisilicon/clk-hisi-phase.c (ffff8000107d0a4c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk-hisi-phase.c:hisi_clk_set_phase
```
```
In drivers/clk/hisilicon/reset.c (ffff8000107d13f8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/hisilicon/reset.c:hisi_reset_deassert
  - drivers/clk/hisilicon/reset.c:hisi_reset_assert
```
```
In drivers/clk/imx/clk-composite-8m.c (ffff8000107d248c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/imx/clk-composite-8m.c:imx8m_clk_composite_divider_set_rate
```
```
In drivers/clk/imx/clk-divider-gate.c (ffff8000107d2e20)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_disable
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_set_rate
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_recalc_rate
```
```
In drivers/clk/imx/clk-fixup-div.c (ffff8000107d33bc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/imx/clk-fixup-div.c:clk_fixup_div_set_rate
```
```
In drivers/clk/imx/clk-fixup-mux.c (ffff8000107d3668)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/imx/clk-fixup-mux.c:clk_fixup_mux_set_parent
```
```
In drivers/clk/imx/clk-gate2.c (ffff8000107d3f80)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/imx/clk-gate2.c:clk_gate2_disable_unused
  - drivers/clk/imx/clk-gate2.c:clk_gate2_disable
  - drivers/clk/imx/clk-gate2.c:clk_gate2_enable
```
```
In drivers/clk/imx/clk-pfdv2.c (ffff8000107d4958)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_set_rate
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_disable
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable
```
```
In drivers/clk/imx/clk-lpcg-scu.c (ffff8000107d76d0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/imx/clk-lpcg-scu.c:clk_lpcg_scu_disable
  - drivers/clk/imx/clk-lpcg-scu.c:clk_lpcg_scu_enable
```
```
In drivers/clk/mediatek/clk-mux.c (ffff8000107e3650)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_setclr_lock
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_lock
```
```
In drivers/clk/meson/clk-mpll.c (ffff8000107e6cf8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/meson/clk-mpll.c:mpll_set_rate
```
```
In drivers/clk/renesas/r9a06g032-clocks.c (ffff8000107eaaa8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_set
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_set
```
```
In drivers/clk/renesas/rcar-gen3-cpg.c (ffff8000107eb02c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-gen3-cpg.c:cpg_reg_modify
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (ffff8000107ec234)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_endisable
```
```
In drivers/clk/rockchip/clk-cpu.c (ffff8000107ee6d4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
```
```
In drivers/clk/rockchip/clk-half-divider.c (ffff8000107eef24)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-half-divider.c:clk_half_divider_set_rate
```
```
In drivers/clk/rockchip/clk-inverter.c (ffff8000107ef358)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-inverter.c:rockchip_inv_set_phase
```
```
In drivers/clk/rockchip/clk-ddr.c (ffff8000107efdc4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-ddr.c:rockchip_ddrclk_sip_set_rate
```
```
In drivers/clk/rockchip/softrst.c (ffff8000107f0080)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/rockchip/softrst.c:rockchip_softrst_deassert
  - drivers/clk/rockchip/softrst.c:rockchip_softrst_assert
```
```
In drivers/clk/sunxi/clk-factors.c (ffff8000107f146c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-factors.c:clk_factors_set_rate
```
```
In drivers/clk/sunxi/clk-a10-ve.c (ffff8000107f2330)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-a10-ve.c:sunxi_ve_reset_deassert
  - drivers/clk/sunxi/clk-a10-ve.c:sunxi_ve_reset_assert
```
```
In drivers/clk/sunxi/clk-mod0.c (ffff8000107f2698)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-mod0.c:mmc_set_phase
```
```
In drivers/clk/sunxi/clk-sun4i-display.c (ffff8000107f2960)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_deassert
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_assert
```
```
In drivers/clk/sunxi/clk-sun4i-tcon-ch1.c (ffff8000107f2c5c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_set_rate
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_set_parent
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_enable
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_disable
```
```
In drivers/clk/sunxi/clk-sun9i-mmc.c (ffff8000107f3754)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_deassert
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_assert
```
```
In drivers/clk/sunxi/clk-usb.c (ffff8000107f3b10)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_deassert
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_assert
```
```
In drivers/clk/sunxi/clk-sun9i-cpus.c (ffff8000107f4208)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-cpus.c:sun9i_a80_cpus_clk_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_mmc_timing.c (ffff8000107f4bbc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mmc_timing.c:sunxi_ccu_set_mmc_timing_mode
```
```
In drivers/clk/sunxi-ng/ccu_reset.c (ffff8000107f4e9c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_reset.c:ccu_reset_deassert
  - drivers/clk/sunxi-ng/ccu_reset.c:ccu_reset_assert
```
```
In drivers/clk/sunxi-ng/ccu_div.c (ffff8000107f5220)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_div.c:ccu_div_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_frac.c (ffff8000107f5818)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_set_rate
  - drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_disable
  - drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_enable
```
```
In drivers/clk/sunxi-ng/ccu_gate.c (ffff8000107f5ad0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_mux.c (ffff8000107f645c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_helper_set_parent
```
```
In drivers/clk/sunxi-ng/ccu_mult.c (ffff8000107f691c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_phase.c (ffff8000107f6bd8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_phase.c:ccu_phase_set_phase
```
```
In drivers/clk/sunxi-ng/ccu_sdm.c (ffff8000107f7094)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_disable
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_disable
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_enable
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_enable
```
```
In drivers/clk/sunxi-ng/ccu_nk.c (ffff8000107f77d0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nk.c:ccu_nk_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_nkm.c (ffff8000107f7ea4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_nkmp.c (ffff8000107f868c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nkmp.c:ccu_nkmp_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_nm.c (ffff8000107f8e00)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_set_rate
  - drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_mp.c (ffff8000107f9628)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_set_rate
```
```
In drivers/clk/versatile/clk-sp810.c (ffff8000107fa048)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clk/versatile/clk-sp810.c:clk_sp810_timerclken_set_parent
```
```
In drivers/dma/dmaengine.c (ffff8000107fcfc0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_run_dependencies
```
```
In drivers/dma/virt-dma.c (ffff8000107fe6dc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_complete
  - drivers/dma/virt-dma.c:vchan_tx_desc_free
  - drivers/dma/virt-dma.c:vchan_tx_submit
```
```
In drivers/dma/amba-pl08x.c (ffff800010800670)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_debugfs_show
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/amba-pl08x.c:pl08x_resume
  - drivers/dma/amba-pl08x.c:pl08x_pause
  - drivers/dma/amba-pl08x.c:pl08x_synchronize
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_prep_dma_cyclic
  - drivers/dma/amba-pl08x.c:pl08x_prep_slave_sg
  - drivers/dma/amba-pl08x.c:pl08x_prep_dma_memcpy
  - drivers/dma/amba-pl08x.c:pl08x_issue_pending
  - drivers/dma/amba-pl08x.c:pl08x_issue_pending
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
  - drivers/dma/amba-pl08x.c:pl08x_phy_free
```
```
In drivers/dma/bcm2835-dma.c (ffff800010804b98)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_synchronize
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_dma_cyclic
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_slave_sg
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_dma_memcpy
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_issue_pending
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_callback
```
```
In drivers/dma/mv_xor.c (ffff800010806cd8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_status
  - drivers/dma/mv_xor.c:mv_xor_free_chan_resources
  - drivers/dma/mv_xor.c:mv_xor_prep_dma_xor
  - drivers/dma/mv_xor.c:mv_xor_alloc_chan_resources
  - drivers/dma/mv_xor.c:mv_xor_tx_submit
  - drivers/dma/mv_xor.c:mv_xor_tasklet
```
```
In drivers/dma/mv_xor_v2.c (ffff800010808574)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_tasklet
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_issue_pending
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_prep_sw_desc
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_tx_submit
```
```
In drivers/dma/ipu/ipu_irq.c (ffff80001080a3c4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_handler
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_handler
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_unmap
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_map
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_status
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_ack
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_mask
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_unmask
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080d128)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
  - drivers/dma/ipu/ipu_idmac.c:idmac_pause
  - drivers/dma/ipu/ipu_idmac.c:idmac_issue_pending
  - drivers/dma/ipu/ipu_idmac.c:idmac_prep_slave_sg
  - drivers/dma/ipu/ipu_idmac.c:ipu_gc_tasklet
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
```
```
In drivers/soc/fsl/qbman/bman_portal.c (ffff800010810f20)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe
```
```
In drivers/soc/fsl/qbman/qman_portal.c (ffff8000108114fc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe
```
```
In drivers/soc/fsl/qbman/bman.c (ffff800010812388)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman.c:bman_create_affine_portal
```
```
In drivers/soc/fsl/qbman/qman.c (ffff8000108144ac)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_delete_cgr
  - drivers/soc/fsl/qbman/qman.c:qman_create_cgr
  - drivers/soc/fsl/qbman/qman.c:qm_congestion_task
  - drivers/soc/fsl/qbman/qman.c:qman_destroy_affine_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_affine_portal
```
```
In drivers/soc/qcom/rpmh-rsc.c (ffff80001081c7e0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_write_ctrl_data
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_send_data
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_send_data
  - drivers/soc/qcom/rpmh-rsc.c:tcs_tx_done
  - drivers/soc/qcom/rpmh-rsc.c:tcs_invalidate
```
```
In drivers/soc/qcom/rpmh.c (ffff80001081cf60)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh.c:rpmh_invalidate
  - drivers/soc/qcom/rpmh.c:rpmh_flush
  - drivers/soc/qcom/rpmh.c:rpmh_write_batch
  - drivers/soc/qcom/rpmh.c:__rpmh_write
```
```
In drivers/soc/renesas/rcar-sysc.c (ffff80001081e21c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
```
```
In drivers/soc/sunxi/sunxi_sram.c (ffff80001081fcb8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_release
  - drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_claim
```
```
In drivers/virtio/virtio.c (ffff8000108216f0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_device_freeze
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_changed
```
```
In drivers/virtio/virtio_mmio.c (ffff800010826094)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_mmio.c:vm_interrupt
```
```
In drivers/virtio/virtio_pci_common.c (ffff8000108286c0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_setup_vq
  - drivers/virtio/virtio_pci_common.c:vp_vring_interrupt
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082a8fc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/xen/grant-table.c (ffff80001082d4c0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_cancel_free_callback
  - drivers/xen/grant-table.c:gnttab_request_free_callback
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/xen/grant-table.c:put_free_entry
  - drivers/xen/grant-table.c:get_free_entries
```
```
In drivers/xen/events/events_2l.c (ffff800010833154)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/xen/xenbus/xenbus_client.c (ffff800010835600)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffff8000108365bc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xs_request_exit
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend_exit
```
```
In drivers/reset/reset-meson.c (ffff80001084d9e0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/reset/reset-meson.c:meson_reset_level
```
```
In drivers/reset/reset-simple.c (ffff80001084de38)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/reset/reset-simple.c:reset_simple_update
```
```
In drivers/tty/tty_io.c (ffff80001085253c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:redirected_tty_write
  - drivers/tty/tty_io.c:start_tty
  - drivers/tty/tty_io.c:stop_tty
  - drivers/tty/tty_io.c:check_tty_count
  - drivers/tty/tty_io.c:tty_add_file
```
```
In drivers/tty/n_tty.c (ffff800010856bd4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffff80001085b968)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In drivers/tty/tty_ldisc.c (ffff80001085bf58)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/tty_ldisc.c:tty_unregister_ldisc
  - drivers/tty/tty_ldisc.c:tty_register_ldisc
```
```
In drivers/tty/tty_port.c (ffff80001085ee94)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_ldsem.c (ffff800010da6d34)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
```
In drivers/tty/tty_jobctrl.c (ffff800010860c38)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:proc_clear_tty
```
```
In drivers/tty/pty.c (ffff800010862988)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_set_termios
  - drivers/tty/pty.c:pty_flush_buffer
  - drivers/tty/pty.c:pty_set_pktmode
  - drivers/tty/pty.c:pty_write
  - drivers/tty/pty.c:pty_close
```
```
In drivers/tty/sysrq.c (ffff80001086432c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
```
```
In drivers/tty/vt/vt_ioctl.c (ffff8000108668d8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:__vt_event_dequeue
  - drivers/tty/vt/vt_ioctl.c:__vt_event_queue
```
```
In drivers/tty/vt/vc_screen.c (ffff8000108679c4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffff80001086f094)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_clr_kbd_mode_bit
  - drivers/tty/vt/keyboard.c:vt_set_kbd_mode_bit
  - drivers/tty/vt/keyboard.c:vt_reset_keyboard
  - drivers/tty/vt/keyboard.c:vt_reset_keyboard
  - drivers/tty/vt/keyboard.c:vt_reset_unicode
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdskbmeta
  - drivers/tty/vt/keyboard.c:vt_do_kdskbmode
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_bh
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_get_leds
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/keyboard.c:compute_shiftstate
```
```
In drivers/tty/vt/vt.c (ffff8000108743e0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/tty/hvc/hvc_console.c (ffff80001087a234)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_port_destruct
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/hvc/hvc_xen.c (ffff80001087c0f8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/hvc/hvc_xen.c:xen_pv_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
```
In drivers/tty/serial/serial_core.c (ffff800010882618)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_tiocmget
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_change_speed
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_update_mctrl
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/tty/serial/8250/8250_core.c (ffff800010884abc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
  - drivers/tty/serial/8250/8250_core.c:serial8250_interrupt
```
```
In drivers/tty/serial/8250/8250_port.c (ffff80001088b1ec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
```
```
In drivers/tty/serial/8250/8250_dma.c (ffff80001088c094)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088fd08)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
```
```
In drivers/tty/serial/8250/8250_fsl.c (ffff800010890880)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff80001089112c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_handle_irq
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff8000108926e0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
```
```
In drivers/tty/serial/amba-pl011.c (ffff800010896f74)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:sbsa_uart_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_disable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_break_ctl
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_callback
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_callback
```
```
In drivers/tty/serial/imx.c (ffff80001089b16c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_suspend_noirq
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_timeout
  - drivers/tty/serial/imx.c:imx_uart_break_ctl
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_rxint
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_rtsint
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
```
```
In drivers/tty/serial/meson_uart.c (ffff80001089ec0c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_serial_port_write
  - drivers/tty/serial/meson_uart.c:meson_serial_port_write
  - drivers/tty/serial/meson_uart.c:meson_uart_set_termios
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_shutdown
```
```
In drivers/tty/serial/sccnxp.c (ffff8000108a0a8c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_get_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_tx_empty
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_ist
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a3238)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
```
```
In drivers/tty/serial/mvebu-uart.c (ffff8000108a5e8c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_break_ctl
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_tx_empty
```
```
In drivers/tty/serial/owl-uart.c (ffff8000108a6ee4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
  - drivers/tty/serial/owl-uart.c:owl_uart_set_termios
  - drivers/tty/serial/owl-uart.c:owl_uart_shutdown
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_tx_empty
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffff8000108a7e54)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
```
In drivers/char/random.c (ffff8000108ac7f4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:_crng_backtrack_protect
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_fast_load
  - drivers/char/random.c:mix_pool_bytes
```
```
In drivers/char/ttyprintk.c (ffff8000108b1e28)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
```
```
In drivers/char/virtio_console.c (ffff8000108b5798)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:port_has_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
  - drivers/char/virtio_console.c:find_port_by_vq
  - drivers/char/virtio_console.c:find_port_by_id
  - drivers/char/virtio_console.c:find_port_by_vtermno
```
```
In drivers/iommu/iommu.c (ffff8000108c76b0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_ops_from_fwnode
  - drivers/iommu/iommu.c:iommu_device_unregister
  - drivers/iommu/iommu.c:iommu_device_register
```
```
In drivers/iommu/iova.c (ffff8000108ce3f0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_cpu_cached_iovas
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_insert
  - drivers/iommu/iova.c:iova_rcache_insert
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:__free_iova
  - drivers/iommu/iova.c:find_iova
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d18a0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard
  - drivers/iommu/arm-smmu.c:arm_smmu_tlb_sync_context
  - drivers/iommu/arm-smmu.c:arm_smmu_tlb_sync_global
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d6278)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_attach_dev
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_detach_dev
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d9860)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_attach_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_detach_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_unmap
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/rockchip-iommu.c:rk_iommu_zap_iova
  - drivers/iommu/rockchip-iommu.c:rk_iommu_iova_to_phys
```
```
In drivers/iommu/qcom_iommu.c (ffff8000108db244)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_iova_to_phys
  - drivers/iommu/qcom_iommu.c:qcom_iommu_unmap
  - drivers/iommu/qcom_iommu.c:qcom_iommu_map
```
```
In drivers/iommu/virtio-iommu.c (ffff8000108dbda4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_iotlb_sync
  - drivers/iommu/virtio-iommu.c:viommu_iova_to_phys
  - drivers/iommu/virtio-iommu.c:viommu_unmap
  - drivers/iommu/virtio-iommu.c:viommu_map
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_del_mappings
  - drivers/iommu/virtio-iommu.c:viommu_send_req_sync
```
```
In drivers/connector/cn_queue.c (ffff8000108dd6b8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffff8000108ddc38)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/base/core.c (ffff8000108e72d0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffff8000108e92e4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffff8000108eb608)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_detach
```
```
In drivers/base/platform.c (ffff8000108ee514)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_driver_probe
```
```
In drivers/base/devres.c (ffff8000108f0214)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_release_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_close_group
  - drivers/base/devres.c:devres_open_group
  - drivers/base/devres.c:devres_release_all
  - drivers/base/devres.c:devres_remove
  - drivers/base/devres.c:devres_get
  - drivers/base/devres.c:devres_find
  - drivers/base/devres.c:devres_add
```
```
In drivers/base/attribute_container.c (ffff8000108f1308)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/base/attribute_container.c:attribute_container_unregister
```
```
In drivers/base/swnode.c (ffff8000108f5dec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_to_swnode
```
```
In drivers/base/devtmpfs.c (ffff8000108f7060)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
```
In drivers/base/power/sysfs.c (ffff8000108f7d20)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In drivers/base/power/common.c (ffff8000108f940c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
  - drivers/base/power/common.c:dev_pm_get_subsys_data
```
```
In drivers/base/power/qos.c (ffff8000108fa9bc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/runtime.c (ffff8000108fe324)
Location: arch/arm64/include/asm/cmpxchg.h:173
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
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:pm_runtime_work
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
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
```
```
In drivers/base/power/wakeirq.c (ffff8000108feb4c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
```
```
In drivers/base/power/main.c (ffff80001090319c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_check_callbacks
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_propagate_wakeup_to_parent
```
```
In drivers/base/power/wakeup.c (ffff800010903e44)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:pm_save_wakeup_count
  - drivers/base/power/wakeup.c:pm_wakeup_pending
  - drivers/base/power/wakeup.c:pm_wakeup_timer_fn
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/power/wakeup.c:wakeup_source_record
```
```
In drivers/base/power/domain.c (ffff80001090a178)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_free_dev_data
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:genpd_lock_interruptible_spin
  - drivers/base/power/domain.c:genpd_lock_nested_spin
  - drivers/base/power/domain.c:genpd_lock_spin
```
```
In drivers/base/power/domain_governor.c (ffff80001090ad38)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:default_suspend_ok
```
```
In drivers/base/power/clock_ops.c (ffff80001090b7ac)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
```
```
In drivers/base/firmware_loader/main.c (ffff80001090cc24)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
```
In drivers/base/regmap/regmap.c (ffff800010913180)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_is_done
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:regmap_lock_spinlock
```
```
In drivers/block/loop.c (ffff800010923634)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/block/xen-blkfront.c (ffff8000109297b4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:kick_pending_request_queues
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:xlbd_release_minors
```
```
In drivers/mfd/htc-i2cpld.c (ffff80001092e35c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (ffff80001094153c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/ezx-pcap.c:pcap_adc_async
  - drivers/mfd/ezx-pcap.c:pcap_adc_irq
  - drivers/mfd/ezx-pcap.c:pcap_adc_trigger
  - drivers/mfd/ezx-pcap.c:pcap_set_ts_bits
  - drivers/mfd/ezx-pcap.c:ezx_pcap_set_bits
  - drivers/mfd/ezx-pcap.c:ezx_pcap_read
  - drivers/mfd/ezx-pcap.c:ezx_pcap_write
```
```
In drivers/mfd/syscon.c (ffff80001094eaf8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:device_node_get_regmap
  - drivers/mfd/syscon.c:of_syscon_register
```
```
In drivers/nvdimm/bus.c (ffff800010951ad8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
```
```
In drivers/nvdimm/region_devs.c (ffff800010956a90)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_acquire_lane
```
```
In drivers/nvdimm/badrange.c (ffff80001095fd1c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_forget
  - drivers/nvdimm/badrange.c:badrange_add
  - drivers/nvdimm/badrange.c:badrange_add
```
```
In drivers/dax/super.c (ffff80001096307c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/dma-buf/dma-buf.c (ffff800010965ce8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_cb
```
```
In drivers/dma-buf/dma-fence.c (ffff800010967554)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_remove_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_signal
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/sw_sync.c (ffff80001096b840)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
```
In drivers/dma-buf/sync_debug.c (ffff80001096c078)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_file_debug_remove
  - drivers/dma-buf/sync_debug.c:sync_file_debug_add
  - drivers/dma-buf/sync_debug.c:sync_timeline_debug_remove
  - drivers/dma-buf/sync_debug.c:sync_timeline_debug_add
```
```
In drivers/scsi/scsi.c (ffff80001096e6bc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__scsi_iterate_devices
```
```
In drivers/scsi/hosts.c (ffff80001096f748)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
```
```
In drivers/scsi/scsi_error.c (ffff800010974e40)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
```
```
In drivers/scsi/scsi_lib.c (ffff800010977108)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_evt_send
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_add_cmd_to_list
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/scsi/scsi_scan.c (ffff80001097cd88)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/scsi/scsi_sysfs.c (ffff80001097fe90)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/scsi/scsi_dh.c (ffff800010984038)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/scsi/scsi_dh.c:__scsi_dh_lookup
```
```
In drivers/scsi/sr.c (ffff80001098ce14)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffff80001098f7b8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_get_rq_mark
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffff800010998934)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_finalize_port_ops
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffff8000109a6a74)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
```
```
In drivers/ata/libata-eh.c (ffff8000109ac640)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_about_to_do
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/ata/libata-sff.c (ffff8000109b0304)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_post_internal_cmd
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_interrupt
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
```
```
In drivers/ata/libata-pmp.c (ffff8000109b3f40)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/ata/libata-acpi.c (ffff8000109b59f8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
```
In drivers/ata/libahci.c (ffff8000109bc16c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_single_level_irq_intr
  - drivers/ata/libahci.c:ahci_multi_irqs_intr_hard
  - drivers/ata/libahci.c:ahci_transmit_led_message
  - drivers/ata/libahci.c:ahci_sw_activity_blink
  - drivers/ata/libahci.c:ahci_store_em_buffer
  - drivers/ata/libahci.c:ahci_read_em_buffer
```
```
In drivers/gpu/vga/vgaarb.c (ffff8000109c01b0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_release
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/gpu/vga/vgaarb.c:vga_client_register
  - drivers/gpu/vga/vgaarb.c:__vga_set_legacy_decoding
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/spi/spi.c (ffff8000109c4e40)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_bus_lock
  - drivers/spi/spi.c:spi_async_locked
  - drivers/spi/spi.c:spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_split_transfers_maxsize
  - drivers/spi/spi.c:spi_split_transfers_maxsize
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_start_queue
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_get_next_queued_message
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
  - drivers/spi/spi.c:spi_statistics_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_statistics_bytes_tx_show
  - drivers/spi/spi.c:spi_statistics_bytes_rx_show
  - drivers/spi/spi.c:spi_statistics_bytes_show
  - drivers/spi/spi.c:spi_statistics_spi_async_show
  - drivers/spi/spi.c:spi_statistics_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_statistics_spi_sync_show
  - drivers/spi/spi.c:spi_statistics_timedout_show
  - drivers/spi/spi.c:spi_statistics_errors_show
  - drivers/spi/spi.c:spi_statistics_transfers_show
  - drivers/spi/spi.c:spi_statistics_messages_show
```
```
In drivers/net/tun.c (ffff8000109dc910)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e4654)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109ea700)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_hwtstamp
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (ffff8000109ecbe4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_time_keep
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_settime
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_gettime
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjtime
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjfreq
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_start_cyclecounter
```
```
In drivers/net/ethernet/freescale/fman/fman.c (ffff8000109ef614)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109f907c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_nwayreset
  - drivers/net/ethernet/smsc/smc91x.c:smc_open
  - drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_shutdown
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
```
```
In drivers/net/ppp/ppp_generic.c (ffff8000109ffe8c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_compressor
  - drivers/net/ppp/ppp_generic.c:ppp_register_compressor
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffff800010a0919c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_open
```
```
In drivers/usb/core/hub.c (ffff800010a18a2c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_set_device_state
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
```
```
In drivers/usb/core/hcd.c (ffff800010a1fd04)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_synchronize_unlinks
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_link_urb_to_ep
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/urb.c (ffff800010a20fb8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_unanchor_urb
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffff800010a22b2c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:sg_complete
```
```
In drivers/usb/core/driver.c (ffff800010a27108)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:usb_match_dynamic_id
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
```
```
In drivers/usb/core/devio.c (ffff800010a2ef90)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:async_getcompleted
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:usbdev_vm_open
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
```
```
In drivers/usb/phy/phy.c (ffff800010a382b0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:usb_remove_phy
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/usb/phy/phy.c:usb_get_phy
```
```
In drivers/usb/dwc2/core_intr.c (ffff800010a3d54c)
Location: arch/arm64/include/asm/cmpxchg.h:173
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
In drivers/usb/dwc2/hcd.c (ffff800010a45d8c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_reset
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
```
```
In drivers/usb/dwc2/hcd_intr.c (ffff800010a4b128)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4c990)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4e004)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/pci-quirks.c (ffff800010a502fc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a5d68c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_remove_device
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_silence_controller
  - drivers/usb/host/ehci-hcd.c:ehci_silence_controller
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
```
In drivers/usb/host/ohci-hcd.c (ffff800010a65cbc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ohci-hcd.c:fill_async_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/uhci-hcd.c (ffff800010a6a9a4)
Location: arch/arm64/include/asm/cmpxchg.h:173
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
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_fsbr_timeout
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
```
```
In drivers/usb/host/xhci.c (ffff800010a6fbb8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a82cfc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
```
```
In drivers/usb/host/xhci-hub.c (ffff800010a86d28)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8be6c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/usb/host/xhci-dbgtty.c (ffff800010a8c948)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_port_activate
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_chars_in_buffer
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write_room
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_put_char
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8fe98)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
```
```
In drivers/input/serio/serio.c (ffff800010a92aec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/serio/libps2.c (ffff800010a94334)
Location: arch/arm64/include/asm/cmpxchg.h:173
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
In drivers/input/input.c (ffff800010a98844)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/input/input.c:__input_unregister_device
  - drivers/input/input.c:input_dev_poweroff
  - drivers/input/input.c:input_dev_freeze
  - drivers/input/input.c:input_dev_resume
  - drivers/input/input.c:input_dev_suspend
  - drivers/input/input.c:input_reset_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_get_keycode
  - drivers/input/input.c:input_inject_event
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/ff-core.c (ffff800010a9b020)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/input/ff-core.c:erase_effect
  - drivers/input/ff-core.c:erase_effect
  - drivers/input/ff-core.c:input_ff_upload
```
```
In drivers/input/mousedev.c (ffff800010a9bfa0)
Location: arch/arm64/include/asm/cmpxchg.h:173
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
In drivers/input/evdev.c (ffff800010a9d918)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
  - drivers/input/evdev.c:evdev_pass_values
```
```
In drivers/input/keyboard/atkbd.c (ffff800010aa2d28)
Location: arch/arm64/include/asm/cmpxchg.h:173
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
In drivers/input/misc/uinput.c (ffff800010aa4434)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
```
```
In drivers/rtc/interface.c (ffff800010aa9744)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_handle_legacy_irq
```
```
In drivers/rtc/dev.c (ffff800010aaa7a0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In drivers/rtc/rtc-sun6i.c (ffff800010aadbb4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_getalarm
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_setaie
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_alarmirq
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_osc_set_parent
```
```
In drivers/i2c/i2c-dev.c (ffff800010ab7390)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:put_i2c_dev
  - drivers/i2c/i2c-dev.c:i2c_dev_get_by_minor
```
```
In drivers/pps/pps.c (ffff800010ac62dc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
```
```
In drivers/pps/kapi.c (ffff800010ac6814)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/pps/kapi.c:pps_event
```
```
In drivers/ptp/ptp_clock.c (ffff800010ac758c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (ffff800010ac8674)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
```
```
In drivers/ptp/ptp_sysfs.c (ffff800010ac8ff8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acc704)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
```
In drivers/thermal/thermal_sysfs.c (ffff800010ad7780)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:total_trans_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
```
```
In drivers/watchdog/watchdog_pretimeout.c (ffff800010ae16a8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_unregister_pretimeout
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_pretimeout
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_unregister_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_notify_pretimeout
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_get
```
```
In drivers/md/md.c (ffff800010aefe24)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:unregister_md_cluster_operations
  - drivers/md/md.c:register_md_cluster_operations
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:register_md_personality
  - drivers/md/md.c:md_seq_next
  - drivers/md/md.c:md_unregister_thread
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:md_attr_store
  - drivers/md/md.c:md_attr_show
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:level_show
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:md_flush_request
```
```
In drivers/md/md-bitmap.c (ffff800010af6a90)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:behind_writes_used_show
  - drivers/md/md-bitmap.c:can_clear_show
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_destroy
  - drivers/md/md-bitmap.c:md_bitmap_set_memory_bits
  - drivers/md/md-bitmap.c:md_bitmap_start_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_checkpage
```
```
In drivers/md/dm.c (ffff800010b01314)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_from_kobject
  - drivers/md/dm.c:dm_uevent_add
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_hold
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:event_callback
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:free_minor
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:queue_io
  - drivers/md/dm.c:dm_cancel_deferred_remove
  - drivers/md/dm.c:dm_lock_for_deletion
  - drivers/md/dm.c:dm_blk_close
  - drivers/md/dm.c:dm_blk_open
```
```
In drivers/md/dm-kcopyd.c (ffff800010b0b7a4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
  - drivers/md/dm-kcopyd.c:process_jobs
  - drivers/md/dm-kcopyd.c:process_jobs
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:complete_io
  - drivers/md/dm-kcopyd.c:push
```
```
In drivers/md/dm-stats.c (ffff800010b0cf90)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
  - drivers/md/dm-stats.c:free_shared_memory
```
```
In drivers/edac/ghes_edac.c (ffff800010b1556c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_unregister
  - drivers/edac/ghes_edac.c:ghes_edac_register
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b1fc20)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_register_driver
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
```
```
In drivers/cpufreq/cpufreq_stats.c (ffff800010b232ec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
```
In drivers/cpuidle/driver.c (ffff800010b27c74)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
```
```
In drivers/cpuidle/sysfs.c (ffff800010b28bc0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:show_driver_name
  - drivers/cpuidle/sysfs.c:show_current_driver
```
```
In drivers/mmc/core/core.c (ffff800010b2f168)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_detach_bus
  - drivers/mmc/core/core.c:mmc_detach_bus
  - drivers/mmc/core/core.c:mmc_attach_bus
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/block.c (ffff800010b40cb8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_rw_wait_cond
  - drivers/mmc/core/block.c:mmc_blk_mq_req_done
  - drivers/mmc/core/block.c:mmc_blk_mq_req_done
  - drivers/mmc/core/block.c:mmc_blk_mq_post_req
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
```
```
In drivers/mmc/core/queue.c (ffff800010b44030)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/mmc/core/queue.c:mmc_mq_queue_rq
  - drivers/mmc/core/queue.c:mmc_mq_queue_rq
  - drivers/mmc/core/queue.c:mmc_mq_recovery_handler
  - drivers/mmc/core/queue.c:mmc_mq_timed_out
  - drivers/mmc/core/queue.c:mmc_cqe_recovery_notifier
```
```
In drivers/mmc/host/mmci.c (ffff800010b46270)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_runtime_resume
  - drivers/mmc/host/mmci.c:mmci_runtime_suspend
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/mmci.c:mmci_request
  - drivers/mmc/host/mmci.c:mmci_irq
  - drivers/mmc/host/mmci.c:mmci_card_busy
```
```
In drivers/leds/led-triggers.c (ffff800010b4a2e4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
```
In drivers/firmware/arm_sdei.c (ffff800010b4c894)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/firmware/arm_sdei.c:sdei_device_thaw
  - drivers/firmware/arm_sdei.c:sdei_device_freeze
  - drivers/firmware/arm_sdei.c:sdei_cpuhp_up
  - drivers/firmware/arm_sdei.c:sdei_cpuhp_down
  - drivers/firmware/arm_sdei.c:sdei_event_register
  - drivers/firmware/arm_sdei.c:sdei_event_disable
  - drivers/firmware/arm_sdei.c:sdei_event_enable
  - drivers/firmware/arm_sdei.c:sdei_event_destroy
  - drivers/firmware/arm_sdei.c:sdei_event_find
```
```
In drivers/firmware/memmap.c (ffff800010b4e350)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:do_raw_spin_lock
```
```
In drivers/firmware/ti_sci.c (ffff800010b518f0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/firmware/ti_sci.c:ti_sci_release_resource
  - drivers/firmware/ti_sci.c:ti_sci_get_free_resource
```
```
In drivers/firmware/arm_scmi/bus.c (ffff800010b55d48)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/bus.c:scmi_protocol_unregister
  - drivers/firmware/arm_scmi/bus.c:scmi_protocol_register
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b56e4c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_get_init
```
```
In drivers/firmware/efi/efi.c (ffff800010d9f464)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b64bec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_clocksource_read
  - drivers/clocksource/sh_cmt.c:sh_cmt_stop
  - drivers/clocksource/sh_cmt.c:sh_cmt_start
  - drivers/clocksource/sh_cmt.c:sh_cmt_set_next
  - drivers/clocksource/sh_cmt.c:sh_cmt_start_stop_ch
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b65b7c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
```
```
In drivers/of/base.c (ffff800010b6be9c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/of/base.c:of_update_property
  - drivers/of/base.c:of_remove_property
  - drivers/of/base.c:of_add_property
  - drivers/of/base.c:of_find_node_by_phandle
  - drivers/of/base.c:of_find_matching_node_and_match
  - drivers/of/base.c:of_match_node
  - drivers/of/base.c:of_find_node_with_property
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_node_opts_by_path
  - drivers/of/base.c:of_get_next_cpu_node
  - drivers/of/base.c:of_get_next_available_child
  - drivers/of/base.c:of_get_next_child
  - drivers/of/base.c:of_get_next_parent
  - drivers/of/base.c:of_get_parent
  - drivers/of/base.c:of_device_is_available
  - drivers/of/base.c:of_device_is_compatible
  - drivers/of/base.c:of_find_all_nodes
  - drivers/of/base.c:of_find_property
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/base.c:of_free_phandle_cache
```
```
In drivers/of/dynamic.c (ffff800010b70f0c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_changeset_entry_apply
  - drivers/of/dynamic.c:of_detach_node
  - drivers/of/dynamic.c:of_attach_node
```
```
In drivers/of/resolver.c (ffff800010b76bc4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/of/resolver.c:of_resolve_phandles
```
```
In drivers/mailbox/mailbox.c (ffff800010b7a924)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_request_channel
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In drivers/mailbox/pcc.c (ffff800010b7bb48)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_free_channel
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
```
```
In drivers/mailbox/bcm2835-mailbox.c (ffff800010b7c308)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/mailbox/bcm2835-mailbox.c:bcm2835_last_tx_done
  - drivers/mailbox/bcm2835-mailbox.c:bcm2835_send_data
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7ee5c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In drivers/extcon/extcon.c (ffff800010b8860c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - drivers/extcon/extcon.c:extcon_unregister_notifier
  - drivers/extcon/extcon.c:extcon_register_notifier
  - drivers/extcon/extcon.c:extcon_set_property
  - drivers/extcon/extcon.c:extcon_get_property
  - drivers/extcon/extcon.c:extcon_set_state
  - drivers/extcon/extcon.c:extcon_get_state
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/extcon/extcon.c:extcon_sync
```
```
In drivers/memory/fsl_ifc.c (ffff800010b8b250)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/memory/fsl_ifc.c:check_nand_stat
```
```
In drivers/vme/vme.c (ffff800010b8e6a4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_master_free
  - drivers/vme/vme.c:vme_master_request
```
```
In drivers/perf/arm-cci.c (ffff800010b91984)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_start
  - drivers/perf/arm-cci.c:cci_pmu_disable
  - drivers/perf/arm-cci.c:cci_pmu_enable
  - drivers/perf/arm-cci.c:pmu_handle_irq
```
```
In drivers/perf/arm-ccn.c (ffff800010b93448)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_xp_dt_config
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b99650)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_start
  - drivers/perf/qcom_l2_pmu.c:get_l2_indirect_reg
  - drivers/perf/qcom_l2_pmu.c:set_l2_indirect_reg
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9c8bc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_pmu_isr
```
```
In net/socket.c (ffff800010ba27a0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/socket.c:sock_register
```
```
In net/core/sock.c (ffff800010bada4c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:release_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/request_sock.c (ffff800010bb0360)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffff800010bb3e60)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/datagram.c (ffff800010bbc920)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/core/gen_stats.c (ffff800010bbf308)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffff800010bbf920)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:est_fetch_counters
```
```
In net/core/net_namespace.c (ffff800010bc120c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffff800010bd5ac8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:dev_add_pack
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffff800010bdf6c8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_mc_sync_multiple
  - net/core/dev_addr_lists.c:dev_mc_sync
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_sync_multiple
  - net/core/dev_addr_lists.c:dev_uc_sync
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (ffff800010be433c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/rtnetlink.c (ffff800010beec00)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffff800010bf3978)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_forget_dev
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/sock_reuseport.c (ffff800010c052ac)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/net-sysfs.c (ffff800010c0a400)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_timeout_show
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
```
```
In net/core/page_pool.c (ffff800010c0cacc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/core/net-procfs.c (ffff800010c0dff4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In net/core/skmsg.c (ffff800010c0f70c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/netpoll.c (ffff800010c1135c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:refill_skbs
  - net/core/netpoll.c:queue_process
```
```
In net/core/fib_rules.c (ffff800010c12b48)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/drop_monitor.c (ffff800010c1b94c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/core/netprio_cgroup.c (ffff800010c1d488)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netprio_cgroup.c:update_netprio
```
```
In net/core/netclassid_cgroup.c (ffff800010c1d7e0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_task
  - net/core/netclassid_cgroup.c:update_classid_sock
```
```
In net/core/sock_map.c (ffff800010c21c9c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:__sock_map_delete
  - net/core/sock_map.c:sock_map_unref
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (ffff800010c26674)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/core/bpf_sk_storage.c (ffff800010c32198)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:__sk_storage_lookup
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:selem_unlink_sk
```
```
In net/sched/sch_generic.c (ffff800010c3a024)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_mq.c (ffff800010c3b0ec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffff800010c3d0a8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (ffff800010c42718)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
```
```
In net/sched/act_api.c (ffff800010c46ea8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (ffff800010c49f20)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/netlink/af_netlink.c (ffff800010c4f04c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/route.c (ffff800010c5a8d0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffff800010c5da30)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_fragment.c (ffff800010c5fdf0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6b314)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6ba84)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6da9c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_add
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffff800010c75890)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_output.c (ffff800010c873b0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffff800010c88744)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8f1f8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_cong.c (ffff800010c91470)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_metrics.c (ffff800010c925d4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c93b7c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
```
```
In net/ipv4/tcp_ulp.c (ffff800010c94d68)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/raw.c (ffff800010c97324)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffff800010c9bad8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
```
```
In net/ipv4/arp.c (ffff800010ca1e68)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
```
```
In net/ipv4/icmp.c (ffff800010ca4adc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_global_allow
```
```
In net/ipv4/af_inet.c (ffff800010cabc2c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv4/igmp.c (ffff800010cb0398)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffff800010cb82d0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:ip_fib_check_default
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffff800010cbeb0c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/ping.c (ffff800010cc0c4c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/sysctl_net_ipv4.c (ffff800010cc72e0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffff800010ccc134)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:vif_delete
```
```
In net/ipv4/ipmr_base.c (ffff800010cd0f40)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd478c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd5a98)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdd5b8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_if_register_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_register_afinfo
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
```
```
In net/xfrm/xfrm_state.c (ffff800010ce5058)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffff800010ceaaec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffff800010cebfe8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_device.c (ffff800010cee714)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
```
In net/unix/af_unix.c (ffff800010cf0804)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_peer_get
```
```
In net/unix/garbage.c (ffff800010cf4bb0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/unix/scm.c (ffff800010cf5444)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
```
In net/ipv6/af_inet6.c (ffff800010cf644c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/anycast.c (ffff800010cf7e7c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (ffff800010d0ab28)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_start
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffff800010d0c044)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffff800010d119e0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:__ip6_ins_rt
  - net/ipv6/route.c:rt6_uncached_list_add
```
```
In net/ipv6/ip6_fib.c (ffff800010d19dec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
  - net/ipv6/ip6_fib.c:fib6_walker_unlink
  - net/ipv6/ip6_fib.c:fib6_walker_link
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1dcc0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/raw.c (ffff800010d292e4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/icmp.c (ffff800010d2c604)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffff800010d308c4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
```
```
In net/ipv6/reassembly.c (ffff800010d35978)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d3981c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3ef00)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffff800010d466c8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/xfrm6_input.c (ffff800010d48fac)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
```
In net/ipv6/calipso.c (ffff800010d4e7c8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d55f08)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffff800010d5bbe8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:__fanout_set_data_bpf
  - net/packet/af_packet.c:__fanout_link
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
```
In net/netlabel/netlabel_domainhash.c (ffff800010d65868)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d68458)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/rfkill/core.c (ffff800010d6bc64)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_blocked
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_init_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_fill_event
```
```
In net/rfkill/input.c (ffff800010d6daf0)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_start
  - net/rfkill/input.c:rfkill_schedule_global_op
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In net/dcb/dcbnl.c (ffff800010d6fbe4)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask
  - net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffff800010d7408c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-rsp.c (ffff800010d76fbc)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
```
```
In net/ncsi/ncsi-aen.c (ffff800010d7745c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffff800010d79290)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_alloc_request
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_report_link
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7d454)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
```
```
In net/xdp/xsk.c (ffff800010d7f0ec)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_destruct_skb
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xdp_umem.c (ffff800010d80cf8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_del_sk_umem
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/dec_and_lock.c (ffff800010d84784)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In lib/flex_proportions.c (ffff800010d88084)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In lib/idr.c (ffff800010d88cf8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/klist.c (ffff800010d89c1c)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_remove
  - lib/klist.c:klist_put
  - lib/klist.c:klist_release
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
```
```
In lib/kobject.c (ffff800010d8a8a8)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - lib/kobject.c:kobj_ns_drop
  - lib/kobject.c:kobj_ns_initial
  - lib/kobject.c:kobj_ns_netlink
  - lib/kobject.c:kobj_ns_grab_current
  - lib/kobject.c:kobj_ns_current_may_mount
  - lib/kobject.c:kobj_ns_type_register
  - lib/kobject.c:kset_find_obj
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobj_kset_leave
```
```
In lib/ratelimit.c (ffff800010d8ed88)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
```
```
In lib/xarray.c (ffff800010d9ac68)
Location: arch/arm64/include/asm/cmpxchg.h:173
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_clear_mark
  - lib/xarray.c:xa_set_mark
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store
  - lib/xarray.c:xa_erase
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
  - lib/xarray.c:__xas_nomem
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
