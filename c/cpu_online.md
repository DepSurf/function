# Function: <code>cpu_online</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff810039e1)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100538a)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/xen/enlighten.c (ffffffff81022d63)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81027d0d)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_mc_batch
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810290ac)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
  - arch/x86/xen/mmu_pv.c:xen_mc_issue
  - arch/x86/xen/mmu_pv.c:xen_mc_batch
```
```
In arch/x86/xen/multicalls.c (ffffffff8102c06a)
Location: include/linux/cpumask.h:893
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
In arch/x86/hyperv/mmu.c (ffffffff81032b70)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff81032f93)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81033f51)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/process_64.c (ffffffff81035242)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/irq.c (ffffffff810385db)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
```
```
In arch/x86/kernel/nmi.c (ffffffff8103a8af)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff8103be5d)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810432af)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810447c5)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81049366)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052c0b)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810560b5)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81057615)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8105837b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81058669)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105acdb)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_add
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106454c)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
```
```
In arch/x86/kernel/smp.c (ffffffff8106b9ed)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106dabb)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106f272)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81070615)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:native_smp_send_reschedule
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81071e90)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/mm/fault.c (ffffffff81c2a992)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff8108c214)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/fork.c (ffffffff810a3c16)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810a7f2b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:bringup_hibernate_cpu
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffff810a9dab)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff810abdf3)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/signal.c (ffffffff810ba85b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810c6c7f)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/kthread.c (ffffffff810cd8dc)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/reboot.c (ffffffff810d5197)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/smpboot.c (ffffffff810d637d)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_thread_fn
```
```
In kernel/kmod.c (ffffffff810d74fa)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810e6b02)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/sched/core.c:call_trace_sched_update_nr_running
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:send_call_function_single_ipi
  - kernel/sched/core.c:ttwu_do_wakeup
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:is_cpu_allowed
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810e7ffc)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:default_idle_call
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/sched/fair.c (ffffffff810ed3b7)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f7d81)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In kernel/sched/pelt.c (ffffffff8110513b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/membarrier.c (ffffffff8110adca)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
```
```
In kernel/power/qos.c (ffffffff8110f6e3)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff81110f92)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff811119ec)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/power/hibernate.c (ffffffff81112331)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/printk/printk.c (ffffffff831e757b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_unlock
```
```
In kernel/irq/handle.c (ffffffff8111e5cc)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff81123cb5)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
```
```
In kernel/irq/matrix.c (ffffffff8112bb56)
Location: include/linux/cpumask.h:893
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
In kernel/rcu/update.c (ffffffff8112c3a9)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/rcu/update.c:trc_inspect_reader
```
```
In kernel/rcu/tree.c (ffffffff811310a2)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/livepatch/transition.c (ffffffff81137d4b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/dma/swiotlb.c (ffffffff8113be47)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In kernel/entry/common.c (ffffffff8113cbb0)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/time/timer.c (ffffffff81143405)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:get_next_timer_interrupt
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/time/hrtimer.c (ffffffff811450b5)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
```
In kernel/time/alarmtimer.c (ffffffff8114bc3b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114fd5c)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff81152381)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff8115461f)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff81155de5)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:can_stop_idle_tick
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In kernel/smp.c (ffffffff8115c650)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:flush_smp_call_function_queue
  - kernel/smp.c:generic_exec_single
```
```
In kernel/module.c (ffffffff811645fc)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/module.c:module_put
  - kernel/module.c:try_module_get
```
```
In kernel/cgroup/cgroup.c (ffffffff811747d8)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81178c63)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff81179688)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119cf87)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811a099a)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In kernel/hung_task.c (ffffffff811a1f4e)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/trace/ring_buffer.c (ffffffff811b64be)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e225c)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_trace
```
```
In kernel/trace/bpf_trace.c (ffffffff811e81cc)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_trace_printk
```
```
In kernel/trace/trace_kdb.c (ffffffff811f118c)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/irq_work.c (ffffffff811f6f29)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/devmap.c (ffffffff81232be2)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_run_prog
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In kernel/bpf/cpumap.c (ffffffff812335ab)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/rseq.c (ffffffff8125ae0d)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:rseq_ip_fixup
```
```
In mm/filemap.c (ffffffff8125ed15)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_set_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/oom_kill.c (ffffffff81264fda)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (ffffffff81267c03)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_on_page_writeback_killable
  - mm/page-writeback.c:wait_on_page_writeback
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff8126da07)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff81278f11)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:pageout
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/backing-dev.c (ffffffff81286523)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
```
```
In mm/percpu.c (ffffffff8128b138)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
```
```
In mm/slab_common.c (ffffffff8128e3fc)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/compaction.c (ffffffff81293ba0)
Location: include/linux/cpumask.h:893
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
  - mm/compaction.c:compaction_defer_reset
  - mm/compaction.c:defer_compaction
```
```
In mm/mmap_lock.c (ffffffff8129bbd8)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
```
```
In mm/memory.c (ffffffff812a191f)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/mmap.c (ffffffff812ab11c)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/mmap.c:vm_unmapped_area
```
```
In mm/page_alloc.c (ffffffff812c41f2)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/slub.c (ffffffff812f03b3)
Location: include/linux/cpumask.h:893
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
In mm/migrate.c (ffffffff812f88e1)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff813043a7)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff81310045)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In mm/memory-failure.c (ffffffff81312d9d)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff81315fbf)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In fs/exec.c (ffffffff8132dda8)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
  - fs/exec.c:__set_task_comm
```
```
In fs/inode.c (ffffffff813487c7)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81360782)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_do_writeback
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
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/buffer.c (ffffffff8136ebd7)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/io_uring.c (ffffffff8139ef00)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_file_get
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_arm_poll_handler
  - fs/io_uring.c:io_async_wake
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:__io_async_wake
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:io_cqring_fill_event
  - fs/io_uring.c:io_queue_async_work
```
```
In fs/dax.c (ffffffff813a6e44)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_one
```
```
In fs/locks.c (ffffffff813b6335)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:leases_conflict
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/iomap/apply.c (ffffffff813c2231)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/iomap/apply.c:iomap_apply
  - fs/iomap/apply.c:iomap_apply
  - fs/iomap/apply.c:iomap_apply
```
```
In fs/iomap/buffered-io.c (ffffffff813c3a67)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_releasepage
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readpage
```
```
In fs/iomap/direct-io.c (ffffffff813c5b41)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/proc/base.c (ffffffff813d6ca4)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In fs/proc/stat.c (ffffffff813de0b8)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/proc/stat.c:get_iowait_time
  - fs/proc/stat.c:get_idle_time
```
```
In fs/ext4/balloc.c (ffffffff813f2306)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff813f49d0)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff813fafb1)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (ffffffff81400fb1)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/fsmap.c (ffffffff814035de)
Location: include/linux/cpumask.h:893
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
In fs/ext4/fsync.c (ffffffff81403b40)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff814064f8)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81408c2b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff814145a1)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_update_other_inode_time
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_readpage
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff81419a1d)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:ext4_shutdown
```
```
In fs/ext4/mballoc.c (ffffffff81421c73)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff81431724)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/super.c (ffffffff81444692)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_nfs_commit_metadata
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/fast_commit.c (ffffffff8145b596)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
```
In fs/jbd2/transaction.c (ffffffff8145fade)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
```
In fs/jbd2/commit.c (ffffffff81461c97)
Location: include/linux/cpumask.h:893
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
In fs/jbd2/checkpoint.c (ffffffff8146443e)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff814697c8)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:__jbd2_update_log_tail
```
```
In security/selinux/avc.c (ffffffff814d18a2)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_audit_post_callback
```
```
In block/bio.c (ffffffff81563ddd)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffff81568ee5)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-merge.c (ffffffff81570e90)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-mq.c (ffffffff81576c70)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-iocost.c (ffffffff81597254)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_activate
```
```
In block/mq-deadline.c (ffffffff8159936b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
```
```
In block/blk-wbt.c (ffffffff8159e822)
Location: include/linux/cpumask.h:893
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
In lib/random32.c (ffffffff815a7e3a)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - lib/random32.c:prandom_u32
```
```
In arch/x86/lib/msr.c (ffffffff815ef5f2)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff8161b294)
Location: include/linux/cpumask.h:893
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
In drivers/pwm/core.c (ffffffff81624e93)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_apply_state
  - drivers/pwm/core.c:pwm_device_request
```
```
In drivers/pci/pcie/aer.c (ffffffff81beb0c8)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In drivers/acpi/sleep.c (ffffffff8168460e)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/processor_throttling.c (ffffffff816e2873)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
```
In drivers/clk/clk.c (ffffffff816fcd64)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
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
In drivers/xen/cpu_hotplug.c (ffffffff81712032)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/xen/events/events_fifo.c (ffffffff8171a3f9)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817249b0)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff8172dd84)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/char/random.c (ffffffff8176fded)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:__mix_pool_bytes
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178ecb6)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/iommu.c (ffffffff8179d595)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_aux_detach_device
  - drivers/iommu/iommu.c:iommu_aux_attach_device
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/iommu/iommu.c:iommu_group_do_detach_device
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/base/syscore.c (ffffffff817b2d84)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/cpu.c (ffffffff817b6044)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
```
```
In drivers/base/power/qos.c (ffffffff817bedea)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff817c1ec8)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (ffffffff817c6997)
Location: include/linux/cpumask.h:893
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
In drivers/base/power/wakeup.c (ffffffff817c766e)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/regmap/regmap.c (ffffffff817d41d5)
Location: include/linux/cpumask.h:893
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
In drivers/base/regmap/regcache.c (ffffffff817d9202)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_read
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8181a752)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818201f4)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff81826cb9)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81829817)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/ata/libata-core.c (ffffffff81848196)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff81854b37)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/spi/spi.c (ffffffff8186e0a0)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81877833)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff8187d625)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/xen-netfront.c (ffffffff8188bce6)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff818f679c)
Location: include/linux/cpumask.h:893
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
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818f9468)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff818fbfec)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_trb
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_ring_ep_doorbell
  - drivers/usb/host/xhci-ring.c:inc_enq
  - drivers/usb/host/xhci-ring.c:inc_deq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81903e31)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81909d39)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/rtc/interface.c (ffffffff819259ba)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_offset
  - drivers/rtc/interface.c:rtc_read_offset
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_alarm_disable
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8192bb3b)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192e724)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff8193b9d7)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/hwmon/hwmon.c:hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:hwmon_attr_show
```
```
In drivers/thermal/thermal_core.c (ffffffff8193dea4)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (ffffffff81942285)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:__thermal_cdev_update
```
```
In drivers/thermal/gov_fair_share.c (ffffffff81944159)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/thermal/gov_fair_share.c:fair_share_throttle
```
```
In drivers/thermal/gov_step_wise.c (ffffffff81944743)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/thermal/gov_step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81945c49)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:pid_controller
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff819467f4)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81946b4b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_count
```
```
In drivers/md/md.c (ffffffff8194bb3c)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_discard_bio
```
```
In drivers/md/dm.c (ffffffff81961508)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
```
```
In drivers/md/dm-rq.c (ffffffff8196fa53)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff81970bd7)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197d384)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:store
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81987d51)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81989575)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/mmc/core/core.c (ffffffff8198d4c5)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819ab0a8)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:send_command
  - drivers/platform/chrome/cros_ec_proto.c:send_command
  - drivers/platform/chrome/cros_ec_proto.c:send_command
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
```
In drivers/devfreq/devfreq.c (ffffffff819b488a)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
```
In drivers/ras/ras.c (ffffffff819be822)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In drivers/interconnect/core.c (ffffffff819c26be)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
```
In net/core/sock.c (ffffffff819c9e9d)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819d83a0)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/core/skbuff.c:__consume_stateless_skb
```
```
In net/core/datagram.c (ffffffff819db56e)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff819f2d26)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:net_rps_send_ipi
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff819fd120)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/filter.c (ffffffff81a1bc30)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
```
```
In net/core/xdp.c (ffffffff81a1f7a4)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/page_pool.c (ffffffff81a23bf8)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/net-procfs.c (ffffffff81a250ce)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In net/core/netpoll.c (ffffffff81a25ed2)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/devlink.c (ffffffff81a3e068)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_health_report
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/sch_generic.c (ffffffff81a55646)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_api.c (ffffffff81a5b088)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff81a68f42)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81a71658)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
```
```
In net/ipv4/tcp_input.c (ffffffff81aaf9ad)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffff81ab8427)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abcb40)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/udp.c (ffffffff81acd9c1)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/af_inet.c (ffffffff81adce6b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
```
```
In net/ipv4/fib_trie.c (ffffffff81aec1a7)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff81b4224e)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b664e1)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/mptcp/protocol.c (ffffffff81baab05)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81bb2d4f)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81bb5e22)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In init/main.c (ffffffff81003a21)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810059a8)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/xen/enlighten.c (ffffffff81026dd4)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102c38a)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_mc_batch
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102d7f9)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
  - arch/x86/xen/mmu_pv.c:xen_mc_issue
  - arch/x86/xen/mmu_pv.c:xen_mc_batch
```
```
In arch/x86/xen/multicalls.c (ffffffff810308f7)
Location: include/linux/cpumask.h:893
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
In arch/x86/hyperv/mmu.c (ffffffff81037d05)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8103813e)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810391fe)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/process_64.c (ffffffff8103a525)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/irq.c (ffffffff8103d975)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
```
```
In arch/x86/kernel/nmi.c (ffffffff81040285)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff81041937)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8104961c)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104a8dd)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104fd7b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105b108)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105ec1f)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff8106045f)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8106124b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8106169e)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8106421b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_add
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106e54e)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
```
```
In arch/x86/kernel/smp.c (ffffffff810764c7)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff810792c8)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8107ac73)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8107c1b5)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:native_smp_send_reschedule
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8107dc87)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/mm/fault.c (ffffffff81d48f72)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff8109ba2b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/fork.c (ffffffff810b5433)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810b99bd)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:bringup_hibernate_cpu
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffff810bb8d8)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff810bda2a)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/softirq.c:__raise_softirq_irqoff
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/signal.c (ffffffff810cd0e7)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810d992f)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/kthread.c (ffffffff810e0ab7)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/reboot.c (ffffffff810e838b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/smpboot.c (ffffffff810e9640)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_thread_fn
```
```
In kernel/kmod.c (ffffffff810eadaa)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810fe0af)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/sched/core.c:call_trace_sched_update_nr_running
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:send_call_function_single_ipi
  - kernel/sched/core.c:ttwu_do_wakeup
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810ff6bc)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:default_idle_call
  - kernel/sched/idle.c:default_idle_call
```
```
In kernel/sched/fair.c (ffffffff81106047)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff8111259a)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In kernel/sched/pelt.c (ffffffff81122b7e)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/membarrier.c (ffffffff811295da)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
```
```
In kernel/power/qos.c (ffffffff8112f030)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff81130a7b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff811316d1)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/power/hibernate.c (ffffffff81132361)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/printk/printk.c (ffffffff832cb706)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_unlock
```
```
In kernel/irq/handle.c (ffffffff8113ea69)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff8114429f)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
```
```
In kernel/irq/matrix.c (ffffffff8114c6d1)
Location: include/linux/cpumask.h:893
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
In kernel/rcu/update.c (ffffffff8114ceb9)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/rcu/update.c:trc_inspect_reader
```
```
In kernel/rcu/tree.c (ffffffff81152e50)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/livepatch/transition.c (ffffffff8115aa9b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/dma/swiotlb.c (ffffffff8115ef47)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In kernel/entry/common.c (ffffffff8115fccd)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/time/timer.c (ffffffff811669b5)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:get_next_timer_interrupt
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/time/hrtimer.c (ffffffff81168945)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
```
In kernel/time/alarmtimer.c (ffffffff8116f952)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81173ed9)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff8117694e)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff81178e3c)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff8117aa75)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:can_stop_idle_tick
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In kernel/smp.c (ffffffff81181770)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:flush_smp_call_function_queue
  - kernel/smp.c:generic_exec_single
```
```
In kernel/module.c (ffffffff81189d10)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/module.c:module_put
  - kernel/module.c:try_module_get
```
```
In kernel/cgroup/cgroup.c (ffffffff8119b882)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811a0550)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff811a0fa2)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811c6cd4)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811ca0ba)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In kernel/hung_task.c (ffffffff811cb6f0)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/trace/ring_buffer.c (ffffffff811e06ae)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff8121234c)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_trace
```
```
In kernel/trace/bpf_trace.c (ffffffff81218e49)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_trace_printk
```
```
In kernel/trace/trace_kdb.c (ffffffff81222254)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/irq_work.c (ffffffff812284f9)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/devmap.c (ffffffff8126ccfb)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8126e71b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In kernel/rseq.c (ffffffff81296bff)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:rseq_ip_fixup
```
```
In mm/filemap.c (ffffffff8129c13e)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_set_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/oom_kill.c (ffffffff812a180b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (ffffffff812a4670)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_on_page_writeback_killable
  - mm/page-writeback.c:wait_on_page_writeback
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff812aa089)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff812b6d37)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:pageout
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/backing-dev.c (ffffffff812c5880)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
```
```
In mm/percpu.c (ffffffff812ca805)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
```
```
In mm/slab_common.c (ffffffff812ce333)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/compaction.c (ffffffff812d41c2)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_defer_reset
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/mmap_lock.c (ffffffff812dc6e5)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
```
```
In mm/memory.c (ffffffff812e2902)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/mmap.c (ffffffff812ec7e9)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/mmap.c:vm_unmapped_area
```
```
In mm/page_alloc.c (ffffffff8130809c)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/slub.c (ffffffff81338d35)
Location: include/linux/cpumask.h:893
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
In mm/kfence/report.c (ffffffff81cc245e)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/kfence/report.c:kfence_report_error
```
```
In mm/migrate.c (ffffffff81342f95)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff8134e0d7)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff8135b384)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In mm/memory-failure.c (ffffffff8135e8c2)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff813620c9)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In fs/exec.c (ffffffff8137b585)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
  - fs/exec.c:__set_task_comm
```
```
In fs/inode.c (ffffffff81396356)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813aedff)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_do_writeback
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
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/buffer.c (ffffffff813bc714)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/io_uring.c (ffffffff813ef1d9)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_file_get_normal
  - fs/io_uring.c:io_drain_req
  - fs/io_uring.c:io_arm_poll_handler
  - fs/io_uring.c:io_async_wake
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:__io_async_wake
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:io_cqring_fill_event
  - fs/io_uring.c:io_queue_async_work
```
```
In fs/dax.c (ffffffff813f6d02)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_one
```
```
In fs/locks.c (ffffffff81406032)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:leases_conflict
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/iomap/buffered-io.c (ffffffff81413fa4)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_releasepage
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readpage
```
```
In fs/iomap/direct-io.c (ffffffff81415fde)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/iomap/iter.c (ffffffff814167d9)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/iomap/iter.c:iomap_iter
  - fs/iomap/iter.c:iomap_iter_done
  - fs/iomap/iter.c:iomap_iter_done
```
```
In fs/proc/base.c (ffffffff814283e3)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In fs/proc/stat.c (ffffffff8142f858)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/proc/stat.c:get_iowait_time
  - fs/proc/stat.c:get_idle_time
```
```
In fs/ext4/balloc.c (ffffffff814442e3)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81446bb0)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff8144d399)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (ffffffff814535ce)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/fsmap.c (ffffffff81455d6b)
Location: include/linux/cpumask.h:893
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
In fs/ext4/fsync.c (ffffffff81456310)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff81458d61)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8145b6a5)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff81467921)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_update_other_inode_time
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_readpage
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8146cc0d)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:ext4_shutdown
```
```
In fs/ext4/mballoc.c (ffffffff814749c7)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff81484f31)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/super.c (ffffffff81498492)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_nfs_commit_metadata
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/fast_commit.c (ffffffff814b0d76)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_update_stats
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
```
In fs/jbd2/transaction.c (ffffffff814b4f8e)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
```
In fs/jbd2/commit.c (ffffffff814b718a)
Location: include/linux/cpumask.h:893
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
In fs/jbd2/checkpoint.c (ffffffff814b9a79)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff814bfc68)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_shrink_count
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
```
```
In security/selinux/avc.c (ffffffff8152a5ff)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_audit_post_callback
```
```
In block/bio.c (ffffffff815c7ab9)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffff815cd18c)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-merge.c (ffffffff815d553b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-mq.c (ffffffff815db9d2)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_start_request
```
```
In block/blk-iocost.c (ffffffff815fe86a)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_activate
```
```
In block/mq-deadline.c (ffffffff81601a35)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_request
```
```
In block/blk-wbt.c (ffffffff81606fc3)
Location: include/linux/cpumask.h:893
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
In lib/random32.c (ffffffff81610db7)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - lib/random32.c:prandom_u32
```
```
In arch/x86/lib/msr.c (ffffffff8165c6ff)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff8168a79e)
Location: include/linux/cpumask.h:893
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
In drivers/pwm/core.c (ffffffff816946a6)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_apply_state
  - drivers/pwm/core.c:pwm_device_request
```
```
In drivers/pci/pcie/aer.c (ffffffff816b7129)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_error
```
```
In drivers/acpi/sleep.c (ffffffff816f98ab)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/processor_throttling.c (ffffffff8175b4b3)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
```
In drivers/clk/clk.c (ffffffff81776dde)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
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
In drivers/xen/cpu_hotplug.c (ffffffff8178eaa2)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/xen/events/events_fifo.c (ffffffff81798af2)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a37fc)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff817ab9c0)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/char/random.c (ffffffff817f57ad)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:__mix_pool_bytes
```
```
In drivers/iommu/intel/dmar.c (ffffffff81816546)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/svm.c (ffffffff81821558)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/iommu/iommu.c (ffffffff818262e2)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_aux_detach_device
  - drivers/iommu/iommu.c:iommu_aux_attach_device
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/iommu/iommu.c:iommu_group_do_detach_device
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/base/syscore.c (ffffffff8183c23f)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/cpu.c (ffffffff8183f5db)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
```
```
In drivers/base/devres.c (ffffffff818411c7)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/devres.c:devm_add_action
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_close_group
  - drivers/base/devres.c:devres_open_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
  - drivers/base/devres.c:devres_get
```
```
In drivers/base/power/qos.c (ffffffff81849157)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff8184bd75)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (ffffffff81850d51)
Location: include/linux/cpumask.h:893
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
In drivers/base/power/wakeup.c (ffffffff81851cd9)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
```
In drivers/base/regmap/regmap.c (ffffffff8185f512)
Location: include/linux/cpumask.h:893
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
In drivers/base/regmap/regcache.c (ffffffff818649a2)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_read
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818a4e4f)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818aa8d0)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff818b2606)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b5374)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/ata/libata-core.c (ffffffff818d51eb)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff818e2ef6)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/spi/spi.c (ffffffff818fe13d)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81908576)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff8190eca2)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/xen-netfront.c (ffffffff8191ec6e)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81994a83)
Location: include/linux/cpumask.h:893
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
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81997ff0)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8199aed9)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_trb
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
  - drivers/usb/host/xhci-ring.c:xhci_ring_ep_doorbell
  - drivers/usb/host/xhci-ring.c:inc_enq
  - drivers/usb/host/xhci-ring.c:inc_deq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff819a405c)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819aa5a6)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/rtc/interface.c (ffffffff819c8923)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_offset
  - drivers/rtc/interface.c:rtc_read_offset
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_alarm_disable
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819cecff)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d1954)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff819e0204)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/hwmon/hwmon.c:hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:hwmon_attr_show
```
```
In drivers/thermal/thermal_core.c (ffffffff819e2760)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (ffffffff819e6b9c)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:__thermal_cdev_update
```
```
In drivers/thermal/gov_fair_share.c (ffffffff819e8b19)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/thermal/gov_fair_share.c:fair_share_throttle
```
```
In drivers/thermal/gov_step_wise.c (ffffffff819e916b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/thermal/gov_step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff819ea676)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:pid_controller
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff819eb1f1)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff819eb614)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_count
```
```
In drivers/md/md.c (ffffffff819f0d39)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_discard_bio
```
```
In drivers/md/dm.c (ffffffff81a0b119)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
```
```
In drivers/md/dm-rq.c (ffffffff81a18393)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff81a194f4)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a26423)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:store
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81a31b0c)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81a33a8d)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/mmc/core/core.c (ffffffff81a38b0f)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81a58b71)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:send_command
  - drivers/platform/chrome/cros_ec_proto.c:send_command
  - drivers/platform/chrome/cros_ec_proto.c:send_command
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
```
In drivers/devfreq/devfreq.c (ffffffff81a633c7)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
```
In drivers/ras/ras.c (ffffffff81a6ddbf)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In drivers/interconnect/core.c (ffffffff81a71f68)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
```
In net/core/sock.c (ffffffff81a792e3)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_error_report
```
```
In net/core/skbuff.c (ffffffff81a881ed)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/core/skbuff.c:__consume_stateless_skb
```
```
In net/core/datagram.c (ffffffff81a8abeb)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff81aa3b87)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:net_rps_send_ipi
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_qdisc_enqueue
```
```
In net/core/neighbour.c (ffffffff81aaf825)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/filter.c (ffffffff81acf401)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
```
```
In net/core/xdp.c (ffffffff81ad370c)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/page_pool.c (ffffffff81ad8281)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/net-procfs.c (ffffffff81ad9b6a)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In net/core/netpoll.c (ffffffff81adac34)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/devlink.c (ffffffff81af62cc)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_health_report
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/sch_generic.c (ffffffff81b0e1c8)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_api.c (ffffffff81b1423d)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff81b2250f)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81b2ad78)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
```
```
In net/ipv4/tcp_input.c (ffffffff81b6c754)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffff81b75614)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b798d0)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/udp.c (ffffffff81b8c39b)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/af_inet.c (ffffffff81b9c258)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
```
```
In net/ipv4/fib_trie.c (ffffffff81bac3f9)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff81c07704)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2fa01)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/mptcp/protocol.c (ffffffff81c7c32b)
Location: include/linux/cpumask.h:893
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81c812e8)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81c84953)
Location: include/linux/cpumask.h:893
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool cpu_online(unsigned int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81001654)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
Direct callers:
  - init/main.c:trace_initcall_level
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004b43)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/xen/enlighten.c (ffffffff8102af3e)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81030ee6)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_mc_batch
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810325e5)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
  - arch/x86/xen/mmu_pv.c:xen_mc_batch
```
```
In arch/x86/xen/multicalls.c (ffffffff81035f63)
Location: include/linux/cpumask.h:919
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
In arch/x86/hyperv/mmu.c (ffffffff8103df2e)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8103e3f4)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8104003a)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/process_64.c (ffffffff81041590)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/irq.c (ffffffff81045546)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
```
```
In arch/x86/kernel/nmi.c (ffffffff81047a05)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff81049630)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810539e6)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054dda)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:fpregs_restore_userregs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810555f4)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpregs_restore_userregs
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8105adda)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810678f2)
Location: include/linux/cpumask.h:919
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106b09d)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff8106cc5d)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8106dc07)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8106deca)
Location: include/linux/cpumask.h:919
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81070d7b)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_add
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107bdae)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
```
```
In arch/x86/kernel/smp.c (ffffffff810855c0)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff8108810e)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_cpu0_nmi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81089d0f)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8108b4f5)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:native_smp_send_reschedule
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8108bd77)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/mm/fault.c (ffffffff81f1833d)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff810aee75)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/fork.c (ffffffff810cb782)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
```
```
In kernel/panic.c (ffffffff81e53573)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/panic.c:__warn
```
```
In kernel/cpu.c (ffffffff810d0448)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:bringup_hibernate_cpu
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffff810d2325)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:delayed_put_task_struct
Direct callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff810d4a34)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/softirq.c:__raise_softirq_irqoff
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/signal.c (ffffffff810e50a8)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/workqueue.c (ffffffff810f361e)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/kthread.c (ffffffff810fabe1)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/reboot.c (ffffffff81102cc9)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/smpboot.c (ffffffff81103e47)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_thread_fn
```
```
In kernel/kmod.c (ffffffff81105bf6)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff8111ab4b)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/sched/core.c:call_trace_sched_update_nr_running
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:send_call_function_single_ipi
  - kernel/sched/core.c:ttwu_do_wakeup
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff81121613)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff811362ca)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:default_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff8114187a)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_wait_end
```
```
In kernel/locking/mutex.c (ffffffff81f23846)
Location: include/linux/cpumask.h:919
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81f24e07)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff81f25995)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (ffffffff81f25eb4)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
```
In kernel/locking/qspinlock.c (ffffffff8114f55a)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f2776b)
Location: include/linux/cpumask.h:919
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff8114fabe)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/qos.c (ffffffff81150369)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_remove_request
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff81152302)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff8115313e)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/power/hibernate.c (ffffffff811540db)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/printk/printk.c (ffffffff8115d41d)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/printk/printk.c:__pr_flush
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:printk_sprint
Direct callers:
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
```
```
In kernel/irq/handle.c (ffffffff811620df)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff81167e05)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
```
```
In kernel/irq/matrix.c (ffffffff8117219c)
Location: include/linux/cpumask.h:919
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
In kernel/rcu/update.c (ffffffff811734c9)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/rcu/update.c:trc_inspect_reader
```
```
In kernel/rcu/tree.c (ffffffff8117d1ad)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
```
In kernel/livepatch/transition.c (ffffffff81184361)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/dma/swiotlb.c (ffffffff81189155)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In kernel/entry/common.c (ffffffff8118a1de)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/module/main.c (ffffffff8118fc49)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
  - kernel/module/main.c:module_put
  - kernel/module/main.c:try_module_get
```
```
In kernel/time/timer.c (ffffffff8119a0d5)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:get_next_timer_interrupt
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/time/hrtimer.c (ffffffff8119c495)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:hrtimer_try_to_cancel
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
```
In kernel/time/alarmtimer.c (ffffffff811a3ead)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811a8b85)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff811abdc6)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff811ae118)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff811b0325)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:can_stop_idle_tick
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In kernel/smp.c (ffffffff811b7d5c)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:generic_exec_single
```
```
In kernel/cgroup/cgroup.c (ffffffff811cbabb)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d0cce)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff811d17e0)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811fa666)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811fdcf9)
Location: include/linux/cpumask.h:919
Inline: True
```
```
In kernel/hung_task.c (ffffffff811ff40a)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/trace/ring_buffer.c (ffffffff81214901)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
```
```
In kernel/trace/trace_events_hist.c (ffffffff8124eb7a)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_trace
```
```
In kernel/trace/bpf_trace.c (ffffffff812573a7)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_trace_vprintk
  - kernel/trace/bpf_trace.c:bpf_trace_printk
```
```
In kernel/trace/trace_kdb.c (ffffffff81261f8d)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/irq_work.c (ffffffff81269571)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/devmap.c (ffffffff812bba0e)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff812bd62c)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In kernel/rseq.c (ffffffff812ec9cd)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_update_cpu_id
```
```
In mm/filemap.c (ffffffff812f2718)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_set_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/oom_kill.c (ffffffff812f9517)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:wake_oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (ffffffff812fcadb)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_wait_writeback_killable
  - mm/page-writeback.c:folio_wait_writeback
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff8130343b)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__folio_activate
```
```
In mm/vmscan.c (ffffffff81312c2f)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:pageout
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/backing-dev.c (ffffffff813245e2)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
```
```
In mm/percpu.c (ffffffff813275c6)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
```
```
In mm/slab_common.c (ffffffff8132c3e4)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/compaction.c (ffffffff813330f0)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_defer_reset
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/mmap_lock.c (ffffffff8133c6d9)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
```
```
In mm/memory.c (ffffffff8134315a)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/mlock.c (ffffffff8134bf75)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/mlock.c:mlock_page_drain_remote
```
```
In mm/mmap.c (ffffffff8134f677)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/mmap.c:vm_unmapped_area
```
```
In mm/rmap.c (ffffffff8135e90a)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/page_alloc.c (ffffffff8137036d)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/slub.c (ffffffff813aa986)
Location: include/linux/cpumask.h:919
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
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/kfence/report.c (ffffffff81e7488a)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/kfence/report.c:kfence_report_error
```
```
In mm/migrate.c (ffffffff813b56f7)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff813c1ede)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
```
```
In mm/khugepaged.c (ffffffff813c7368)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff813d4a88)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In mm/memory-failure.c (ffffffff813d8b9c)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff813deb7b)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In fs/exec.c (ffffffff813fa656)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
  - fs/exec.c:__set_task_comm
```
```
In fs/inode.c (ffffffff81417769)
Location: include/linux/cpumask.h:919
Inline: True
```
```
In fs/fs-writeback.c (ffffffff814334ab)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/buffer.c (ffffffff814463d0)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/dax.c (ffffffff81469902)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_one
```
```
In fs/locks.c (ffffffff8147982b)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:leases_conflict
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/iomap/iter.c (ffffffff81487d65)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/iomap/iter.c:iomap_iter
  - fs/iomap/iter.c:iomap_iter_done
  - fs/iomap/iter.c:iomap_iter_done
```
```
In fs/iomap/buffered-io.c (ffffffff8148a680)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_folio
```
```
In fs/iomap/direct-io.c (ffffffff8148d80c)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/proc/base.c (ffffffff814a1628)
Location: include/linux/cpumask.h:919
Inline: True
```
```
In fs/proc/stat.c (ffffffff814a9498)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/proc/stat.c:get_iowait_time
  - fs/proc/stat.c:get_idle_time
```
```
In fs/ext4/balloc.c (ffffffff814c01d0)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff814c2e01)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff814c9e4a)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (ffffffff814d0bed)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/fsmap.c (ffffffff814d36e4)
Location: include/linux/cpumask.h:919
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
In fs/ext4/fsync.c (ffffffff814d3ccc)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff814d6939)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff814d953c)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff814e75ba)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_update_other_inode_time
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_release_folio
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:ext4_invalidate_folio
  - fs/ext4/inode.c:ext4_read_folio
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff814ed2a5)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:ext4_shutdown
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff814f69fb)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff8150822b)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/super.c (ffffffff8152355c)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_nfs_commit_metadata
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/fast_commit.c (ffffffff815396e4)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_update_stats
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
```
In fs/jbd2/transaction.c (ffffffff8153e86d)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
```
In fs/jbd2/commit.c (ffffffff81540f2d)
Location: include/linux/cpumask.h:919
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
In fs/jbd2/checkpoint.c (ffffffff81543774)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8154a411)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_shrink_count
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
```
```
In security/selinux/avc.c (ffffffff815bf7fe)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_audit_post_callback
```
```
In block/bio.c (ffffffff816727cb)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffff8167983d)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-merge.c (ffffffff81681371)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-mq.c (ffffffff81689a18)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_commit_rqs
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_add_rq_to_plug
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
```
```
In block/blk-iocost.c (ffffffff816b1fc4)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_activate
```
```
In block/mq-deadline.c (ffffffff816b44d5)
Location: include/linux/cpumask.h:919
Inline: True
```
```
In block/blk-wbt.c (ffffffff816baafc)
Location: include/linux/cpumask.h:919
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
In io_uring/io_uring.c (ffffffff816d8cd6)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_file_get_normal
  - io_uring/io_uring.c:io_arm_poll_handler
  - io_uring/io_uring.c:io_fail_links
  - io_uring/io_uring.c:io_fill_cqe_aux
  - io_uring/io_uring.c:io_cqring_event_overflow
  - io_uring/io_uring.c:io_queue_iowq
Direct callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_sq_offload_create
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_drain_req
```
```
In arch/x86/lib/msr.c (ffffffff8177589d)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff817a797f)
Location: include/linux/cpumask.h:919
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
In drivers/pwm/core.c (ffffffff817b5624)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_apply_state
  - drivers/pwm/core.c:pwm_device_request
```
```
In drivers/pci/pcie/aer.c (ffffffff817dae00)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_error
```
```
In drivers/acpi/sleep.c (ffffffff81826be0)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/processor_throttling.c (ffffffff8188ed7e)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
```
In drivers/clk/clk.c (ffffffff818ad683)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
Direct callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
```
```
In drivers/xen/cpu_hotplug.c (ffffffff818c6ab9)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/xen/events/events_fifo.c (ffffffff818d1bfe)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818ddb96)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff818e65e7)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/iommu/intel/dmar.c (ffffffff81957476)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/svm.c (ffffffff819616f4)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/iommu/iommu.c (ffffffff81965cc2)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/iommu/iommu.c:iommu_group_do_detach_device
  - drivers/iommu/iommu.c:__iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/base/syscore.c (ffffffff8197e8a5)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/cpu.c (ffffffff819826cb)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
```
```
In drivers/base/devres.c (ffffffff81983b87)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/devres.c:devm_add_action
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_close_group
  - drivers/base/devres.c:devres_open_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
  - drivers/base/devres.c:devres_get
```
```
In drivers/base/power/qos.c (ffffffff8198e2f5)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff819916c6)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (ffffffff819967d6)
Location: include/linux/cpumask.h:919
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
In drivers/base/power/wakeup.c (ffffffff8199710b)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/regmap/regmap.c (ffffffff819a796c)
Location: include/linux/cpumask.h:919
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
In drivers/base/regmap/regcache.c (ffffffff819acc32)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_read
```
```
In drivers/dma-buf/dma-fence.c (ffffffff819eeace)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/dma-buf/sw_sync.c (ffffffff819f47d2)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff819fd73d)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a02004)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/ata/libata-core.c (ffffffff81a2593a)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff81a351d3)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_done
  - drivers/ata/libata-eh.c:ata_eh_about_to_do
  - drivers/ata/libata-eh.c:__ata_port_freeze
```
```
In drivers/ata/libata-sff.c (ffffffff81a3c7b8)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_post_internal_cmd
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:__ata_sff_port_intr
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_tf_to_host
  - drivers/ata/libata-sff.c:ata_tf_to_host
```
```
In drivers/ata/ata_piix.c (ffffffff81a425fb)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_irq_check
```
```
In drivers/spi/spi.c (ffffffff81a4f8b7)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81a5be25)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff81a62439)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/xen-netfront.c (ffffffff81a73ffb)
Location: include/linux/cpumask.h:919
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81af165a)
Location: include/linux/cpumask.h:919
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
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af4f49)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81af851d)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_trb
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_ring_ep_doorbell
  - drivers/usb/host/xhci-ring.c:inc_enq
  - drivers/usb/host/xhci-ring.c:inc_deq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81b01a53)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b0826a)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/rtc/interface.c (ffffffff81b2989b)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_offset
  - drivers/rtc/interface.c:rtc_read_offset
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_alarm_disable
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b30a57)
Location: include/linux/cpumask.h:919
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b33ef4)
Location: include/linux/cpumask.h:919
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81b449a3)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/hwmon/hwmon.c:hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:hwmon_attr_show
```
```
In drivers/thermal/thermal_core.c (ffffffff81b47daf)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:handle_thermal_trip
```
```
In drivers/thermal/thermal_helpers.c (ffffffff81b4c0d4)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:__thermal_cdev_update
```
```
In drivers/thermal/gov_fair_share.c (ffffffff81b4e41a)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/thermal/gov_fair_share.c:get_trip_level
```
```
In drivers/thermal/gov_step_wise.c (ffffffff81b4ec7b)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/thermal/gov_step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81b5036d)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:pid_controller
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81b510bf)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81b518fb)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_count
```
```
In drivers/md/md.c (ffffffff81b5a1a7)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_discard_bio
```
```
In drivers/md/dm.c (ffffffff81b72bb0)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_submit_bio_remap
```
```
In drivers/md/dm-rq.c (ffffffff81b81070)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff81b82499)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b8ff79)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:store
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81b97542)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9dde4)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81ba01e3)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/mmc/core/core.c (ffffffff81ba5b50)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81bc88ec)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:send_command
  - drivers/platform/chrome/cros_ec_proto.c:send_command
  - drivers/platform/chrome/cros_ec_proto.c:send_command
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd4572)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
```
In drivers/ras/ras.c (ffffffff81bdebe9)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In drivers/interconnect/core.c (ffffffff81be39fd)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
```
In net/core/sock.c (ffffffff81bed7d6)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_error_report
```
```
In net/core/skbuff.c (ffffffff81bffcce)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_attempt_defer_free
  - net/core/skbuff.c:__consume_stateless_skb
```
```
In net/core/datagram.c (ffffffff81c0021b)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff81c1c56d)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:net_rps_send_ipi
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_qdisc_enqueue
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/neighbour.c (ffffffff81c287d0)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/filter.c (ffffffff81c4cb5b)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
```
```
In net/core/xdp.c (ffffffff81c51068)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/gro.c (ffffffff81c545f2)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:napi_gro_receive
```
```
In net/core/page_pool.c (ffffffff81c5908a)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/net-procfs.c (ffffffff81c5ad1a)
Location: include/linux/cpumask.h:919
Inline: True
```
```
In net/core/netpoll.c (ffffffff81c5baf3)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/devlink.c (ffffffff81c727cc)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_health_report
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/sch_generic.c (ffffffff81c95bd2)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_api.c (ffffffff81c9b65c)
Location: include/linux/cpumask.h:919
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ca9c39)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81cb4f51)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
```
```
In net/ipv4/tcp_input.c (ffffffff81cfbd7f)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffff81cfef09)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d09642)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_cong.c (ffffffff81d0fbf8)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_ca_state
```
```
In net/ipv4/udp.c (ffffffff81d1c9de)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/af_inet.c (ffffffff81d2e1b6)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
```
```
In net/ipv4/fib_trie.c (ffffffff81d3f191)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff81da21ef)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcce7a)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/mptcp/protocol.c (ffffffff81e216fc)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mptcp/subflow.c (ffffffff81e26d19)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81e29c33)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/mptcp/options.c:ack_update_msk
```
```
In net/mctp/af_mctp.c (ffffffff81e37578)
Location: include/linux/cpumask.h:919
Inline: True
```
```
In net/mctp/route.c (ffffffff81e3a917)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:__mctp_key_done_in
```
**Symbols:**

```
ffffffff81000c70-ffffffff81000c84: cpu_online (STB_LOCAL)
ffffffff810d0810-ffffffff810d0824: cpu_online (STB_LOCAL)
ffffffff8115aca0-ffffffff8115acb4: cpu_online (STB_LOCAL)
ffffffff81178270-ffffffff81178284: cpu_online (STB_LOCAL)
ffffffff816c5370-ffffffff816c5384: cpu_online (STB_LOCAL)
ffffffff81ebb176-ffffffff81ebb18a: cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool cpu_online(unsigned int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83e61a5b)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810055b3)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/xen/enlighten.c (ffffffff81031bbc)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81038336)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_mc_batch
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81039fe5)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
  - arch/x86/xen/mmu_pv.c:xen_mc_batch
```
```
In arch/x86/xen/multicalls.c (ffffffff8103dd53)
Location: include/linux/cpumask.h:1028
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
In arch/x86/hyperv/mmu.c (ffffffff81046c96)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff810472b8)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8104926a)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/process_64.c (ffffffff8104aca9)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/irq.c (ffffffff8104f5a7)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
```
```
In arch/x86/kernel/nmi.c (ffffffff81052471)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff810546b0)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81061456)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106293d)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106393d)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106ad66)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_rendezvous_handler
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81076e32)
Location: include/linux/cpumask.h:1028
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107affd)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff8107cd5d)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8107deb7)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108e2e9)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/smp.c (ffffffff810987f0)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109baa5)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_cpu0_nmi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109dc5c)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8109f8b5)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:native_smp_send_reschedule
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a0267)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/mm/fault.c (ffffffff820bfad6)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff810c91f5)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/fork.c (ffffffff810e8d60)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
```
```
In kernel/panic.c (ffffffff810eab19)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/panic.c:__warn
```
```
In kernel/cpu.c (ffffffff810eeca1)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:bringup_hibernate_cpu
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffff810f0d95)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:delayed_put_task_struct
Direct callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff810f39c4)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/softirq.c:__raise_softirq_irqoff
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/signal.c (ffffffff811056bd)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/workqueue.c (ffffffff8111505e)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/kthread.c (ffffffff8111da2c)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/reboot.c (ffffffff81128189)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/smpboot.c (ffffffff811295b7)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_thread_fn
```
```
In kernel/kmod.c (ffffffff8112b716)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff8114259b)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/sched/core.c:call_trace_sched_update_nr_running
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:send_call_function_single_ipi
  - kernel/sched/core.c:ttwu_do_wakeup
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff8114ce30)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_cpu_capacity
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff8116088e)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:default_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff8116e26a)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_wait_end
```
```
In kernel/locking/mutex.c (ffffffff820ced2a)
Location: include/linux/cpumask.h:1028
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff820d0537)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff820d1367)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (ffffffff820d1936)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
```
In kernel/locking/qspinlock.c (ffffffff820d682a)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff820d32a3)
Location: include/linux/cpumask.h:1028
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff820d6e1e)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/qos.c (ffffffff8117eca9)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_remove_request
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff8118134f)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff8118254d)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/power/hibernate.c (ffffffff8118380f)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/printk/printk.c (ffffffff83eab057)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_flush_all
  - kernel/printk/printk.c:printk_sprint
```
```
In kernel/irq/handle.c (ffffffff81195b4f)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff8119c295)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
```
```
In kernel/irq/matrix.c (ffffffff811a88ac)
Location: include/linux/cpumask.h:1028
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
In kernel/rcu/update.c (ffffffff811ab5c9)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:trc_check_slow_task
  - kernel/rcu/update.c:trc_inspect_reader
```
```
In kernel/rcu/tree.c (ffffffff811b6ab3)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/livepatch/transition.c (ffffffff811bf625)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/dma/swiotlb.c (ffffffff811c5535)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In kernel/entry/common.c (ffffffff811c671e)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/module/main.c (ffffffff811ccbe8)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
  - kernel/module/main.c:module_put
  - kernel/module/main.c:try_module_get
```
```
In kernel/time/timer.c (ffffffff811d8958)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:get_next_timer_interrupt
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/time/hrtimer.c (ffffffff811dae65)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:hrtimer_try_to_cancel
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
```
In kernel/time/alarmtimer.c (ffffffff811e373d)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811e89a5)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff811ec066)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff811ee7c8)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff811f0df5)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:can_stop_idle_tick
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In kernel/smp.c (ffffffff811f8ffc)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:generic_exec_single
```
```
In kernel/cgroup/cgroup.c (ffffffff8120ef5b)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81214816)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff812153cd)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81241c6b)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81245539)
Location: include/linux/cpumask.h:1028
Inline: True
```
```
In kernel/hung_task.c (ffffffff81246dfc)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/trace/ring_buffer.c (ffffffff812600ba)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
```
```
In kernel/trace/trace_events_hist.c (ffffffff8129c80a)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_trace
```
```
In kernel/trace/bpf_trace.c (ffffffff812a69e7)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_trace_vprintk
  - kernel/trace/bpf_trace.c:bpf_trace_printk
```
```
In kernel/trace/trace_kdb.c (ffffffff812b36a8)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (ffffffff812bd077)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
```
```
In kernel/irq_work.c (ffffffff812be401)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/devmap.c (ffffffff8131ed9e)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff81320ac7)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In kernel/rseq.c (ffffffff81357025)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:rseq_ip_fixup
```
```
In mm/filemap.c (ffffffff8135ac5b)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_set_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/oom_kill.c (ffffffff81363297)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:wake_oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (ffffffff81366e3b)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_wait_writeback_killable
  - mm/page-writeback.c:folio_wait_writeback
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff8136eb30)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff81386078)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:pageout
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/backing-dev.c (ffffffff81398f12)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
```
```
In mm/percpu.c (ffffffff8139bded)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff813a1a71)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_large_node
  - mm/slab_common.c:kmalloc_large
  - mm/slab_common.c:kmalloc_node_trace
  - mm/slab_common.c:kmalloc_trace
  - mm/slab_common.c:kfree
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc_node
  - mm/slab_common.c:__kmalloc_node
```
```
In mm/compaction.c (ffffffff813a9cad)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_defer_reset
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/mmap_lock.c (ffffffff813b4149)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
```
```
In mm/memory.c (ffffffff813bb340)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff813c4b15)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/mlock.c:mlock_page_drain_remote
```
```
In mm/mmap.c (ffffffff813ca0ac)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_unmapped_area
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_mas_remove
  - mm/mmap.c:vma_mas_store
```
```
In mm/rmap.c (ffffffff813d9b44)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/vmalloc.c (ffffffff813dc6a9)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/page_alloc.c (ffffffff813eca0d)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/slub.c (ffffffff8142c2a1)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/kfence/report.c (ffffffff81430ff1)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/kfence/report.c:kfence_report_error
```
```
In mm/migrate.c (ffffffff814356f7)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff814440de)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
```
```
In mm/khugepaged.c (ffffffff8144ab09)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff8145a4c8)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In mm/memory-failure.c (ffffffff8145ee33)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff8146583b)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In fs/exec.c (ffffffff81484186)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
  - fs/exec.c:__set_task_comm
```
```
In fs/inode.c (ffffffff814a2ee9)
Location: include/linux/cpumask.h:1028
Inline: True
```
```
In fs/fs-writeback.c (ffffffff814c17f1)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/buffer.c (ffffffff814d54b0)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/dax.c (ffffffff814fa6cf)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_pmd_load_hole
  - fs/dax.c:dax_pmd_load_hole
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_one
```
```
In fs/locks.c (ffffffff8150c1bb)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:leases_conflict
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/iomap/iter.c (ffffffff8151b9b7)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/iomap/iter.c:iomap_iter
  - fs/iomap/iter.c:iomap_iter_done
  - fs/iomap/iter.c:iomap_iter_done
```
```
In fs/iomap/buffered-io.c (ffffffff8151e00f)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_folio
```
```
In fs/iomap/direct-io.c (ffffffff81520dcd)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/proc/base.c (ffffffff81536648)
Location: include/linux/cpumask.h:1028
Inline: True
```
```
In fs/proc/stat.c (ffffffff8153ef68)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/proc/stat.c:get_iowait_time
  - fs/proc/stat.c:get_idle_time
```
```
In fs/ext4/balloc.c (ffffffff8155821b)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8155b171)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff815624e0)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (ffffffff815695ed)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/fsmap.c (ffffffff8156c2e5)
Location: include/linux/cpumask.h:1028
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
In fs/ext4/fsync.c (ffffffff8156c91c)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff8156f6fd)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8157270a)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff81580f7a)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_update_other_inode_time
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_release_folio
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:ext4_invalidate_folio
  - fs/ext4/inode.c:ext4_read_folio
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff81587149)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:ext4_shutdown
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff81590ed4)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff815a2d14)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/super.c (ffffffff815c072c)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_nfs_commit_metadata
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/fast_commit.c (ffffffff815d7aeb)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_update_stats
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
```
In fs/jbd2/transaction.c (ffffffff815dd25f)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
```
In fs/jbd2/commit.c (ffffffff815e005f)
Location: include/linux/cpumask.h:1028
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
In fs/jbd2/checkpoint.c (ffffffff815e26c4)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff815e9d02)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_shrink_count
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
```
```
In security/selinux/avc.c (ffffffff8166bb5e)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_audit_post_callback
```
```
In block/bio.c (ffffffff8172e149)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffff81735cd0)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct_nocheck
```
```
In block/blk-merge.c (ffffffff8173e8ff)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:__bio_split_to_limits
```
```
In block/blk-mq.c (ffffffff81747f1c)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_commit_rqs
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_add_rq_to_plug
  - block/blk-mq.c:blk_add_rq_to_plug
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
```
```
In block/blk-iocost.c (ffffffff81770c17)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_activate
```
```
In block/mq-deadline.c (ffffffff81773ed5)
Location: include/linux/cpumask.h:1028
Inline: True
```
```
In block/blk-wbt.c (ffffffff8177b0ff)
Location: include/linux/cpumask.h:1028
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
In io_uring/io_uring.c (ffffffff8178c88d)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_file_get_normal
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:io_fill_cqe_aux
  - io_uring/io_uring.c:io_cqring_event_overflow
  - io_uring/io_uring.c:io_queue_iowq
  - io_uring/io_uring.c:__io_fill_cqe_req
```
```
In io_uring/timeout.c (ffffffff8179959c)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - io_uring/timeout.c:io_disarm_next
```
```
In io_uring/sqpoll.c (ffffffff8179aebf)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
```
```
In io_uring/poll.c (ffffffff8179db2f)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - io_uring/poll.c:io_arm_poll_handler
  - io_uring/poll.c:__io_poll_execute
```
```
In io_uring/rw.c (ffffffff817a4b5b)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
  - io_uring/rw.c:__io_fill_cqe_req
```
```
In arch/x86/lib/msr.c (ffffffff818a654d)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff818bff33)
Location: include/linux/cpumask.h:1028
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
In drivers/pwm/core.c (ffffffff818cf96b)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_apply_state
  - drivers/pwm/core.c:pwm_device_request
```
```
In drivers/pci/pcie/aer.c (ffffffff818fcc6d)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
```
In drivers/acpi/sleep.c (ffffffff81958b04)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/processor_throttling.c (ffffffff819d69b5)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
```
In drivers/clk/clk.c (ffffffff819f8e43)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81a17449)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a23e77)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a31086)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff81a3b37f)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abe387)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/svm.c (ffffffff81aca17c)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/iommu/iommu.c (ffffffff81acf282)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/iommu/iommu.c:iommu_group_do_detach_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/base/syscore.c (ffffffff81aebe96)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/cpu.c (ffffffff81af054b)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
```
```
In drivers/base/devres.c (ffffffff81af1c37)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/devres.c:devm_add_action
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_close_group
  - drivers/base/devres.c:devres_open_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
  - drivers/base/devres.c:devres_get
```
```
In drivers/base/power/qos.c (ffffffff81afe505)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff81b01a96)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (ffffffff81b07552)
Location: include/linux/cpumask.h:1028
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
In drivers/base/power/wakeup.c (ffffffff81b087eb)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/regmap/regmap.c (ffffffff81b1a9dc)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:_regmap_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/base/regmap/regcache.c (ffffffff81b203f2)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_read
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81b6c1de)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81b71c02)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff81b7bb58)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b806d8)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b9629f)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/ata/libata-core.c (ffffffff81ba7afa)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff81bb9ab8)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_done
  - drivers/ata/libata-eh.c:ata_eh_about_to_do
  - drivers/ata/libata-eh.c:__ata_port_freeze
```
```
In drivers/ata/libata-sff.c (ffffffff81bc1a58)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_post_internal_cmd
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:__ata_sff_port_intr
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_tf_to_host
  - drivers/ata/libata-sff.c:ata_tf_to_host
```
```
In drivers/ata/ata_piix.c (ffffffff81bc8a4b)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_irq_check
```
```
In drivers/spi/spi.c (ffffffff81bd7217)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81be6255)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff81becbd9)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/xen-netfront.c (ffffffff81c08093)
Location: include/linux/cpumask.h:1028
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81c7e5a6)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c82796)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81c8642d)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_trb
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_ring_ep_doorbell
  - drivers/usb/host/xhci-ring.c:inc_enq
  - drivers/usb/host/xhci-ring.c:inc_deq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81c90a54)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c98057)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/rtc/interface.c (ffffffff81cbd48b)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_offset
  - drivers/rtc/interface.c:rtc_read_offset
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_alarm_disable
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc531f)
Location: include/linux/cpumask.h:1028
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc8eb1)
Location: include/linux/cpumask.h:1028
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81cdba73)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/hwmon/hwmon.c:hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:hwmon_attr_show
```
```
In drivers/thermal/thermal_core.c (ffffffff81cddca5)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:handle_thermal_trip
```
```
In drivers/thermal/thermal_helpers.c (ffffffff81ce3cb4)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:__thermal_cdev_update
```
```
In drivers/thermal/gov_fair_share.c (ffffffff81ce634a)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/thermal/gov_fair_share.c:get_trip_level
```
```
In drivers/thermal/gov_step_wise.c (ffffffff81ce6a8f)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/thermal/gov_step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81ce82ac)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:pid_controller
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81ce90cf)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81ce9a1b)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_count
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81ceb357)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81ced516)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff81cf2927)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_discard_bio
```
```
In drivers/md/dm.c (ffffffff81d0f9c0)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_submit_bio_remap
```
```
In drivers/md/dm-rq.c (ffffffff81d1f380)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff81d20df4)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d301dc)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81d3840a)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3fc66)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81d41fc5)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/cpuidle/governors/haltpoll.c (ffffffff81d45c9a)
Location: include/linux/cpumask.h:1028
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff81d47e60)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81d7187b)
Location: include/linux/cpumask.h:1028
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff81d80582)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
```
In drivers/ras/ras.c (ffffffff81d8a049)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In drivers/interconnect/core.c (ffffffff81d8f6f2)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
```
In net/core/sock.c (ffffffff81d9dd88)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_error_report
```
```
In net/core/skbuff.c (ffffffff81daf05e)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_attempt_defer_free
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:kfree_skb_reason
  - net/core/skbuff.c:kfree_skb_reason
```
```
In net/core/datagram.c (ffffffff81daf62b)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff81dcd589)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:net_rps_send_ipi
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_qdisc_enqueue
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/neighbour.c (ffffffff81ddb490)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/filter.c (ffffffff81e019a0)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
```
```
In net/core/xdp.c (ffffffff81e062c8)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/gro.c (ffffffff81e09d42)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:napi_gro_receive
```
```
In net/core/page_pool.c (ffffffff81e0efea)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
```
In net/core/net-procfs.c (ffffffff81e10f2a)
Location: include/linux/cpumask.h:1028
Inline: True
```
```
In net/core/netpoll.c (ffffffff81e11f23)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/devlink.c (ffffffff81e2abb8)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_health_report
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/sch_generic.c (ffffffff81e51762)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_api.c (ffffffff81e57b63)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff81e66c29)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81e734a1)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
```
```
In net/ipv4/tcp_input.c (ffffffff81ec08ff)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3f59)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ece900)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_cong.c (ffffffff81ed5858)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_ca_state
```
```
In net/ipv4/udp.c (ffffffff81ee3a77)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/af_inet.c (ffffffff81ef6106)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
```
```
In net/ipv4/fib_trie.c (ffffffff81f07d59)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv6/route.c (ffffffff81f7158f)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9df89)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/mptcp/protocol.c (ffffffff81ff8bcc)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mptcp/subflow.c (ffffffff81ffe4aa)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff82001d33)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/mptcp/options.c:ack_update_msk
```
```
In net/mctp/af_mctp.c (ffffffff820103c6)
Location: include/linux/cpumask.h:1028
Inline: True
```
```
In net/mctp/route.c (ffffffff82013ec1)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:__mctp_key_done_in
```
```
In lib/maple_tree.c (ffffffff82030c17)
Location: include/linux/cpumask.h:1028
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mtree_erase
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_load
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_store
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_slot_store
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_is_span_wr
```
**Symbols:**

```
ffffffff810ef150-ffffffff810ef164: cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool cpu_online(unsigned int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83681e7b)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004dc2)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/xen/enlighten.c (ffffffff81031bbc)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81038296)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_mc_batch
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103a075)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
  - arch/x86/xen/mmu_pv.c:xen_mc_batch
```
```
In arch/x86/xen/multicalls.c (ffffffff8103dc07)
Location: include/linux/cpumask.h:1080
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
In arch/x86/hyperv/mmu.c (ffffffff8104703b)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff81047638)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810494ca)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/process_64.c (ffffffff8104b4e9)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/irq.c (ffffffff81050257)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
```
```
In arch/x86/kernel/nmi.c (ffffffff81053777)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_backtrace_stall_check
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff81055710)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81062d26)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81064728)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:check_xstate_in_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106529e)
Location: include/linux/cpumask.h:1080
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106c6d6)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_rendezvous_handler
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81079032)
Location: include/linux/cpumask.h:1080
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107d29d)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff8107f10d)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81080297)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81091199)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/smp.c (ffffffff8109b700)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a0c38)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a2845)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:native_smp_send_reschedule
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a31e7)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/mm/fault.c (ffffffff82141806)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff810cc885)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/fork.c (ffffffff810f496f)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
```
```
In kernel/panic.c (ffffffff810f66f9)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/panic.c:__warn
```
```
In kernel/cpu.c (ffffffff810fac51)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:bringup_hibernate_cpu
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_bringup_ap
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffff810fcd45)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:delayed_put_task_struct
Direct callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff810ffd14)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/softirq.c:__raise_softirq_irqoff
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/signal.c (ffffffff81111958)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/workqueue.c (ffffffff8112102e)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/kthread.c (ffffffff8112ac1c)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/notifier.c (ffffffff811327b5)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/notifier.c:notifier_call_chain
  - kernel/notifier.c:notifier_chain_unregister
```
```
In kernel/reboot.c (ffffffff81135639)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/smpboot.c (ffffffff81136a57)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_thread_fn
```
```
In kernel/sched/core.c (ffffffff8114e2ab)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/sched/core.c:call_trace_sched_update_nr_running
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:call_function_single_prep_ipi
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff8115b275)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81170fb6)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:default_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff8117e890)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_wait_end
```
```
In kernel/locking/mutex.c (ffffffff821531bd)
Location: include/linux/cpumask.h:1080
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff821548c7)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff821556db)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (ffffffff82155ca6)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
```
In kernel/locking/qspinlock.c (ffffffff82159c19)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff821575f3)
Location: include/linux/cpumask.h:1080
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff8215a1ae)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/qos.c (ffffffff8118f8f9)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_remove_request
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff8119224f)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff81193406)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/power/hibernate.c (ffffffff8119467f)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/printk/printk.c (ffffffff836d0017)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_flush_all
  - kernel/printk/printk.c:printk_sprint
```
```
In kernel/irq/handle.c (ffffffff811a751f)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff811ae0f5)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
```
```
In kernel/irq/matrix.c (ffffffff811ba583)
Location: include/linux/cpumask.h:1080
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
In kernel/rcu/update.c (ffffffff811bd4e9)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:trc_check_slow_task
  - kernel/rcu/update.c:trc_inspect_reader
```
```
In kernel/rcu/tree.c (ffffffff811c74e3)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/livepatch/transition.c (ffffffff811d2105)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/dma/swiotlb.c (ffffffff811d8105)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In kernel/entry/common.c (ffffffff811d933e)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/module/main.c (ffffffff811e009b)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
  - kernel/module/main.c:module_put
  - kernel/module/main.c:try_module_get
```
```
In kernel/module/kmod.c (ffffffff811e1858)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/module/kmod.c:__request_module
```
```
In kernel/time/timer.c (ffffffff811ecd83)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:get_next_timer_interrupt
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/time/hrtimer.c (ffffffff811ef385)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
```
In kernel/time/alarmtimer.c (ffffffff811f7dad)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fcfb5)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff81200796)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff81202ef8)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff81205825)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:can_stop_idle_tick
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In kernel/smp.c (ffffffff8120dcac)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:generic_exec_single
  - kernel/smp.c:generic_exec_single
  - kernel/smp.c:generic_exec_single
  - kernel/smp.c:__smp_call_single_queue
  - kernel/smp.c:__smp_call_single_queue
```
```
In kernel/cgroup/cgroup.c (ffffffff8122496b)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8122a136)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff8122acfd)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81258ceb)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8125c5c9)
Location: include/linux/cpumask.h:1080
Inline: True
```
```
In kernel/hung_task.c (ffffffff8125de7a)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/trace/ring_buffer.c (ffffffff81277384)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
```
```
In kernel/trace/trace_osnoise.c (ffffffff812978ff)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:trace_sched_switch_callback
  - kernel/trace/trace_osnoise.c:trace_softirq_exit_callback
  - kernel/trace/trace_osnoise.c:osnoise_trace_irq_exit
  - kernel/trace/trace_osnoise.c:trace_osnoise_callback
```
```
In kernel/trace/trace_events_hist.c (ffffffff812ba14a)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_trace
```
```
In kernel/trace/bpf_trace.c (ffffffff812c8aec)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_trace_vprintk
  - kernel/trace/bpf_trace.c:bpf_trace_printk
```
```
In kernel/trace/trace_kdb.c (ffffffff812d5f78)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (ffffffff812e3c47)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
```
```
In kernel/irq_work.c (ffffffff812e5041)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/devmap.c (ffffffff8134ebbe)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff81350977)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In kernel/rseq.c (ffffffff81388806)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_update_cpu_node_id
```
```
In mm/filemap.c (ffffffff8138c67f)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_set_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/oom_kill.c (ffffffff813956c7)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:wake_oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (ffffffff813994bb)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_wait_writeback_killable
  - mm/page-writeback.c:folio_wait_writeback
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff813a0c5d)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff813b9345)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:pageout
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/backing-dev.c (ffffffff813cbe72)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
```
```
In mm/percpu.c (ffffffff813cedcd)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff813d4d41)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_large_node
  - mm/slab_common.c:kmalloc_large
  - mm/slab_common.c:kmalloc_node_trace
  - mm/slab_common.c:kmalloc_trace
  - mm/slab_common.c:kfree
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc_node
  - mm/slab_common.c:__kmalloc_node
```
```
In mm/compaction.c (ffffffff813dcf68)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_defer_reset
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/mmap_lock.c (ffffffff813e8dc9)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
```
```
In mm/memory.c (ffffffff813efe1b)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff813f9085)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/mlock.c:mlock_drain_remote
```
```
In mm/mmap.c (ffffffff813fe601)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_unmapped_area
```
```
In mm/rmap.c (ffffffff8140e36d)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/vmalloc.c (ffffffff81410f97)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/page_alloc.c (ffffffff8142197f)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/ksm.c (ffffffff81457c45)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/slub.c (ffffffff81461847)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/kfence/report.c (ffffffff814668f6)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/kfence/report.c:kfence_report_error
```
```
In mm/migrate.c (ffffffff8146b507)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81479674)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
```
```
In mm/khugepaged.c (ffffffff81480d0f)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff81490128)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In mm/memory-failure.c (ffffffff81494d9b)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff8149b2c4)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In fs/exec.c (ffffffff814b8a99)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
  - fs/exec.c:__set_task_comm
```
```
In fs/inode.c (ffffffff814d8038)
Location: include/linux/cpumask.h:1080
Inline: True
```
```
In fs/fs-writeback.c (ffffffff814f6b87)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/buffer.c (ffffffff8150831e)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/dax.c (ffffffff81531b39)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_pmd_load_hole
  - fs/dax.c:dax_pmd_load_hole
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_one
```
```
In fs/locks.c (ffffffff81543931)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:leases_conflict
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/iomap/iter.c (ffffffff81553c77)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/iomap/iter.c:iomap_iter
  - fs/iomap/iter.c:iomap_iter_done
  - fs/iomap/iter.c:iomap_iter_done
```
```
In fs/iomap/buffered-io.c (ffffffff81556170)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_folio
```
```
In fs/iomap/direct-io.c (ffffffff81558971)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/base.c (ffffffff8156e807)
Location: include/linux/cpumask.h:1080
Inline: True
```
```
In fs/proc/stat.c (ffffffff815772b8)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/proc/stat.c:get_iowait_time
  - fs/proc/stat.c:get_idle_time
```
```
In fs/ext4/balloc.c (ffffffff8158ff3d)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81593004)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff8159a240)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (ffffffff815a1362)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/fsmap.c (ffffffff815a4123)
Location: include/linux/cpumask.h:1080
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
In fs/ext4/fsync.c (ffffffff815a47c9)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff815a7545)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815aa4ac)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff815b852a)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_update_other_inode_time
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_release_folio
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:ext4_invalidate_folio
  - fs/ext4/inode.c:ext4_read_folio
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff815bd6a9)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:ext4_force_shutdown
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff815c7f2b)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff815d96f4)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/super.c (ffffffff815f7ebc)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_nfs_commit_metadata
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/fast_commit.c (ffffffff8160f63a)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_update_stats
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
```
In fs/jbd2/transaction.c (ffffffff81614cff)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
```
In fs/jbd2/commit.c (ffffffff816173e6)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8161a014)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81621b52)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_shrink_count
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
```
```
In security/selinux/avc.c (ffffffff816a42ce)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_audit_post_callback
```
```
In block/bio.c (ffffffff8176a40c)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffff817721a1)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct_nocheck
```
```
In block/blk-merge.c (ffffffff8177ae5f)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:__bio_split_to_limits
```
```
In block/blk-mq.c (ffffffff81783882)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_add_rq_to_plug
  - block/blk-mq.c:blk_add_rq_to_plug
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_account_io_done
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
```
```
In block/blk-iocost.c (ffffffff817b07d3)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_activate
```
```
In block/mq-deadline.c (ffffffff817b40c6)
Location: include/linux/cpumask.h:1080
Inline: True
```
```
In block/blk-wbt.c (ffffffff817bac7a)
Location: include/linux/cpumask.h:1080
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
In io_uring/io_uring.c (ffffffff817cda47)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_register
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_file_get_normal
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:io_fill_cqe_aux
  - io_uring/io_uring.c:io_cqring_event_overflow
  - io_uring/io_uring.c:io_queue_iowq
  - io_uring/io_uring.c:__io_fill_cqe_req
```
```
In io_uring/timeout.c (ffffffff817da669)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - io_uring/timeout.c:io_disarm_next
```
```
In io_uring/sqpoll.c (ffffffff817dbf7c)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
```
```
In io_uring/poll.c (ffffffff817ded31)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - io_uring/poll.c:io_arm_poll_handler
  - io_uring/poll.c:__io_poll_execute
```
```
In io_uring/rw.c (ffffffff817e5b5e)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
  - io_uring/rw.c:__io_fill_cqe_req
```
```
In arch/x86/lib/msr.c (ffffffff818e93bd)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff81902f13)
Location: include/linux/cpumask.h:1080
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
In drivers/pwm/core.c (ffffffff819129a8)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_apply_state
  - drivers/pwm/core.c:pwm_device_request
```
```
In drivers/pci/pcie/aer.c (ffffffff819400ec)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
```
In drivers/acpi/sleep.c (ffffffff8199eed0)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a1e375)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
```
In drivers/clk/clk.c (ffffffff81a41903)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81a604d9)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a6d3a7)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a7a896)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff81a851ff)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0ad17)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/svm.c (ffffffff81b16cf4)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/iommu/iommu.c (ffffffff81b1dc92)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:__iommu_group_release_device
```
```
In drivers/base/syscore.c (ffffffff81b3a08d)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/cpu.c (ffffffff81b3e6ab)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
```
```
In drivers/base/devres.c (ffffffff81b3fdb7)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/devres.c:__devm_add_action
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_close_group
  - drivers/base/devres.c:devres_open_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
  - drivers/base/devres.c:devres_get
```
```
In drivers/base/power/qos.c (ffffffff81b4c8c5)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff81b4fbc0)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (ffffffff81b555a2)
Location: include/linux/cpumask.h:1080
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
In drivers/base/power/wakeup.c (ffffffff81b5681b)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/regmap/regmap.c (ffffffff81b695ec)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:_regmap_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/base/regmap/regcache.c (ffffffff81b6f642)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_read
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81bbf9be)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc58d9)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff81bcf87b)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd4758)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81beca99)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/ata/libata-core.c (ffffffff81bfe7a0)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff81c112f0)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_done
  - drivers/ata/libata-eh.c:ata_eh_about_to_do
  - drivers/ata/libata-eh.c:__ata_port_freeze
```
```
In drivers/ata/libata-sff.c (ffffffff81c19c28)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_post_internal_cmd
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:__ata_sff_port_intr
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_tf_to_host
  - drivers/ata/libata-sff.c:ata_tf_to_host
```
```
In drivers/ata/ata_piix.c (ffffffff81c205db)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_irq_check
```
```
In drivers/spi/spi.c (ffffffff81c2dc47)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81c3ebd1)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff81c450d9)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/virtio_net.c (ffffffff81c4f90f)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d7d0)
Location: include/linux/cpumask.h:1080
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81ce5912)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81ce944e)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81ced25d)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_trb
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_ring_ep_doorbell
  - drivers/usb/host/xhci-ring.c:inc_enq
  - drivers/usb/host/xhci-ring.c:inc_deq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81cf71fa)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cff3b4)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/rtc/interface.c (ffffffff81d24d9b)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_offset
  - drivers/rtc/interface.c:rtc_read_offset
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_alarm_disable
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2cf0f)
Location: include/linux/cpumask.h:1080
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d30bcb)
Location: include/linux/cpumask.h:1080
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81d43dd3)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/hwmon/hwmon.c:hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:hwmon_attr_show
```
```
In drivers/thermal/thermal_core.c (ffffffff81d4764a)
Location: include/linux/cpumask.h:1080
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (ffffffff81d4c2e4)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:__thermal_cdev_update
```
```
In drivers/thermal/gov_fair_share.c (ffffffff81d4ec32)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/thermal/gov_fair_share.c:fair_share_throttle
```
```
In drivers/thermal/gov_step_wise.c (ffffffff81d4f254)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/thermal/gov_step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81d50a8c)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:pid_controller
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81d5188f)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81d51dab)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_count
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81d53f9f)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81d5626a)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff81d5a7e7)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_discard_bio
```
```
In drivers/md/dm.c (ffffffff81d78de2)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_submit_bio_remap
```
```
In drivers/md/dm-rq.c (ffffffff81d88563)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff81d89ffe)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d994bc)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81da2805)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81daa7d6)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff82142764)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/cpuidle/governors/haltpoll.c (ffffffff81db042a)
Location: include/linux/cpumask.h:1080
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff81db26c0)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81ddf55b)
Location: include/linux/cpumask.h:1080
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff81dee912)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
```
In drivers/ras/ras.c (ffffffff81df8649)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In drivers/interconnect/core.c (ffffffff81dfdcd2)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
```
In net/socket.c (ffffffff81e013ad)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/socket.c:call_trace_sock_recv_length
```
```
In net/core/sock.c (ffffffff81e0951b)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_error_report
```
```
In net/core/skbuff.c (ffffffff81e1f24e)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_attempt_defer_free
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_reason
  - net/core/skbuff.c:kfree_skb_reason
```
```
In net/core/datagram.c (ffffffff81e1f86b)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff81e3e0ea)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:net_rps_send_ipi
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_qdisc_enqueue
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/neighbour.c (ffffffff81e4c256)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/filter.c (ffffffff81e73c40)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
```
```
In net/core/xdp.c (ffffffff81e78a08)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/gro.c (ffffffff81e7c507)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:napi_gro_receive
```
```
In net/core/page_pool.c (ffffffff81e827aa)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
```
In net/core/net-procfs.c (ffffffff81e8483a)
Location: include/linux/cpumask.h:1080
Inline: True
```
```
In net/core/netpoll.c (ffffffff81e85836)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/skmsg.c (ffffffff81ea1a2e)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
```
```
In net/sched/sch_generic.c (ffffffff81eacfb2)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_api.c (ffffffff81eb1ea9)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff81ec29e9)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81ecf231)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
```
```
In net/ipv4/tcp_input.c (ffffffff81f1ee6f)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffff81f22269)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2dcb6)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_cong.c (ffffffff81f34538)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_ca_state
```
```
In net/ipv4/udp.c (ffffffff81f43327)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/af_inet.c (ffffffff81f55b66)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
```
```
In net/ipv4/fib_trie.c (ffffffff81f67844)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/xfrm/espintcp.c (ffffffff81fa75b2)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_data_ready
```
```
In net/ipv6/route.c (ffffffff81fd165d)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/udp.c (ffffffff81fe860b)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe9e8)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/devlink/leftover.c (ffffffff8202ead8)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_trap_report
```
```
In net/devlink/health.c (ffffffff82047d98)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_health_report
  - net/devlink/health.c:devlink_health_report
```
```
In net/mptcp/protocol.c (ffffffff8207509b)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mptcp/subflow.c (ffffffff8207be2f)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff8207e1f3)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/mptcp/options.c:ack_update_msk
```
```
In net/mctp/af_mctp.c (ffffffff8208d796)
Location: include/linux/cpumask.h:1080
Inline: True
```
```
In net/mctp/route.c (ffffffff82090d43)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:__mctp_key_done_in
```
```
In net/handshake/netlink.c (ffffffff820928c9)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_nl_done_doit
  - net/handshake/netlink.c:handshake_nl_done_doit
  - net/handshake/netlink.c:handshake_nl_accept_doit
  - net/handshake/netlink.c:handshake_nl_accept_doit
```
```
In net/handshake/request.c (ffffffff82093884)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_complete
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_sk_destruct
```
```
In lib/maple_tree.c (ffffffff820ac5c4)
Location: include/linux/cpumask.h:1080
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mtree_erase
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_load
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_store
  - lib/maple_tree.c:mas_wr_modify
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_is_span_wr
```
**Symbols:**

```
ffffffff810fb170-ffffffff810fb184: cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool cpu_online(unsigned int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff838b0eb0)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810076d2)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/xen/enlighten.c (ffffffff81037eac)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103e606)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_mc_batch
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81040535)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
  - arch/x86/xen/mmu_pv.c:xen_mc_batch
```
```
In arch/x86/xen/multicalls.c (ffffffff810440c7)
Location: include/linux/cpumask.h:1102
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
In arch/x86/hyperv/mmu.c (ffffffff8104d6f0)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8104dd6f)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8105042e)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/process_64.c (ffffffff81052759)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/irq.c (ffffffff81057486)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
```
```
In arch/x86/kernel/nmi.c (ffffffff8105a997)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_backtrace_stall_check
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff8105c96f)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8106a016)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:fpregs_lock_and_load
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106bbe8)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:check_xstate_in_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106c945)
Location: include/linux/cpumask.h:1102
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81073926)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_rendezvous_handler
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81080702)
Location: include/linux/cpumask.h:1102
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8108476c)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff810865ec)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81087da7)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81098556)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/cpu/debugfs.c (ffffffff810a0ae1)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/debugfs.c:cpu_debug_show
```
```
In arch/x86/kernel/smp.c (ffffffff810a2caf)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a7e3e)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a9515)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:native_smp_send_reschedule
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810aa117)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__vector_schedule_cleanup
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/mm/fault.c (ffffffff82223786)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff810d4f15)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/fork.c (ffffffff810fdd0f)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
```
```
In kernel/panic.c (ffffffff810ffaa9)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/panic.c:__warn
```
```
In kernel/cpu.c (ffffffff81104071)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:bringup_hibernate_cpu
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_bringup_ap
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffff81107255)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:delayed_put_task_struct
Direct callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff81109434)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/softirq.c:__raise_softirq_irqoff
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/signal.c (ffffffff8111b2f8)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/workqueue.c (ffffffff8112b7de)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe_key
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/kthread.c (ffffffff8113533c)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/notifier.c (ffffffff8113d6c5)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/notifier.c:notifier_call_chain
  - kernel/notifier.c:notifier_chain_unregister
```
```
In kernel/reboot.c (ffffffff81140699)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/smpboot.c (ffffffff81141c57)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_thread_fn
```
```
In kernel/sched/core.c (ffffffff8115a0eb)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/sched/core.c:call_trace_sched_update_nr_running
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:sched_tick_remote
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:call_function_single_prep_ipi
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/fair.c (ffffffff8116c492)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:update_curr_common
```
```
In kernel/sched/build_policy.c (ffffffff81180ff3)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:do_idle
  - kernel/sched/build_policy.c:default_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff8118c7dc)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_wait_end
```
```
In kernel/locking/mutex.c (ffffffff82235ffd)
Location: include/linux/cpumask.h:1102
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff82237707)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff8223851b)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (ffffffff82238ae6)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
```
In kernel/locking/qspinlock.c (ffffffff8223d499)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff8223a433)
Location: include/linux/cpumask.h:1102
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff8223da2e)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/qos.c (ffffffff8119e2b9)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_remove_request
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff811a0c3f)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff811a1df6)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/power/hibernate.c (ffffffff811a306f)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/printk/printk.c (ffffffff83901427)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_flush_all
  - kernel/printk/printk.c:printk_sprint
```
```
In kernel/irq/handle.c (ffffffff811b707f)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff811bdcf5)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
```
```
In kernel/irq/matrix.c (ffffffff811ca443)
Location: include/linux/cpumask.h:1102
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
In kernel/rcu/update.c (ffffffff811cc759)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/update.c:trc_check_slow_task
  - kernel/rcu/update.c:trc_inspect_reader
```
```
In kernel/rcu/tree.c (ffffffff811d7a03)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_nocb_cpu_offload
  - kernel/rcu/tree.c:rcu_nocb_cpu_deoffload
  - kernel/rcu/tree.c:rcu_nocb_rdp_deoffload
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/livepatch/transition.c (ffffffff811e6d85)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/dma/swiotlb.c (ffffffff811edb3a)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In kernel/entry/common.c (ffffffff811eec7e)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
  - kernel/entry/common.c:syscall_trace_enter
```
```
In kernel/module/main.c (ffffffff811f5dcb)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
  - kernel/module/main.c:module_put
  - kernel/module/main.c:try_module_get
```
```
In kernel/module/kmod.c (ffffffff811f75b0)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/module/kmod.c:__request_module
```
```
In kernel/time/timer.c (ffffffff81202edd)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:timer_clear_idle
  - kernel/time/timer.c:get_next_timer_interrupt
  - kernel/time/timer.c:get_next_timer_interrupt
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/time/hrtimer.c (ffffffff812055f6)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_cpu_dying
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
```
In kernel/time/alarmtimer.c (ffffffff8120df4d)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff812131a5)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff81216c36)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff812194b8)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff8121be58)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:can_stop_idle_tick
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:check_tick_dependency
  - kernel/time/tick-sched.c:check_tick_dependency
  - kernel/time/tick-sched.c:check_tick_dependency
  - kernel/time/tick-sched.c:check_tick_dependency
  - kernel/time/tick-sched.c:check_tick_dependency
  - kernel/time/tick-sched.c:check_tick_dependency
```
```
In kernel/smp.c (ffffffff8122543c)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:generic_exec_single
  - kernel/smp.c:generic_exec_single
  - kernel/smp.c:generic_exec_single
  - kernel/smp.c:__smp_call_single_queue
  - kernel/smp.c:__smp_call_single_queue
```
```
In kernel/cgroup/cgroup.c (ffffffff8123c64b)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81241fd6)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff81242cbd)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81272bdb)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81276509)
Location: include/linux/cpumask.h:1102
Inline: True
```
```
In kernel/hung_task.c (ffffffff81277dbb)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/trace/ring_buffer.c (ffffffff81291de4)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b2f51)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:trace_sched_switch_callback
  - kernel/trace/trace_osnoise.c:trace_softirq_exit_callback
  - kernel/trace/trace_osnoise.c:osnoise_trace_irq_exit
  - kernel/trace/trace_osnoise.c:trace_osnoise_callback
```
```
In kernel/trace/trace_events_hist.c (ffffffff812d679a)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_trace
```
```
In kernel/trace/bpf_trace.c (ffffffff812e5abc)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_trace_vprintk
  - kernel/trace/bpf_trace.c:bpf_trace_printk
```
```
In kernel/trace/trace_kdb.c (ffffffff812f3a88)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (ffffffff81301cc7)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
```
```
In kernel/irq_work.c (ffffffff813030f1)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/devmap.c (ffffffff813760bb)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff81377da7)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In kernel/context_tracking.c (ffffffff822245a6)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/context_tracking.c:__ct_user_exit
  - kernel/context_tracking.c:__ct_user_enter
```
```
In kernel/rseq.c (ffffffff813b2266)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_update_cpu_node_id
```
```
In mm/filemap.c (ffffffff813b61e1)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_set_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/oom_kill.c (ffffffff813bf487)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:wake_oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (ffffffff813c32ba)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_wait_writeback_killable
  - mm/page-writeback.c:folio_wait_writeback
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff813ca8db)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff813e2370)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:pageout
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/shrinker.c (ffffffff813e40ed)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/shrinker.c:do_shrink_slab
  - mm/shrinker.c:do_shrink_slab
```
```
In mm/backing-dev.c (ffffffff813f67e2)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
```
```
In mm/percpu.c (ffffffff813f992d)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/compaction.c (ffffffff81406ec8)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_defer_reset
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/mmap_lock.c (ffffffff81413a39)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
```
```
In mm/memory.c (ffffffff8141b3b5)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/memory.c:set_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff81424c35)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/mlock.c:mlock_drain_remote
```
```
In mm/mmap.c (ffffffff8142aa34)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_unmapped_area
```
```
In mm/rmap.c (ffffffff8143aa51)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/vmalloc.c (ffffffff8143d787)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/page_alloc.c (ffffffff8144e7af)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/slub.c (ffffffff81459583)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmalloc_node_trace
  - mm/slub.c:kmalloc_trace
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:kmalloc_large
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
```
```
In mm/ksm.c (ffffffff81492715)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:scan_time_advisor
```
```
In mm/kfence/report.c (ffffffff81495b07)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/kfence/report.c:kfence_report_error
```
```
In mm/migrate.c (ffffffff8149a4ae)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff814a8c09)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
```
```
In mm/khugepaged.c (ffffffff814aece9)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff814bf938)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In mm/memory-failure.c (ffffffff814c469b)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff814ca99d)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In fs/exec.c (ffffffff814eafa9)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
  - fs/exec.c:__set_task_comm
```
```
In fs/inode.c (ffffffff8150a818)
Location: include/linux/cpumask.h:1102
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8152b2c7)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/buffer.c (ffffffff8153d0ce)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/dax.c (ffffffff81566a1d)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_pmd_load_hole
  - fs/dax.c:dax_pmd_load_hole
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_one
```
```
In fs/locks.c (ffffffff81578e31)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:leases_conflict
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/iomap/iter.c (ffffffff81589c37)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/iomap/iter.c:iomap_iter
  - fs/iomap/iter.c:iomap_iter_done
  - fs/iomap/iter.c:iomap_iter_done
```
```
In fs/iomap/buffered-io.c (ffffffff8158c64b)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_folio
```
```
In fs/iomap/direct-io.c (ffffffff8158f09e)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/base.c (ffffffff815a71c7)
Location: include/linux/cpumask.h:1102
Inline: True
```
```
In fs/proc/stat.c (ffffffff815afbc8)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/proc/stat.c:get_iowait_time
  - fs/proc/stat.c:get_idle_time
```
```
In fs/ext4/balloc.c (ffffffff815c8acc)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff815cbcf4)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff815d3090)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (ffffffff815da127)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/fsmap.c (ffffffff815dcf63)
Location: include/linux/cpumask.h:1102
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
In fs/ext4/fsync.c (ffffffff815dd60d)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff815e037e)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815e324c)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff815f12ca)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_update_other_inode_time
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_release_folio
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:ext4_invalidate_folio
  - fs/ext4/inode.c:ext4_read_folio
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff815f6469)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:ext4_force_shutdown
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff815ffb7b)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff81611da4)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/super.c (ffffffff81630a6c)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_nfs_commit_metadata
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/fast_commit.c (ffffffff816483fa)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_update_stats
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
```
In fs/jbd2/transaction.c (ffffffff8164daef)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
```
In fs/jbd2/commit.c (ffffffff816501fc)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81652f71)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8165a07d)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_shrink_count
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
```
```
In security/selinux/avc.c (ffffffff816e0d2e)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_audit_post_callback
```
```
In block/bio.c (ffffffff817ac86f)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - block/bio.c:bio_endio
```
```
In block/blk-core.c (ffffffff817b447a)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct_nocheck
```
```
In block/blk-merge.c (ffffffff817bd247)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:__bio_split_to_limits
```
```
In block/blk-mq.c (ffffffff817c5bf2)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_add_rq_to_plug
  - block/blk-mq.c:blk_add_rq_to_plug
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_account_io_done
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
```
```
In block/blk-iocost.c (ffffffff817f45e3)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_activate
```
```
In block/mq-deadline.c (ffffffff817f805c)
Location: include/linux/cpumask.h:1102
Inline: True
```
```
In block/blk-wbt.c (ffffffff817ff3e7)
Location: include/linux/cpumask.h:1102
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
In io_uring/io_uring.c (ffffffff81816b76)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_file_get_normal
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:io_fill_cqe_aux
  - io_uring/io_uring.c:io_cqring_event_overflow
  - io_uring/io_uring.c:io_queue_iowq
```
```
In io_uring/timeout.c (ffffffff8181e959)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - io_uring/timeout.c:io_disarm_next
```
```
In io_uring/sqpoll.c (ffffffff818202fe)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
```
```
In io_uring/poll.c (ffffffff81823108)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - io_uring/poll.c:io_arm_poll_handler
  - io_uring/poll.c:__io_poll_execute
```
```
In io_uring/rw.c (ffffffff81829e20)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
```
```
In io_uring/register.c (ffffffff8182bf63)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - io_uring/register.c:__do_sys_io_uring_register
```
```
In arch/x86/lib/msr.c (ffffffff8193085d)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff8194aae4)
Location: include/linux/cpumask.h:1102
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
In drivers/pwm/core.c (ffffffff8195a6d1)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/pwm/core.c:__pwm_apply
  - drivers/pwm/core.c:pwm_device_request
```
```
In drivers/pci/pcie/aer.c (ffffffff8198893c)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
```
In drivers/acpi/sleep.c (ffffffff819e7570)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a69685)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
```
In drivers/clk/clk.c (ffffffff81a8d313)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81ab2d19)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/xen/events/events_fifo.c (ffffffff81abf417)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acc9fd)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff81ad79df)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5ed67)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/svm.c (ffffffff81b6c3d4)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/iommu/iommu.c (ffffffff81b74922)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/iommu/iommu.c:iommu_group_alloc_device
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7b149)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
```
In drivers/base/syscore.c (ffffffff81b91b4d)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/cpu.c (ffffffff81b9633b)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
```
```
In drivers/base/devres.c (ffffffff81b97c37)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/devres.c:__devm_add_action
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_close_group
  - drivers/base/devres.c:devres_open_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
  - drivers/base/devres.c:devres_get
```
```
In drivers/base/power/qos.c (ffffffff81ba4d95)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff81ba8140)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (ffffffff81badb62)
Location: include/linux/cpumask.h:1102
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
In drivers/base/power/wakeup.c (ffffffff81baee0b)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbd2ac)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:_regmap_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/base/regmap/regcache.c (ffffffff81bc3212)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_read
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c1413e)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c1a2b9)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff81c244db)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c293c5)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c4216d)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/ata/libata-core.c (ffffffff81c54491)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff81c664c9)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_done
  - drivers/ata/libata-eh.c:ata_eh_about_to_do
  - drivers/ata/libata-eh.c:ata_eh_thaw_port
  - drivers/ata/libata-eh.c:__ata_port_freeze
```
```
In drivers/ata/libata-sff.c (ffffffff81c6ed18)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_post_internal_cmd
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:__ata_sff_port_intr
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_tf_to_host
  - drivers/ata/libata-sff.c:ata_tf_to_host
```
```
In drivers/ata/ata_piix.c (ffffffff81c7579b)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_irq_check
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb69b6)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_handle_vblank_events
  - drivers/gpu/drm/drm_vblank.c:drm_queue_vblank_event
  - drivers/gpu/drm/drm_vblank.c:send_vblank_event
```
```
In drivers/spi/spi.c (ffffffff81ce064a)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81cf36b1)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff81cfa322)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/virtio_net.c (ffffffff81d055ed)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/xen-netfront.c (ffffffff81d22116)
Location: include/linux/cpumask.h:1102
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81d9a990)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81d9ec3e)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81da274d)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_trb
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_ring_ep_doorbell
  - drivers/usb/host/xhci-ring.c:inc_enq
  - drivers/usb/host/xhci-ring.c:inc_deq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81dacb2a)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db44b4)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/rtc/interface.c (ffffffff81ddaafb)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_offset
  - drivers/rtc/interface.c:rtc_read_offset
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_alarm_disable
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de2df0)
Location: include/linux/cpumask.h:1102
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de6b87)
Location: include/linux/cpumask.h:1102
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81dfa7a3)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/hwmon/hwmon.c:hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:hwmon_attr_show
```
```
In drivers/thermal/thermal_core.c (ffffffff81dfdc49)
Location: include/linux/cpumask.h:1102
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (ffffffff81e03063)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:__thermal_cdev_update
```
```
In drivers/thermal/gov_fair_share.c (ffffffff81e056d6)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/thermal/gov_fair_share.c:fair_share_throttle
```
```
In drivers/thermal/gov_step_wise.c (ffffffff81e05c75)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/thermal/gov_step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81e07305)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:pid_controller
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81e0860f)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81e08b1b)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_count
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81e0ae6f)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0d17a)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff81e11c17)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_discard_bio
```
```
In drivers/md/dm.c (ffffffff81e2ff73)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_submit_bio_remap
```
```
In drivers/md/dm-rq.c (ffffffff81e3fc73)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff81e4174e)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e5113c)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81e5a914)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e6291a)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff82224e54)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/cpuidle/governors/haltpoll.c (ffffffff81e687ba)
Location: include/linux/cpumask.h:1102
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff81e6aa50)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81e9548b)
Location: include/linux/cpumask.h:1102
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea4e8e)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
```
In drivers/ras/ras.c (ffffffff81eaed59)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In drivers/interconnect/core.c (ffffffff81eb4732)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
```
In net/socket.c (ffffffff81ebdd5d)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/socket.c:call_trace_sock_recv_length
```
```
In net/core/sock.c (ffffffff81ec5f0b)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_error_report
```
```
In net/core/skbuff.c (ffffffff81edc8ae)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_attempt_defer_free
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_reason
  - net/core/skbuff.c:kfree_skb_reason
```
```
In net/core/datagram.c (ffffffff81edcf1b)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/dev.c (ffffffff81efecc6)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:net_rps_send_ipi
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_qdisc_enqueue
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/neighbour.c (ffffffff81f0af63)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/filter.c (ffffffff81f333fd)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
```
```
In net/core/xdp.c (ffffffff81f388d8)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/gro.c (ffffffff81f3c857)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:napi_gro_receive
```
```
In net/core/page_pool.c (ffffffff81f43a45)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_return_page
  - net/core/page_pool.c:page_pool_inflight
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
```
In net/core/net-procfs.c (ffffffff81f467ea)
Location: include/linux/cpumask.h:1102
Inline: True
```
```
In net/core/netpoll.c (ffffffff81f47766)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/skmsg.c (ffffffff81f6423e)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
```
```
In net/sched/sch_generic.c (ffffffff81f6fa46)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_api.c (ffffffff81f74958)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff81f85d39)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81f92b81)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
```
```
In net/ipv4/tcp_input.c (ffffffff81fe350c)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffff81fe5f29)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7549)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_cong.c (ffffffff81ffa6b8)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_ca_state
```
```
In net/ipv4/udp.c (ffffffff82009292)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/af_inet.c (ffffffff8201c046)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
```
```
In net/ipv4/fib_trie.c (ffffffff8202de26)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204cce4)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:sigpool_reserve_scratch
```
```
In net/xfrm/espintcp.c (ffffffff82074862)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_data_ready
```
```
In net/ipv6/route.c (ffffffff8209ed1d)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/udp.c (ffffffff820b7161)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd6f7)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/devlink/health.c (ffffffff82113def)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_health_report
  - net/devlink/health.c:devlink_health_report
```
```
In net/devlink/trap.c (ffffffff82114908)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_trap_report
```
```
In net/mptcp/protocol.c (ffffffff821499a9)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mptcp/subflow.c (ffffffff82151241)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff821536e3)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/mptcp/options.c:ack_update_msk
```
```
In net/mctp/af_mctp.c (ffffffff82163c56)
Location: include/linux/cpumask.h:1102
Inline: True
```
```
In net/mctp/route.c (ffffffff82167283)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:__mctp_key_done_in
```
```
In net/handshake/alert.c (ffffffff8216888c)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/handshake/alert.c:tls_alert_recv
  - net/handshake/alert.c:tls_alert_send
```
```
In net/handshake/netlink.c (ffffffff821691c1)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_nl_done_doit
  - net/handshake/netlink.c:handshake_nl_done_doit
  - net/handshake/netlink.c:handshake_nl_accept_doit
  - net/handshake/netlink.c:handshake_nl_accept_doit
```
```
In net/handshake/request.c (ffffffff8216a134)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_complete
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_sk_destruct
```
```
In lib/maple_tree.c (ffffffff8218deef)
Location: include/linux/cpumask.h:1102
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mtree_erase
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_load
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_store
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_append
  - lib/maple_tree.c:mas_wr_slot_store
  - lib/maple_tree.c:mas_wr_walk
```
**Symbols:**

```
ffffffff81104620-ffffffff81104634: cpu_online (STB_LOCAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
