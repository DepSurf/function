# Function: <code>rcu_read_lock_sched_notrace</code>

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
In arch/x86/entry/common.c (ffffffff81003696)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter_phase2
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810048b2)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/xen/enlighten.c (ffffffff8101bf94)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:load_TLS_descriptor
  - arch/x86/xen/enlighten.c:xen_write_idt_entry
  - arch/x86/xen/enlighten.c:xen_load_tls
  - arch/x86/xen/enlighten.c:xen_load_tls
  - arch/x86/xen/enlighten.c:xen_clts
  - arch/x86/xen/enlighten.c:xen_clts
  - arch/x86/xen/enlighten.c:xen_clts
  - arch/x86/xen/enlighten.c:xen_write_cr0
  - arch/x86/xen/enlighten.c:xen_write_cr0
  - arch/x86/xen/enlighten.c:xen_write_cr0
  - arch/x86/xen/enlighten.c:xen_load_sp0
  - arch/x86/xen/enlighten.c:xen_load_sp0
  - arch/x86/xen/enlighten.c:xen_load_sp0
  - arch/x86/xen/enlighten.c:xen_set_ldt
  - arch/x86/xen/enlighten.c:xen_set_ldt
  - arch/x86/xen/enlighten.c:xen_set_ldt
  - arch/x86/xen/enlighten.c:xen_set_ldt
```
```
In arch/x86/xen/multicalls.c (ffffffff8101d8dd)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_flush
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
```
```
In arch/x86/xen/mmu.c (ffffffff8101e160)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_set_domain_pte
  - arch/x86/xen/mmu.c:xen_set_domain_pte
  - arch/x86/xen/mmu.c:xen_set_domain_pte
  - arch/x86/xen/mmu.c:xen_set_domain_pte
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_extend_mmu_update
  - arch/x86/xen/mmu.c:xen_set_pud_hyper
  - arch/x86/xen/mmu.c:xen_set_pud_hyper
  - arch/x86/xen/mmu.c:xen_set_pud
  - arch/x86/xen/mmu.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu.c:xen_set_pmd
  - arch/x86/xen/mmu.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
```
```
In arch/x86/kernel/traps.c (ffffffff8102fd25)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/irq.c (ffffffff81030bf5)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
```
```
In arch/x86/kernel/nmi.c (ffffffff8103241d)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff81033c4b)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
```
```
In arch/x86/kernel/process.c (ffffffff81038e11)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104512f)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81048f81)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff810490b1)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff810498d1)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff81050b8b)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81827025)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt
```
```
In arch/x86/mm/fault.c (ffffffff8106b82a)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:trace_do_page_fault
  - arch/x86/mm/fault.c:trace_do_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff81072578)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:flush_tlb_current_task
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/mm/mpx.c (ffffffff810751c8)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
```
In kernel/fork.c (ffffffff8107f59e)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff81081c30)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/exit.c (ffffffff81082310)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/exit.c:delayed_put_task_struct
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff8108525c)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:cpu_callback
  - kernel/softirq.c:cpu_callback
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:raise_softirq
```
```
In kernel/signal.c (ffffffff8108e5f3)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:get_signal
```
```
In kernel/kmod.c (ffffffff810969f3)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/workqueue.c (ffffffff81097e71)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
```
```
In kernel/kthread.c (ffffffff810a087c)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/sched/core.c (ffffffff810aa351)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:ttwu_do_wakeup
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:idle_task_exit
```
```
In kernel/sched/fair.c (ffffffff810b4895)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_stats_wait_end
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/idle.c (ffffffff810c3f7d)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In kernel/power/qos.c (ffffffff810cc3d0)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_work_fn
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/power/process.c (ffffffff810cdd38)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810ce18b)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:pm_suspend
```
```
In kernel/power/hibernate.c (ffffffff810cf349)
Location: include/linux/rcupdate.h:983
Inline: True
```
```
In kernel/printk/printk.c (ffffffff810d73c8)
Location: include/linux/rcupdate.h:983
Inline: True
```
```
In kernel/irq/handle.c (ffffffff810da92e)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/handle.c:handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810de535)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
```
```
In kernel/rcu/tree.c (ffffffff810e70df)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
```
```
In kernel/time/timer.c (ffffffff810eba8a)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:init_timer_key
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:migrate_timer_list
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer
```
```
In kernel/time/hrtimer.c (ffffffff810eead1)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/itimer.c (ffffffff810f0390)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f2a4a)
Location: include/linux/rcupdate.h:983
Inline: True
```
```
In kernel/time/tick-common.c (ffffffff810fcc2b)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_unfreeze
```
```
In kernel/time/tick-sched.c (ffffffff810fe9a9)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/module.c (ffffffff8110532e)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/module.c:module_put
  - kernel/module.c:try_module_get
  - kernel/module.c:__module_get
  - kernel/module.c:free_module
  - kernel/module.c:load_module
```
```
In kernel/hung_task.c (ffffffff8113a6d5)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In mm/filemap.c (ffffffff8118de54)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff81192769)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_prepare
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_hot_cold_page_list
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/page-writeback.c (ffffffff811980ec)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - mm/page-writeback.c:domain_dirty_limits
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff8119ccb7)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff811a0887)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node_zone
  - mm/vmscan.c:mem_cgroup_shrink_node_zone
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
```
In mm/backing-dev.c (ffffffff811ae441)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:wait_iff_congested
```
```
In mm/mmu_context.c (ffffffff811afd46)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/slab_common.c (ffffffff811b2833)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/compaction.c (ffffffff811b58c6)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:defer_compaction
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:__compact_pgdat
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
```
```
In mm/rmap.c (ffffffff811ca6db)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush
```
```
In mm/slub.c (ffffffff811eae7a)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
```
```
In mm/migrate.c (ffffffff811f0b13)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_update_ratelimit
  - mm/migrate.c:migrate_pages
```
```
In mm/memory-failure.c (ffffffff81201660)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - mm/memory-failure.c:action_result
```
```
In mm/cma.c (ffffffff8120718b)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - mm/cma.c:cma_alloc
  - mm/cma.c:cma_release
```
```
In fs/open.c (ffffffff8120b8ed)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff81212195)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__set_task_comm
```
```
In fs/inode.c (ffffffff81227f3b)
Location: include/linux/rcupdate.h:983
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81235d9d)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
```
```
In fs/buffer.c (ffffffff81242aa3)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/locks.c (ffffffff81261772)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
```
In fs/proc/base.c (ffffffff8127ad0c)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In fs/ext4/balloc.c (ffffffff8129014c)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/fsync.c (ffffffff81292bb5)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff812939ad)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81295e05)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff812a81fa)
Location: include/linux/rcupdate.h:983
Inline: True
```
```
In fs/ext4/super.c (ffffffff812a8ec3)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/ext4/extents.c (ffffffff81322df1)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:get_reserved_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/ext4_jbd2.c (ffffffff812cb866)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/mballoc.c (ffffffff812ce702)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/ext4/indirect.c (ffffffff812d95ab)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/extents_status.c (ffffffff812dabea)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_remove_extent
```
```
In fs/jbd2/transaction.c (ffffffff812e7582)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff812e9a06)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff812eca58)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff812f1a2e)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In block/elevator.c (ffffffff813b401f)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In block/blk-core.c (ffffffff813b574e)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
```
```
In block/blk-mq.c (ffffffff813c3133)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:blk_mq_map_request
  - block/blk-mq.c:blk_mq_map_request
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_sq_make_request
```
```
In block/bounce.c (ffffffff813d5199)
Location: include/linux/rcupdate.h:983
Inline: True
```
```
In lib/swiotlb.c (ffffffff8141279c)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_page
```
```
In drivers/gpio/gpiolib.c (ffffffff81425b7c)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:_gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:_gpio_set_open_drain_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_source_value
  - drivers/gpio/gpiolib.c:_gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_priv
```
```
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff814496d7)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
```
```
In drivers/acpi/sleep.c (ffffffff8147b97c)
Location: include/linux/rcupdate.h:983
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff814d5259)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff814d9864)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
```
In drivers/char/random.c (ffffffff8151199d)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:__mix_pool_bytes
  - drivers/char/random.c:mix_pool_bytes
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:extract_entropy
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:extract_entropy_user
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:get_random_bytes_arch
```
```
In drivers/iommu/iommu.c (ffffffff81529f30)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_attach_device
  - drivers/iommu/iommu.c:__iommu_detach_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/base/syscore.c (ffffffff8154c33e)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/qos.c (ffffffff81554cfa)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff815562ec)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/base/power/main.c (ffffffff8155880b)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/wakeup.c (ffffffff8155bb39)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
```
In drivers/base/regmap/regmap.c (ffffffff815629b5)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:regmap_async_complete
  - drivers/base/regmap/regmap.c:regmap_async_complete
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:_regmap_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
```
```
In drivers/base/regmap/regcache.c (ffffffff81567317)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
```
```
In drivers/dma-buf/fence.c (ffffffff815a3c2e)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/dma-buf/fence.c:fence_init
  - drivers/dma-buf/fence.c:fence_signal_locked
  - drivers/dma-buf/fence.c:fence_add_callback
```
```
In drivers/scsi/scsi_error.c (ffffffff815abb8c)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff815adda9)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/scsi/scsi_lib.c:scsi_done
```
```
In drivers/ata/libata-core.c (ffffffff815caff1)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_issue
```
```
In drivers/ata/libata-eh.c (ffffffff815d6c07)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/spi/spi.c (ffffffff815e7363)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_sync
```
```
In drivers/usb/host/xhci.c (ffffffff8164b1a7)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816529c7)
Location: include/linux/rcupdate.h:983
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81657437)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/usb/host/xhci-hub.c (ffffffff8165d177)
Location: include/linux/rcupdate.h:983
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81662397)
Location: include/linux/rcupdate.h:983
Inline: True
```
```
In drivers/i2c/i2c-core.c (ffffffff81679be7)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:__i2c_transfer
  - drivers/i2c/i2c-core.c:__i2c_transfer
  - drivers/i2c/i2c-core.c:__i2c_transfer
  - drivers/i2c/i2c-core.c:__i2c_transfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
```
```
In drivers/thermal/thermal_core.c (ffffffff81684fee)
Location: include/linux/rcupdate.h:983
Inline: True
```
```
In drivers/thermal/fair_share.c (ffffffff81688e90)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
```
```
In drivers/thermal/step_wise.c (ffffffff81689470)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/thermal/step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/power_allocator.c (ffffffff8168a33a)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
```
In drivers/md/dm.c (ffffffff816a0b53)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:map_request
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816aecb0)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff816ba6d5)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_timer_func
```
```
In drivers/cpuidle/cpuidle.c (ffffffff816bba84)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/clk/clk.c (ffffffff816e5449)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
```
```
In net/core/sock.c (ffffffff81702c9c)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8170606b)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:consume_skb
```
```
In net/core/datagram.c (ffffffff8170d17f)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff8171920a)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netpoll.c (ffffffff81739004)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/ipv4/udp.c (ffffffff81786fdf)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/fib_frontend.c (ffffffff8179af5d)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv4/fib_trie.c (ffffffff8179ed00)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/udp.c (ffffffff817e3290)
Location: include/linux/rcupdate.h:983
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In arch/x86/entry/common.c (ffffffff810038fb)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100498d)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/xen/enlighten.c (ffffffff8101c231)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_write_cr0
  - arch/x86/xen/enlighten.c:xen_write_cr0
  - arch/x86/xen/enlighten.c:xen_write_cr0
  - arch/x86/xen/enlighten.c:xen_clts
  - arch/x86/xen/enlighten.c:xen_clts
  - arch/x86/xen/enlighten.c:xen_clts
  - arch/x86/xen/enlighten.c:xen_load_sp0
  - arch/x86/xen/enlighten.c:xen_load_sp0
  - arch/x86/xen/enlighten.c:xen_load_sp0
  - arch/x86/xen/enlighten.c:xen_write_idt_entry
  - arch/x86/xen/enlighten.c:xen_load_tls
  - arch/x86/xen/enlighten.c:xen_load_tls
  - arch/x86/xen/enlighten.c:load_TLS_descriptor
  - arch/x86/xen/enlighten.c:xen_set_ldt
  - arch/x86/xen/enlighten.c:xen_set_ldt
  - arch/x86/xen/enlighten.c:xen_set_ldt
  - arch/x86/xen/enlighten.c:xen_set_ldt
```
```
In arch/x86/xen/multicalls.c (ffffffff8101d0ed)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/mmu.c (ffffffff8101e8db)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_set_pud
  - arch/x86/xen/mmu.c:xen_set_pud_hyper
  - arch/x86/xen/mmu.c:xen_set_pud_hyper
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pmd
  - arch/x86/xen/mmu.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu.c:xen_extend_mmu_update
  - arch/x86/xen/mmu.c:xen_set_domain_pte
  - arch/x86/xen/mmu.c:xen_set_domain_pte
  - arch/x86/xen/mmu.c:xen_set_domain_pte
  - arch/x86/xen/mmu.c:xen_set_domain_pte
```
```
In arch/x86/kernel/process_64.c (ffffffff8102c80c)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff8102edb7)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/irq.c (ffffffff8102fc9e)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
```
```
In arch/x86/kernel/nmi.c (ffffffff81031543)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff81032e24)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
```
```
In arch/x86/kernel/process.c (ffffffff81038095)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039a87)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_write
  - arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_write
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a927)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810451b7)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104914a)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff8104926a)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049a8a)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff81050f34)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105449e)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
```
```
In arch/x86/mm/fault.c (ffffffff8106b703)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:trace_do_page_fault
  - arch/x86/mm/fault.c:trace_do_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff810729a8)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:flush_tlb_current_task
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mpx.c (ffffffff81077766)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
```
In kernel/fork.c (ffffffff8108212a)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff81084f79)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffff8108668a)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff810888e6)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/softirq.c:cpu_callback
  - kernel/softirq.c:cpu_callback
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/signal.c (ffffffff81093490)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/kmod.c (ffffffff81099db0)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/workqueue.c (ffffffff8109d6c8)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/kthread.c (ffffffff810a3f69)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/sched/core.c (ffffffff810b13d9)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:ttwu_do_wakeup
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810bbde6)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:update_stats_wait_end
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/idle.c (ffffffff810c7c6e)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In kernel/power/qos.c (ffffffff810d1673)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff810d2878)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810d35c1)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (ffffffff810d3de6)
Location: include/linux/rcupdate.h:992
Inline: True
```
```
In kernel/printk/printk.c (ffffffff810dc368)
Location: include/linux/rcupdate.h:992
Inline: True
```
```
In kernel/irq/handle.c (ffffffff810dff22)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810e3e77)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
```
```
In kernel/rcu/tree.c (ffffffff810ed6f0)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
```
```
In kernel/time/timer.c (ffffffff810f59da)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:init_timer_key
```
```
In kernel/time/hrtimer.c (ffffffff810f6ff3)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
```
In kernel/time/itimer.c (ffffffff810f77ce)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f9b53)
Location: include/linux/rcupdate.h:992
Inline: True
```
```
In kernel/time/tick-common.c (ffffffff81104052)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff81105d52)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/module.c (ffffffff81111843)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/module.c:module_put
  - kernel/module.c:try_module_get
  - kernel/module.c:__module_get
```
```
In kernel/hung_task.c (ffffffff81142bfd)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In mm/filemap.c (ffffffff811a0ec5)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff811ab1e4)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:free_hot_cold_page_list
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:__rmqueue
  - mm/page_alloc.c:__rmqueue
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/page-writeback.c (ffffffff811af245)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff811b20c0)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff811b91e0)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/backing-dev.c (ffffffff811c7d0d)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:bdi_register
```
```
In mm/slab_common.c (ffffffff811cc295)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/compaction.c (ffffffff811d1f10)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:__compact_pgdat
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/rmap.c (ffffffff811e70b0)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush
```
```
In mm/slub.c (ffffffff8120e0e5)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/migrate.c (ffffffff8120fd49)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_update_ratelimit
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff8121c33f)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memory-failure.c (ffffffff81225ed9)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff81229045)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/cma.c (ffffffff8122ccaa)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - mm/cma.c:cma_release
  - mm/cma.c:cma_alloc
```
```
In fs/open.c (ffffffff81231605)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff8123aad8)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - fs/exec.c:__set_task_comm
  - fs/exec.c:do_open_execat
```
```
In fs/inode.c (ffffffff8125066b)
Location: include/linux/rcupdate.h:992
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81262e7b)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/buffer.c (ffffffff8126ad73)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/locks.c (ffffffff8128ef16)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/proc/base.c (ffffffff812a9b52)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/ext4/balloc.c (ffffffff812bd664)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/fsync.c (ffffffff812c00eb)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff812c1b2a)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812c92e4)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/namei.c (ffffffff812d72e7)
Location: include/linux/rcupdate.h:992
Inline: True
```
```
In fs/ext4/super.c (ffffffff812e142b)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_drop_inode
```
```
In fs/ext4/extents.c (ffffffff812f9cd0)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:get_reserved_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ext4_jbd2.c (ffffffff812fb4d1)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/mballoc.c (ffffffff813059d8)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/indirect.c (ffffffff8130937a)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/extents_status.c (ffffffff8130b0a2)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
```
In fs/jbd2/transaction.c (ffffffff81315ad2)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_extend
```
```
In fs/jbd2/commit.c (ffffffff81317a2f)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
```
In fs/jbd2/checkpoint.c (ffffffff8131a4bd)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8131f279)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In block/elevator.c (ffffffff813f7cf6)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In block/blk-core.c (ffffffff813fa5c7)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
```
In block/blk-merge.c (ffffffff81404783)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-mq.c (ffffffff81409dba)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_map_request
  - block/blk-mq.c:blk_mq_map_request
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/bounce.c (ffffffff8141ae4e)
Location: include/linux/rcupdate.h:992
Inline: True
```
```
In lib/swiotlb.c (ffffffff8145a4e6)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_page
```
```
In arch/x86/lib/msr.c (ffffffff81463cc9)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff81472260)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:_gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_source_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_drain_value
  - drivers/gpio/gpiolib.c:_gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:gpiod_direction_input
```
```
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff81495c34)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
```
```
In drivers/acpi/sleep.c (ffffffff814c9f9c)
Location: include/linux/rcupdate.h:992
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81525655)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff8152aa71)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/char/random.c (ffffffff8156802e)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:extract_entropy
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:mix_pool_bytes
  - drivers/char/random.c:__mix_pool_bytes
```
```
In drivers/iommu/iommu.c (ffffffff8157dcc4)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:__iommu_detach_device
  - drivers/iommu/iommu.c:__iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/base/syscore.c (ffffffff8159e12a)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/qos.c (ffffffff815a6fc3)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff815a88af)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (ffffffff815ad531)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/base/power/wakeup.c (ffffffff815add42)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
```
In drivers/base/regmap/regmap.c (ffffffff815b7693)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete
  - drivers/base/regmap/regmap.c:regmap_async_complete
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
```
```
In drivers/base/regmap/regcache.c (ffffffff815bbee1)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
```
```
In drivers/dma-buf/fence.c (ffffffff815fad24)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/dma-buf/fence.c:fence_init
  - drivers/dma-buf/fence.c:fence_add_callback
  - drivers/dma-buf/fence.c:fence_signal_locked
```
```
In drivers/scsi/scsi_error.c (ffffffff81603d4c)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff816067af)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/scsi/scsi_lib.c:scsi_done
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/ata/libata-core.c (ffffffff81623d5f)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff816306f9)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/spi/spi.c (ffffffff81646c50)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/host/xhci.c (ffffffff816acd30)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816b32d0)
Location: include/linux/rcupdate.h:992
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816baaa3)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/usb/host/xhci-hub.c (ffffffff816bd8e0)
Location: include/linux/rcupdate.h:992
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816c25d0)
Location: include/linux/rcupdate.h:992
Inline: True
```
```
In drivers/i2c/i2c-core.c (ffffffff816dbc84)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:__i2c_transfer
  - drivers/i2c/i2c-core.c:__i2c_transfer
  - drivers/i2c/i2c-core.c:__i2c_transfer
  - drivers/i2c/i2c-core.c:__i2c_transfer
```
```
In drivers/thermal/thermal_core.c (ffffffff816e4d0c)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_cdev_update
```
```
In drivers/thermal/fair_share.c (ffffffff816e9b8b)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
```
```
In drivers/thermal/step_wise.c (ffffffff816ea1d0)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/thermal/step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/power_allocator.c (ffffffff816eb012)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/md/dm.c (ffffffff8170209f)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff8170f7e8)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81710617)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8171c36d)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_min_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8171d34e)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/mmc/core/core.c (ffffffff81721562)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/clk/clk.c (ffffffff8174a8a5)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
```
```
In net/core/sock.c (ffffffff817680d8)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8176e55d)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (ffffffff817747d8)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff8178393a)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff817a52b7)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/ipv4/udp.c (ffffffff817f42a9)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/fib_frontend.c (ffffffff81808b6a)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv4/fib_trie.c (ffffffff8180c958)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff8184394c)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/udp.c (ffffffff8185181f)
Location: include/linux/rcupdate.h:992
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
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
In arch/x86/entry/common.c (ffffffff810038bb)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004a0d)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/xen/enlighten.c (ffffffff8101c901)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_write_cr0
  - arch/x86/xen/enlighten.c:xen_write_cr0
  - arch/x86/xen/enlighten.c:xen_write_cr0
  - arch/x86/xen/enlighten.c:xen_load_sp0
  - arch/x86/xen/enlighten.c:xen_load_sp0
  - arch/x86/xen/enlighten.c:xen_load_sp0
  - arch/x86/xen/enlighten.c:xen_write_idt_entry
  - arch/x86/xen/enlighten.c:xen_load_tls
  - arch/x86/xen/enlighten.c:xen_load_tls
  - arch/x86/xen/enlighten.c:load_TLS_descriptor
  - arch/x86/xen/enlighten.c:xen_set_ldt
  - arch/x86/xen/enlighten.c:xen_set_ldt
  - arch/x86/xen/enlighten.c:xen_set_ldt
  - arch/x86/xen/enlighten.c:xen_set_ldt
```
```
In arch/x86/xen/multicalls.c (ffffffff8101d80d)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/mmu.c (ffffffff8101efcb)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_flush_tlb_single
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_set_pud
  - arch/x86/xen/mmu.c:xen_set_pud_hyper
  - arch/x86/xen/mmu.c:xen_set_pud_hyper
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pmd
  - arch/x86/xen/mmu.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu.c:xen_extend_mmu_update
  - arch/x86/xen/mmu.c:xen_set_domain_pte
  - arch/x86/xen/mmu.c:xen_set_domain_pte
  - arch/x86/xen/mmu.c:xen_set_domain_pte
  - arch/x86/xen/mmu.c:xen_set_domain_pte
```
```
In arch/x86/kernel/process_64.c (ffffffff8102c838)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff8102ed77)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/irq.c (ffffffff8102fc79)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
```
```
In arch/x86/kernel/nmi.c (ffffffff81031193)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff81032aa4)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
```
```
In arch/x86/kernel/process.c (ffffffff818d3bf0)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810393a7)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_write
  - arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_write
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a1e0)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046dac)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104b215)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff8104b6c5)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104be85)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff810537e4)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81057199)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
```
```
In arch/x86/mm/fault.c (ffffffff8106f323)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:trace_do_page_fault
  - arch/x86/mm/fault.c:trace_do_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff81076559)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:flush_tlb_current_task
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mpx.c (ffffffff8107b316)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
```
In kernel/fork.c (ffffffff81086b8a)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff81089f15)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffff8108b5f6)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff8108d87b)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/signal.c (ffffffff81098420)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/kmod.c (ffffffff8109ed60)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/workqueue.c (ffffffff810a2238)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/kthread.c (ffffffff810a95b7)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/sched/core.c (ffffffff810b7645)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:ttwu_do_wakeup
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810bd46a)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/idle.c (ffffffff818d3e0b)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d4bd5)
Location: include/linux/rcupdate.h:997
Inline: True
```
```
In kernel/power/qos.c (ffffffff810d80d3)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff810d9428)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810da151)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (ffffffff810da976)
Location: include/linux/rcupdate.h:997
Inline: True
```
```
In kernel/printk/printk.c (ffffffff810e349e)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
```
In kernel/irq/handle.c (ffffffff810e687f)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810ea966)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
```
```
In kernel/rcu/tree.c (ffffffff810f4653)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
```
```
In kernel/time/timer.c (ffffffff810fca1a)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:init_timer_key
```
```
In kernel/time/hrtimer.c (ffffffff810fe0b3)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
```
In kernel/time/alarmtimer.c (ffffffff81104e2b)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811074e3)
Location: include/linux/rcupdate.h:997
Inline: True
```
```
In kernel/time/itimer.c (ffffffff81109e8e)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff8110b753)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff8110d49e)
Location: include/linux/rcupdate.h:997
Inline: True
```
```
In kernel/module.c (ffffffff81118e61)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/module.c:module_put
  - kernel/module.c:try_module_get
  - kernel/module.c:__module_get
```
```
In kernel/cgroup.c (ffffffff81128602)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_rmdir
  - kernel/cgroup.c:css_release_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:cgroup_rename
  - kernel/cgroup.c:cgroup_attach_task
  - kernel/cgroup.c:cgroup_setup_root
  - kernel/cgroup.c:cgroup_remount
```
```
In kernel/hung_task.c (ffffffff8114c9eb)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In mm/filemap.c (ffffffff811b0ac5)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff811bb827)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:free_hot_cold_page_list
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:__rmqueue
  - mm/page_alloc.c:__rmqueue
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/page-writeback.c (ffffffff811bf8e5)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff811c271c)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff811c9820)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/backing-dev.c (ffffffff811d7e2d)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:bdi_register
```
```
In mm/slab_common.c (ffffffff811dc369)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/compaction.c (ffffffff811e1de7)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/rmap.c (ffffffff811f844a)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush
```
```
In mm/slub.c (ffffffff81220125)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/migrate.c (ffffffff81221e79)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_update_ratelimit
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff8122dd53)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memory-failure.c (ffffffff812384b9)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff8123b5d6)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/cma.c (ffffffff8123f1d6)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - mm/cma.c:cma_release
  - mm/cma.c:cma_alloc
```
```
In fs/open.c (ffffffff81243bb5)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff8124d888)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - fs/exec.c:__set_task_comm
  - fs/exec.c:do_open_execat
```
```
In fs/inode.c (ffffffff8126370b)
Location: include/linux/rcupdate.h:997
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812762cb)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/buffer.c (ffffffff8127dea3)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/locks.c (ffffffff812a2dab)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/proc/base.c (ffffffff812bf472)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/ext4/balloc.c (ffffffff812d2cb4)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/fsync.c (ffffffff812d571b)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff812d718a)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812def32)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/namei.c (ffffffff812ecf37)
Location: include/linux/rcupdate.h:997
Inline: True
```
```
In fs/ext4/super.c (ffffffff812f6f5b)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_drop_inode
```
```
In fs/ext4/extents.c (ffffffff8130fca0)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:get_reserved_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81311471)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/mballoc.c (ffffffff8131b996)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/indirect.c (ffffffff8131f38a)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/extents_status.c (ffffffff813210a2)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
```
In fs/jbd2/transaction.c (ffffffff8132bac2)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_extend
```
```
In fs/jbd2/commit.c (ffffffff8132da1f)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
```
In fs/jbd2/checkpoint.c (ffffffff813304ad)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813352fb)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In block/elevator.c (ffffffff8141171f)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In block/blk-core.c (ffffffff81413f47)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
```
In block/blk-merge.c (ffffffff8141dee2)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-mq.c (ffffffff81424780)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_map_request
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/bounce.c (ffffffff81436396)
Location: include/linux/rcupdate.h:997
Inline: True
```
```
In block/blk-wbt.c (ffffffff8144a525)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:rwb_trace_step
```
```
In lib/swiotlb.c (ffffffff81479006)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_page
```
```
In arch/x86/lib/msr.c (ffffffff81482f69)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff81494380)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:_gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_source_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_drain_value
  - drivers/gpio/gpiolib.c:_gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:gpiod_direction_input
```
```
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff814b75e8)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
```
```
In drivers/acpi/sleep.c (ffffffff814ebef7)
Location: include/linux/rcupdate.h:997
Inline: True
```
```
In drivers/clk/clk.c (ffffffff8153310e)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81551b2e)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff8155708d)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/char/random.c (ffffffff81594755)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:extract_entropy
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:mix_pool_bytes
  - drivers/char/random.c:__mix_pool_bytes
```
```
In drivers/iommu/iommu.c (ffffffff815aa264)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:__iommu_detach_device
  - drivers/iommu/iommu.c:__iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/base/syscore.c (ffffffff815cc6da)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/qos.c (ffffffff815d5783)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff815d739d)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (ffffffff815dc2f1)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/base/power/wakeup.c (ffffffff815dcb12)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
```
In drivers/base/regmap/regmap.c (ffffffff815e697e)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete
  - drivers/base/regmap/regmap.c:regmap_async_complete
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
```
```
In drivers/base/regmap/regcache.c (ffffffff815eb2f1)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81628ff4)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8162c5a5)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_error.c (ffffffff8163342c)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81635ccf)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/scsi/scsi_lib.c:scsi_done
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/ata/libata-core.c (ffffffff816548df)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff81661849)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/spi/spi.c (ffffffff81677d40)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8167d478)
Location: include/linux/rcupdate.h:997
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff816dafc3)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816e1480)
Location: include/linux/rcupdate.h:997
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816e8d08)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/usb/host/xhci-hub.c (ffffffff816eb790)
Location: include/linux/rcupdate.h:997
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816f0590)
Location: include/linux/rcupdate.h:997
Inline: True
```
```
In drivers/i2c/i2c-core.c (ffffffff8170bfc4)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:__i2c_transfer
  - drivers/i2c/i2c-core.c:__i2c_transfer
  - drivers/i2c/i2c-core.c:__i2c_transfer
  - drivers/i2c/i2c-core.c:__i2c_transfer
```
```
In drivers/thermal/thermal_core.c (ffffffff81715c12)
Location: include/linux/rcupdate.h:997
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (ffffffff81719ffc)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:thermal_cdev_update
```
```
In drivers/thermal/fair_share.c (ffffffff8171a9eb)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
```
```
In drivers/thermal/step_wise.c (ffffffff8171b030)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/thermal/step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/power_allocator.c (ffffffff8171bf32)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/md/dm.c (ffffffff81733f81)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff81741813)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81742637)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8174f6d3)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_prepare_request
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8174ff2e)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/mmc/core/core.c (ffffffff81754436)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In net/core/sock.c (ffffffff817950c5)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8179ba1d)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (ffffffff817a1ad8)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff817b0ef0)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff817d3d20)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/ipv4/udp.c (ffffffff81827dc1)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
```
```
In net/ipv4/fib_frontend.c (ffffffff81839c4b)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv4/fib_trie.c (ffffffff8183dbd8)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff818756bc)
Location: include/linux/rcupdate.h:997
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
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
In arch/x86/entry/common.c (ffffffff81003748)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004959)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/xen/multicalls.c (ffffffff8101a33a)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/mmu.c (ffffffff8101a7c9)
Location: include/linux/rcupdate.h:731
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8101f774)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81021bc9)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_single
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_single
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_single
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_single
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
  - arch/x86/xen/mmu_pv.c:xen_set_domain_pte
  - arch/x86/xen/mmu_pv.c:xen_set_domain_pte
  - arch/x86/xen/mmu_pv.c:xen_set_domain_pte
  - arch/x86/xen/mmu_pv.c:xen_set_domain_pte
```
```
In arch/x86/kernel/process_64.c (ffffffff8102aac3)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff8102d091)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/irq.c (ffffffff8190e1a4)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
```
```
In arch/x86/kernel/nmi.c (ffffffff8102f45f)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff8190e2a5)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
```
```
In arch/x86/kernel/process.c (ffffffff8190adac)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810372c1)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_write
  - arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_write
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81038130)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046577)
Location: include/linux/rcupdate.h:731
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8190e3a0)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff8190e4a0)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8190e5a0)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff8190e865)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8190eb3a)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
```
```
In arch/x86/mm/fault.c (ffffffff8106ea73)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:trace_do_page_fault
  - arch/x86/mm/fault.c:trace_do_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff81074aec)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mpx.c (ffffffff81079b99)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
```
In kernel/fork.c (ffffffff810838d3)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff81086dd7)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffff81088375)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff8108a8aa)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/signal.c (ffffffff8109570c)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/kmod.c (ffffffff8109c547)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/workqueue.c (ffffffff8109f732)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/kthread.c (ffffffff810a62e1)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/sched/core.c (ffffffff810b381c)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810bc967)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/idle.c (ffffffff8190afd1)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d36f6)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_commit
```
```
In kernel/power/qos.c (ffffffff810d710f)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff810d844f)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810d924c)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (ffffffff810d9a52)
Location: include/linux/rcupdate.h:731
Inline: True
```
```
In kernel/printk/printk.c (ffffffff810e2ab6)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
```
In kernel/irq/handle.c (ffffffff810e5e85)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810ea01b)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
```
```
In kernel/rcu/tree.c (ffffffff810f55cb)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
```
```
In kernel/time/timer.c (ffffffff810fee6b)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/hrtimer.c (ffffffff811003ed)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
```
In kernel/time/alarmtimer.c (ffffffff81106e54)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8110986f)
Location: include/linux/rcupdate.h:731
Inline: True
```
```
In kernel/time/itimer.c (ffffffff8110bd0a)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff8110d643)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff8110f36d)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/module.c (ffffffff8111aa2f)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/module.c:module_put
  - kernel/module.c:try_module_get
```
```
In kernel/cgroup/cgroup.c (ffffffff81127e9f)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8112998c)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff8114e96b)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/bpf/syscall.c (ffffffff811938b5)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/inode.c (ffffffff8119a091)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
```
```
In mm/filemap.c (ffffffff811b8011)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/oom_kill.c (ffffffff811bc131)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/page_alloc.c (ffffffff811c3b6e)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:free_hot_cold_page_list
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:__rmqueue
  - mm/page_alloc.c:__rmqueue
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/page-writeback.c (ffffffff811c7aaf)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff811cab90)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff811d22a6)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/backing-dev.c (ffffffff811e0a0d)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
```
```
In mm/percpu.c (ffffffff811e46e5)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
```
```
In mm/slab_common.c (ffffffff811e627f)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/compaction.c (ffffffff811ebbe7)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/slub.c (ffffffff8122beef)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/migrate.c (ffffffff8122dafa)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_update_ratelimit
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff81239ebb)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memory-failure.c (ffffffff81243ff9)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff81247218)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/cma.c (ffffffff8124aac7)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - mm/cma.c:cma_release
  - mm/cma.c:cma_alloc
```
```
In fs/open.c (ffffffff8124f37b)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff81259848)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/exec.c:__set_task_comm
  - fs/exec.c:do_open_execat
```
```
In fs/inode.c (ffffffff812710c9)
Location: include/linux/rcupdate.h:731
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81283762)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/buffer.c (ffffffff8128ba5f)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/dax.c (ffffffff812ab16a)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/locks.c (ffffffff812b1f8a)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/proc/base.c (ffffffff812cc08d)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/ext4/balloc.c (ffffffff812e41b1)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff812e639d)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff812ee25b)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:get_reserved_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (ffffffff812f0071)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
```
In fs/ext4/fsmap.c (ffffffff812f2fa7)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/fsync.c (ffffffff812f342c)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff812f5436)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff812f7e9b)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff8130315e)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813083e2)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
```
```
In fs/ext4/mballoc.c (ffffffff81312c38)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff8131cc53)
Location: include/linux/rcupdate.h:731
Inline: True
```
```
In fs/ext4/super.c (ffffffff8132b83a)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_drop_inode
```
```
In fs/jbd2/transaction.c (ffffffff81340d7a)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_extend
```
```
In fs/jbd2/commit.c (ffffffff81342c12)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
```
In fs/jbd2/checkpoint.c (ffffffff813453e3)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8134a09a)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In block/bio.c (ffffffff8141dac4)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - block/bio.c:bio_endio
```
```
In block/elevator.c (ffffffff8141f32a)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In block/blk-core.c (ffffffff814224e7)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_requeue_request
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
```
In block/blk-merge.c (ffffffff8142c291)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-mq.c (ffffffff81431838)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-mq-sched.c (ffffffff814351ab)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
```
```
In block/bounce.c (ffffffff81442ff0)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/blk-wbt.c (ffffffff8145859e)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:rwb_trace_step
```
```
In lib/swiotlb.c (ffffffff81482366)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_page
```
```
In arch/x86/lib/msr.c (ffffffff8148c6c9)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff8149d8c1)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:_gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_source_value
  - drivers/gpio/gpiolib.c:_gpio_set_open_drain_value
  - drivers/gpio/gpiolib.c:_gpiod_get_raw_value
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
  - drivers/gpio/gpiolib.c:_gpiod_direction_output_raw
```
```
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff814c1f26)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
```
```
In drivers/acpi/sleep.c (ffffffff814f88b8)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/clk/clk.c (ffffffff81545e85)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81566261)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff8156b6e3)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/char/random.c (ffffffff815a8787)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:mix_pool_bytes
  - drivers/char/random.c:__mix_pool_bytes
```
```
In drivers/iommu/iommu.c (ffffffff815bf3e3)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:__iommu_detach_device
  - drivers/iommu/iommu.c:__iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/base/syscore.c (ffffffff815e129b)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/qos.c (ffffffff815ea1e3)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff815ebaea)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (ffffffff815f0e6d)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:legacy_suspend
  - drivers/base/power/main.c:legacy_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/base/power/wakeup.c (ffffffff815f1978)
Location: include/linux/rcupdate.h:731
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff815fb069)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
```
```
In drivers/base/regmap/regcache.c (ffffffff815ffc1a)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8163ec63)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81641b73)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_error.c (ffffffff8164818c)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164af29)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/scsi/scsi_lib.c:scsi_done
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/ata/libata-core.c (ffffffff81668eed)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff81676884)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/spi/spi.c (ffffffff8168c420)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81692578)
Location: include/linux/rcupdate.h:731
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff816ef67e)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816f708f)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816fa697)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:inc_enq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff816ffd80)
Location: include/linux/rcupdate.h:731
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81705df0)
Location: include/linux/rcupdate.h:731
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8172059f)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8172313c)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
```
```
In drivers/thermal/thermal_core.c (ffffffff8172d77e)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:handle_thermal_trip
```
```
In drivers/thermal/thermal_helpers.c (ffffffff817322ac)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:thermal_cdev_update
```
```
In drivers/thermal/fair_share.c (ffffffff81732c9a)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
```
```
In drivers/thermal/step_wise.c (ffffffff817332dc)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/thermal/step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/power_allocator.c (ffffffff817341dc)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/md/dm.c (ffffffff8174d09e)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-rq.c (ffffffff8175afcf)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff8175cbb3)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81760cb6)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8176d95d)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8176e9f7)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/mmc/core/core.c (ffffffff81772115)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/ras/ras.c (ffffffff817a4a45)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In net/core/sock.c (ffffffff817b379c)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff817bdca7)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (ffffffff817bf73c)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff817d1237)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff817f309a)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/ipv4/udp.c (ffffffff81848ac6)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/fib_frontend.c (ffffffff8185b1d6)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv4/fib_trie.c (ffffffff8185f3dd)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff8189a503)
Location: include/linux/rcupdate.h:731
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
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
In arch/x86/entry/common.c (ffffffff81003788)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004bb6)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/xen/multicalls.c (ffffffff8101abea)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/mmu.c (ffffffff8101b099)
Location: include/linux/rcupdate.h:753
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102051a)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810226c0)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102a751)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/kernel/process_64.c (ffffffff8102b817)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff8102de51)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/irq.c (ffffffff81a0272c)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
```
```
In arch/x86/kernel/nmi.c (ffffffff81031465)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff81a027fa)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/process.c (ffffffff81995122)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039563)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a3b2)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81049da7)
Location: include/linux/rcupdate.h:753
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81a028cf)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff81a0299f)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81a02a6f)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff81a02cda)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81a03093)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105b287)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/mm/fault.c (ffffffff81073b01)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_page_fault
  - arch/x86/mm/fault.c:do_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff8107ac5c)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mpx.c (ffffffff8107fdc9)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
```
In kernel/fork.c (ffffffff8108a1b3)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff8108db6b)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffff8108f0fb)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff8109145d)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/signal.c (ffffffff8109c592)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810a5f61)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/kthread.c (ffffffff810ac874)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/kmod.c (ffffffff810b10b6)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810baa8c)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff810c0ffb)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/idle.c (ffffffff8199534d)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810db2c5)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_commit
```
```
In kernel/power/qos.c (ffffffff810df0af)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff810e0542)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810e0f61)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (ffffffff810e2155)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/printk/printk.c (ffffffff810ea955)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
```
In kernel/irq/handle.c (ffffffff810ee0fe)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810f2586)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
```
```
In kernel/irq/matrix.c (ffffffff810f99f1)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_remove_reserved
  - kernel/irq/matrix.c:irq_matrix_reserve
  - kernel/irq/matrix.c:irq_matrix_assign
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_assign_system
  - kernel/irq/matrix.c:irq_matrix_offline
  - kernel/irq/matrix.c:irq_matrix_online
```
```
In kernel/rcu/tree.c (ffffffff810ff3b0)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
```
```
In kernel/time/timer.c (ffffffff81109bfd)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/hrtimer.c (ffffffff8110b1ed)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
```
In kernel/time/alarmtimer.c (ffffffff81111f6a)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81114a3f)
Location: include/linux/rcupdate.h:753
Inline: True
```
```
In kernel/time/itimer.c (ffffffff81116f5a)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff811188c3)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff8111a3a1)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/module.c (ffffffff81125ad1)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/module.c:module_put
  - kernel/module.c:try_module_get
```
```
In kernel/cgroup/cgroup.c (ffffffff811343bf)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8113660c)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff8115b1fb)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/bpf/syscall.c (ffffffff811a1214)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:sockmap_get_from_fd
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/inode.c (ffffffff811a9446)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
```
```
In kernel/bpf/cpumap.c (ffffffff811af845)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/filemap.c (ffffffff811cc6d1)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/oom_kill.c (ffffffff811d0d61)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/page_alloc.c (ffffffff811d8911)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/page-writeback.c (ffffffff811dc8ef)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff811df900)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff811e7746)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/backing-dev.c (ffffffff811f69fd)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
```
```
In mm/percpu.c (ffffffff811f9c71)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
```
```
In mm/slab_common.c (ffffffff811fc4bf)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/compaction.c (ffffffff81201f5e)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/slub.c (ffffffff81247645)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/migrate.c (ffffffff8124967a)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_update_ratelimit
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff81259eea)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memory-failure.c (ffffffff81263e59)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff8126736c)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/cma.c (ffffffff8126acd7)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - mm/cma.c:cma_release
  - mm/cma.c:cma_alloc
```
```
In fs/open.c (ffffffff812712fb)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff8127baa8)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/exec.c:__set_task_comm
  - fs/exec.c:do_open_execat
```
```
In fs/inode.c (ffffffff812939ed)
Location: include/linux/rcupdate.h:753
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812a62f4)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/buffer.c (ffffffff812ae612)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/dax.c (ffffffff812cdad3)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/locks.c (ffffffff812d5aed)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/proc/base.c (ffffffff812f082b)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/ext4/balloc.c (ffffffff81308d19)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8130adad)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff81312d1b)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:get_reserved_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (ffffffff81314b71)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
```
In fs/ext4/fsmap.c (ffffffff81317539)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/fsync.c (ffffffff813179c0)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff81319bbe)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8131c4db)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff81327b4e)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8132ce32)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
```
```
In fs/ext4/mballoc.c (ffffffff813373f3)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff81341273)
Location: include/linux/rcupdate.h:753
Inline: True
```
```
In fs/ext4/super.c (ffffffff8134fc9a)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_drop_inode
```
```
In fs/jbd2/transaction.c (ffffffff8136538a)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_extend
```
```
In fs/jbd2/commit.c (ffffffff81367242)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
```
In fs/jbd2/checkpoint.c (ffffffff81369a8c)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8136e6ea)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In block/bio.c (ffffffff814489b0)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - block/bio.c:bio_endio
```
```
In block/elevator.c (ffffffff81449e14)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In block/blk-core.c (ffffffff8144d5c7)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_requeue_request
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
```
In block/blk-merge.c (ffffffff814574a1)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-mq.c (ffffffff8145d1cf)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-mq-sched.c (ffffffff81460db1)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
```
```
In block/bounce.c (ffffffff8146fa6f)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/blk-wbt.c (ffffffff8148431e)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:rwb_trace_step
```
```
In lib/swiotlb.c (ffffffff814be310)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_page
```
```
In arch/x86/lib/msr.c (ffffffff814c87c1)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff814dc2f8)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
```
```
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff8150213a)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
```
```
In drivers/acpi/sleep.c (ffffffff81539f98)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/clk/clk.c (ffffffff815a7e58)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815ca401)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff815cf8f2)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/char/random.c (ffffffff8160f083)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:mix_pool_bytes
  - drivers/char/random.c:__mix_pool_bytes
```
```
In drivers/iommu/iommu.c (ffffffff816259e6)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/base/syscore.c (ffffffff816483c1)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/qos.c (ffffffff81651593)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff81652ed5)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (ffffffff81658460)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/base/power/wakeup.c (ffffffff81658f68)
Location: include/linux/rcupdate.h:753
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff81663229)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
```
```
In drivers/base/regmap/regcache.c (ffffffff81667f66)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816a7a67)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816aa98d)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff816b1271)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b4269)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/scsi/scsi_lib.c:scsi_done
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/ata/libata-core.c (ffffffff816d254f)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff816dfc04)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/spi/spi.c (ffffffff816f5dd0)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/net/phy/mdio_bus.c (ffffffff816fc38e)
Location: include/linux/rcupdate.h:753
Inline: True
```
```
In drivers/net/tun.c (ffffffff816ffbb3)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/usb/host/xhci.c (ffffffff817614f3)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81763dc5)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817670d7)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:inc_enq
  - drivers/usb/host/xhci-ring.c:inc_deq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff8176c9e4)
Location: include/linux/rcupdate.h:753
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817738c4)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81776fb4)
Location: include/linux/rcupdate.h:753
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817918d5)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8179455a)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
```
```
In drivers/thermal/thermal_core.c (ffffffff8179ede3)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:handle_thermal_trip
```
```
In drivers/thermal/thermal_helpers.c (ffffffff817a3402)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:thermal_cdev_update
```
```
In drivers/thermal/fair_share.c (ffffffff817a3e29)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
```
```
In drivers/thermal/step_wise.c (ffffffff817a448e)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/thermal/step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/power_allocator.c (ffffffff817a539e)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff817a5ec8)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/md/dm.c (ffffffff817bf280)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-rq.c (ffffffff817cd21d)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff817ced8d)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/edac/ghes_edac.c (ffffffff817d2cd2)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817d6c74)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff817e2d2b)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff817e423e)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/mmc/core/core.c (ffffffff817e7a11)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/ras/ras.c (ffffffff8181bb89)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In net/core/sock.c (ffffffff8182bb90)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818372ec)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (ffffffff818390cc)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff8184b344)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:do_xdp_generic
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/filter.c (ffffffff8186876d)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect_map
  - net/core/filter.c:xdp_do_generic_redirect_map
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
```
```
In net/core/netpoll.c (ffffffff8186e490)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff8187ab72)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/tcp.c (ffffffff818a188f)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff818adad8)
Location: include/linux/rcupdate.h:753
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff818b655f)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b8bd7)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/udp.c (ffffffff818c84d6)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/fib_frontend.c (ffffffff818db160)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv4/fib_trie.c (ffffffff818df447)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff8191d1db)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81939409)
Location: include/linux/rcupdate.h:753
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
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
In init/main.c (ffffffff81002865)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/entry/common.c (ffffffff81003ea7)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810052e9)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/xen/multicalls.c (ffffffff8101b5da)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/mmu.c (ffffffff8101b8c2)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81021124)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81024eee)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102b412)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/kernel/process_64.c (ffffffff8102c830)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff8102edcd)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/irq.c (ffffffff81a01da4)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
```
```
In arch/x86/kernel/nmi.c (ffffffff810327f8)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff81a01e82)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/process.c (ffffffff819f1637)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103aa9e)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103b894)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104c3f6)
Location: include/linux/rcupdate.h:751
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81a01f57)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff81a02037)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81a02117)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff81a02412)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81a0279c)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105e1c7)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/mm/fault.c (ffffffff81076497)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_page_fault
  - arch/x86/mm/fault.c:do_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff8107da0c)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mpx.c (ffffffff81082d5f)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
```
In kernel/fork.c (ffffffff8108d9bf)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff8109178b)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffff81092c0b)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff81094eb4)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/signal.c (ffffffff810a0988)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810acb11)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/kthread.c (ffffffff810b3870)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/kmod.c (ffffffff810b7ebb)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810c1efc)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff819f1844)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/sched/fair.c (ffffffff810ca423)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810e3510)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
```
In kernel/power/qos.c (ffffffff810e76ff)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff810e8a94)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810e96a2)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (ffffffff810ea546)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/printk/printk.c (ffffffff826f6aa9)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_unlock
```
```
In kernel/irq/handle.c (ffffffff810f635e)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810fa9d6)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
```
```
In kernel/irq/matrix.c (ffffffff81101f41)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_remove_reserved
  - kernel/irq/matrix.c:irq_matrix_reserve
  - kernel/irq/matrix.c:irq_matrix_assign
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_assign_system
  - kernel/irq/matrix.c:irq_matrix_offline
  - kernel/irq/matrix.c:irq_matrix_online
```
```
In kernel/rcu/tree.c (ffffffff81106d37)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
```
```
In kernel/dma/swiotlb.c (ffffffff8110e144)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map_page
```
```
In kernel/time/timer.c (ffffffff8111521f)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/hrtimer.c (ffffffff819f0f03)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
```
In kernel/time/alarmtimer.c (ffffffff8111d7f8)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811211eb)
Location: include/linux/rcupdate.h:751
Inline: True
```
```
In kernel/time/itimer.c (ffffffff811238ba)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff8112546d)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff8112738f)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In kernel/module.c (ffffffff81133d4b)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/module.c:try_module_get
```
```
In kernel/cgroup/cgroup.c (ffffffff81142aef)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81144f47)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff81169db9)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/bpf/devmap.c (ffffffff811c9884)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In kernel/bpf/cpumap.c (ffffffff811ca352)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/rseq.c (ffffffff811ea669)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/filemap.c (ffffffff811ed49c)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/oom_kill.c (ffffffff811f201c)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page_alloc.c (ffffffff811f9a94)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/page-writeback.c (ffffffff811fc93c)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff81202053)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff81208d05)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/backing-dev.c (ffffffff81217ce4)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
```
```
In mm/percpu.c (ffffffff8121be9e)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
```
```
In mm/slab_common.c (ffffffff8121d61f)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/compaction.c (ffffffff8122332e)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/slub.c (ffffffff8126a57e)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/migrate.c (ffffffff8127171c)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff8127d246)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memory-failure.c (ffffffff81288153)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff8128bc58)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/cma.c (ffffffff8128f6b5)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - mm/cma.c:cma_release
  - mm/cma.c:cma_alloc
```
```
In fs/open.c (ffffffff81296f2f)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff812a2848)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/exec.c:__set_task_comm
  - fs/exec.c:do_open_execat
```
```
In fs/inode.c (ffffffff812b9d0d)
Location: include/linux/rcupdate.h:751
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812cce7a)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/buffer.c (ffffffff812d61f3)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/dax.c (ffffffff812f81ec)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/locks.c (ffffffff8130059e)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/proc/base.c (ffffffff8131df32)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/ext4/balloc.c (ffffffff81336bdc)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81338dca)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff81340be1)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:get_reserved_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (ffffffff813429a4)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
```
In fs/ext4/fsmap.c (ffffffff81345388)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/fsync.c (ffffffff8134585f)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff81347c99)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8134a3df)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff813558d0)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8135c83e)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
```
```
In fs/ext4/mballoc.c (ffffffff81365899)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff8136f44f)
Location: include/linux/rcupdate.h:751
Inline: True
```
```
In fs/ext4/super.c (ffffffff8137deaa)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/jbd2/transaction.c (ffffffff81393a8a)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_extend
```
```
In fs/jbd2/commit.c (ffffffff81396318)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
```
In fs/jbd2/checkpoint.c (ffffffff81398213)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8139cd4a)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In security/security.c (ffffffff82715e7b)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - security/security.c:security_init
  - security/security.c:security_init
  - security/security.c:security_init
```
```
In block/bio.c (ffffffff8147bb12)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - block/bio.c:bio_endio
```
```
In block/elevator.c (ffffffff8147cc1b)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In block/blk-core.c (ffffffff814817b5)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_requeue_request
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
```
In block/blk-merge.c (ffffffff8148a797)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-mq.c (ffffffff814909a7)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-mq-sched.c (ffffffff81494670)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
```
```
In block/bounce.c (ffffffff814a3d9b)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/blk-wbt.c (ffffffff814b94ce)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:rwb_trace_step
```
```
In arch/x86/lib/msr.c (ffffffff814f9761)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff8150a6cc)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
```
```
In drivers/pci/pcie/aer.c (ffffffff815340b6)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:cper_print_aer
```
```
In drivers/acpi/sleep.c (ffffffff8156fd7b)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/clk/clk.c (ffffffff815dfa45)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81602ca5)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff81607811)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/char/random.c (ffffffff81648b7d)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:mix_pool_bytes
  - drivers/char/random.c:__mix_pool_bytes
```
```
In drivers/iommu/iommu.c (ffffffff816609c6)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:__iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/base/syscore.c (ffffffff81683963)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/qos.c (ffffffff8168ce43)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff8168f1e1)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (ffffffff81693e4e)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/base/power/wakeup.c (ffffffff81694b98)
Location: include/linux/rcupdate.h:751
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff8169eb3b)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/base/regmap/regcache.c (ffffffff816a38b6)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816e3b47)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816e6f3d)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff816ed5c9)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f0b09)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/scsi/scsi_lib.c:scsi_done
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/ata/libata-core.c (ffffffff8170ec77)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff8171c377)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/spi/spi.c (ffffffff81733870)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817398d7)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff8173d20d)
Location: include/linux/rcupdate.h:751
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff817a1e97)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a404d)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817a7de5)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:inc_enq
  - drivers/usb/host/xhci-ring.c:inc_deq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff817afc45)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b3eab)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817b7d34)
Location: include/linux/rcupdate.h:751
Inline: True
```
```
In drivers/rtc/interface.c (ffffffff817cec45)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_offset
  - drivers/rtc/interface.c:rtc_read_offset
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817d435c)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff817d70b9)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
```
```
In drivers/thermal/thermal_core.c (ffffffff817e6389)
Location: include/linux/rcupdate.h:751
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (ffffffff817eb0ba)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:thermal_cdev_update
```
```
In drivers/thermal/fair_share.c (ffffffff817eb8fe)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
```
```
In drivers/thermal/step_wise.c (ffffffff817ebfcb)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/thermal/step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/power_allocator.c (ffffffff817ece9d)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff817ed948)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/md/dm.c (ffffffff818078da)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-rq.c (ffffffff81816025)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff81817940)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/edac/ghes_edac.c (ffffffff8181bab7)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8181f8fa)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8182bf30)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8182d545)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/mmc/core/core.c (ffffffff81831171)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/ras/ras.c (ffffffff81865c79)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In net/core/sock.c (ffffffff81875717)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818817ac)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - net/core/skbuff.c:__consume_stateless_skb
```
```
In net/core/datagram.c (ffffffff81883809)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff8189573e)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/filter.c (ffffffff818b517b)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
```
```
In net/core/netpoll.c (ffffffff818bf61e)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff818ccd45)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/tcp_input.c (ffffffff81904efa)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffff8190bdc9)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190e093)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/udp.c (ffffffff8191e3ea)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/af_inet.c (ffffffff8192b597)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
```
```
In net/ipv4/fib_trie.c (ffffffff819376e5)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff819741cf)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81992cfb)
Location: include/linux/rcupdate.h:751
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
</details>
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
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810d25f4)
Location: include/linux/rcupdate.h:871
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810d5a64)
Location: include/linux/rcupdate.h:847
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_handler
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
In arch/x86/mm/kmmio.c (ffffffff810de294)
Location: include/linux/rcupdate.h:848
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_handler
```
```
In lib/stackdepot.c (ffffffff81928960)
Location: include/linux/rcupdate.h:848
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_save_flags
  - lib/stackdepot.c:stack_depot_save_flags
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
