# Function: <code>rcu_read_unlock_sched_notrace</code>

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
In arch/x86/entry/common.c (ffffffff810036bd)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter_phase2
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810048d6)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/xen/enlighten.c (ffffffff8101bfbd)
Location: include/linux/rcupdate.h:1004
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
In arch/x86/xen/multicalls.c (ffffffff8101d90a)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_flush
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
```
```
In arch/x86/xen/mmu.c (ffffffff8101e184)
Location: include/linux/rcupdate.h:1004
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
In arch/x86/kernel/traps.c (ffffffff8102fd4c)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/irq.c (ffffffff81030c1b)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
```
```
In arch/x86/kernel/nmi.c (ffffffff8103244d)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff81033c71)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
```
```
In arch/x86/kernel/process.c (ffffffff81038e3a)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045153)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81048fa7)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff810490d7)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff810498f7)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff81050bb1)
Location: include/linux/rcupdate.h:1004
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
In arch/x86/kernel/apic/apic.c (ffffffff8182704b)
Location: include/linux/rcupdate.h:1004
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
In arch/x86/mm/fault.c (ffffffff8106b854)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:trace_do_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff810725a2)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:flush_tlb_current_task
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/mm/mpx.c (ffffffff810751ef)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
```
In kernel/fork.c (ffffffff8107f5c3)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff81081c5d)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/exit.c (ffffffff81082334)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - kernel/exit.c:delayed_put_task_struct
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff8108527f)
Location: include/linux/rcupdate.h:1004
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
In kernel/signal.c (ffffffff8108e625)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:get_signal
```
```
In kernel/kmod.c (ffffffff81096a23)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/workqueue.c (ffffffff81097e98)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
```
```
In kernel/kthread.c (ffffffff810a08a0)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/sched/core.c (ffffffff810aa377)
Location: include/linux/rcupdate.h:1004
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
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:idle_task_exit
```
```
In kernel/sched/fair.c (ffffffff810b48c6)
Location: include/linux/rcupdate.h:1004
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
In kernel/sched/idle.c (ffffffff810c3fa3)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In kernel/power/qos.c (ffffffff810cc3fd)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_work_fn
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/power/process.c (ffffffff810cdd63)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810ce1bf)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:pm_suspend
```
```
In kernel/power/hibernate.c (ffffffff810cf37c)
Location: include/linux/rcupdate.h:1004
Inline: True
```
```
In kernel/printk/printk.c (ffffffff810d73f3)
Location: include/linux/rcupdate.h:1004
Inline: True
```
```
In kernel/irq/handle.c (ffffffff810da959)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/handle.c:handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810de55c)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
```
```
In kernel/rcu/tree.c (ffffffff810e7103)
Location: include/linux/rcupdate.h:1004
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
In kernel/time/timer.c (ffffffff810ebaae)
Location: include/linux/rcupdate.h:1004
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
In kernel/time/hrtimer.c (ffffffff810eeaf5)
Location: include/linux/rcupdate.h:1004
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
In kernel/time/itimer.c (ffffffff810f03bb)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f2a76)
Location: include/linux/rcupdate.h:1004
Inline: True
```
```
In kernel/time/tick-common.c (ffffffff810fcc57)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_unfreeze
```
```
In kernel/time/tick-sched.c (ffffffff810fe9d9)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/module.c (ffffffff81105355)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - kernel/module.c:module_put
  - kernel/module.c:try_module_get
  - kernel/module.c:__module_get
  - kernel/module.c:free_module
  - kernel/module.c:load_module
```
```
In kernel/hung_task.c (ffffffff8113a709)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In mm/filemap.c (ffffffff8118de7b)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff81192790)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_prepare
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_hot_cold_page_list
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/page-writeback.c (ffffffff81198115)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - mm/page-writeback.c:domain_dirty_limits
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff8119ccde)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff811a08de)
Location: include/linux/rcupdate.h:1004
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
In mm/backing-dev.c (ffffffff811ae468)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:wait_iff_congested
```
```
In mm/mmu_context.c (ffffffff811afd70)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/slab_common.c (ffffffff811b2875)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/compaction.c (ffffffff811b5902)
Location: include/linux/rcupdate.h:1004
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
In mm/rmap.c (ffffffff811ca70b)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush
```
```
In mm/slub.c (ffffffff811eaeac)
Location: include/linux/rcupdate.h:1004
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
In mm/migrate.c (ffffffff811f0b3d)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_update_ratelimit
  - mm/migrate.c:migrate_pages
```
```
In mm/memory-failure.c (ffffffff8120168a)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - mm/memory-failure.c:action_result
```
```
In mm/cma.c (ffffffff812071c0)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - mm/cma.c:cma_alloc
  - mm/cma.c:cma_release
```
```
In fs/open.c (ffffffff8120b918)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff812121b9)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__set_task_comm
```
```
In fs/inode.c (ffffffff81227f5f)
Location: include/linux/rcupdate.h:1004
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81235dc4)
Location: include/linux/rcupdate.h:1004
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
In fs/buffer.c (ffffffff81242ac7)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/locks.c (ffffffff81261799)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
```
```
In fs/proc/base.c (ffffffff8127ad33)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In fs/ext4/balloc.c (ffffffff81290176)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/fsync.c (ffffffff81292bdc)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff812939e4)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81295e29)
Location: include/linux/rcupdate.h:1004
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
In fs/ext4/namei.c (ffffffff812a8221)
Location: include/linux/rcupdate.h:1004
Inline: True
```
```
In fs/ext4/super.c (ffffffff812a8eed)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:ext4_sync_fs
```
```
In fs/ext4/extents.c (ffffffff81322dfd)
Location: include/linux/rcupdate.h:1004
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
In fs/ext4/ext4_jbd2.c (ffffffff812cb894)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_forget
```
```
In fs/ext4/mballoc.c (ffffffff812ce72c)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
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
In fs/ext4/indirect.c (ffffffff812d95ee)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/extents_status.c (ffffffff812dac14)
Location: include/linux/rcupdate.h:1004
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
In fs/jbd2/transaction.c (ffffffff812e75ba)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff812e9a2a)
Location: include/linux/rcupdate.h:1004
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
In fs/jbd2/checkpoint.c (ffffffff812eca85)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff812f1a55)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In block/elevator.c (ffffffff813b4046)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In block/blk-core.c (ffffffff813b5786)
Location: include/linux/rcupdate.h:1004
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
```
```
In block/blk-mq.c (ffffffff813c315a)
Location: include/linux/rcupdate.h:1004
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
In block/bounce.c (ffffffff813d51c2)
Location: include/linux/rcupdate.h:1004
Inline: True
```
```
In lib/swiotlb.c (ffffffff814127ca)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_page
```
```
In drivers/gpio/gpiolib.c (ffffffff81425bac)
Location: include/linux/rcupdate.h:1004
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
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff8144970b)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
```
```
In drivers/acpi/sleep.c (ffffffff8147b98c)
Location: include/linux/rcupdate.h:1004
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff814d5287)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff814d9888)
Location: include/linux/rcupdate.h:1004
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
In drivers/char/random.c (ffffffff815119c4)
Location: include/linux/rcupdate.h:1004
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
In drivers/iommu/iommu.c (ffffffff81529f54)
Location: include/linux/rcupdate.h:1004
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
In drivers/base/syscore.c (ffffffff8154c369)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/qos.c (ffffffff81554d25)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff81556313)
Location: include/linux/rcupdate.h:1004
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
In drivers/base/power/main.c (ffffffff8155883e)
Location: include/linux/rcupdate.h:1004
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
In drivers/base/power/wakeup.c (ffffffff8155bb64)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
```
In drivers/base/regmap/regmap.c (ffffffff815629d9)
Location: include/linux/rcupdate.h:1004
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
In drivers/base/regmap/regcache.c (ffffffff81567341)
Location: include/linux/rcupdate.h:1004
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
In drivers/dma-buf/fence.c (ffffffff815a3c55)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - drivers/dma-buf/fence.c:fence_init
  - drivers/dma-buf/fence.c:fence_signal_locked
  - drivers/dma-buf/fence.c:fence_add_callback
```
```
In drivers/scsi/scsi_error.c (ffffffff815abbb3)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff815addd0)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/scsi/scsi_lib.c:scsi_done
```
```
In drivers/ata/libata-core.c (ffffffff815cb018)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_issue
```
```
In drivers/ata/libata-eh.c (ffffffff815d6c33)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/spi/spi.c (ffffffff815e7387)
Location: include/linux/rcupdate.h:1004
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
In drivers/usb/host/xhci.c (ffffffff8164b1ce)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816529ee)
Location: include/linux/rcupdate.h:1004
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8165745e)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/usb/host/xhci-hub.c (ffffffff8165d19e)
Location: include/linux/rcupdate.h:1004
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816623be)
Location: include/linux/rcupdate.h:1004
Inline: True
```
```
In drivers/i2c/i2c-core.c (ffffffff81679c14)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:__i2c_transfer
  - drivers/i2c/i2c-core.c:__i2c_transfer
  - drivers/i2c/i2c-core.c:__i2c_transfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
```
```
In drivers/thermal/thermal_core.c (ffffffff81685015)
Location: include/linux/rcupdate.h:1004
Inline: True
```
```
In drivers/thermal/fair_share.c (ffffffff81688eba)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
```
```
In drivers/thermal/step_wise.c (ffffffff8168949a)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - drivers/thermal/step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/power_allocator.c (ffffffff8168a3a3)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
```
In drivers/md/dm.c (ffffffff816a0b7f)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:map_request
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816aecd7)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff816ba702)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_timer_func
```
```
In drivers/cpuidle/cpuidle.c (ffffffff816bbaaa)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/clk/clk.c (ffffffff816e546f)
Location: include/linux/rcupdate.h:1004
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
In net/core/sock.c (ffffffff81702cc6)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81706092)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:consume_skb
```
```
In net/core/datagram.c (ffffffff8170d1ad)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff8171922e)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
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
In net/core/netpoll.c (ffffffff81739028)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/ipv4/udp.c (ffffffff81787009)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/fib_frontend.c (ffffffff8179af88)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv4/fib_trie.c (ffffffff8179ed27)
Location: include/linux/rcupdate.h:1004
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/udp.c (ffffffff817e32be)
Location: include/linux/rcupdate.h:1004
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
In arch/x86/entry/common.c (ffffffff81003922)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810049b1)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/xen/enlighten.c (ffffffff8101c255)
Location: include/linux/rcupdate.h:1013
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
In arch/x86/xen/multicalls.c (ffffffff8101d114)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/mmu.c (ffffffff8101e905)
Location: include/linux/rcupdate.h:1013
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
In arch/x86/kernel/process_64.c (ffffffff8102c830)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff8102edde)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/irq.c (ffffffff8102fcc4)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
```
```
In arch/x86/kernel/nmi.c (ffffffff81031574)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff81032e4a)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
```
```
In arch/x86/kernel/process.c (ffffffff810380be)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039aab)
Location: include/linux/rcupdate.h:1013
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
In arch/x86/kernel/fpu/signal.c (ffffffff8103a94b)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810451db)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81049170)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff81049290)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049ab0)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff81050f5a)
Location: include/linux/rcupdate.h:1013
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
In arch/x86/kernel/apic/apic.c (ffffffff810544c4)
Location: include/linux/rcupdate.h:1013
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
In arch/x86/mm/fault.c (ffffffff8106b72d)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:trace_do_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff810729d3)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:flush_tlb_current_task
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mpx.c (ffffffff81077797)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
```
In kernel/fork.c (ffffffff81082151)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff81084fa6)
Location: include/linux/rcupdate.h:1013
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
In kernel/exit.c (ffffffff810866b1)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff8108890c)
Location: include/linux/rcupdate.h:1013
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
In kernel/signal.c (ffffffff810934c5)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/kmod.c (ffffffff81099ddf)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/workqueue.c (ffffffff8109d6ec)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/kthread.c (ffffffff810a3f8d)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/sched/core.c (ffffffff810b1403)
Location: include/linux/rcupdate.h:1013
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
In kernel/sched/fair.c (ffffffff810bbe17)
Location: include/linux/rcupdate.h:1013
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
In kernel/sched/idle.c (ffffffff810c7c96)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In kernel/power/qos.c (ffffffff810d169e)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff810d28a3)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810d35ed)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (ffffffff810d3e15)
Location: include/linux/rcupdate.h:1013
Inline: True
```
```
In kernel/printk/printk.c (ffffffff810dc396)
Location: include/linux/rcupdate.h:1013
Inline: True
```
```
In kernel/irq/handle.c (ffffffff810dff4b)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810e3e9e)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
```
```
In kernel/rcu/tree.c (ffffffff810ed714)
Location: include/linux/rcupdate.h:1013
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
In kernel/time/timer.c (ffffffff810f5a00)
Location: include/linux/rcupdate.h:1013
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
In kernel/time/hrtimer.c (ffffffff810f7017)
Location: include/linux/rcupdate.h:1013
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
In kernel/time/itimer.c (ffffffff810f77f6)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f9b7f)
Location: include/linux/rcupdate.h:1013
Inline: True
```
```
In kernel/time/tick-common.c (ffffffff8110407b)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff81105d7d)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/module.c (ffffffff8111186a)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/module.c:module_put
  - kernel/module.c:try_module_get
  - kernel/module.c:__module_get
```
```
In kernel/hung_task.c (ffffffff81142c31)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In mm/filemap.c (ffffffff811a0eec)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff811ab211)
Location: include/linux/rcupdate.h:1013
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
In mm/page-writeback.c (ffffffff811af26c)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff811b20e7)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff811b9216)
Location: include/linux/rcupdate.h:1013
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
In mm/backing-dev.c (ffffffff811c7d34)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:bdi_register
```
```
In mm/slab_common.c (ffffffff811cc2d7)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/compaction.c (ffffffff811d1f34)
Location: include/linux/rcupdate.h:1013
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
In mm/rmap.c (ffffffff811e70e0)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush
```
```
In mm/slub.c (ffffffff8120e123)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/migrate.c (ffffffff8120fd74)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_update_ratelimit
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff8121c380)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memory-failure.c (ffffffff81225f03)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff81229073)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/cma.c (ffffffff8122ccd6)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - mm/cma.c:cma_release
  - mm/cma.c:cma_alloc
```
```
In fs/open.c (ffffffff81231630)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff8123aaff)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - fs/exec.c:__set_task_comm
  - fs/exec.c:do_open_execat
```
```
In fs/inode.c (ffffffff8125068f)
Location: include/linux/rcupdate.h:1013
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81262e9f)
Location: include/linux/rcupdate.h:1013
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
In fs/buffer.c (ffffffff8126ad97)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/locks.c (ffffffff8128ef40)
Location: include/linux/rcupdate.h:1013
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
In fs/proc/base.c (ffffffff812a9b76)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/ext4/balloc.c (ffffffff812bd68e)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/fsync.c (ffffffff812c0112)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff812c1b63)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812c930b)
Location: include/linux/rcupdate.h:1013
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
In fs/ext4/namei.c (ffffffff812d730e)
Location: include/linux/rcupdate.h:1013
Inline: True
```
```
In fs/ext4/super.c (ffffffff812e1452)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_drop_inode
```
```
In fs/ext4/extents.c (ffffffff812f9cfc)
Location: include/linux/rcupdate.h:1013
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
In fs/ext4/ext4_jbd2.c (ffffffff812fb4ff)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/mballoc.c (ffffffff81305a0e)
Location: include/linux/rcupdate.h:1013
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
In fs/ext4/indirect.c (ffffffff813093bd)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/extents_status.c (ffffffff8130b0cf)
Location: include/linux/rcupdate.h:1013
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
In fs/jbd2/transaction.c (ffffffff81315b6a)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_extend
```
```
In fs/jbd2/commit.c (ffffffff81317a56)
Location: include/linux/rcupdate.h:1013
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
In fs/jbd2/checkpoint.c (ffffffff8131a4ed)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8131f2a0)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In block/elevator.c (ffffffff813f7d1d)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In block/blk-core.c (ffffffff813fa5ff)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
```
In block/blk-merge.c (ffffffff814047ad)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-mq.c (ffffffff81409dde)
Location: include/linux/rcupdate.h:1013
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
In block/bounce.c (ffffffff8141ae80)
Location: include/linux/rcupdate.h:1013
Inline: True
```
```
In lib/swiotlb.c (ffffffff8145a514)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_page
```
```
In arch/x86/lib/msr.c (ffffffff81463cfc)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff81472293)
Location: include/linux/rcupdate.h:1013
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
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff81495c66)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
```
```
In drivers/acpi/sleep.c (ffffffff814c9fa8)
Location: include/linux/rcupdate.h:1013
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81525684)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff8152aa9b)
Location: include/linux/rcupdate.h:1013
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
In drivers/char/random.c (ffffffff81568066)
Location: include/linux/rcupdate.h:1013
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
In drivers/iommu/iommu.c (ffffffff8157dcef)
Location: include/linux/rcupdate.h:1013
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
In drivers/base/syscore.c (ffffffff8159e155)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/qos.c (ffffffff815a6ff6)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff815a88d9)
Location: include/linux/rcupdate.h:1013
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
In drivers/base/power/main.c (ffffffff815ad561)
Location: include/linux/rcupdate.h:1013
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
In drivers/base/power/wakeup.c (ffffffff815add6d)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
```
In drivers/base/regmap/regmap.c (ffffffff815b76ba)
Location: include/linux/rcupdate.h:1013
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
In drivers/base/regmap/regcache.c (ffffffff815bbf08)
Location: include/linux/rcupdate.h:1013
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
In drivers/dma-buf/fence.c (ffffffff815fad4b)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/dma-buf/fence.c:fence_init
  - drivers/dma-buf/fence.c:fence_add_callback
  - drivers/dma-buf/fence.c:fence_signal_locked
```
```
In drivers/scsi/scsi_error.c (ffffffff81603d70)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff816067d3)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/scsi/scsi_lib.c:scsi_done
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/ata/libata-core.c (ffffffff81623d86)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff8163071d)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/spi/spi.c (ffffffff81646c7c)
Location: include/linux/rcupdate.h:1013
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
In drivers/usb/host/xhci.c (ffffffff816acd77)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816b32f7)
Location: include/linux/rcupdate.h:1013
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816baacd)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/usb/host/xhci-hub.c (ffffffff816bd907)
Location: include/linux/rcupdate.h:1013
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816c25f7)
Location: include/linux/rcupdate.h:1013
Inline: True
```
```
In drivers/i2c/i2c-core.c (ffffffff816dbcc3)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:__i2c_transfer
  - drivers/i2c/i2c-core.c:__i2c_transfer
  - drivers/i2c/i2c-core.c:__i2c_transfer
```
```
In drivers/thermal/thermal_core.c (ffffffff816e4d33)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_cdev_update
```
```
In drivers/thermal/fair_share.c (ffffffff816e9bb7)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
```
```
In drivers/thermal/step_wise.c (ffffffff816ea1fa)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/thermal/step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/power_allocator.c (ffffffff816eb098)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/md/dm.c (ffffffff817020cc)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff8170f815)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8171063e)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8171c398)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_min_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8171d375)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/mmc/core/core.c (ffffffff81721589)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/clk/clk.c (ffffffff8174a8cd)
Location: include/linux/rcupdate.h:1013
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
In net/core/sock.c (ffffffff81768103)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8176e581)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (ffffffff81774806)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff81783971)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff817a52e1)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/ipv4/udp.c (ffffffff817f42d8)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_recvmsg
```
```
In net/ipv4/fib_frontend.c (ffffffff81808b95)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv4/fib_trie.c (ffffffff8180c98f)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff8184397c)
Location: include/linux/rcupdate.h:1013
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/udp.c (ffffffff8185184f)
Location: include/linux/rcupdate.h:1013
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
In arch/x86/entry/common.c (ffffffff810038e2)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004a31)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/xen/enlighten.c (ffffffff8101c925)
Location: include/linux/rcupdate.h:1018
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
In arch/x86/xen/multicalls.c (ffffffff8101d834)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/mmu.c (ffffffff8101eff5)
Location: include/linux/rcupdate.h:1018
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
In arch/x86/kernel/process_64.c (ffffffff8102c85c)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff8102ed9e)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/irq.c (ffffffff8102fc9f)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
```
```
In arch/x86/kernel/nmi.c (ffffffff810311c4)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff81032aca)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
```
```
In arch/x86/kernel/process.c (ffffffff818d3c19)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810393cb)
Location: include/linux/rcupdate.h:1018
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
In arch/x86/kernel/fpu/signal.c (ffffffff8103a204)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046dd3)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104b23b)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff8104b6eb)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104beab)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff8105380a)
Location: include/linux/rcupdate.h:1018
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
In arch/x86/kernel/apic/apic.c (ffffffff810571bf)
Location: include/linux/rcupdate.h:1018
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
In arch/x86/mm/fault.c (ffffffff8106f34d)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:trace_do_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff81076584)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:flush_tlb_current_task
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mpx.c (ffffffff8107b347)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
```
In kernel/fork.c (ffffffff81086bb1)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff81089f42)
Location: include/linux/rcupdate.h:1018
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
```
```
In kernel/exit.c (ffffffff8108b61d)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff8108d8a1)
Location: include/linux/rcupdate.h:1018
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
In kernel/signal.c (ffffffff81098455)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/kmod.c (ffffffff8109ed8f)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/workqueue.c (ffffffff810a225c)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/kthread.c (ffffffff810a95db)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/sched/core.c (ffffffff810b766f)
Location: include/linux/rcupdate.h:1018
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
In kernel/sched/fair.c (ffffffff810bd491)
Location: include/linux/rcupdate.h:1018
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
In kernel/sched/idle.c (ffffffff818d3e31)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d4bfc)
Location: include/linux/rcupdate.h:1018
Inline: True
```
```
In kernel/power/qos.c (ffffffff810d80fe)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff810d9453)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810da17d)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (ffffffff810da9a5)
Location: include/linux/rcupdate.h:1018
Inline: True
```
```
In kernel/printk/printk.c (ffffffff810e34cc)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
```
In kernel/irq/handle.c (ffffffff810e68a8)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810ea98d)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
```
```
In kernel/rcu/tree.c (ffffffff810f4677)
Location: include/linux/rcupdate.h:1018
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
In kernel/time/timer.c (ffffffff810fca40)
Location: include/linux/rcupdate.h:1018
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
In kernel/time/hrtimer.c (ffffffff810fe0d7)
Location: include/linux/rcupdate.h:1018
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
In kernel/time/alarmtimer.c (ffffffff81104e52)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8110750f)
Location: include/linux/rcupdate.h:1018
Inline: True
```
```
In kernel/time/itimer.c (ffffffff81109eb6)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff8110b77c)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff8110d4c9)
Location: include/linux/rcupdate.h:1018
Inline: True
```
```
In kernel/module.c (ffffffff81118e88)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/module.c:module_put
  - kernel/module.c:try_module_get
  - kernel/module.c:__module_get
```
```
In kernel/cgroup.c (ffffffff81128628)
Location: include/linux/rcupdate.h:1018
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
In kernel/hung_task.c (ffffffff8114ca1f)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In mm/filemap.c (ffffffff811b0aec)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff811bb854)
Location: include/linux/rcupdate.h:1018
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
In mm/page-writeback.c (ffffffff811bf90c)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff811c2743)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff811c9856)
Location: include/linux/rcupdate.h:1018
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
In mm/backing-dev.c (ffffffff811d7e54)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:bdi_register
```
```
In mm/slab_common.c (ffffffff811dc3a9)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/compaction.c (ffffffff811e1e0b)
Location: include/linux/rcupdate.h:1018
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
In mm/rmap.c (ffffffff811f847a)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush
```
```
In mm/slub.c (ffffffff81220163)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/migrate.c (ffffffff81221ea4)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_update_ratelimit
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff8122dd96)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memory-failure.c (ffffffff812384e3)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff8123b603)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/cma.c (ffffffff8123f200)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - mm/cma.c:cma_release
  - mm/cma.c:cma_alloc
```
```
In fs/open.c (ffffffff81243be0)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff8124d8af)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - fs/exec.c:__set_task_comm
  - fs/exec.c:do_open_execat
```
```
In fs/inode.c (ffffffff8126372f)
Location: include/linux/rcupdate.h:1018
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812762ef)
Location: include/linux/rcupdate.h:1018
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
In fs/buffer.c (ffffffff8127dec7)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/locks.c (ffffffff812a2dd9)
Location: include/linux/rcupdate.h:1018
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
In fs/proc/base.c (ffffffff812bf496)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/ext4/balloc.c (ffffffff812d2cde)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/fsync.c (ffffffff812d5742)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff812d71c3)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812def59)
Location: include/linux/rcupdate.h:1018
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
In fs/ext4/namei.c (ffffffff812ecf5e)
Location: include/linux/rcupdate.h:1018
Inline: True
```
```
In fs/ext4/super.c (ffffffff812f6f82)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_drop_inode
```
```
In fs/ext4/extents.c (ffffffff8130fccc)
Location: include/linux/rcupdate.h:1018
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
In fs/ext4/ext4_jbd2.c (ffffffff8131149f)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/mballoc.c (ffffffff8131b9cc)
Location: include/linux/rcupdate.h:1018
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
In fs/ext4/indirect.c (ffffffff8131f3cd)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/extents_status.c (ffffffff813210cf)
Location: include/linux/rcupdate.h:1018
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
In fs/jbd2/transaction.c (ffffffff8132bb5a)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_extend
```
```
In fs/jbd2/commit.c (ffffffff8132da46)
Location: include/linux/rcupdate.h:1018
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
In fs/jbd2/checkpoint.c (ffffffff813304dd)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81335322)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In block/elevator.c (ffffffff81411746)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In block/blk-core.c (ffffffff81413f7f)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
```
In block/blk-merge.c (ffffffff8141df0c)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-mq.c (ffffffff814247a6)
Location: include/linux/rcupdate.h:1018
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
In block/bounce.c (ffffffff814363c7)
Location: include/linux/rcupdate.h:1018
Inline: True
```
```
In block/blk-wbt.c (ffffffff8144a54e)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:rwb_trace_step
```
```
In lib/swiotlb.c (ffffffff81479036)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_page
```
```
In arch/x86/lib/msr.c (ffffffff81482f9c)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff814943b3)
Location: include/linux/rcupdate.h:1018
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
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff814b761d)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
```
```
In drivers/acpi/sleep.c (ffffffff814ebf03)
Location: include/linux/rcupdate.h:1018
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81533137)
Location: include/linux/rcupdate.h:1018
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
In drivers/xen/swiotlb-xen.c (ffffffff81551b5d)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff815570ba)
Location: include/linux/rcupdate.h:1018
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
In drivers/char/random.c (ffffffff8159478d)
Location: include/linux/rcupdate.h:1018
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
In drivers/iommu/iommu.c (ffffffff815aa28f)
Location: include/linux/rcupdate.h:1018
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
In drivers/base/syscore.c (ffffffff815cc705)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/qos.c (ffffffff815d57b6)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff815d73c7)
Location: include/linux/rcupdate.h:1018
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
In drivers/base/power/main.c (ffffffff815dc321)
Location: include/linux/rcupdate.h:1018
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
In drivers/base/power/wakeup.c (ffffffff815dcb3d)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
```
In drivers/base/regmap/regmap.c (ffffffff815e69a5)
Location: include/linux/rcupdate.h:1018
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
In drivers/base/regmap/regcache.c (ffffffff815eb318)
Location: include/linux/rcupdate.h:1018
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
In drivers/dma-buf/dma-fence.c (ffffffff8162901b)
Location: include/linux/rcupdate.h:1018
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
In drivers/dma-buf/sw_sync.c (ffffffff8162c5c9)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_error.c (ffffffff81633450)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81635cf3)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/scsi/scsi_lib.c:scsi_done
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/ata/libata-core.c (ffffffff81654906)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff8166186d)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/spi/spi.c (ffffffff81677d6c)
Location: include/linux/rcupdate.h:1018
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
In drivers/net/phy/mdio_bus.c (ffffffff8167d4bb)
Location: include/linux/rcupdate.h:1018
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff816db00c)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816e14a7)
Location: include/linux/rcupdate.h:1018
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816e8d2f)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/usb/host/xhci-hub.c (ffffffff816eb7b7)
Location: include/linux/rcupdate.h:1018
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816f05b7)
Location: include/linux/rcupdate.h:1018
Inline: True
```
```
In drivers/i2c/i2c-core.c (ffffffff8170c003)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:__i2c_transfer
  - drivers/i2c/i2c-core.c:__i2c_transfer
  - drivers/i2c/i2c-core.c:__i2c_transfer
```
```
In drivers/thermal/thermal_core.c (ffffffff81715c3c)
Location: include/linux/rcupdate.h:1018
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (ffffffff8171a023)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:thermal_cdev_update
```
```
In drivers/thermal/fair_share.c (ffffffff8171aa17)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
```
```
In drivers/thermal/step_wise.c (ffffffff8171b05a)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/thermal/step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/power_allocator.c (ffffffff8171bfb8)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/md/dm.c (ffffffff81733fae)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff81741840)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8174265e)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8174f74a)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_prepare_request
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8174ff55)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/mmc/core/core.c (ffffffff8175445d)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In net/core/sock.c (ffffffff817950f2)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8179ba41)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (ffffffff817a1b06)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff817b0f26)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff817d3d52)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/ipv4/udp.c (ffffffff81827df0)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
```
```
In net/ipv4/fib_frontend.c (ffffffff81839c76)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv4/fib_trie.c (ffffffff8183dc0c)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff818756ec)
Location: include/linux/rcupdate.h:1018
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
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
In arch/x86/entry/common.c (ffffffff81003771)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100497f)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/xen/multicalls.c (ffffffff8101a361)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/mmu.c (ffffffff8101a7ec)
Location: include/linux/rcupdate.h:752
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8101f79b)
Location: include/linux/rcupdate.h:752
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
In arch/x86/xen/mmu_pv.c (ffffffff81021c01)
Location: include/linux/rcupdate.h:752
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
In arch/x86/kernel/process_64.c (ffffffff8102aaf5)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff8102d0b7)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/irq.c (ffffffff8190e1ca)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
```
```
In arch/x86/kernel/nmi.c (ffffffff8102f4a7)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff8190e2cb)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
```
```
In arch/x86/kernel/process.c (ffffffff8190add5)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810372e5)
Location: include/linux/rcupdate.h:752
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
In arch/x86/kernel/fpu/signal.c (ffffffff81038154)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104659e)
Location: include/linux/rcupdate.h:752
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8190e3c6)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff8190e4c6)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8190e5c6)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff8190e88b)
Location: include/linux/rcupdate.h:752
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
In arch/x86/kernel/apic/apic.c (ffffffff8190eb60)
Location: include/linux/rcupdate.h:752
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
In arch/x86/mm/fault.c (ffffffff8106ea9d)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:trace_do_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff81074b1f)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mpx.c (ffffffff81079bca)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
```
In kernel/fork.c (ffffffff810838fa)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff81086e05)
Location: include/linux/rcupdate.h:752
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
```
```
In kernel/exit.c (ffffffff8108839c)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff8108a8d3)
Location: include/linux/rcupdate.h:752
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
In kernel/signal.c (ffffffff81095757)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/kmod.c (ffffffff8109c575)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/workqueue.c (ffffffff8109f75e)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/kthread.c (ffffffff810a6308)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/sched/core.c (ffffffff810b3848)
Location: include/linux/rcupdate.h:752
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
In kernel/sched/fair.c (ffffffff810bc995)
Location: include/linux/rcupdate.h:752
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
In kernel/sched/idle.c (ffffffff8190aff7)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d371d)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_commit
```
```
In kernel/power/qos.c (ffffffff810d713d)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff810d847a)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810d9278)
Location: include/linux/rcupdate.h:752
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
In kernel/power/hibernate.c (ffffffff810d9a85)
Location: include/linux/rcupdate.h:752
Inline: True
```
```
In kernel/printk/printk.c (ffffffff810e2af0)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
```
In kernel/irq/handle.c (ffffffff810e5eaf)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810ea044)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
```
```
In kernel/rcu/tree.c (ffffffff810f55ef)
Location: include/linux/rcupdate.h:752
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
In kernel/time/timer.c (ffffffff810fee92)
Location: include/linux/rcupdate.h:752
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
In kernel/time/hrtimer.c (ffffffff81100414)
Location: include/linux/rcupdate.h:752
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
In kernel/time/alarmtimer.c (ffffffff81106e7b)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811098ab)
Location: include/linux/rcupdate.h:752
Inline: True
```
```
In kernel/time/itimer.c (ffffffff8110bd34)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff8110d66c)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff8110f397)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/module.c (ffffffff8111aa4e)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/module.c:module_put
  - kernel/module.c:try_module_get
```
```
In kernel/cgroup/cgroup.c (ffffffff81127ec3)
Location: include/linux/rcupdate.h:752
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
In kernel/cgroup/cgroup-v1.c (ffffffff811299b3)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff8114e9a0)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/bpf/syscall.c (ffffffff811938f4)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/inode.c (ffffffff8119a0ba)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
```
```
In mm/filemap.c (ffffffff811b8038)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/oom_kill.c (ffffffff811bc155)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/page_alloc.c (ffffffff811c3b9b)
Location: include/linux/rcupdate.h:752
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
In mm/page-writeback.c (ffffffff811c7ad6)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff811cabbb)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff811d22d0)
Location: include/linux/rcupdate.h:752
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
In mm/backing-dev.c (ffffffff811e0a34)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
```
```
In mm/percpu.c (ffffffff811e470d)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
```
```
In mm/slab_common.c (ffffffff811e62c6)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/compaction.c (ffffffff811ebc0b)
Location: include/linux/rcupdate.h:752
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
In mm/slub.c (ffffffff8122bf2f)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/migrate.c (ffffffff8122db24)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_update_ratelimit
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff81239f20)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memory-failure.c (ffffffff81244023)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff81247244)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/cma.c (ffffffff8124aaf9)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - mm/cma.c:cma_release
  - mm/cma.c:cma_alloc
```
```
In fs/open.c (ffffffff8124f3a9)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff8125986f)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - fs/exec.c:__set_task_comm
  - fs/exec.c:do_open_execat
```
```
In fs/inode.c (ffffffff812710f0)
Location: include/linux/rcupdate.h:752
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81283788)
Location: include/linux/rcupdate.h:752
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
In fs/buffer.c (ffffffff8128ba86)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/dax.c (ffffffff812ab19b)
Location: include/linux/rcupdate.h:752
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
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/locks.c (ffffffff812b1fbb)
Location: include/linux/rcupdate.h:752
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
In fs/proc/base.c (ffffffff812cc0b1)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/ext4/balloc.c (ffffffff812e41db)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff812e63cc)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff812ee287)
Location: include/linux/rcupdate.h:752
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
In fs/ext4/extents_status.c (ffffffff812f00a0)
Location: include/linux/rcupdate.h:752
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
In fs/ext4/fsmap.c (ffffffff812f2ff9)
Location: include/linux/rcupdate.h:752
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
In fs/ext4/fsync.c (ffffffff812f3456)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff812f546f)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff812f7ef4)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff81303188)
Location: include/linux/rcupdate.h:752
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
In fs/ext4/ioctl.c (ffffffff81308410)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
```
```
In fs/ext4/mballoc.c (ffffffff81312c6e)
Location: include/linux/rcupdate.h:752
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
In fs/ext4/namei.c (ffffffff8131cc7a)
Location: include/linux/rcupdate.h:752
Inline: True
```
```
In fs/ext4/super.c (ffffffff8132b861)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_drop_inode
```
```
In fs/jbd2/transaction.c (ffffffff81340e0b)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_extend
```
```
In fs/jbd2/commit.c (ffffffff81342c3c)
Location: include/linux/rcupdate.h:752
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
In fs/jbd2/checkpoint.c (ffffffff81345412)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8134a0c3)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In block/bio.c (ffffffff8141daf2)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - block/bio.c:bio_endio
```
```
In block/elevator.c (ffffffff8141f353)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In block/blk-core.c (ffffffff8142251f)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_requeue_request
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
```
In block/blk-merge.c (ffffffff8142c2be)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-mq.c (ffffffff8143185c)
Location: include/linux/rcupdate.h:752
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
In block/blk-mq-sched.c (ffffffff814351d5)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
```
```
In block/bounce.c (ffffffff81443017)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/blk-wbt.c (ffffffff814583b5)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:rwb_trace_step
```
```
In lib/swiotlb.c (ffffffff81482397)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_page
```
```
In arch/x86/lib/msr.c (ffffffff8148c6fc)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff8149d8ff)
Location: include/linux/rcupdate.h:752
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
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff814c1f5a)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
```
```
In drivers/acpi/sleep.c (ffffffff814f88e4)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/clk/clk.c (ffffffff81545eab)
Location: include/linux/rcupdate.h:752
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
In drivers/xen/swiotlb-xen.c (ffffffff81566293)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff8156b716)
Location: include/linux/rcupdate.h:752
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
In drivers/char/random.c (ffffffff815a87bf)
Location: include/linux/rcupdate.h:752
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
In drivers/iommu/iommu.c (ffffffff815bf40d)
Location: include/linux/rcupdate.h:752
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
In drivers/base/syscore.c (ffffffff815e12c6)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/qos.c (ffffffff815ea216)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff815ebb11)
Location: include/linux/rcupdate.h:752
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
In drivers/base/power/main.c (ffffffff815f0e9d)
Location: include/linux/rcupdate.h:752
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
In drivers/base/power/wakeup.c (ffffffff815f19a6)
Location: include/linux/rcupdate.h:752
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff815fb08f)
Location: include/linux/rcupdate.h:752
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
In drivers/base/regmap/regcache.c (ffffffff815ffc44)
Location: include/linux/rcupdate.h:752
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
In drivers/dma-buf/dma-fence.c (ffffffff8163ec8d)
Location: include/linux/rcupdate.h:752
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
In drivers/dma-buf/sw_sync.c (ffffffff81641b97)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_error.c (ffffffff816481b3)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164af4d)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/scsi/scsi_lib.c:scsi_done
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/ata/libata-core.c (ffffffff81668f14)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff816768ab)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/spi/spi.c (ffffffff8168c44c)
Location: include/linux/rcupdate.h:752
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
In drivers/net/phy/mdio_bus.c (ffffffff816925bd)
Location: include/linux/rcupdate.h:752
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff816ef6ad)
Location: include/linux/rcupdate.h:752
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
In drivers/usb/host/xhci-mem.c (ffffffff816f70b3)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816fa6c9)
Location: include/linux/rcupdate.h:752
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
In drivers/usb/host/xhci-hub.c (ffffffff816ffda7)
Location: include/linux/rcupdate.h:752
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81705e17)
Location: include/linux/rcupdate.h:752
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817205d2)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81723182)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
```
```
In drivers/thermal/thermal_core.c (ffffffff8172d7a8)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:handle_thermal_trip
```
```
In drivers/thermal/thermal_helpers.c (ffffffff817322d3)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:thermal_cdev_update
```
```
In drivers/thermal/fair_share.c (ffffffff81732cc3)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
```
```
In drivers/thermal/step_wise.c (ffffffff81733305)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/thermal/step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/power_allocator.c (ffffffff81734260)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/md/dm.c (ffffffff8174d0cb)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-rq.c (ffffffff8175b002)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff8175cc38)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81760ce1)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8176d999)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8176ea26)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/mmc/core/core.c (ffffffff8177213e)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/ras/ras.c (ffffffff817a4a6c)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In net/core/sock.c (ffffffff817b37cf)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff817bdccb)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (ffffffff817bf76d)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff817d1274)
Location: include/linux/rcupdate.h:752
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
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/netpoll.c (ffffffff817f30d4)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/ipv4/udp.c (ffffffff81848af2)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/fib_frontend.c (ffffffff8185b20f)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv4/fib_trie.c (ffffffff8185f411)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff8189a533)
Location: include/linux/rcupdate.h:752
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
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
In arch/x86/entry/common.c (ffffffff810037b4)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004bdd)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/xen/multicalls.c (ffffffff8101ac14)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/mmu.c (ffffffff8101b0bf)
Location: include/linux/rcupdate.h:774
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81020544)
Location: include/linux/rcupdate.h:774
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
In arch/x86/xen/mmu_pv.c (ffffffff810226fa)
Location: include/linux/rcupdate.h:774
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
In arch/x86/hyperv/mmu.c (ffffffff8102a77d)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/kernel/process_64.c (ffffffff8102b856)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff8102de7a)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/irq.c (ffffffff81a02755)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
```
```
In arch/x86/kernel/nmi.c (ffffffff810314af)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff81a02823)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/process.c (ffffffff8199514e)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103958a)
Location: include/linux/rcupdate.h:774
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
In arch/x86/kernel/fpu/signal.c (ffffffff8103a3d9)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81049dd1)
Location: include/linux/rcupdate.h:774
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81a028f8)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff81a029c8)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81a02a98)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff81a02d03)
Location: include/linux/rcupdate.h:774
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
In arch/x86/kernel/apic/apic.c (ffffffff81a030bc)
Location: include/linux/rcupdate.h:774
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
In arch/x86/kernel/apic/vector.c (ffffffff8105b2ba)
Location: include/linux/rcupdate.h:774
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
In arch/x86/mm/fault.c (ffffffff81073b2e)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff8107ac92)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mpx.c (ffffffff8107fdfd)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
```
In kernel/fork.c (ffffffff8108a1dd)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff8108db9c)
Location: include/linux/rcupdate.h:774
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
```
```
In kernel/exit.c (ffffffff8108f125)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff81091489)
Location: include/linux/rcupdate.h:774
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
In kernel/signal.c (ffffffff8109c5d5)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810a5f90)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/kthread.c (ffffffff810ac89e)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/kmod.c (ffffffff810b10e7)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810baabb)
Location: include/linux/rcupdate.h:774
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
In kernel/sched/fair.c (ffffffff810c1025)
Location: include/linux/rcupdate.h:774
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
In kernel/sched/idle.c (ffffffff81995376)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810db2ef)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_commit
```
```
In kernel/power/qos.c (ffffffff810df0df)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff810e0570)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810e0f95)
Location: include/linux/rcupdate.h:774
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
In kernel/power/hibernate.c (ffffffff810e2186)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/printk/printk.c (ffffffff810ea992)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
```
In kernel/irq/handle.c (ffffffff810ee12b)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810f25b2)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
```
```
In kernel/irq/matrix.c (ffffffff810f9a2c)
Location: include/linux/rcupdate.h:774
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
In kernel/rcu/tree.c (ffffffff810ff3d7)
Location: include/linux/rcupdate.h:774
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
In kernel/time/timer.c (ffffffff81109c27)
Location: include/linux/rcupdate.h:774
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
In kernel/time/hrtimer.c (ffffffff8110b217)
Location: include/linux/rcupdate.h:774
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
In kernel/time/alarmtimer.c (ffffffff81111f94)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81114a7d)
Location: include/linux/rcupdate.h:774
Inline: True
```
```
In kernel/time/itimer.c (ffffffff81116f87)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff811188ef)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff8111a3ce)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/module.c (ffffffff81125af6)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/module.c:module_put
  - kernel/module.c:try_module_get
```
```
In kernel/cgroup/cgroup.c (ffffffff811343e6)
Location: include/linux/rcupdate.h:774
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
In kernel/cgroup/cgroup-v1.c (ffffffff81136636)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff8115b233)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/bpf/syscall.c (ffffffff811a10ef)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
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
In kernel/bpf/inode.c (ffffffff811a9472)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/inode.c:bpf_obj_pin_user
```
```
In kernel/bpf/cpumap.c (ffffffff811af876)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In mm/filemap.c (ffffffff811cc6fb)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/oom_kill.c (ffffffff811d0d88)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/page_alloc.c (ffffffff811d8941)
Location: include/linux/rcupdate.h:774
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
In mm/page-writeback.c (ffffffff811dc919)
Location: include/linux/rcupdate.h:774
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
In mm/swap.c (ffffffff811df92e)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff811e7773)
Location: include/linux/rcupdate.h:774
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
In mm/backing-dev.c (ffffffff811f6a27)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
```
```
In mm/percpu.c (ffffffff811f9c98)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
```
```
In mm/slab_common.c (ffffffff811fc508)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/compaction.c (ffffffff81201f85)
Location: include/linux/rcupdate.h:774
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
In mm/slub.c (ffffffff81247687)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/migrate.c (ffffffff812496a7)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_update_ratelimit
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff81259f35)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memory-failure.c (ffffffff81263e86)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff8126739b)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/cma.c (ffffffff8126ad0b)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - mm/cma.c:cma_release
  - mm/cma.c:cma_alloc
```
```
In fs/open.c (ffffffff8127132b)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff8127bad2)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - fs/exec.c:__set_task_comm
  - fs/exec.c:do_open_execat
```
```
In fs/inode.c (ffffffff81293a17)
Location: include/linux/rcupdate.h:774
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812a631d)
Location: include/linux/rcupdate.h:774
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
In fs/buffer.c (ffffffff812ae63c)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/dax.c (ffffffff812cdb00)
Location: include/linux/rcupdate.h:774
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
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/locks.c (ffffffff812d5b21)
Location: include/linux/rcupdate.h:774
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
In fs/proc/base.c (ffffffff812f0852)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/ext4/balloc.c (ffffffff81308d46)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8130adde)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff81312d4a)
Location: include/linux/rcupdate.h:774
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
In fs/ext4/extents_status.c (ffffffff81314ba2)
Location: include/linux/rcupdate.h:774
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
In fs/ext4/fsmap.c (ffffffff8131758d)
Location: include/linux/rcupdate.h:774
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
In fs/ext4/fsync.c (ffffffff813179ed)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff81319c01)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8131c536)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff81327b7b)
Location: include/linux/rcupdate.h:774
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
In fs/ext4/ioctl.c (ffffffff8132ce63)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
```
```
In fs/ext4/mballoc.c (ffffffff8133742c)
Location: include/linux/rcupdate.h:774
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
In fs/ext4/namei.c (ffffffff8134129d)
Location: include/linux/rcupdate.h:774
Inline: True
```
```
In fs/ext4/super.c (ffffffff8134fcc4)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_drop_inode
```
```
In fs/jbd2/transaction.c (ffffffff8136541d)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_extend
```
```
In fs/jbd2/commit.c (ffffffff8136726f)
Location: include/linux/rcupdate.h:774
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
In fs/jbd2/checkpoint.c (ffffffff81369abe)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8136e716)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In block/bio.c (ffffffff814489e0)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - block/bio.c:bio_endio
```
```
In block/elevator.c (ffffffff81449e40)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In block/blk-core.c (ffffffff8144d602)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_requeue_request
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
```
In block/blk-merge.c (ffffffff814574d1)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-mq.c (ffffffff8145d1f6)
Location: include/linux/rcupdate.h:774
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
In block/blk-mq-sched.c (ffffffff81460dde)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
```
```
In block/bounce.c (ffffffff8146fa99)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/blk-wbt.c (ffffffff81484115)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:rwb_trace_step
```
```
In lib/swiotlb.c (ffffffff814be34b)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_page
```
```
In arch/x86/lib/msr.c (ffffffff814c87f7)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff814dc338)
Location: include/linux/rcupdate.h:774
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
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff81502171)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
```
```
In drivers/acpi/sleep.c (ffffffff81539fc7)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/clk/clk.c (ffffffff815a7e81)
Location: include/linux/rcupdate.h:774
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
In drivers/xen/swiotlb-xen.c (ffffffff815ca435)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff815cf927)
Location: include/linux/rcupdate.h:774
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
In drivers/char/random.c (ffffffff8160f0be)
Location: include/linux/rcupdate.h:774
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
In drivers/iommu/iommu.c (ffffffff81625a13)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/base/syscore.c (ffffffff816483ef)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/qos.c (ffffffff816515c9)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff81652eff)
Location: include/linux/rcupdate.h:774
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
In drivers/base/power/main.c (ffffffff81658494)
Location: include/linux/rcupdate.h:774
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
In drivers/base/power/wakeup.c (ffffffff81658f99)
Location: include/linux/rcupdate.h:774
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff81663252)
Location: include/linux/rcupdate.h:774
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
In drivers/base/regmap/regcache.c (ffffffff81667f93)
Location: include/linux/rcupdate.h:774
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
In drivers/dma-buf/dma-fence.c (ffffffff816a7a94)
Location: include/linux/rcupdate.h:774
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
In drivers/dma-buf/sw_sync.c (ffffffff816aa9b4)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff816b1298)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b4290)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/scsi/scsi_lib.c:scsi_done
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/ata/libata-core.c (ffffffff816d2578)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff816dfc2e)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/spi/spi.c (ffffffff816f5dff)
Location: include/linux/rcupdate.h:774
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
In drivers/net/phy/mdio_bus.c (ffffffff816fc3d5)
Location: include/linux/rcupdate.h:774
Inline: True
```
```
In drivers/net/tun.c (ffffffff816ffbde)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/usb/host/xhci.c (ffffffff81761533)
Location: include/linux/rcupdate.h:774
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
In drivers/usb/host/xhci-mem.c (ffffffff81763dec)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8176710c)
Location: include/linux/rcupdate.h:774
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
In drivers/usb/host/xhci-hub.c (ffffffff8176ca0e)
Location: include/linux/rcupdate.h:774
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817738f2)
Location: include/linux/rcupdate.h:774
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
In drivers/usb/host/xhci-pci.c (ffffffff81776fde)
Location: include/linux/rcupdate.h:774
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8179190a)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff817945a2)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
```
```
In drivers/thermal/thermal_core.c (ffffffff8179ee10)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:handle_thermal_trip
```
```
In drivers/thermal/thermal_helpers.c (ffffffff817a342c)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:thermal_cdev_update
```
```
In drivers/thermal/fair_share.c (ffffffff817a3e55)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
```
```
In drivers/thermal/step_wise.c (ffffffff817a44ba)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/thermal/step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/power_allocator.c (ffffffff817a5425)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff817a5ef8)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/md/dm.c (ffffffff817bf2b7)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-rq.c (ffffffff817cd25b)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff817cee20)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/edac/ghes_edac.c (ffffffff817d2d6c)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817d6ca1)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff817e2d6a)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff817e4270)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/mmc/core/core.c (ffffffff817e7a3e)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/ras/ras.c (ffffffff8181bbb3)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In net/core/sock.c (ffffffff8182bbc5)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81837313)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (ffffffff81839100)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff8184b383)
Location: include/linux/rcupdate.h:774
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
In net/core/filter.c (ffffffff818687ac)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect_map
  - net/core/filter.c:xdp_do_generic_redirect_map
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
```
```
In net/core/netpoll.c (ffffffff8186e4c9)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff8187aba6)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/tcp.c (ffffffff818a18bc)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_set_state
```
```
In net/ipv4/tcp_input.c (ffffffff818adb02)
Location: include/linux/rcupdate.h:774
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff818b6588)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b8c01)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/udp.c (ffffffff818c8505)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/fib_frontend.c (ffffffff818db19c)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
```
In net/ipv4/fib_trie.c (ffffffff818df481)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff8191d20f)
Location: include/linux/rcupdate.h:774
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81939443)
Location: include/linux/rcupdate.h:774
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
In init/main.c (ffffffff8100288e)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/entry/common.c (ffffffff81003ed4)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005312)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/xen/multicalls.c (ffffffff8101b604)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/mmu.c (ffffffff8101b8e9)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
  - arch/x86/xen/mmu.c:xen_flush_tlb_all
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102114e)
Location: include/linux/rcupdate.h:772
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
In arch/x86/xen/mmu_pv.c (ffffffff81024f28)
Location: include/linux/rcupdate.h:772
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
In arch/x86/hyperv/mmu.c (ffffffff8102b43c)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/kernel/process_64.c (ffffffff8102c86d)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff8102edf7)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/irq.c (ffffffff81a01dcd)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
```
```
In arch/x86/kernel/nmi.c (ffffffff81032842)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff81a01eab)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/process.c (ffffffff819f1663)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103aac5)
Location: include/linux/rcupdate.h:772
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
In arch/x86/kernel/fpu/signal.c (ffffffff8103b8bb)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104c420)
Location: include/linux/rcupdate.h:772
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81a01f80)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff81a02060)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81a02140)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff81a0243b)
Location: include/linux/rcupdate.h:772
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
In arch/x86/kernel/apic/apic.c (ffffffff81a027c5)
Location: include/linux/rcupdate.h:772
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
In arch/x86/kernel/apic/vector.c (ffffffff8105e1fa)
Location: include/linux/rcupdate.h:772
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
In arch/x86/mm/fault.c (ffffffff8107647e)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff8107da42)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mpx.c (ffffffff81082d8d)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
```
In kernel/fork.c (ffffffff8108d9e9)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff8109179b)
Location: include/linux/rcupdate.h:772
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
```
```
In kernel/exit.c (ffffffff81092c32)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff81094ee0)
Location: include/linux/rcupdate.h:772
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
In kernel/signal.c (ffffffff810a09cd)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810acb3b)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/kthread.c (ffffffff810b389a)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/kmod.c (ffffffff810b7eec)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810c1f29)
Location: include/linux/rcupdate.h:772
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
In kernel/sched/idle.c (ffffffff819f186d)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/sched/fair.c (ffffffff810ca451)
Location: include/linux/rcupdate.h:772
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810e353a)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
```
In kernel/power/qos.c (ffffffff810e772f)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff810e8ac2)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810e96d7)
Location: include/linux/rcupdate.h:772
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
In kernel/power/hibernate.c (ffffffff810ea579)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/printk/printk.c (ffffffff826f6ad2)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_unlock
```
```
In kernel/irq/handle.c (ffffffff810f638b)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff810faa00)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
```
```
In kernel/irq/matrix.c (ffffffff81101f7c)
Location: include/linux/rcupdate.h:772
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
In kernel/rcu/tree.c (ffffffff81106d5e)
Location: include/linux/rcupdate.h:772
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
In kernel/dma/swiotlb.c (ffffffff8110e17f)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map_page
```
```
In kernel/time/timer.c (ffffffff81115246)
Location: include/linux/rcupdate.h:772
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
In kernel/time/hrtimer.c (ffffffff819f0f37)
Location: include/linux/rcupdate.h:772
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
In kernel/time/alarmtimer.c (ffffffff8111d825)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81121224)
Location: include/linux/rcupdate.h:772
Inline: True
```
```
In kernel/time/itimer.c (ffffffff811238e5)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff81125499)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff811273c2)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In kernel/module.c (ffffffff81133d70)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/module.c:try_module_get
```
```
In kernel/cgroup/cgroup.c (ffffffff81142b16)
Location: include/linux/rcupdate.h:772
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
In kernel/cgroup/cgroup-v1.c (ffffffff81144f71)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_remount
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff81169ded)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/bpf/devmap.c (ffffffff811c98d0)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In kernel/bpf/cpumap.c (ffffffff811ca385)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/rseq.c (ffffffff811ea6a1)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/filemap.c (ffffffff811ed4c6)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/oom_kill.c (ffffffff811f2043)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page_alloc.c (ffffffff811f9ac4)
Location: include/linux/rcupdate.h:772
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
In mm/page-writeback.c (ffffffff811fc966)
Location: include/linux/rcupdate.h:772
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
In mm/swap.c (ffffffff8120207d)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff81208d38)
Location: include/linux/rcupdate.h:772
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
In mm/backing-dev.c (ffffffff81217d0e)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
```
```
In mm/percpu.c (ffffffff8121bec5)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
```
```
In mm/slab_common.c (ffffffff8121d668)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/compaction.c (ffffffff81223355)
Location: include/linux/rcupdate.h:772
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
In mm/slub.c (ffffffff8126a5bd)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/migrate.c (ffffffff81271760)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff8127d2a5)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memory-failure.c (ffffffff81288180)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff8128bc85)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/cma.c (ffffffff8128f6e2)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - mm/cma.c:cma_release
  - mm/cma.c:cma_alloc
```
```
In fs/open.c (ffffffff81296f5f)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff812a2872)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - fs/exec.c:__set_task_comm
  - fs/exec.c:do_open_execat
```
```
In fs/inode.c (ffffffff812b9d34)
Location: include/linux/rcupdate.h:772
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812ccea1)
Location: include/linux/rcupdate.h:772
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
In fs/buffer.c (ffffffff812d621d)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/dax.c (ffffffff812f8219)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/locks.c (ffffffff813005cf)
Location: include/linux/rcupdate.h:772
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
In fs/proc/base.c (ffffffff8131df59)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/ext4/balloc.c (ffffffff81336c08)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81338dfb)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff81340c10)
Location: include/linux/rcupdate.h:772
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
In fs/ext4/extents_status.c (ffffffff813429d2)
Location: include/linux/rcupdate.h:772
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
In fs/ext4/fsmap.c (ffffffff813453d6)
Location: include/linux/rcupdate.h:772
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
In fs/ext4/fsync.c (ffffffff8134588c)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff81347cd6)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8134a426)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff813558fd)
Location: include/linux/rcupdate.h:772
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
In fs/ext4/ioctl.c (ffffffff8135c86b)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
```
```
In fs/ext4/mballoc.c (ffffffff813658d2)
Location: include/linux/rcupdate.h:772
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
In fs/ext4/namei.c (ffffffff8136f479)
Location: include/linux/rcupdate.h:772
Inline: True
```
```
In fs/ext4/super.c (ffffffff8137ded4)
Location: include/linux/rcupdate.h:772
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
In fs/jbd2/transaction.c (ffffffff81393b1a)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_extend
```
```
In fs/jbd2/commit.c (ffffffff81396345)
Location: include/linux/rcupdate.h:772
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
In fs/jbd2/checkpoint.c (ffffffff81398245)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8139cd74)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In security/security.c (ffffffff82715ea4)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - security/security.c:security_init
  - security/security.c:security_init
  - security/security.c:security_init
```
```
In block/bio.c (ffffffff8147bb42)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - block/bio.c:bio_endio
```
```
In block/elevator.c (ffffffff8147cc47)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In block/blk-core.c (ffffffff814817f0)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_requeue_request
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
```
In block/blk-merge.c (ffffffff8148a7c6)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-mq.c (ffffffff814909d1)
Location: include/linux/rcupdate.h:772
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
In block/blk-mq-sched.c (ffffffff8149469d)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
```
```
In block/bounce.c (ffffffff814a3dc5)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/blk-wbt.c (ffffffff814b94f9)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:rwb_trace_step
```
```
In arch/x86/lib/msr.c (ffffffff814f9797)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff8150a70f)
Location: include/linux/rcupdate.h:772
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
In drivers/pci/pcie/aer.c (ffffffff81534137)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:cper_print_aer
```
```
In drivers/acpi/sleep.c (ffffffff8156fdac)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/clk/clk.c (ffffffff815dfa6e)
Location: include/linux/rcupdate.h:772
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
In drivers/xen/swiotlb-xen.c (ffffffff81602cd9)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff8160783e)
Location: include/linux/rcupdate.h:772
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
In drivers/char/random.c (ffffffff81648bbb)
Location: include/linux/rcupdate.h:772
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
In drivers/iommu/iommu.c (ffffffff816609f3)
Location: include/linux/rcupdate.h:772
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
In drivers/base/syscore.c (ffffffff81683991)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/qos.c (ffffffff8168ce79)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff8168f20b)
Location: include/linux/rcupdate.h:772
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
In drivers/base/power/main.c (ffffffff81693e82)
Location: include/linux/rcupdate.h:772
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
In drivers/base/power/wakeup.c (ffffffff81694bc9)
Location: include/linux/rcupdate.h:772
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff8169eb64)
Location: include/linux/rcupdate.h:772
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
In drivers/base/regmap/regcache.c (ffffffff816a38e3)
Location: include/linux/rcupdate.h:772
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
In drivers/dma-buf/dma-fence.c (ffffffff816e3b74)
Location: include/linux/rcupdate.h:772
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
In drivers/dma-buf/sw_sync.c (ffffffff816e6f64)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff816ed5f3)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f0b30)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/scsi/scsi_lib.c:scsi_done
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/ata/libata-core.c (ffffffff8170eca0)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff8171c3a2)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/spi/spi.c (ffffffff8173389f)
Location: include/linux/rcupdate.h:772
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
In drivers/net/phy/mdio_bus.c (ffffffff81739917)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff8173d23d)
Location: include/linux/rcupdate.h:772
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff817a1ecd)
Location: include/linux/rcupdate.h:772
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
In drivers/usb/host/xhci-mem.c (ffffffff817a4074)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817a7e11)
Location: include/linux/rcupdate.h:772
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
In drivers/usb/host/xhci-hub.c (ffffffff817afc72)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b3eda)
Location: include/linux/rcupdate.h:772
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
In drivers/usb/host/xhci-pci.c (ffffffff817b7d5e)
Location: include/linux/rcupdate.h:772
Inline: True
```
```
In drivers/rtc/interface.c (ffffffff817cec6f)
Location: include/linux/rcupdate.h:772
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
In drivers/i2c/i2c-core-base.c (ffffffff817d4340)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff817d70f7)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
```
```
In drivers/thermal/thermal_core.c (ffffffff817e63b6)
Location: include/linux/rcupdate.h:772
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (ffffffff817eb0e4)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:thermal_cdev_update
```
```
In drivers/thermal/fair_share.c (ffffffff817eb92f)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
```
```
In drivers/thermal/step_wise.c (ffffffff817ebff7)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/thermal/step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/power_allocator.c (ffffffff817ecf04)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff817ed978)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/md/dm.c (ffffffff81807915)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-rq.c (ffffffff81816065)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff818179c1)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/edac/ghes_edac.c (ffffffff8181bb51)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8181f927)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8182bf62)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8182d572)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/mmc/core/core.c (ffffffff8183119e)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/ras/ras.c (ffffffff81865ca3)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In net/core/sock.c (ffffffff81875744)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818817d3)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - net/core/skbuff.c:__consume_stateless_skb
```
```
In net/core/datagram.c (ffffffff81883836)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff81895778)
Location: include/linux/rcupdate.h:772
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
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/filter.c (ffffffff818b536e)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
```
```
In net/core/netpoll.c (ffffffff818bf652)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff818ccd77)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/tcp_input.c (ffffffff81904f24)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffff8190bdf2)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190e0bd)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/udp.c (ffffffff8191e419)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
```
In net/ipv4/af_inet.c (ffffffff8192b5c4)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
```
```
In net/ipv4/fib_trie.c (ffffffff8193771d)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff81974203)
Location: include/linux/rcupdate.h:772
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81992d35)
Location: include/linux/rcupdate.h:772
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
In arch/x86/mm/kmmio.c (ffffffff810d1fc7)
Location: include/linux/rcupdate.h:892
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
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
In arch/x86/mm/kmmio.c (ffffffff810d5437)
Location: include/linux/rcupdate.h:868
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
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
In arch/x86/mm/kmmio.c (ffffffff810ddc07)
Location: include/linux/rcupdate.h:869
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
  - arch/x86/mm/kmmio.c:kmmio_handler
```
```
In lib/stackdepot.c (ffffffff819289cd)
Location: include/linux/rcupdate.h:869
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
